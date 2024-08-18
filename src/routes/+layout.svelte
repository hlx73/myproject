<script>
    import Navbar from "$lib/components/navbar.svelte";
import "../app.css";
    import { ModeWatcher } from "mode-watcher";
    import Footer from "$lib/components/Footer.svelte"
</script>
<Navbar/>

<ModeWatcher />
<slot></slot>
<Footer/>

