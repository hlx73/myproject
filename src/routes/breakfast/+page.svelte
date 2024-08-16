<script lang="ts">
  import { buttonVariants } from "$lib/components/ui/button";
  import Button from "$lib/components/ui/button/button.svelte";
  import * as Dialog from "$lib/components/ui/dialog";
</script>

<div class="flex flex-col items-center pb-20">
  <div
    class="lg:h-fit w-[80vw] bg-secondary shadow-[0_10px_60px_-15px_rgba(0,0,0,0.3)]
     rounded-xl grid grid-cols-4 gap-5 p-4 px-2"
  >
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/b3.PNG" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              { variant: 'outline' },
            )}">سكرمبل الشوفان</Dialog.Trigger
          >
          <Dialog.Content
            class=" w-[70vw] h-[90vh] bg-secondary shadow-md"
          >
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
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
      <img src="/b4.JPG" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              { variant: 'outline' },
            )}">شكشوكة تركية</Dialog.Trigger
          >
          <Dialog.Content
            class=" bg-secondary shadow-md"
          >
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >شكشوكة تركية 
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
      <img src="/b1.PNG" alt="" class=" rounded-xl" />
     
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              { variant: 'outline' },
            )}">  بانكيك البروتين</Dialog.Trigger
          >
          <Dialog.Content
            class=" bg-secondary shadow-md"
          >
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >بانكيك البروتين 
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
      <img src="/b7.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              { variant: 'outline' },
            )}">   فرنش توست</Dialog.Trigger
          >
          <Dialog.Content
            class=" bg-secondary shadow-md"
          >
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >فرنش توست  
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
      <img src="/b5.JPG" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              { variant: 'outline' },
            )}">  ساندوتش بيض </Dialog.Trigger
          >
          <Dialog.Content
            class=" bg-secondary shadow-md"
          >
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >ساندوتش بيض  
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
      <img src="/b2.JPG" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              { variant: 'outline' },
            )}">  بانكيك </Dialog.Trigger
          >
          <Dialog.Content
            class=" bg-secondary shadow-md"
          >
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >بانكيك  
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
      <img src="/b6.JPG" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              { variant: 'outline' },
            )}">أفكار للتوست</Dialog.Trigger
          >
          <Dialog.Content
            class="bg-secondary shadow-md"
          >
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >أفكار للتوست  
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
      <img src="/b8.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              { variant: 'outline' },
            )}">  بانكيك غير</Dialog.Trigger
          >
          <Dialog.Content
            class=" bg-secondary shadow-md"
          >
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >بانكيك زبدة الفول السوداني 
              </Dialog.Title>
              <h2
                class="py-10 flex justify-start items-start text-secondary-foreground">
                
            </h2>
            </Dialog.Header>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
  </div>
</div>
