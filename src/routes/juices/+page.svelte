<script>
  import Button from "$lib/components/ui/button/button.svelte";
  import * as Dialog from "$lib/components/ui/dialog";
  import { buttonVariants } from "$lib/components/ui/button";

</script>
<div class="">
  <div class="flex flex-col items-center pb-20">
    <div
      class="
      lg:h-fit w-auto bg-secondary  shadow-[0_10px_60px_-15px_rgba(0,0,0,0.3)]  rounded-xl
      p-6 grid grid-cols-3 gap-8 gap-y-6
     justify-items-center
       "
    >
      <div class=" w-[15vw] h-auto rounded-xl">
        <img src="/j1.JPG" alt="" class=" rounded-xl" />
        <span class="flex justify-center py-2 pr-2">
          <Dialog.Root>
            <Dialog.Trigger
              class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
                { variant: 'outline' },
              )}">مانجو وأناناس</Dialog.Trigger
            >
            <Dialog.Content
            >
              <Dialog.Header class="">
                <Dialog.Title
                  >سكرمبل الشوفان
                </Dialog.Title>
                <h2
                  class="py-10 flex justify-start items-start text-secondary-foreground">
  
              </h2>
              </Dialog.Header>
            </Dialog.Content>
          </Dialog.Root>
        </span>
      </div>
      <div class=" w-[15vw] h-auto rounded-xl">
        <img src="/j2.JPG" alt="" class=" rounded-xl" />
        <span class="flex justify-center py-2">
          <Button
            variant="outline"
            href="/breakfast"
            class="  text-secondary-foreground  w-[20vw] h-7 lg:h-fit "
          >
          برتقال و جزر
          </Button>
        </span>
      </div>
      <div class=" w-[15vw] h-auto rounded-xl">
        <img src="/j3.JPG" alt="" class=" rounded-xl" />
        <span class="flex justify-center py-2">
          <Button
            variant="outline"
            href="/breakfast"
            class="  text-secondary-foreground  w-[20vw] h-7 lg:h-fit "
          >
           فراولة و موز
          </Button>
        </span>
      </div>
      <div class=" w-[15vw] h-auto rounded-xl">
        <img src="/juice .jpg" alt="" class=" rounded-xl" />
        <span class="flex justify-center py-2">
          <Button
            variant="outline"
            href="/breakfast"
            class="  text-secondary-foreground  w-[20vw] h-7 lg:h-fit "
          >
        بطيخ و نعناع
          </Button>
        </span>
      </div>
      <div class=" w-[15vw] h-auto rounded-xl">
        <img src="/j4.JPG" alt="" class=" rounded-xl" />
        <span class="flex justify-center py-2">
          <Button
            variant="outline"
            href="/breakfast"
            class="  text-secondary-foreground  w-[20vw] h-7 lg:h-fit "
          >
           عنب و توت
          </Button>
        </span>
      </div>
      <div class=" w-[15vw] h-auto rounded-xl">
        <img src="/j5.JPG" alt="" class=" rounded-xl" />
        <span class="flex justify-center py-2">
          <Button
            variant="outline"
            href="/breakfast"
            class="  text-secondary-foreground  w-[20vw] h-7 lg:h-fit "
          >
            أناناس و كيوي
          </Button>
        </span>
      </div>
     
    </div>
  </div>
</div>

