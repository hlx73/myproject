<script lang="ts">
  import { buttonVariants } from "$lib/components/ui/button";
  import Button from "$lib/components/ui/button/button.svelte";
  import * as Dialog from "$lib/components/ui/dialog";
  import { ScrollArea } from "$lib/components/ui/scroll-area/index.js";
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
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}">كرات التمر</Dialog.Trigger
          >
          <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >كرات التمر
              </Dialog.Title>
            </Dialog.Header>
            <div class="flex justify-center items-center">
              <ScrollArea
                class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4"
              >
                <div class=" lg:text-sm text-xs">
                  <section>
                    <h2 class="text-secondary-foreground py-1">المكونات:</h2>
                    <ul>
                      <li>- 160 جم تمر معجون.</li>
                      <li>- 30 جم كاجو.</li>
                      <li>- 20 جم جوز هند.</li>
                      <li>- ملعقة كبيرة زبدة فول سوداني (حوالي 32 جم).</li>
                      <li>- رشة هيل مطحون.</li>
                      <li></li>
                      <li>- 40 جرام دقيق أو شوفان مطحون</li>
                      <li>- رشة ملح</li>
                      <li>- 15 جرام شوكولاتة</li>
                    </ul>
                  </section>
                  <section class="py-2">
                    <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
                    <ol class="">
                      <li>
                        1. ضع جميع المكونات في محضرة الطعام واخلطها حتى تتجانس.
                      </li>
                      <li>
                        2. شكّل الخليط إلى كرات متساوية الحجم. يمكنك صنع حوالي 16 كرة.
                      </li>
                      <li>3. زين الكرات بزبدة الفول السوداني وجوز الهند.
                        </li>
                    </ol>
                  </section>
                  <section class="py-2">
                    <h2 class="text-secondary-foreground py-1">
                      السعرات الحرارية:
                    </h2>
                    <p>- السعرات الحرارية لكل كرة: 58 سعرة حرارية.</p>
                    <p>- السعرات الحرارية للكمية الكاملة: 937 سعرة حرارية.</p>
                  </section>
                </div>
              </ScrollArea>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/s5.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[14vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}">كرات الحلوى</Dialog.Trigger
          >
          <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >كرات الحلوى
              </Dialog.Title>
            </Dialog.Header>
            <div class="flex justify-center items-center">
              <ScrollArea
                class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4"
              >
                <div class=" lg:text-sm text-xs">
                  <section>
                    <h2 class="text-secondary-foreground py-1">المكونات:</h2>
                    <ul>
                      <li>- شوفان مطحون.</li>
                      <li>- زبدة فول سوداني.</li>
                      <li>- جوز هند مبشور.</li>
                      <li>- شوكولاتة داكنة.</li>
                      <li>- سكر ستيفيا أو عسل.</li>
                    </ul>
                  </section>
                  <section class="py-2">
                    <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
                    <ol class="">
                      <li>
                        1. اخلط جميع المكونات معًا حتى تتجانس.

                      </li>
                      <li>
                        2. شكّل الخليط إلى كرات صغيرة.
                      </li>
                      <li>
                        3. زين الكرات بالشوكولاتة الداكنة أو نوتيلا صحية.   البيكربونات، والملح وامزج حتى تتجانس المكونات.
                      </li>
                     
                    </ol>
                  </section>
                  <section class="py-2">
                    <h2 class="text-secondary-foreground py-1">
                      ملاحظة :
                    </h2>
                    <p>يمكنك تعديل كميات المكونات حسب رغبتك للحصول على الكمية التي تريدها.</p>
                  </section>
                </div>
              </ScrollArea>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/s4.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[14vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}">شوكولاتة دارك</Dialog.Trigger
          >
          <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >شوكولاتة دارك
              </Dialog.Title>
            </Dialog.Header>
            <div class="flex justify-center items-center">
              <ScrollArea
                class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4"
              >
                <div class=" text-sm ">
                  <section>
                    <h2 class="text-secondary-foreground py-1">المكونات:</h2>
                    <ul >
                      <li>- 21 حبة مكسرات (اخترت 3 أنواع: 7 حبات من كل نوع).</li>
                      <li>  - جوز.</li>
                      <li>  - بيكان.</li>
                      <li>  - لوز.</li>
                      <li>- شوكولاتة داكنة.</li>
                      <li>- رشة ملح.</li>
                    </ul>
                  </section>
                  <section class="py-2">
                    <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
                    <ol class="">
                      <li>
                        1. ذوّب الشوكولاتة في الميكروويف لمدة دقيقة ونصف. تأكد من إخراجها كل 30 ثانية لتحريكها.
                      </li>
                      <li>
                        2. غطِّ حبات الجوز بالشوكولاتة، ثم ضعها في صحن.
                      </li>
                      <li>3. غطِّ حبات البيكان بالشوكولاتة وأضفها إلى الجوز.
                      </li>
                     <li>
                      4. أخيرًا، غطِّ حبات اللوز بالشوكولاتة وأضفها إلى باقي المكسرات.
                    </li>
                    <li>
                      5. كرر العملية حتى تنتهي الكمية.
                    </li>
                    <li>6. في النهاية، رشّ الملح على المكسرات.
                    </li>
                    <li>
                      7. ضعها في الفريزر أو الثلاجة لبضع دقائق حتى تتماسك أكثر.
                    </li>
                    </ol>
                  </section>
                  <section class="py-2">
                    <h2 class="text-secondary-foreground py-1">
                      السعرات الحرارية: :
                    </h2>
                    <p>- سعرات المجموعة الواحدة (3 حبات مكسرات): 50 - 60 سعرة حرارية، حسب نوع المكسرات والشوكولاتة المستخدمة.</p>
                  </section>
                </div>
              </ScrollArea>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/s2.jpg" alt="" class=" rounded-xl" />
     <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class="  text-secondary-foreground  text-xs w-[20vw] h-7 lg:h-fit "
        >
          بليلة
        </Button>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/s7.jpg" alt="" class=" rounded-xl" />
     <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class="  text-secondary-foreground  text-xs w-[20vw] h-7 lg:h-fit "
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
          class="  text-secondary-foreground text-xs w-[20vw] h-7 lg:h-fit "
        >
          فراولة و شوكولاتة
        </Button>
      </span>
    </div>
  </div>
</div>
