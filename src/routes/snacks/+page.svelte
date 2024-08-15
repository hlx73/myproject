<script>
  import Button from "$lib/components/ui/button/button.svelte";
</script>

<div class="flex flex-col items-center pb-20">
  <div
    class="
 lg:h-fit w-auto bg-secondary shadow-[0_10px_60px_-15px_rgba(0,0,0,0.3)] rounded-xl
      p-6 grid grid-cols-3 gap-5 gap-y-6
     justify-items-center"
  >
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/snacks.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class=" bg-secondary text-secondary-foreground text-xs w-[20vw] h-7 lg:h-fit "
        >
          كرات التمر
        </Button>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/s5.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class=" bg-secondary text-secondary-foreground text-xs w-[23vw] h-7 lg:h-fit "
        >
         كرات الفول اسوداني 
        </Button>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/s4.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class=" bg-secondary text-secondary-foreground text-xs w-[20vw] h-7 lg:h-fit "
        >
          شوكولاتة دارك
        </Button>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/s2.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class=" bg-secondary text-secondary-foreground text-xs w-[20vw] h-7 lg:h-fit "
        >
          بليلة
        </Button>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl text-sm">
      <img src="/s7.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class=" bg-secondary text-secondary-foreground  text-xs w-[20vw] h-7 lg:h-fit "
        >
          بطاطس
        </Button>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/s3.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class=" bg-secondary text-secondary-foreground text-xs w-[20vw] h-7 lg:h-fit "
        >
          فراولة و شوكلاتة
        </Button>
      </span>
    </div>
    <div class=" w-[20vw] h-auto rounded-xl col-end-3">
      <img src="/ss.jpg" alt="" class=" rounded-xl flex justify-cente" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class=" bg-secondary text-secondary-foreground text-xs w-[20vw] h-7 lg:h-fit "
        >
          سناك بارد
        </Button>
      </span>
    </div>
  </div>
</div>
