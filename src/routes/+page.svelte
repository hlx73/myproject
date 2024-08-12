<script>
    import Button from "./../lib/components/ui/button/button.svelte";
</script>

<div class="flex justify-end">
    <div
        class="bg-secondary min-h-[calc(100vh-6.5rem)] w-[60vw] relative flex items-center"
    >
        <div
            class="bg-[rgb(148,248,248)] shadow-[0_20px_70px_-15px_rgba(0,0,0,0.3)]
         w-[20rem] absolute start-10 -translate-x-full pt-8 flex flex-col
        "
        >
            <img
                src="/profile.png"
                class="rounded-full w-40 h-50 mx-auto"
                alt="personal pic"
            />
            <div class="flex flex-col items-center gap-2">
                <h1 class="font-bold p-3 text-2xl">Hadeel</h1>
                <hr class="w-16 border-2 border-primary" />
                <h2 class="text-lg">AI student</h2>
                <div class="bg-secondary w-full flex  justify-center mt-5">
                    <Button variant="ghost" size="icon" href="https://x.com/_hadeell1">
                        <svg class="h-auro w-5"
                            xmlns="http://www.w3.org/2000/svg"
                            
                            viewBox="0 0 512 512"
                            ><path
                                fill="currentColor"
                                d="M389.2 48h70.6L305.6 224.2L487 464H345L233.7 318.6L106.5 464H35.8l164.9-188.5L26.8 48h145.6l100.5 132.9zm-24.8 373.8h39.1L151.1 88h-42z"
                            /></svg
                        >
                    </Button>
                    <Button variant="ghost" size="icon" href="">
                        <svg 
                            class="h-auto w-5"
                            xmlns="http://www.w3.org/2000/svg"
                            viewBox="0 0 36 36"
                            ><path
                                fill="currentColor"
                                d="M32.33 6a2 2 0 0 0-.41 0h-28a2 2 0 0 0-.53.08l14.45 14.39Z"
                                class="clr-i-solid clr-i-solid-path-1"
                            /><path
                                fill="currentColor"
                                d="m33.81 7.39l-14.56 14.5a2 2 0 0 1-2.82 0L2 7.5a2 2 0 0 0-.07.5v20a2 2 0 0 0 2 2h28a2 2 0 0 0 2-2V8a2 2 0 0 0-.12-.61M5.3 28H3.91v-1.43l7.27-7.21l1.41 1.41Zm26.61 0h-1.4l-7.29-7.23l1.41-1.41l7.27 7.21Z"
                                class="clr-i-solid clr-i-solid-path-2"
                            /><path fill="none" d="M0 0h36v36H0z" /></svg
                        >
                    </Button>
                    <Button variant="ghost" size="icon">
                        <svg
                            class="h-auto w-5"
                            xmlns="http://www.w3.org/2000/svg"
                            viewBox="0 0 24 24"
                            ><path
                                fill="currentColor"
                                d="M20.01 15.38c-1.23 0-2.42-.2-3.53-.56a.98.98 0 0 0-1.01.24l-1.57 1.97c-2.83-1.35-5.48-3.9-6.89-6.83l1.95-1.66c.27-.28.35-.67.24-1.02c-.37-1.11-.56-2.3-.56-3.53c0-.54-.45-.99-.99-.99H4.19C3.65 3 3 3.24 3 3.99C3 13.28 10.73 21 20.01 21c.71 0 .99-.63.99-1.18v-3.45c0-.54-.45-.99-.99-.99"
                            /></svg
                        >
                    </Button>
                </div>
            </div>
        </div>
    </div>
</div>
