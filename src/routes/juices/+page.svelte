<script>
  import Button from "$lib/components/ui/button/button.svelte";
  import * as Dialog from "$lib/components/ui/dialog";
  import { buttonVariants } from "$lib/components/ui/button";
</script>

<div class="">
  <div class="flex flex-col items-center pb-20">
    <div
      class="
      lg:h-fit w-auto ring-1 ring-secondary lg:p-10 lg:gap-16 lg:gap-y-4  bg-gradient-to-r from-background/90 to-primary/50 dark:bg-primary shadow-[0_20px_60px_-15px_rgba(0,0,0,0.7)] rounded-xl
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
            <Dialog.Content>
              <Dialog.Header class="">
                <Dialog.Title>مانجو وأناناس</Dialog.Title>
              </Dialog.Header>
              <div class="  text-sm ">
                <section>
                  <h2 class="text-primary font-bold py-1">المكونات:</h2>
                  <ul>
                    <li>-نصف كوب اناناس طازج</li>
                    <li>-حبة مانجو طازجة</li>
                    <li>-1 م ك عسل (ويمكن زيادة سكر دايت)</li>
                    <li>-ثلج</li>
                    <li>-½ كوب ماء بارد</li>
                  </ul>
                </section>
                <section class="pt-3">
                  <h2 class=" text-primary font-bold ">الطريقة:</h2>
                  <ol class="">
                    <li>1. ينظف الأناناس ويقشر ويقطع</li>
                    <li>2. تقشر المانجو وتقطع</li>
                    <li>3. تخلط جميع المقادير بالخلاط ثم نصفيهم</li>
                    <li>4. نسكبهم في كاسات التقديم</li>
                    <li></li>
                  </ol>
                </section>
                <div class="pt-3">
                  <h2 class="text-primary font-bold ">
                    السعرات الحرارية:
                  </h2>
                  <p>-حوالي 336 سعرة حرارية</p>
                </div>
              </div>
              <div></div>
            </Dialog.Content>
          </Dialog.Root>
        </span>
      </div>
      <div class=" w-[15vw] h-auto rounded-xl">
        <img src="/j2.JPG" alt="" class=" rounded-xl" />
        <span class="flex justify-center py-2 pr-2">
          <Dialog.Root>
            <Dialog.Trigger
              class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
                { variant: 'outline' },
              )}">برتقال وجزر</Dialog.Trigger
            >
            <Dialog.Content>
              <Dialog.Header class="">
                <Dialog.Title>برتقال وجزر</Dialog.Title>
              </Dialog.Header>
              <div class=" text-sm ">
                <section>
                  <h2 class="text-primary font-bold py-1">المكونات:</h2>
                  <ul>
                    <li>-2 برتقال</li>
                    <li>-2 جزر</li>
                    <li>-عصرة ليمونه</li>
                    <li>-كوب ماء</li>
                  </ul>
                </section>
                <section class="pt-3">
                  <h2 class=" text-primary font-bold ">الطريقة:</h2>
                  <ol class="">
                    <li>1. ينظف الجزر ويقطع</li>
                    <li>
                      2. يقشر البرتقال ويقطع ونضيف عليه الماء وعصير الليمون
                    </li>
                    <li>3. تخلط جميع المكونات بالخلاط الكهربائي</li>
                    <li></li>
                    <li>4. نسكبهم في كاسات التقديم</li>
                  </ol>
                </section>
                <div class="pt-3">
                  <h2 class="text-primary font-bold ">
                    السعرات الحرارية:
                  </h2>
                  <p>-حوالي 125 سعرة حرارية.</p>
                </div>
              </div>
              <div></div>
              <div></div>
              <div></div>
            </Dialog.Content>
          </Dialog.Root>
        </span>
      </div>
      <div class=" w-[15vw] h-auto rounded-xl">
        <img src="/j3.JPG" alt="" class=" rounded-xl" />
        <span class="flex justify-center py-2 pr-2">
          <Dialog.Root>
            <Dialog.Trigger
              class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
                { variant: 'outline' },
              )}">فراولة وموز</Dialog.Trigger
            >
            <Dialog.Content>
              <Dialog.Header class="">
                <Dialog.Title>فراولة وموز</Dialog.Title>
              </Dialog.Header>
              <div class=" text-sm">
                <section>
                  <h2 class="text-primary font-bold py-1">المكونات:</h2>
                  <ul>
                    <li>-نصف كوب من الفراولة</li>
                    <li>-موزة واحدة</li>
                    <li>-نصف كوب حليب لوز</li>
                    <li>-ملعقة عسل كبيرة</li>
                  </ul>
                </section>
                <section class="pt-3">
                  <h2 class=" text-primary font-bold ">الطريقة:</h2>
                  <ol class="">
                    <li>1. تنظف الموزة وتقشر</li>
                    <li>2. تنظف الفراولة ونضعها في الخلاط</li>
                    <li>3. قم بخلط جميع المكونات في الخلاط الكهربائي</li>
                  </ol>
                </section>
                <div class="pt-3">
                  <h2 class="text-primary font-bold ">
                    السعرات الحرارية:
                  </h2>
                  <p>حوالي 217 سعرة حرارية.</p>
                </div>
              </div>
              <div></div>
              <div></div>
              <div></div>
            </Dialog.Content>
          </Dialog.Root>
        </span>
      </div>
      <div class=" w-[15vw] h-auto rounded-xl">
        <img src="/juice .jpg" alt="" class=" rounded-xl" />
        <span class="flex justify-center py-2 pr-2">
          <Dialog.Root>
            <Dialog.Trigger
              class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
                { variant: 'outline' },
              )}">بطيخ ونعناع</Dialog.Trigger
            >
            <Dialog.Content>
              <Dialog.Header class="">
                <Dialog.Title>بطيخ ونعناع</Dialog.Title>
              </Dialog.Header>
              <div class="   text-sm">
                <section>
                  <h2 class="text-primary font-bold py-1">المكونات:</h2>
                  <ul>
                    <li>-كوب من قطع البطيخ</li>
                    <li>-حفنة من أوراق النعناع</li>
                  </ul>
                </section>
                <section class="pt-3">
                  <h2 class=" text-primary font-bold ">الطريقة:</h2>
                  <ol class="">
                    <li>1. نقشر البطيخ ونقطعه لمكعبات</li>
                    <li>2. ننزع اوراق النعناع ونغسلها جيدًا</li>
                    <li>3. نخلط المكونات في الخلاط الكهربائي</li>
                  </ol>
                </section>
                <div class="pt-3">
                  <h2 class="text-primary font-bold ">
                    السعرات الحرارية:
                  </h2>
                  <p>حوالي 45-50 سعرة حرارية.</p>
                </div>
              </div>
              <div></div>
              <div></div>
              <div></div>
            </Dialog.Content>
          </Dialog.Root>
        </span>
      </div>
      <div class=" w-[15vw] h-auto rounded-xl">
        <img src="/j4.JPG" alt="" class=" rounded-xl" />
        <span class="flex justify-center py-2 pr-2">
          <Dialog.Root>
            <Dialog.Trigger
              class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
                { variant: 'outline' },
              )}">عنب وتوت</Dialog.Trigger
            >
            <Dialog.Content>
              <Dialog.Header class="">
                <Dialog.Title>عنب وتوت</Dialog.Title>
              </Dialog.Header>
              <div class=" text-sm">
                <section>
                  <h2 class="text-primary font-bold py-1">المكونات:</h2>
                  <ul>
                    <li>-نصف كوب من العنب الأحمر</li>
                    <li>-نصف كوب من التوت المشكل</li>
                    <li>-ماء</li>
                    <li>-ثلج</li>
                  </ul>
                </section>
                <section class="pt-3">
                  <h2 class=" text-primary font-bold ">الطريقة:</h2>
                  <ol class="">
                    <li>
                      1. ضع التوت الأزرق، والعنب الأحمر في وعاء الخلاط
                      الكهربائي.
                    </li>
                    <li>
                      2. أضيف الماء، واخلط المكونات جيداً حتى تتجانس تماماً.
                    </li>
                    <li>
                      3. وزع مكعبات الثلج في أكواب التقديم، ثم صُب العصير وقدميه
                      بارداً.
                    </li>
                  </ol>
                </section>
                <div class="pt-3">
                  <h2 class="text-primary font-bold ">
                    السعرات الحرارية:
                  </h2>
                  <p>حوالي 85-100 سعرة حرارية.</p>
                </div>
              </div>
              <div></div>
              <div></div>
              <div></div>
            </Dialog.Content>
          </Dialog.Root>
        </span>
      </div>
      <div class=" w-[15vw] h-auto rounded-xl">
        <img src="/j5.JPG" alt="" class=" rounded-xl" />
        <span class="flex justify-center py-2 pr-2">
          <Dialog.Root>
            <Dialog.Trigger
              class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
                { variant: 'outline' },
              )}">كيوي وأناناس</Dialog.Trigger
            >
            <Dialog.Content>
              <Dialog.Header class="">
                <Dialog.Title>كيوي وأناناس</Dialog.Title>
              </Dialog.Header>
              <div class=" text-sm">
                <section>
                  <h2 class="text-primary font-bold py-1">المكونات:</h2>
                  <ul>
                    <li>-2 كيوي</li>
                    <li>-150 غرام أناناس</li>
                    <li>-ماء وثلج(حسب الرغبة)</li>
                    <li>-ثلج</li>
                  </ul>
                </section>
                <section class="pt-3">
                  <h2 class=" text-primary font-bold ">الطريقة:</h2>
                  <ol class="">
                    <li>1. قم بتقشير الكيوي والأناناس وتقطيعهم إلى مكعبات.</li>
                    <li>2. ضع القطع في عصارة العصائر ومن ثم في كاسات.</li>
                    <li>
                      3. يمكن اضافة العسل إذا رغبت بذلك(واحسب السعرات مع
                      المجموع)
                    </li>
                  </ol>
                </section>
                <div class="pt-3">
                  <h2 class="text-primary font-bold ">
                    السعرات الحرارية:
                  </h2>
                  <p>حوالي 175-180 سعرة حرارية.</p>
                </div>
              </div>
              <div></div>
              <div></div>
              <div></div>
            </Dialog.Content>
          </Dialog.Root>
        </span>
      </div>
    </div>
  </div>
</div>
