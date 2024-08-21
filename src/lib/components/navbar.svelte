<script>
    // @ts-nocheck

    import Themeswich from "./themeswich.svelte";
    import Button from "$lib/components/ui/button/button.svelte";
    import { page } from "$app/stores";
    import * as Sheet from "$lib/components/ui/sheet";

    const links = [
        {
            text: "الرئيسية",
            href: "/",
        },
        {
            text: "فطور",
            href: "/breakfast",
        },
        {
            text: "وجبات رئيسية",
            href: "/mainDishes",
        },
        {
            text: " مأكولات خفيفة",
            href: "/snacks",
        },
        {
            text: " عصيرات",
            href: "/juices",
        },
        {
            text: " حلويات",
            href: "/sweets",
        },
        {
            text: " سلطات",
            href: "/salad",
        },
        {
            text: "مبرمجة الموقع",
            href: "/hadeel",
        },
    ];
    let isSheetOpen = false;
</script>

<div
    class=" bg-backround text-secondary-foreground py-8 pb-14 px-7 lg:px-25 h-[25vh]
"
>
    <nav class="max-w-screen-2xl flex justify-between items-center mx-auto">
        <div class="flex items-center gap- text-xl">
            <div class="" />
            <Sheet.Root bind:open={isSheetOpen}>
                <Sheet.Trigger class="flex lg:hidden">
                    <Button variant="ghost" size="icon">
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
                <Sheet.Content class="flex flex-col justify-center w-[40vw]">
                    {#each links as link}
                        <Button
                            class="text-xl {$page.url.pathname == link.href &&
                                'text-primary/50 dark:text-[#ffc9cf] '}"
                            href={link.href}
                            variant="link"
                            on:click={() => (isSheetOpen = false)}
                        >
                            {link.text}
                        </Button>
                    {/each}
                </Sheet.Content>
            </Sheet.Root>
            <div class=" ">
                <svg class="text-primary"
                    xmlns="http://www.w3.org/2000/svg"
                    width="2em"
                    height="1.5em"
                    viewBox="0 0 32 32"
                    ><path
                        fill="currentColor"
                        d="M9 10h2v2H9zm0 4h2v2H9zm4-2h2v2h-2z"
                    /><path
                        fill="currentColor"
                        d="M9 28a5 5 0 0 1-.744-.054A5.094 5.094 0 0 1 4 22.866V11.2a7.16 7.16 0 0 1 6.31-7.166a6.96 6.96 0 0 1 4.464 1.07l7.97 4.981a6.98 6.98 0 0 1-.69 12.19l-10.88 5.229A5 5 0 0 1 9 28m2.002-22q-.248 0-.5.024A5.146 5.146 0 0 0 6 11.198v11.669a3.084 3.084 0 0 0 2.544 3.1a3.03 3.03 0 0 0 1.762-.265l10.883-5.23a4.98 4.98 0 0 0 .488-8.696l-7.972-4.982A4.97 4.97 0 0 0 11.002 6M26 7h-4a4.005 4.005 0 0 1-4-4V2h2v1a2 2 0 0 0 2 2h4z"
                    /></svg
                >
            </div>

            <span class=" font-bold text-primary">Joy Bite</span>
            <div class="uppercase hidden lg:flex">
                {#each links as link}
                    <Button
                        class=" {$page.url.pathname == link.href &&
                            'text-primary/50 '}"
                        href={link.href}
                        variant="link">{link.text}</Button
                    >
                {/each}
                <Themeswich></Themeswich>
            </div>
        </div>
        <!---->
        <div class="flex text-secondary-foreground px-6">
            <div class="flex justify-center lg:hidden">
                <Themeswich></Themeswich>
            </div>
        </div>
    </nav>
</div>
