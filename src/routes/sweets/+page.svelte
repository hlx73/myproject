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
           <li>2. أضف صفار البيضة وسكر ستيفيا إلى الزبدة وامزجهم جيداً.</li>
           <li>
            3. أضف الدقيق (أو الشوفان المطحون)، البيكينج باودر، البيكربونات،
            والملح وامزج حتى تتجانس المكونات.
           </li>
           <li>
            4. إذا كان الخليط جافاً، أضف 10 مل من الماء تدريجياً حتى يصبح الخليط
            قابلاً للتشكيل.
           </li>
           <li>
            5. أضف الشوكولاتة المقطعة أو المذابة إلى الخليط واخلطها جيداً.
           </li>
           <li>
            6. قسم الخليط إلى 4 قطع وضعه في صينية مدهونة أو مبطنة بورق زبدة.
           </li>
           <li>
            7. اخبز في فرن مسبق التسخين على حرارة 180 درجة مئوية لمدة 7 دقائق من
            الأسفل ودقيقتين من الأعلى.
           </li>
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
            - اخلط الشوفان المطحون، باكينج باودر، بروتين باودر (إذا استخدمته)،
            وزبادي يوناني. أضف محلي فانيلا أو سكر دايت مع فانيلا سائلة أو بودرة.
           </li>
           <li>- أضف ماء بكمية 60 مل.</li>
           <li>
            - صب الخليط في قالب واخبزه في فرن مسبق التسخين على درجة حرارة 180
            مئوية لمدة 15 دقيقة. ثم، ازل الكيك من الفرن واتركه ليبرد في الفريزر
            لمدة 15 دقيقة.
           </li>
          </ol>
         </section>
         <section class="py-2">
          <h2 class=" text-secondary-foreground py-1">
           2. تحضير الكريمة البيضاء:
          </h2>
          <p>- اخلط زبادي يوناني مع جبن فيلادلفيا لايت.</p>
         </section>
         <section class="py-2">
          <h2 class=" text-secondary-foreground py-1">3. تحضير مربى التوت:</h2>
          <p>
           - ضع مزيج التوت على النار مع سكر دايت وأضف قليل من الماء لمنع
           احتراقه.
          </p>
          <p>- أضف نشا مذوب في 20 مل من الماء، وخلط جيداً حتى يتماسك.</p>
         </section>
         <section>
          <h2 class="text-secondary-foreground py-1">4. التجميع:</h2>
          <ul>
           <li>
            - بين كل طبقة من الكيك، ضع طبقة من الكريمة البيضاء ومربى التوت.
           </li>
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
           <li>- 80 جرام من الزبادي اليوناني خالي الدسم</li>
           <li>- 4 جرام من النشا</li>
           <li>- 45 جرام من البيض (حوالي بيضة واحدة)</li>
           <li>- 100 جرام من الفراولة</li>
          </ul>
         </section>
         <section class="py-2">
          <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
          <p class=" text-secondary-foreground">1. تحضير الطبقة الأولى:</p>
          <ol>
           <li>- اطحن البسكويت وأضف إليه 7 مل من الماء.</li>
           <li>
            - ضع 8 جرامات من خليط البسكويت في قوالب الكب كيك واضغط عليه باستخدام
            كوب أو ملعقة صغيرة.
           </li>
          </ol>
         </section>
         <section class="py-2">
          <h2 class=" text-secondary-foreground py-2">
           2. تحضير الطبقة الثانية:
          </h2>
          <p>
           - اخلط جبنة فيلادلفيا، الزبادي، 2 جرام من النشا، البيضة، ومحلي خالٍ
           من السعرات أو ستيفيا.
          </p>
          <p>- ضع 24 جرامًا من هذا الخليط فوق طبقة البسكويت.</p>
          <h2 class=" text-secondary-foreground py-1">3. الخبز:</h2>
          <p>- سخن الفرن على درجة حرارة 170 درجة مئوية.</p>
          <p>
           - اخبز القوالب لمدة 10 دقائق من كل جهة. إذا كنت بحاجة إلى وقت أكثر أو
           أقل، راقب القوالب واضغط عليها بطرف الملعقة. إذا لم تلتصق، فهي جاهزة.
          </p>
         </section>
         <section class="py-2">
          <h2 class=" text-secondary-foreground py-1">سعرات خليط الشوفان:</h2>
          <p>- 325 سعرة حرارية (بدون كاسترد)</p>
          <p>- مع الكاسترد: 366 سعرة حرارية</p>
         </section>
         <section>
          <h2 class="text-secondary-foreground py-2">4. التبريد:</h2>
          <ul>
           <li>- ضع القوالب في الفريزر لمدة ساعة ثم أخرجها من القوالب.</li>
          </ul>
         </section>
         <section class="py-2">
          <h2 class="text-secondary-foreground py-1">
           5. تحضير الطبقة الأخيرة (صلصة الفراولة):
          </h2>
          <ul>
           <li>
            - اعصر الفراولة في الخلاط، ثم أضف 2 جرام من النشا، 6 مل من الماء،
            ونقطتين من المحلي (يمكن استعمال العسل واضافة سعراته للمجموع).
           </li>
           <li>
            - ضع الخليط على النار و استمر بالتقليب حتى تذبل الفراولة وتصبح لديك
            الصلصة جاهزة
           </li>
           <li>- زين الطبقة الأخيرة حسب رغبتك.</li>
          </ul>
         </section>
         <section class="py-2">
          <h2 class="text-secondary-foreground py-1">السعرات الحرارية:</h2>
          <p>الحبة 65 سعرة</p>
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
   <span class="flex justify-center py-2 pr-2">
    <Dialog.Root>
     <Dialog.Trigger
      class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants({
       variant: 'outline',
      })}">حلى الاوريو</Dialog.Trigger
     >
     <Dialog.Content
      class=" w-[70vw] h-[90vh] lg-w-[90vw] lg:h-fit bg-secondary shadow-md"
     >
      <Dialog.Header class="">
       <Dialog.Title class="flex justify-center text-secondary-foreground"
        >حلى الاوريو
       </Dialog.Title>
      </Dialog.Header>
      <div class=" lg:text-sm text-xs">
       <section>
        <h2 class="text-secondary-foreground py-1">المكونات:</h2>
        <ul>
         <li>
          - حبتان أوريو (واحدة بكريمة وواحدة بدون)، تساوي 16 جرام (أربعة حبات).
         </li>
         <li>- حليب قليل الدسم: ملعقة ونصف كبيرة، 15 مل.</li>
         <li>- كريم كراميل باودر: ملعقة ونصف، 15 جرام.</li>
         <li>- ظرف سكر ستيفيا.</li>
         <li>- جبن فيلادلفيا لايت: ملعقتين كبيرتين، 55 جرام.</li>
         <li>- بسكويت ماري: حبة واحدة، 5 جرام.</li>
         <li>- قطعة شوكولاتة بالحليب: 10 جرام.</li>
        </ul>
       </section>
       <section class="py-2">
        <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
        <ol class="">
         <li>1. ضع 3 حبات أوريو في وعاء، ثم أضف 10 مل حليب.</li>
         <li>
          2. لتحضير الطبقة الثانية، اخلط 40 جرام من فيلادلفيا مع ملعقة ونصف من
          كريم كراميل باودر، سكر ستيفيا، و5 مل حليب. أضف نقطة ماء إذا لزم الأمر،
          وامزج حتى يتجانس.
         </li>
         <li>3. اغمس البسكويت ماري المتبقي في الحليب.</li>
         <li>
          4. ذوب قطعة الشوكولاتة بالحليب في حمام مائي، ثم أضف إليها 15 جرام من
          فيلادلفيا لايت.
         </li>
         <li>
          5. ضع الحبة الأخيرة من أوريو في الأعلى، ثم أضف خليط الشوكولاتة فوقها.
         </li>
        </ol>
       </section>
       <section class="py-2">
        <h2 class="text-secondary-foreground py-1">السعرات الحرارية:</h2>
        <p>-249 سعرة حرارية</p>
       </section>
      </div>
     </Dialog.Content>
    </Dialog.Root>
   </span>
  </div>
  <div class=" w-[15vw] h-auto rounded-xl">
   <img src="/sw6.jpg" alt="" class=" rounded-xl" />
   <span class="flex justify-center py-2 pr-2">
    <Dialog.Root>
     <Dialog.Trigger
      class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants({
       variant: 'outline',
      })}">حلى الآيسكريم</Dialog.Trigger
     >
     <Dialog.Content
      class=" w-[70vw] h-[90vh] lg-w-[90vw] lg:h-fit bg-secondary shadow-md"
     >
      <Dialog.Header class="">
       <Dialog.Title class="flex justify-center text-secondary-foreground"
        >حلى الآيسكريم
       </Dialog.Title>
      </Dialog.Header>
      <div class=" lg:text-sm text-xs">
       <section>
        <h2 class="text-secondary-foreground py-1">المكونات:</h2>
        <ul>
         <li>- قطعتان من كعك الأرز، 14 جرام.</li>
         <li>- نصف قطعة شوكولاتة غامقة، 5 جرام.</li>
         <li>- قطعة كاملة شوكولاتة بالحليب، 10 جرام.</li>
         <li>- ملعقة كبيرة من آيس كريم فانيلا لايت، 35 جرام.</li>
         <li>- للتزيين: توت أحمر مجمد، 2 جرام.</li>
        </ul>
       </section>
       <section class="py-2">
        <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
        <ol class="">
         <li>1. ذوّب الشوكولاتة الغامقة وشوكولاتة الحليب في حمام مائي.</li>
         <li>2. ضع ملعقة كبيرة من الآيس كريم على إحدى قطع كعك الأرز.</li>
         <li></li>
         <li>3. غطِّها بقطعة أخرى من كعك الأرز.</li>
         <li>4. صب الشوكولاتة المذابة فوق الكعك وزينه بالتوت الأحمر.</li>
         <li>5. اتركه في الفريزر ليجمد لمدة 10 دقائق على الأقل.</li>
        </ol>
       </section>
       <section class="py-2">
        <h2 class="text-secondary-foreground py-1">السعرات الحرارية:</h2>
        <p>-158 سعرة حرارية</p>
       </section>
      </div>
     </Dialog.Content>
    </Dialog.Root>
   </span>
  </div>
  <div class=" w-[15vw] h-auto rounded-xl">
   <img src="/sw7.jpg" alt="" class=" rounded-xl" />
   <span class="flex justify-center py-2 pr-2">
    <Dialog.Root>
     <Dialog.Trigger
      class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants({
       variant: 'outline',
      })}">مافن</Dialog.Trigger
     >
     <Dialog.Content
      class=" w-[70vw] h-[90vh] lg-w-[90vw] lg:h-fit bg-secondary shadow-md"
     >
      <Dialog.Header class="">
       <Dialog.Title class="flex justify-center text-secondary-foreground"
        >مافن
       </Dialog.Title>
      </Dialog.Header>
      <div class="flex justify-center items-center">
       <ScrollArea
        class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4"
       >
        <div class="text-sm">
         <section>
          <h2 class="text-secondary-foreground py-1">المكونات:</h2>
          <ul>
           <li>- شوفان مطحون أو دقيق: 50 جرام</li>
           <li>- بروتين باودر: 32 جرام</li>
           <li>- باكينج باودر: 1 جرام</li>
           <li></li>
           <li>- بيضة: 56 جرام</li>
           <li>- تفاح: 57 جرام</li>
           <li>- توت أزرق: 35 جرام</li>
           <li>- توت أحمر: 23 جرام</li>
           <li>- قرفة: 1 جرام</li>
           <li>- ماء: 30 مل</li>
           <li>- بودرة فول سوداني (اختياري): 7 جرام</li>
          </ul>
         </section>
         <section class="py-2">
          <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
          <ol class="">
           <li>
            1. امزج الشوفان أو الدقيق، بروتين البودر، باكينج باودر، البيضة،
            التفاح، والتوت (البلوberry والأحمر)، القرفة، والماء في الخلاط.
           </li>
           <li>2. أضف ظرفين من سكر ستيفيا وامزج حتى يتجانس الخليط.</li>
           <li>3. غطِّها بقطعة أخرى من كعك الأرز.</li>
           <li>3. صب الخليط في قوالب المافن وزينه بقطع التفاح والتوت.</li>
           <li></li>
           <li>
            4. اخبز في الفرن المسبق تسخينه على درجة حرارة 200 مئوية لمدة 10
            دقائق من الأسفل ثم 5 دقائق من الأعلى حتى ينضج.
           </li>
           <li>
            5. بعد أن يبرد، حضر صوص الفول السوداني بخلط بودرة الفول السوداني مع
            ضعف كمية الماء وسكر ستيفيا، ثم زين المافن بالصوص.
           </li>
          </ol>
         </section>
         <section class="py-2">
          <h2 class="text-secondary-foreground py-1">السعرات الحرارية:</h2>
          <p>-158 سعرة حرارية</p>
         </section>
        </div>
       </ScrollArea>
      </div>
     </Dialog.Content>
    </Dialog.Root>
   </span>
  </div>

  <div class=" w-[15vw] h-auto rounded-xl">
   <img src="/sw9.jpg" alt="" class=" rounded-xl" />
   <span class="flex justify-center py-2 pr-2">
    <Dialog.Root>
     <Dialog.Trigger
      class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants({
       variant: 'outline',
      })}">حلى منعش</Dialog.Trigger
     >
     <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
      <Dialog.Header class="">
       <Dialog.Title class="flex justify-center text-secondary-foreground"
        >حلى منعش
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
           <li>- 5 حبات توست أبيض (نقطع الحواف).</li>
           <li>- 50 جم حليب (لتغميس التوست).</li>
          </ul>
         </section>
         <section class="py-2">
          <h2 class=" text-secondary-foreground py-1">للكريمة:</h2>
          <ol>
           <li>- 24 جم دريم ويب.</li>
           <li>- ملعقة صغيرة فانيلا.</li>
           <li>- ظرفين سكر ستيفيا.</li>
           <li>- 80 جم ماء بارد.</li>
           <li>- علبتين زبادي بالفراولة (اكتيفيا).</li>
          </ol>
         </section>
         <section class="py-2">
          <h2 class=" text-secondary-foreground py-2">للجلي:</h2>
          <p>- 23 جم جيلي.</p>
          <p></p>
         </section>

         <section>
          <h2 class="text-secondary-foreground py-2">الطريقة:</h2>
          <ul>
           <li>
            1. في وعاء، اخفق الدريم ويب مع الماء البارد حتى يتكون قوام شبه كريمي
            (5-7 دقائق تقريباً).
           </li>
           <li>
            2. أضف الفانيلا، الزبادي، وسكر ستيفيا، ثم استمر في الخفق حتى تمتزج
            المكونات جيداً.
           </li>
           <li>
            3. في صحن تقديم، رص التوست واغمره في الحليب. ضع طبقة من الكريمة فوق
            التوست. كرر الطبقات حتى ينفد التوست.
           </li>
           <li>
            4. لتحضير الجلي، اخلط الجيلي مع الماء المغلي حتى يذوب. اتركه ليبرد
            قليلاً ثم اسكبه فوق آخر طبقة من الكريمة.
           </li>
           <li>5. اتركه في الثلاجة حتى يتماسك الجلي، ثم زينه بالفراولة.</li>
          </ul>
         </section>

         <section class="py-2">
          <h2 class="text-secondary-foreground py-1">السعرات الحرارية:</h2>
          <p>- لكل الكمية: 794 سعرة حرارية.</p>
          <p>- لكل قطعة (من أصل 6 قطع): 133 سعرة حرارية.</p>
         </section>
        </div>
       </ScrollArea>
      </div>
     </Dialog.Content>
    </Dialog.Root>
   </span>
  </div>
  <div class=" w-[15vw] h-auto rounded-xl">
   <img src="/sw11.jpg" alt="" class=" rounded-xl" />
   <span class="flex justify-center py-2 pr-2">
    <Dialog.Root>
     <Dialog.Trigger
      class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants({
       variant: 'outline',
      })}">بانكيك السينابون</Dialog.Trigger
     >
     <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
      <Dialog.Header class="">
       <Dialog.Title class="flex justify-center text-secondary-foreground"
        >بانكيك السينابون
       </Dialog.Title>
      </Dialog.Header>
      <div class="flex justify-center items-center">
       <ScrollArea
        class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4"
       >
        <div class="  text-sm">
         <section>
          <h2 class="text-secondary-foreground py-1">المكونات:</h2>
          <ul>
           <li>- 50 جم بيضة.</li>
           <li>- 60 جم زبادي يوناني (أو أي نوع متوفر، حتى لو سائل).</li>
           <li>- 40 جم دقيق أبيض أو شوفان مطحون.</li>
           <li>- 3 جم باكينج باودر.</li>
           <li>
            - 25 جم بروتين باودر شوكولاتة بيضاء (اختياري) = 99 سعرة حرارية.
           </li>
           <li>- 10 جم جبن فيلادلفيا لايت.</li>
           <li>- 10 مل ميبل سيرب أو عسل.</li>
          </ul>
         </section>

         <section>
          <h2 class="text-secondary-foreground py-2">الطريقة:</h2>
          <ul>
           <li>
            1. اخلط البيضة، الزبادي اليوناني، ومحلي الفانيلا أو سكر ستيفيا مع
            الفانيليا حتى تمتزج المكونات جيدًا.
           </li>
           <li>
            2. أضف المكونات الجافة (الدقيق، الباكينج باودر، وبروتين البودرة) إلى
            الخليط، ثم أضف ملعقتين كبيرتين من الماء إذا لزم الأمر. اترك الخليط
            لمدة 10 دقائق.
           </li>
          </ul>
         </section>
         <section class="py-2">
          <h2 class=" text-secondary-foreground py-2">3. لتحضير الصوص:</h2>
          <p>
           - اخلط القرفة مع ميبل سيرب وظرف سكر ستيفيا. استخدم كيس حلواني لتشكيل
           الصوص بشكل حلزوني.
          </p>
          <p></p>
          <h2 class=" text-secondary-foreground py-2">
           4. لتحضير الصوص الأبيض (اختياري):
          </h2>
          <p>
           - اخلط جبن فيلادلفيا لايت مع ماء وسكر ستيفيا حتى تحصل على القوام
           المناسب.
          </p>
         </section>
         <section class="py-2">
          <h2 class="text-secondary-foreground py-1">السعرات الحرارية:</h2>
          <p>- 379 سعرة حرارية.</p>
         </section>
        </div>
       </ScrollArea>
      </div>
     </Dialog.Content>
    </Dialog.Root>
   </span>
  </div>
  <div class=" w-[15vw] h-auto rounded-xl">
   <img src="/sw12.jpg" alt="" class=" rounded-xl" />
   <span class="flex justify-center py-2 pr-2">
    <Dialog.Root>
     <Dialog.Trigger
      class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants({
       variant: 'outline',
      })}">كيكة الكندر</Dialog.Trigger
     >
     <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
      <Dialog.Header class="">
       <Dialog.Title class="flex justify-center text-secondary-foreground"
        >كيكة الكندر
       </Dialog.Title>
      </Dialog.Header>
      <div class="flex justify-center items-center">
       <ScrollArea
        class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4"
       >
        <div class="  text-sm">
         <section>
          <h2 class="text-secondary-foreground py-1">المكونات:</h2>
          <ul>
           <li>- شوفان مطحون: 30 جرام</li>
           <li></li>
           <li>- باكينج باودر: 4 جرام (ملعقتين كبيرتين)</li>
           <li>- زبادي يوناني خالي الدسم: 25 جرام (نصف ملعقة صغيرة)</li>
           <li>- كاكاو بودرة: 5 جرام (ملعقة كبيرة)</li>
           <li>- سكر ستيفيا أو أي سكر دايت: ظرفين</li>
           <li>- قهوة: 50 مل</li>
           <li>- كندر: 21 جرام</li>
          </ul>
         </section>

         <section>
          <h2 class="text-secondary-foreground py-2">الطريقة:</h2>
          <ul>
           <li>
            1. اخلط الشوفان المطحون، باكينج باودر، الزبادي، كاكاو بودرة، سكر ستيفيا، والقهوة في وعاء حتى تتجانس المكونات.
           </li>
           <li>
            2. صب الخليط في قوالب مخصصة للقلاية الهوائية.
           </li>
           <li>3. سخن القلاية الهوائية مسبقاً، ثم ضع القوالب داخلها.
           </li>
           <li>4. اطبخ على درجة حرارة 180 مئوية لمدة 10 دقائق.</li>
           <li>5. بعد انتهاء الطهي، أضف الكندر المقطّع إلى الأعلى، ثم قدمه.
           </li>
          </ul>
         </section>
         <section class="py-2">
          <h2 class="text-secondary-foreground py-1">السعرات الحرارية:</h2>
          <p>- 266  سعرة حرارية.</p>
         </section>
        </div>
       </ScrollArea>
      </div>
     </Dialog.Content>
    </Dialog.Root>
   </span>
  </div>
  <div class=" w-[15vw] h-auto rounded-xl">
   <img src="/sw14.jpg" alt="" class=" rounded-xl" />
   <span class="flex justify-center py-2 pr-2">
    <Dialog.Root>
     <Dialog.Trigger
      class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants({
       variant: 'outline',
      })}">كيكة ليمون بالتوت</Dialog.Trigger
     >
     <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
      <Dialog.Header class="">
       <Dialog.Title class="flex justify-center text-secondary-foreground"
        >كيكة ليمون بالتوت
       </Dialog.Title>
      </Dialog.Header>
      <div class="flex justify-center items-center">
       <ScrollArea
        class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4"
       >
        <div class="  text-sm">
         <section>
          <h2 class="text-secondary-foreground py-1">المكونات:</h2>
          <ul>
           <li>- 10 جم بروتين فانيلا (اختياري).</li>
           <li>
            - 150 جم زبادي يوناني خال الدسم.           </li>
           <li>
            - توت مشكل.
           </li>
           <li>- بيضة.</li>
           <li>- ملعقة صغيرة باكينج باودر.
           </li>
           <li>
            - عصرة ليمون.           </li>
           <li>- 40 جم دقيق أبيض.</li>
           <li>- 6 جم بسكوت بدون سكر.</li>
           <li>- ظرف سكر ستيفيا.</li>
          </ul>
         </section>

         <section>
          <h2 class="text-secondary-foreground py-2">الطريقة:</h2>
          <ul>
           <li>
            1. في وعاء، اخلط الزبادي، البيضة، وسكر ستيفيا.
           </li>
           <li>
            2. قسم الخليط إلى قسمين:
           </li>
           <li>   - اخلط القسم الأول مع البروتين الفانيلا (إذا كنت تستخدمه)، الدقيق، الباكينج باودر، وعصرة الليمون. صب الخليط في الصينية.</li>
           <li>   - اخلط القسم الثاني مع التوت المشكل، ثم اسكبه فوق الخليط الأول في الصينية.</li>
          </ul>
         </section>
         <section class="py-2">
          <h2 class=" text-secondary-foreground py-2">الصينية</h2>
          <p>
           3. رش البسكوت بدون سكر على السطح.
          </p>
          <p>4. اخبز الخليط في فرن مُسخن مسبقًا على حرارة 180 درجة مئوية حتى ينضج (من الأعلى والأسفل).</p>
          
         </section>
         <section class="py-2">
          <h2 class="text-secondary-foreground py-1">السعرات الحرارية:</h2>
          <p>- 384  سعرة حرارية.</p>
         </section>
        </div>
       </ScrollArea>
      </div>
     </Dialog.Content>
    </Dialog.Root>
   </span>
  </div>
 </div>
</div>
