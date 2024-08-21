<script>
  import Button from "./../lib/components/ui/button/button.svelte";
</script>

<header class="flex justify-center items-center">
  <div class="  w-[50rem] max-h-[35rem] p-5 mb-10 flex flex-col items-center">
    <div class="">
      <h1 class="text-4xl font-bold text-primary">Joy Bite</h1>
      <div class="text-primary/90 pt-2 font-serif flex flex-col items-center">
        <p>اخترنا لك الوصفات بعناية</p>
        <p>لتستمتع بمذاق لذيذ وصحي</p>
      </div>
    </div>

    <div
      class=" lg:h-fit w-auto
        p-5 grid grid-cols-4 gap-5
       justify-items-center"
    >
      <div
        class="max-w-10 h-10 rounded-full text-4xl text-primary-foreground bg-primary flex justify-center items-center"
      >
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="1em"
          height="1em"
          viewBox="0 0 48 48"
          ><path
            fill="none"
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M16.202 29.664c-.877.5-4.34 3.213-4.34 3.213s5.341 4.674 5.884 5.425c0 0-1.544-7.512-1.544-8.638"
          /><path
            fill="none"
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M20.375 19.982c-1.753 0-4.173 1.947-6.385 4.145s-7.804 7.039-7.804 9.167s11.059 10.183 14.898 10.183s9.014.375 12.019-1.878s8.22-7.47 8.43-8.388a12.9 12.9 0 0 0 .167-4.132a1.89 1.89 0 0 0-1.586-1.168c-.814 0-2.942.876-2.942 2.358a13.7 13.7 0 0 0 .542 2.817a60 60 0 0 1-5.55 3.86s.125-7.575-.27-9.452s-3.86-4.883-3.86-5.467s1.188-4.465 1.188-4.465s2.442.542 2.713-.94s.083-1.543.083-1.543a1.95 1.95 0 0 0 .564-1.586c-.167-.876-.668-.689-.647-1.19S32.873 4.5 26.029 4.5s-6.885 5.634-6.885 6.698s3.15 5.404 2.837 7.136s-.271 1.586-.271 1.586s-.692.062-1.335.062"
          /><path
            fill="none"
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M19.978 13.764c-.772.23-5.153 6.594-7.95 6.594a5.6 5.6 0 0 1-3.672-1.94c2.462.146 5.592-4.632 7.992-4.987a12.5 12.5 0 0 1 3.63.333"
          />
        </svg>
      </div>
      <div
        class="w-10 h-10 rounded-full text-4xl text-primary-foreground bg-primary flex justify-center items-center"
      >
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="1em"
          height="1em"
          viewBox="0 0 48 48"
          ><path
            fill="none"
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M31.221 16.053c-.64 0-1.254.255-1.707.707l-6.546 6.551l-3.14-3.216a2.413 2.413 0 1 0-3.452 3.374l4.844 4.962a2.413 2.413 0 0 0 3.433.02l8.274-8.277a2.415 2.415 0 0 0-1.705-4.12z"
          /><path
            fill="none"
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M39.858 11.853C35.855 6.988 27.412 6.804 24 12.165c-3.412-5.36-11.854-5.176-15.858-.312C-1.953 24.117 19.84 39.826 24 39.826s25.953-15.71 15.858-27.973"
          />
        </svg>
      </div>
      <div
        class="w-10 h-10 text-4xl text-primary-foreground bg-primary rounded-full flex justify-center items-center"
      >
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="1em"
          height="1em"
          viewBox="0 0 48 48"
          ><path
            fill="none"
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M30.507 36.163h-13.01m0-4.025h13.006m10.054 4.649h.835c.613 0 1.108-.491 1.108-1.104v-3.152c0-.61-.494-1.104-1.104-1.104h-.835m-3.893 8.58h2.786a1.1 1.1 0 0 0 1.103-1.103v-9.59a1.104 1.104 0 0 0-1.1-1.107h-2.785m-1.104-2.355H31.61c-.61 0-1.104.494-1.104 1.104v14.302a1.1 1.1 0 0 0 1.104 1.104h3.957a1.1 1.1 0 0 0 1.104-1.104V26.96a1.104 1.104 0 0 0-1.1-1.108zM7.439 36.791h-.831a1.104 1.104 0 0 1-1.108-1.1v-3.16c0-.612.491-1.104 1.108-1.104h.831m3.893 8.58h-2.79a1.103 1.103 0 0 1-1.103-1.103v-9.59c0-.612.491-1.107 1.104-1.107h2.782m1.107-2.355h3.954c.616 0 1.107.491 1.107 1.108v14.298a1.1 1.1 0 0 1-1.107 1.104h-3.95c-.61 0-1.104-.494-1.104-1.104V26.96c0-.613.492-1.108 1.104-1.108zm8.701 2.82h9.37m-13.01-1.078l1.531-1.538m2.11-4.94h13.25m-20.625-.159l1.41 1.414l3.855-3.874m2.11-4.94h13.25m-20.625-.16l1.41 1.414l3.855-3.87m11.48 28.5H17.496M9.374 28.206V7.849c0-1.225.98-2.211 2.193-2.211h24.87c1.217 0 2.196.983 2.196 2.211v20.358"
          />
        </svg>
      </div>
      <div
        class="w-10 h-10 text-4xl text-primary-foreground bg-primary rounded-full flex justify-center items-center"
      >
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="1em"
          height="1em"
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
    </div>
  </div>
</header>
<div
  class="font-bold text-lg text-primary flex justify-center pb-2"
>
  اختر قائمة 
</div>
<div class=" flex flex-col items-center pb-20">
  <div
    class="bg-gradient-to-r from-background/90  to-primary/50 dark:bg-primary
     shadow-[0_30px_80px_-15px_rgba(0,0,0,0.4)]  lg:h-fit w-auto  rounded-xl ring-1 ring-secondary
      p-6 grid grid-cols-3 gap-8 gap-y-6 
     justify-items-center"
  >
    <div class="lg:w-[15vw] w-[20vw] h-auto rounded-xl ">
      <img src="/breakfast.png" alt="" class=" rounded-xl " />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class=" text-secondary-foreground w-[20vw] h-7 lg:h-fit "
        >
          فطور
        </Button>
      </span>
    </div>
    <div class="lg:w-[15vw] w-[20vw] h-auto rounded-xl">
      <img src="/main dishes .jpg" alt="" class="rounded-xl " />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/mainDishes"
          class=" text-secondary-foreground w-[20vw] h-7 lg:h-fit "
        >
          وجبات رئيسية
        </Button>
      </span>
    </div>
    <div class="lg:w-[15vw] w-[20vw] h-auto rounded-xl">
      <img src="/snacks.jpg" alt="" class="rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/snacks"
          class=" text-secondary-foreground   w-[20vw] h-7 lg:h-fit"
        >
          مأكولات خفيفة
        </Button>
      </span>
    </div>
    <div class=" lg:w-[15vw] w-[20vw] h-auto rounded-xl">
      <img src="/juice .jpg" alt="" class="rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/juices"
          class=" text-secondary-foreground   w-[20vw] h-7 lg:h-fit"
        >
          عصيرات
        </Button>
      </span>
    </div>
    <div class=" lg:w-[15vw] w-[20vw] h-auto rounded-xl">
      <img src="/sweets.jpg" alt="" class="rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/sweets"
          class=" text-secondary-foreground  w-[20vw] h-7 lg:h-fit"
        >
          حلويات
        </Button>
      </span>
    </div>
    <div class=" lg:w-[15vw] w-[20vw] h-auto rounded-xl">
      <img src="/salad.jpg" alt="" class="rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/salad"
          class=" text-secondary-foreground  w-[20vw] h-7 lg:h-fit"
        >
          سلطات
        </Button>
      </span>
    </div>
  </div>
</div>
