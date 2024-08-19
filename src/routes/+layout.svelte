<script>
    import Navbar from "$lib/components/navbar.svelte";
import "../app.css";
    import { ModeWatcher } from "mode-watcher";
    import Footer from "$lib/components/Footer.svelte"
    import { onNavigate } from '$app/navigation';
	// @ts-ignore
	import { pwaInfo } from 'virtual:pwa-info'; 


onNavigate((navigation) => {
	// @ts-ignore
	if (!document.startViewTransition) return;

	return new Promise((resolve) => {
		// @ts-ignore
		document.startViewTransition(async () => {
			resolve();
			await navigation.complete;
		});
	});
});
$: webManifestLink = pwaInfo ? pwaInfo.webManifest.linkTag : '' 

    </script>
	<svelte:head> 
		{@html webManifestLink} 
   </svelte:head>
<Navbar />

<ModeWatcher />
<slot></slot>
<Footer />
