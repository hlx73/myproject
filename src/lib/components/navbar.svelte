<script>
import Button from "./ui/button/button.svelte";
import {page} from "$app/stores"
</script>

<div class="w-[1000dvm]  bg-secondary  py-8 px-4
text-secondary-forground">
    <nav
    class="max-w-screen-2xl flex justify-between  items-baseline mx-auto"
>
    <div class="flex items-center gap-2 text-xl">
        <div class="bg-primary w-4 h-4 me-2"/>
        <span class=" font-bold">Hadeel</span>
        <span class="text-lg uppercase"> /AI  student </span>
        
    </div>
    <div class="uppercase">
        <Button class="{$page.url.pathname=='/'&&'text-primary'}"
         href="./"
          variant="link"
          >about me</Button>
        <Button 
        class="{$page.url.pathname=='/resume'&&'text-primary'}"
        href="./resume" 
        variant="resume">Project</Button>
        <Button
        class="{$page.url.pathname=='/contact'&&'text-primary'}"
         href="./contact" 
         variant="link">Contact</Button>
        <Button 
        class="{$page.url.pathname=='/projects'&&'text-primary'}"
        href="./projects" 
        variant="link">Project</Button>
    </div>
    
</nav>
</div>
