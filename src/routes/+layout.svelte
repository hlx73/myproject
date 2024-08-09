<script>
    import Navbar from "$lib/components/navbar.svelte";
import "../app.css";
    import { ModeWatcher } from "mode-watcher";
</script>
<Navbar/>

<ModeWatcher />
<slot></slot>

