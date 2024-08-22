<script lang="ts">
  import * as Carousel from "$lib/components/ui/carousel/index.js";
  import { ScrollArea } from "$lib/components/ui/scroll-area/index.js";

  </script>
<div class=" flex justify-center items-center pb-20">
    <div
        class="max-w-[18rem] lg:max-w-[20rem] h-auto
         bg-gradient-to-r from-background/90 to-primary/50 dark:bg-primary shadow-[0_30px_80px_-15px_rgba(0,0,0,0.4)]
       ring-1 ring-secondary
       rounded-xl p-6 "
    >
        <div class="text-secondary-foreground">
            <h1 class="font-bold flex justify-center lg:text-xl pb-5">المبرمجة هديل </h1>
            <div class="font-bold text-xs lg:text-sm">
                <h2>
                    هديل,
                     طالبة ذكاء اصطناعي بكلية
                 الحاسب 💕🤍.
                </h2>

                <h2>
                    أمارس نمط حياة صحي ولدي اهتمام كبير بالصحة والتغذية🌼🍓، ولذلك
                    قمت بتصميم وبرمجة موقعي Joy Bite ليكون وسيلة لجعل الناس يحبون الطعام
                  الصحي ويسهل عليهم الوصول إلى وصفات صحية ولذيذة ✨.
                </h2>
                <h2>
                    لدي شغف كبير بصنع الحلويات والموازنة بينها وبين الحياة
                    الصحية، وهذه بعض من أعمالي ✨💖:
                </h2>
                
            </div>
            
        </div>
        <div class=" p-5">
          <Carousel.Root class="" dir="ltr">
            <Carousel.Content>
              
                <Carousel.Item  >
                  <img src="cake2.jpg" alt="" class=" rounded-xl  w-auto h-auto ">
                </Carousel.Item> 
                <Carousel.Item>
                  <img src="cake1.jpg" alt="" class=" rounded-xl w-auto h-aut">
                </Carousel.Item> 
               
            </Carousel.Content>
            <Carousel.Previous />

              <Carousel.Next />
           
        </Carousel.Root>
        </div>
         
          
    </div>
</div>

