<script>
// @ts-nocheck

	import Themeswich from './themeswich.svelte';
    import Button from "$lib/components/ui/button/button.svelte";
    import { page } from "$app/stores";
    import * as Sheet from "$lib/components/ui/sheet";

    const links = [
        {
            text: "About me",
            href: "/",
        },
        {
            text: "resume",
            href: "/resume",
        },
        {
            text: "projects",
            href: "/projects",
        },
        {
            text: "contact",
            href: "/contact",
        },
    ];
		let isSheetOpen=false
</script>

<div
    class=" bg-secondary py-8 px-4
text-secondary-forground"
>
    <nav class="max-w-screen-2xl flex justify-between items-center mx-auto">
        <div class="flex items-center gap-2 text-xl">
            <div class="bg-primary w-4 h-4 me-2" />
            <span class=" font-bold">Hadeel</span>
            <span class="text-lg uppercase"> /AI student </span>
        </div>
        <div class="flex">
            <Themeswich>
            </Themeswich>
            <div class="uppercase hidden md:flex">
                {#each links as link}
                <Button
                    class={$page.url.pathname == link.href &&
                        "text-primary"}
                    hrf={link.href}
                    variant="link">
                    {link.text}
                </Button>
            {/each}
            </div>
           <!---->
            <Sheet.Root bind:open={isSheetOpen}>
                <Sheet.Trigger>
                    <Button class="flex n" variant="ghost" size="icon">
                        <svg
                            xmlns="http://www.w3.org/2000/svg"
                            class="w-6 h-auto"
                            viewBox="0 0 24 24"
                            ><g fill="none"
                                ><path
                                    d="M24 0v24H0V0zM12.593 23.258l-.011.002l-.071.035l-.02.004l-.014-.004l-.071-.035q-.016-.005-.024.005l-.004.01l-.017.428l.005.02l.01.013l.104.074l.015.004l.012-.004l.104-.074l.012-.016l.004-.017l-.017-.427q-.004-.016-.017-.018m.265-.113l-.013.002l-.185.093l-.01.01l-.003.011l.018.43l.005.012l.008.007l.201.093q.019.005.029-.008l.004-.014l-.034-.614q-.005-.019-.02-.022m-.715.002a.02.02 0 0 0-.027.006l-.006.014l-.034.614q.001.018.017.024l.015-.002l.201-.093l.01-.008l.004-.011l.017-.43l-.003-.012l-.01-.01z"
                                /><path
                                    fill="currentColor"
                                    d="M20 17.5a1.5 1.5 0 0 1 .144 2.993L20 20.5H4a1.5 1.5 0 0 1-.144-2.993L4 17.5zm0-7a1.5 1.5 0 0 1 0 3H4a1.5 1.5 0 0 1 0-3zm0-7a1.5 1.5 0 0 1 0 3H4a1.5 1.5 0 1 1 0-3z"
                                /></g
                            ></svg
                        >
                        
                    </Button>
                </Sheet.Trigger>
                <Sheet.Content class="flex flex-col justify-center">
                    {#each links as link}
                    <Button
                        class="text-lg {$page.url.pathname == link.href &&
                            "text-primary"}"
                        hrf={link.href}
                        variant="link"
												on:click={()=> isSheetOpen=false}
                    >
                        {link.text}
												
                    </Button>
                {/each}
                </Sheet.Content>
              </Sheet.Root>
        </div>
    </nav>
</div>
