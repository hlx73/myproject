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
   <img src="/sweets.jpg" alt="" class=" rounded-xl" />
   <span class="flex justify-center py-2 pr-2">
    <Dialog.Root>
     <Dialog.Trigger
      class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants({
       variant: 'outline',
      })}">بودينج الشوكولاتة</Dialog.Trigger
     >
     <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
      <Dialog.Header class="">
       <Dialog.Title class="flex justify-center text-secondary-foreground"
        >بودينج الشوكولاتة
       </Dialog.Title>
      </Dialog.Header>
      <div class="flex justify-center items-center">
       <ScrollArea
        class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4"
       >
        <div class=" lg:text-sm text-xs">
         <section>
          <h2 class="text-secondary-foreground py-1">المكونات:</h2>
          <p class="text-secondary-foreground py-1">للكيك:</p>
          <ul>
           <li>- شوفان أو دقيق أبيض: 30 جرام</li>
           <li>
            - بروتين باودر: 20 جرام (أو حليب بروتين 70 جرام مع بيضة إذا رغبت في
            زيادة البروتين)
           </li>
           <li>- باكينج باودر: 2 جرام (ربع ملعقة صغيرة)</li>
           <li>- كاكاو بودرة: 8 جرام (ملعقة صغيرة)</li>
           <li>- سكر ستيفيا: 3 أظرف</li>
           <li>- نشا: 5 جرام</li>
           <li>- حليب خالي الدسم: ثلاث أرباع كوب تقريباً</li>
           <li>- نسكافيه: 1 جرام</li>
           <li>- فواكه: فراولة ومزيج توت 100 جرام (نصف كوب)</li>
           <li>- بيكان: 1 حبة</li>
           <li>- لوز مبشور: 3 جرام</li>
          </ul>
         </section>
         <section class="py-3">
          <h2 class=" text-secondary-foreground py-1">لطريقة البودينغ:</h2>
          <ol class="">
           <li>- كاكاو: 3 جرام</li>
           <li>- حليب: مقدار كافٍ</li>
           <li>- نسكافيه: كمية حسب الرغبة</li>
           <li>- سكر ستيفيا: حسب الرغبة</li>
           <li>- نشا: مذاب في ماء</li>
          </ol>
         </section>
         <section class="py-3">
          <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
          <p class="text-secondary-foreground py-1">الكيك:</p>

          <ol class="">
           <li></li>
           <li>
            1. في وعاء، اخلط البيض، الشوفان، 30 جم من الزبادي اليوناني، القرفة،
            والمحلي.
           </li>
           <li>
            2. اطبخ الخليط على الصاج من الجهتين، ثم قطّعه إلى قطع عشوائية.
           </li>
           <li>
            3. في صحن التقديم، ضع 150 جم زبادي يوناني مع محلي حسب الرغبة.
           </li>
           <li>
            4. أضف قطع الشوفان التي حضرتها، والفواكه، وزبدة الفول السوداني إذا
            كنت تستخدمها.
           </li>
          </ol>
         </section>
         <section class="py-4">
          <h2 class="text-secondary-foreground py-1">السعرات الحرارية:</h2>
          <p>-388 سعرة حرارية</p>
         </section>
        </div>
       </ScrollArea>
      </div>
     </Dialog.Content>
    </Dialog.Root>
   </span>
  </div>
  <div class=" w-[15vw] h-auto rounded-xl">
   <img src="/sw1.jpg" alt="" class=" rounded-xl" />
   <span class="flex justify-center py-2 pr-2">
    <Dialog.Root>
     <Dialog.Trigger
      class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants({
       variant: 'outline',
      })}">ميني بانكيك</Dialog.Trigger
     >
     <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
      <Dialog.Header class="">
       <Dialog.Title class="flex justify-center text-secondary-foreground"
        >ميني بانكيك
       </Dialog.Title>
      </Dialog.Header>
      <div class="flex justify-center items-center">
       <ScrollArea
        class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4"
       >
        <div class=" lg:text-sm text-xs">
         <section>
          <h2 class="text-secondary-foreground py-1">المكونات:</h2>
          <p class="text-secondary-foreground py-1">1. خليط الشوفان:</p>
          <ul>
           <li>- شوفان مطحون: 50 جرام (5 ملاعق)</li>
           <li>- ماء: 70 مل</li>
           <li>- باكينج بودر: 3 جرام (ربع ملعقة صغيرة)</li>
           <li>- بياض بيضتين: 71 جرام (أو بيضة واحدة: 30 جرام)</li>
           <li>- سكوب بروتين: 25 جرام (اختياري)</li>
          </ul>
         </section>
         <section class="py-2">
          <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
          <ol class="">
           <li>
            1. امزج الشوفان المطحون مع الماء، باكينج بودر، وبياض البيض (أو
            البيضة الكاملة) في وعاء.
           </li>
           <li>2. أضف بروتين باودر إذا رغبت، ثم قلّب الخليط جيداً.</li>
           <li>
            3. ضع الخليط في المايكروويف على درجة حرارة عالية لمدة 30 ثانية.
           </li>
          </ol>
         </section>
         <section class="py-2">
          <h2 class=" text-secondary-foreground py-1">للكاسترد:</h2>
          <p>- 60 مل من الحليب قليل الدسم</p>
          <p>- 1 ملعقة كبيرة من مسحوق الكاسترد</p>
          <p>- ملعقة صغيرة من سكر ستيفيا</p>
          <p>- نقطة من نكهة الموز (تعطي طعم رائع)</p>
          <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
          <p>
           اخلطي جميع المكونات معًا جيدًا، ثم ضعي الخليط في- الميكروويف لمدة 30
           ثانية.
          </p>
         </section>
         <section class="py-2">
          <h2 class=" text-secondary-foreground py-1">سعرات خليط الشوفان:</h2>
          <p>- 325 سعرة حرارية (بدون كاسترد)</p>
          <p>- مع الكاسترد: 366 سعرة حرارية</p>
         </section>
         <section>
          <h2 class="text-secondary-foreground py-1">إضافات الفاكهة:</h2>
          <ul>
           <li>- خليط الفراولة:أضف 24 جرام من الفراولة إلى نصف الخليط</li>
           <li>-السعرات:28 سعرة حرارية</li>

           <li>-خليط التفاح:أضف 10 جرام من التفاح إلى النصف الآخر</li>
           <li>-السعرات:24 سعرة حرارية</li>
          </ul>
         </section>
         <section class="py-3">
          <h2 class="text-secondary-foreground py-1">
           2. بانكيك الموز واللوز:
          </h2>
          <ul>
           <li>- زبدة اللوز: 4 جرام</li>
           <li>- بروتين باودر: 4 جرام (اختياري)</li>
           <li>- موز: 11 جرام</li>
           <li>- شرائح اللوز: نصف جرام</li>
           <li>- ماء: 6 جرام (إذا استخدمت بروتين باودر)</li>
           <li class="py-1">-السعرات:41 سعرة حرارية</li>
           <li></li>
          </ul>
         </section>
         <section class="py-2">
          <h2 class="text-secondary-foreground py-1">3. بانكيك المانجو:</h2>
          <ul>
           <li>- زبادي يوناني: 22 جرام</li>
           <li>- بروتين باودر: 6 جرام (اختياري)</li>
           <li>- مانجو: 16 جرام</li>
           <li>-السعرات:47 سعرة حرارية</li>
          </ul>
         </section>
         <section class="py-2">
          <h2 class="text-secondary-foreground py-1">4. بانكيك التمر:</h2>
          <ul>
           <li>
            - تمر: 10 جرام (حبة مقسمة إلى نصفين، نصف للتزيين ونصف لحشو البانكيك)
           </li>
           <li>- جبن فيتا: 2 جرام</li>
           <li>-السعرات:49 سعرة حرارية</li>
          </ul>
         </section>
        </div>
       </ScrollArea>
      </div>
     </Dialog.Content>
    </Dialog.Root>
   </span>
  </div>
  <div class=" w-[15vw] h-auto rounded-xl">
   <img src="/sw2.jpg" alt="" class=" rounded-xl" />
   <span class="flex justify-center py-2 pr-2">
    <Dialog.Root>
     <Dialog.Trigger
      class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants({
       variant: 'outline',
      })}">كوكيز</Dialog.Trigger
     >
     <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
      <Dialog.Header class="">
       <Dialog.Title class="flex justify-center text-secondary-foreground"
        >كوكيز
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
           <li>- 30 جرام زبدة فول سوداني</li>
           <li>- صفار بيضة</li>
           <li>- ظرف سكر ستيفيا</li>
           <li>- رشة فانيلا</li>
           <li>- 2 جرام باكينج باودر</li>
           <li>- رشة بيكربونات الصوديوم</li>
           <li>- 40 جرام دقيق أو شوفان مطحون</li>
           <li>- رشة ملح</li>
           <li>- 15 جرام شوكولاتة</li>
          </ul>
         </section>
         <section class="py-2">
          <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
          <ol class="">
           <li>
            1. ذوّب زبدة الفول السوداني في المايكروويف واتركها لتبرد قليلاً.
           </li>
           <li>2. أضف صفار البيضة وسكر ستيفيا إلى الزبدة وامزجهم جيداً.
           </li>
           <li>3. أضف الدقيق (أو الشوفان المطحون)، البيكينج باودر، البيكربونات، والملح وامزج حتى تتجانس المكونات.</li>
           <li>4. إذا كان الخليط جافاً، أضف 10 مل من الماء تدريجياً حتى يصبح الخليط قابلاً للتشكيل.
           </li>
           <li>5. أضف الشوكولاتة المقطعة أو المذابة إلى الخليط واخلطها جيداً.
           </li>
           <li>6. قسم الخليط إلى 4 قطع وضعه في صينية مدهونة أو مبطنة بورق زبدة.</li>
           <li>7. اخبز في فرن مسبق التسخين على حرارة 180 درجة مئوية لمدة 7 دقائق من الأسفل ودقيقتين من الأعلى.</li>
          </ol>
         </section>
         <section class="py-2">
         <h2 class="text-secondary-foreground py-1">السعرات الحرارية:</h2>
         <p>-109 سعرة حرارية</p>
        </section>
        </div>
       </ScrollArea>
      </div>
     </Dialog.Content>
    </Dialog.Root>
   </span>
  </div>
  <div class=" w-[15vw] h-auto rounded-xl">
   <img src="/sw3.jpg" alt="" class=" rounded-xl" />
   <span class="flex justify-center py-2 pr-2">
    <Dialog.Root>
     <Dialog.Trigger
      class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants({
       variant: 'outline',
      })}">فاكتوريا كيك</Dialog.Trigger
     >
     <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
      <Dialog.Header class="">
       <Dialog.Title class="flex justify-center text-secondary-foreground"
        >فاكتوريا كيك
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
           <li>- زبادي يوناني: 100 جرام</li>
           <li>- شوفان مطحون: 30 جرام</li>
           <li>- باكينج باودر: 5 جرام</li>
           <li>- بروتين باودر (اختياري): 30 جرام (117 سعرة)</li>
           <li>- مجموعة توت: 100 جرام</li>
           <li>- نشا: 3 جرام</li>
           <li>- جبن فيلادلفيا لايت: 40 جرام</li>
          </ul>
         </section>
         <section class="py-2">
          <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
          <p class=" text-secondary-foreground py-1">1. تحضير الكيك:</p>
          <ol class="">
           <li>
            - اخلط الشوفان المطحون، باكينج باودر، بروتين باودر (إذا استخدمته)، وزبادي يوناني. أضف محلي فانيلا أو سكر دايت مع فانيلا سائلة أو بودرة.
           </li>
           <li>- أضف ماء بكمية 60 مل.</li>
           <li>   - صب الخليط في قالب واخبزه في فرن مسبق التسخين على درجة حرارة 180 مئوية لمدة 15 دقيقة. ثم، ازل الكيك من الفرن واتركه ليبرد في الفريزر لمدة 15 دقيقة.
           </li>
          </ol>
         </section>
         <section class="py-2">
          <h2 class=" text-secondary-foreground py-1">2. تحضير الكريمة البيضاء:</h2>
          <p>   - اخلط زبادي يوناني مع جبن فيلادلفيا لايت.</p>
         </section>
         <section class="py-2">
          <h2 class=" text-secondary-foreground py-1">3. تحضير مربى التوت:</h2>
          <p>- ضع مزيج التوت على النار مع سكر دايت وأضف قليل من الماء لمنع احتراقه.</p>
          <p>- أضف نشا مذوب في 20 مل من الماء، وخلط جيداً حتى يتماسك.
          </p>
         </section>
         <section>
          <h2 class="text-secondary-foreground py-1">4. التجميع:</h2>
          <ul>
           <li>- بين كل طبقة من الكيك، ضع طبقة من الكريمة البيضاء ومربى التوت.</li>
           <li>- زين الوجه بالفراولة، التوت، ونعناع إذا رغبت.</li>
          </ul>
         </section>
         <section class="py-2">
         <h2 class="text-secondary-foreground py-1">السعرات الحرارية:</h2>
         <p>-422 سعرة حرارية</p>
        </section>
        </div>
       </ScrollArea>
      </div>
     </Dialog.Content>
    </Dialog.Root>
   </span>
  </div>
  <div class=" w-[15vw] h-auto rounded-xl">
   <img src="/sw4.jpg" alt="" class=" rounded-xl" />
   <span class="flex justify-center py-2 pr-2">
    <Dialog.Root>
     <Dialog.Trigger
      class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants({
       variant: 'outline',
      })}">تشيز كيك الفراولة</Dialog.Trigger
     >
     <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
      <Dialog.Header class="">
       <Dialog.Title class="flex justify-center text-secondary-foreground"
        >تشيز كيك فراولة
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
           <li>- 50 جرام من بسكويت سانتغيري خالي من السكر</li>
           <li>- 25 جرام من جبنة فيلادلفيا لايت</li>
           <li>
            - 80 جرام من الزبادي اليوناني خالي الدسم           </li>
           <li>- 4 جرام من النشا</li>
           <li>- 45 جرام من البيض (حوالي بيضة واحدة)</li>
           <li>- 100 جرام من الفراولة</li>
          </ul>
         </section>
         <section class="py-2">
          <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
          <p class=" text-secondary-foreground py-1"></p>
          <ol class="">
           <li>
            1. امزج الشوفان المطحون مع الماء، باكينج بودر، وبياض البيض (أو
            البيضة الكاملة) في وعاء.
           </li>
           <li>2. أضف بروتين باودر إذا رغبت، ثم قلّب الخليط جيداً.</li>
           <li>
            3. ضع الخليط في المايكروويف على درجة حرارة عالية لمدة 30 ثانية.
           </li>
          </ol>
         </section>
         <section class="py-2">
          <h2 class=" text-secondary-foreground py-1">للكاسترد:</h2>
          <p>- 60 مل من الحليب قليل الدسم</p>
          <p>- 1 ملعقة كبيرة من مسحوق الكاسترد</p>
          <p>- ملعقة صغيرة من سكر ستيفيا</p>
          <p>- نقطة من نكهة الموز (تعطي طعم رائع)</p>
          <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
          <p>
           اخلطي جميع المكونات معًا جيدًا، ثم ضعي الخليط في- الميكروويف لمدة 30
           ثانية.
          </p>
         </section>
         <section class="py-2">
          <h2 class=" text-secondary-foreground py-1">سعرات خليط الشوفان:</h2>
          <p>- 325 سعرة حرارية (بدون كاسترد)</p>
          <p>- مع الكاسترد: 366 سعرة حرارية</p>
         </section>
         <section>
          <h2 class="text-secondary-foreground py-1">إضافات الفاكهة:</h2>
          <ul>
           <li>- خليط الفراولة:أضف 24 جرام من الفراولة إلى نصف الخليط</li>
           <li>-السعرات:28 سعرة حرارية</li>

           <li>-خليط التفاح:أضف 10 جرام من التفاح إلى النصف الآخر</li>
           <li>-السعرات:24 سعرة حرارية</li>
          </ul>
         </section>
         <section class="py-3">
          <h2 class="text-secondary-foreground py-1">
           2. بانكيك الموز واللوز:
          </h2>
          <ul>
           <li>- زبدة اللوز: 4 جرام</li>
           <li>- بروتين باودر: 4 جرام (اختياري)</li>
           <li>- موز: 11 جرام</li>
           <li>- شرائح اللوز: نصف جرام</li>
           <li>- ماء: 6 جرام (إذا استخدمت بروتين باودر)</li>
           <li class="py-1">-السعرات:41 سعرة حرارية</li>
           <li></li>
          </ul>
         </section>
         <section class="py-2">
          <h2 class="text-secondary-foreground py-1">3. بانكيك المانجو:</h2>
          <ul>
           <li>- زبادي يوناني: 22 جرام</li>
           <li>- بروتين باودر: 6 جرام (اختياري)</li>
           <li>- مانجو: 16 جرام</li>
           <li>-السعرات:47 سعرة حرارية</li>
          </ul>
         </section>
         <section class="py-2">
          <h2 class="text-secondary-foreground py-1">4. بانكيك التمر:</h2>
          <ul>
           <li>
            - تمر: 10 جرام (حبة مقسمة إلى نصفين، نصف للتزيين ونصف لحشو البانكيك)
           </li>
           <li>- جبن فيتا: 2 جرام</li>
           <li>-السعرات:49 سعرة حرارية</li>
          </ul>
         </section>
        </div>
       </ScrollArea>
      </div>
     </Dialog.Content>
    </Dialog.Root>
   </span>
  </div>
  <div class=" w-[15vw] h-auto rounded-xl">
   <img src="/sw5.jpg" alt="" class=" rounded-xl" />
   <span class="flex justify-center py-2">
    <Button
     variant="outline"
     href="/breakfast"
     class=" text-secondary-foreground text-xs w-[18vw] h-7 lg:h-fit "
    >
     حلى الأوريو
    </Button>
   </span>
  </div>
  <div class=" w-[15vw] h-auto rounded-xl">
   <img src="/sw6.jpg" alt="" class=" rounded-xl" />
   <span class="flex justify-center py-2">
    <Button
     variant="outline"
     href="/breakfast"
     class=" text-secondary-foreground text-xs w-[18vw] h-7 lg:h-fit "
    >
     حلى الايسكريم
    </Button>
   </span>
  </div>
  <div class=" w-[15vw] h-auto rounded-xl">
   <img src="/sw7.jpg" alt="" class=" rounded-xl" />
   <span class="flex justify-center py-2">
    <Button
     variant="outline"
     href="/breakfast"
     class=" text-secondary-foreground text-xs w-[18vw] h-7 lg:h-fit "
    >
     مافن
    </Button>
   </span>
  </div>
  <div class=" w-[15vw] h-auto rounded-xl">
   <img src="/sw8.jpg" alt="" class=" rounded-xl" />
   <span class="flex justify-center py-2">
    <Button
     variant="outline"
     href="/breakfast"
     class=" text-secondary-foreground text-xs  w-[18vw] h-7 lg:h-fit "
    >
     ايسكريم التوت
    </Button>
   </span>
  </div>
  <div class=" w-[15vw] h-auto rounded-xl">
   <img src="/sw9.jpg" alt="" class=" rounded-xl" />
   <span class="flex justify-center py-2">
    <Button
     variant="outline"
     href="/breakfast"
     class=" text-secondary-foreground text-xs w-[18vw] h-7 lg:h-fit "
    >
     حلى الجيلي
    </Button>
   </span>
  </div>
  <div class=" w-[15vw] h-auto rounded-xl">
   <img src="/sw10.jpg" alt="" class=" rounded-xl" />
   <span class="flex justify-center py-2">
    <Button
     variant="outline"
     href="/breakfast"
     class=" text-secondary-foreground text-xs w-[20vw] h-7 lg:h-fit "
    >
     لافا كيك
    </Button>
   </span>
  </div>
  <div class=" w-[15vw] h-auto rounded-xl">
   <img src="/sw11.jpg" alt="" class=" rounded-xl" />
   <span class="flex justify-center py-2">
    <Button
     variant="outline"
     href="/breakfast"
     class=" text-secondary-foreground text-xs w-[18vw] h-7 lg:h-fit "
    >
     سينابون بانكيك
    </Button>
   </span>
  </div>
  <div class=" w-[15vw] h-auto rounded-xl">
   <img src="/sw12.jpg" alt="" class=" rounded-xl" />
   <span class="flex justify-center py-2">
    <Button
     variant="outline"
     href="/breakfast"
     class=" text-secondary-foreground text-xs w-[18vw] h-7 lg:h-fit "
    >
     كيكة كندر
    </Button>
   </span>
  </div>
  <div class=" w-[15vw] h-auto rounded-xl">
   <img src="/sw14.jpg" alt="" class=" rounded-xl" />
   <span class="flex justify-center py-2">
    <Button
     variant="outline"
     href="/breakfast"
     class=" text-secondary-foreground text-xs w-[18vw] h-7 lg:h-fit ring"
    >
     كيكة ليمون و توت
    </Button>
   </span>
  </div>
 </div>
</div>
