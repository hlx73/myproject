<script>
    import Button from "$lib/components/ui/button/button.svelte";
</script>

<footer class=" bg-secondary text-secondary-foreground  p-6 p ">
    <div class="max-w-screen-2xl flex justify-end items-center mx-auto gap-5">
            <span class="flex flex-col items-center">
                <span class="font-bold text-sm">
                    Email 
                </span>
                <a class="text-xs" href="mailto:hadelturki@hotmail.com"
                    >hadelturki@hotmail
                </a>
            </span>
            

        <div class="flex flex-col items-center">
            <span class="text-sm font-bold "> © {new Date().getFullYear()}          </span>
                <span class="text-xs">by Hadeel</span>  
        </div>
      </div>
</footer>
