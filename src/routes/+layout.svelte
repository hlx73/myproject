<script>
    import Navbar from "$lib/components/navbar.svelte";
import "../app.css";
    import { ModeWatcher } from "mode-watcher";
    import Footer from "$lib/components/Footer.svelte"
    import { onNavigate } from '$app/navigation';

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
    </script>

<Navbar />

<ModeWatcher />
<slot></slot>
<Footer />
