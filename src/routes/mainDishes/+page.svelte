<script lang="ts">
  import { buttonVariants } from "$lib/components/ui/button";
  import Button from "$lib/components/ui/button/button.svelte";
  import * as Dialog from "$lib/components/ui/dialog";
  import { ScrollArea } from "$lib/components/ui/scroll-area/index.js";
</script>

<div class="flex flex-col items-center pb-20">
  <div
    class="lg:h-fit w-[80vw] bg-secondary shadow-[0_10px_60px_-15px_rgba(0,0,0,0.3)]
     rounded-xl grid grid-cols-4 gap-5 p-4 px-2"
  >
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/m1.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}">ساندوتش روبيان</Dialog.Trigger
          >
          <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >ساندوتش روبيان
              </Dialog.Title>
            </Dialog.Header>
            <div class="flex justify-center items-center">
              <ScrollArea
                class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4"
              >
                <div class=" text-sm">
                  <section>
                    <h2 class="text-secondary-foreground py-1">المكونات:</h2>
                    <ul>
                      <li>- 73 جرام خبز صامولي</li>
                      <li>- ملعقة صغيرة زيت زيتون</li>
                      <li>- 16 مل كريمة طبخ</li>
                      <li>- 149 جرام روبيان</li>
                      <li>- فص ثوم</li>
                      <li>- فلفل أسود وملح وكمون وبهارات مشكلة حسب الذوق</li>
                      <li>- عصير ليمون</li>
                    <li>- خس وبقدونس (للحشو)</li>
                    </ul>
                  </section>
                  <section class="py-3">
                    <h2 class=" text-secondary-foreground py-1">
                      الطريقة:
                    </h2>
                    <h2 class=" text-secondary-foreground ">
                      1. تحضير الروبيان:</h2>
                    <ol class="">
                      <li> 
                        - أضف فص ثوم مفروم وفلفل (بعد إزالة البذور) وقلِّب حتى يتحمر الثوم.                        </li>
                      <li>
                        - أضف البصل المفروم وحمِّسه حتى يذوب ويتكرمل.
                      </li>
                      <li>
                        - أضف قليل من الماء إذا لزم الأمر لذوبان البصل.                      </li>
                      <li>
                        - التوابل: ملح، الفلفل الأسود، الكمون، والبهارات المشكلة.                      </li>
                      <li>
                        - أضف ملعقة كبيرة من الكريمة وامزج جيداً.
                      </li>
                      <li>   - اعصر ليمونة فوق الخليط قبل الانتهاء.</li>
                    </ol>
                  </section>
                  <section class="py-3">
                    <h2 class=" text-secondary-foreground py-1">2. تحضير الصامولي:</h2>
                    <ol class="">
                      <li></li>
                      <li>
                        - فرغ الصامولي من الداخل.
                      </li>
                      <li>
                        - ضع فيه طبقة من الخس والبقدونس.
                      </li>
                      <li>
                        - أضف خليط الروبيان فوق الخضار.
                      </li>
                     
                    </ol>
                  </section>
                  <section class="py-4">
                    <h2 class="text-secondary-foreground py-1">
                      السعرات الحرارية:
                    </h2>
                    <p>-371  سعرة حرارية</p>
                  </section>
                </div>
              </ScrollArea>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/m2.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class="  text-secondary-foreground text-xs w-[18vw] h-7 lg:h-fit "
        >
          بيتزا خضار
        </Button>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/m3.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class="  text-secondary-foreground text-xs w-[20vw] h-7 lg:h-fit "
        >
          فاهيتا دجاج
        </Button>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/m4.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class="  text-secondary-foreground text-xs w-[18vw] h-7 lg:h-fit "
        >
          سبرينغ رول
        </Button>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/m5.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class="  text-secondary-foreground text-xs w-[18vw] h-7 lg:h-fit "
        >
          زنجر
        </Button>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/m6.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class="  text-secondary-foreground text-xs w-[18vw] h-7 lg:h-fit "
        >
          كلوب ديلوكس
        </Button>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/m7.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class="  text-secondary-foreground text-xs w-[18vw] h-7 lg:h-fit "
        >
          صحن فاهيتا
        </Button>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/m9.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class="  text-secondary-foreground text-xs w-[18vw] h-7 lg:h-fit "
        >
          صينية بطاطس
        </Button>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/m10.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class="  text-secondary-foreground text-xs  w-[18vw] h-7 lg:h-fit "
        >
          معكرونة لحم
        </Button>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/m11.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class="  text-secondary-foreground text-xs w-[18vw] h-7 lg:h-fit "
        >
          بيتزا بالشوفان
        </Button>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/main dishes .jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class="  text-secondary-foreground text-xs w-[20vw] h-7 lg:h-fit "
        >
          فطيرة بطاطس
        </Button>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/m12.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class="  text-secondary-foreground text-xs w-[18vw] h-7 lg:h-fit "
        >
          معكرونة بالصلصة
        </Button>
      </span>
    </div>
  </div>
</div>
