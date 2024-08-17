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
          <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >سكرمبل الشوفان
              </Dialog.Title>
            </Dialog.Header>
            <div class=" lg:text-sm text-xs">
              <section>
                <h2 class="text-secondary-foreground py-1">المكونات:</h2>
                <ul>
                  <li>- 30 جم شوفان (أو 4 ملاعق).</li>
                  <li>- 180 جم زبادي يوناني (أو 4 ملاعق كبيرة ممتلئة).</li>
                  <li>-71 جم بياض بيض</li>
                  <li>-
                    18 جم صفار بيض =(من بيضتين: بياض بيضة كاملة وصفار بيضة)
                  </li>
                  <li>-محلي فانيليا</li>
                  <li>-100 جم مزيج توت</li>
                  <li>
                    - (اختياري) 12 جم زبدة فول سوداني قليلة السعرات (أو ملعقة
                    صغيرة)
                  </li>
                </ul>
              </section>
              <section class="py-3">
                <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
                <ol class="">
                  <li>1.
                    في وعاء، اخلط البيض، الشوفان، 30 جم من الزبادي اليوناني،
                    القرفة، والمحلي.
                  </li>
                  <li>2.
                    اطبخ الخليط على الصاج من الجهتين، ثم قطّعه إلى قطع عشوائية.
                  </li>
                  <li>3.
                    في صحن التقديم، ضع 150 جم زبادي يوناني مع محلي حسب الرغبة.
                  </li>
                  <li>4.
                    أضف قطع الشوفان التي حضرتها، والفواكه، وزبدة الفول السوداني
                    إذا كنت تستخدمها.
                  </li>
                </ol>
              </section>
              <section class="py-4">
                <h2 class="text-secondary-foreground py-1">السعرات الحرارية:</h2>
                <p>-388 سعرة حرارية</p>
              </section>
            </div>
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
          <Dialog.Content class=" bg-secondary shadow-md">
            <Dialog.Header>
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >شكشوكة تركية
              </Dialog.Title>
            </Dialog.Header>
            <div class=" lg:text-sm text-xs">
              <section>
                <h2 class="text-secondary-foreground">المكونات:</h2>
                <ul>
                  <li>- 120 جم طماطم حجم وسط.</li>
                  <li>- 25 جم ربع بصلة.</li>
                  <li>- 16 جم معجون طماطم.</li>
                  <li>- 44 جم بيضة.</li>
                  <li>- 1 شريحة توست عالية بالبروتين (185 سعرة حرارية).</li>
                </ul>
              </section>
              <section class="py-2">
                <h2 class=" text-secondary-foreground">الطريقة:</h2>
                <ol class="">
                  <li>1. اقلي البصل على النار حتى يذوب.</li>
                  <li>
                    2. أضف الطماطم المقطعة إلى البصل وغطِّه حتى تنضج الطماطم.
                  </li>
                  <li>
                    3. أضف معجون الطماطم وقليل من الماء، ثم أضف البهارات (ملح،
                    فلفل أسود، بابريكا، بودرة ثوم) حسب الذوق.
                  </li>
                  <li>4. حضر البيض بالطريقة التي تفضلها.</li>
                  <li>5. قدم الطبق مع شريحة التوست.</li>
                </ol>
              </section>
              <section class="py-2">
                <h2 class="text-secondary-foreground">السعرات الحرارية :</h2>
                -292 سعرة حرارية
              </section>
            </div>
            <div></div>
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
            )}"
          >
            شوفان وبروتين</Dialog.Trigger
          >
          <Dialog.Content class=" bg-secondary shadow-md">
            <Dialog.Header>
              <Dialog.Title>شوفان وبروتين</Dialog.Title>
            </Dialog.Header>
            <div class=" lg:text-sm text-xs">
              <section>
                <h2 class="text-secondary-foreground">المكونات:</h2>
                <ul>
                  <li>- 30 جم شوفان كامل الحبة.</li>
                  <li>- 30 جم بروتين باودر.</li>
                  <li>- 3 جم كاكاو باودر.</li>
                  <li>- 38 جم توت.</li>
                  <li>- 20 جم زبادي يوناني.</li>
                  <li>- (اختياري) ملعقة كبيرة عسل.</li>
                </ul>
              </section>
              <section class="py-2">
                <h2 class=" text-secondary-foreground">الطريقة:</h2>
                <ol class="">
                  <li>
                    1.ضع الشوفان في وعاء وأضف ضعف الكمية ماء. سخنه في الميكروويف
                    لمدة دقيقة.
                  </li>
                  <li>
                    2. في وعاء آخر، اخلط البروتين باودر، كاكاو باودر، وسكر
                    ستيفيا (بنفس كمية البروتين). أضف 30 مل ماء واخلط جيدًا
                  </li>
                  <li>3. أضف الخليط إلى الشوفان وامزج جيدًا.</li>
                  <li>4. زين الطبق بالزبادي اليوناني والتوت الأحمر.</li>
                </ol>
              </section>
              <section class="">
                <h2 class="text-secondary-foreground">السعرات الحرارية:</h2>
                <p>- بدون العسل: 320 سعرة حرارية.</p>
                <p>- مع العسل: 384 سعرة حرارية.</p>
              </section>
            </div>
            <div></div>
            <div></div>
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
            )}"
          >
             فرنش توست</Dialog.Trigger
          >
          <Dialog.Content class=" bg-secondary shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >فرنش توست مالح
              </Dialog.Title>
            </Dialog.Header>
            <div class="lg:text-sm text-xs">
              <section>
                <h2 class="text-secondary-foreground">المكونات:</h2>
                <ul>
                  <li>- 3 شرائح توست (90 جم).</li>
                  <li>- بيضتين (واحدة بياض بيضة والأخرى كاملة) [66 جم بياض، 20 جم صفار].</li>
                  <li>- ربع كوب (50 جم) حليب بروتين أو أي حليب متوفر (استخدمت حليب نادك السادة عالي البروتين).</li>
                  <li>- 60 جم حلوم.</li>
                  <li>- ملعقتين (20 جم) جبن موزاريلا لايت.</li>
                </ul>
              </section>
              <section class="py-3">
                <h2 class=" text-secondary-foreground">الطريقة:</h2>
                <ol class="">
                  <li>
                    1. اخفق البيض مع الحليب، وأضف الزعتر والملح.
                  </li>
                  <li>
                    2. غمس شرائح التوست في خليط البيض والحليب، ثم اطهها على الصاج من جميع الجوانب.
                  </li>
                  <li>3. حمّص الحلوم في مقلاة أو اسلقه حسب تفضيلك، أو يمكنك وضعه على التوست الساخن حتى يذوب.</li>
                  <li>4. رشّ الجبن الموزاريلا على التوست الساخن واتركه يذوب.
                  </li>
                <li>
                  5. زين الطبق بالطماطم والنعناع.
                </li>
                </ol>
              </section>
              <h2 class="text-secondary-foreground">السعرات الحرارية:</h2>
              <p>- 555 سعرة حرارية.</p>
            </div>
            <div></div>
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
            )}"
          >
            ساندوتش بيض
          </Dialog.Trigger>
          <Dialog.Content class=" bg-secondary shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >ساندوتش بيض
              </Dialog.Title>
            </Dialog.Header>
           <div class="  lg:text-sm text-xs">
              <section>
                <h2 class="text-secondary-foreground">المكونات:</h2>
                <ul>
                  <li>-58 جم توست أسمر.</li>
                  <li>- 148 جم بياض 4 بيضات أو 2 بيض كامل.</li>
                  <li>- 50 جم صفار بيضة.</li>
                  <li>- 19 جم شريحة جبن قليل الدسم.</li>
                  <li>- 60 جم سبانخ.</li>
                  <li>- 2 فص ثوم.</li>
                  <li>
                    - (اختياري) 60 جم سبانخ إضافية، 35 جم طماطم، 32 جم جزر.
                  </li>
                </ul>
              </section>
              <section class="py-3">
                <h2 class=" text-secondary-foreground">الطريقة:</h2>
                <ol class="">
                  <li>1. سخّن الثوم على الصاج حتى يصبح ذهبي اللون.</li>
                  <li>2. أضف السبانخ إلى الثوم واطبخ حتى تذبل.</li>
                  <li>
                    3. أضف البيض إلى السبانخ، ثم أضف قليل من الملح وامزج جيدًا.
                  </li>
                  <li>
                    4. على شريحة التوست، ضع طبقة من البيض، الجبن، الجزر المقشر
                    (بمبشرة رفيعة)، والطماطم.
                  </li>
                  <li>5. أضف طبقة أخرى من البيض، ثم أضف الجرجير.</li>
                  <li>
                    6. غلف الساندويتش بنايلون لضمان ثبات المكونات، ثم قطعه إلى
                    أجزاء.
                  </li>
                </ol>
              </section>
              <h2 class="text-secondary-foreground">السعرات الحرارية:</h2>
              <p>- 377 سعرة حرارية.</p>
            </div>
            <div></div>
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
            )}"
          >
            بانكيك
          </Dialog.Trigger>
          <Dialog.Content class=" bg-secondary shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >بانكيك
              </Dialog.Title>
            </Dialog.Header>
            <div class="  lg:text-sm text-xs">
              <section>
                <h2 class="text-secondary-foreground">المكونات:</h2>
                <ul>
                  <li>- 50 جم شوفان مطحون (حوالي 5 ملاعق).</li>
                  <li>- ربع ملعقة صغيرة باكينج باودر (3 جم).</li>
                  <li>- 150 مل لبن سائل (علبة صغيرة).</li>
                  <li>- 37 جم بياض بيضة.</li>
                  <li>- ربع ملعقة صغيرة باكينج باودر (3 جم).</li>
                </ul>
              </section>
              <section class="py-3">
                <h2 class=" text-secondary-foreground">الطريقة:</h2>
                <ol>
                  <li>
                    1. اخلط المكونات الجافة (الشوفان، باكينج باودر، والبروتين)
                    جيدًا.
                  </li>
                  <li>
                    2. أضف اللبن السائل وامزج حتى يتجانس الخليط. أضف حوالي 30 مل
                    ماء إضافي ونقطة من محلي الفانيلا (يمكنك استبداله بسكر ستيفيا
                    حسب الرغبة).
                  </li>
                  <li>
                    3. في وعاء آخر، اخفق بياض البيض جيدًا بالخلاط حتى يصبح قوامه
                    كالكريمة.
                  </li>
                  <li>
                    4. أضف بياض البيض المخفوق إلى الخليط تدريجيًا، وامزج بلطف
                    حتى يصبح الخليط جاهزًا.
                  </li>
                </ol>
                <section class="py-3">
                  <h2 class=" text-secondary-foreground">الإضافات:</h2>
                  <h3 class=" text-primary">الصوص الأبيض:</h3>
                  <p>
                    زبادي يوناني + محلي فانيلا خالي السعرات أو ظرف سكر ستيفيا.
                    الطعم يشبه الطبقة البيضاء في التشيز كيك وتوت أزرق.
                  </p>
                </section>
              </section>
              <h2 class="text-secondary-foreground">السعرات الحرارية:</h2>
              <p>- بدون الإضافات: 411 سعرة حرارية.</p>
              <p>- مع الإضافات: 472 سعرة حرارية.</p>
            </div>
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
          <Dialog.Content class="bg-secondary shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >أفكار للتوست
              </Dialog.Title>
            </Dialog.Header>
            <div class="  lg:text-sm text-xs">
              <section>
                <h2 class="text-secondary-foreground">شريحة البيض:</h2>
                <ul>
                  <li>- 30 جم زبادي يوناني سادة قليل الدسم.</li>
                  <li>- 42 جم بيض مسلوق أو بطريقة بنديكت.</li>
                  <li>- 2 جم فص ثوم.</li>
                  <li>- 2 جم فلفل هلابينو (حبة صغيرة).</li>
                  <li>- بهارات: فلفل مجروش، فلفل أسود، وكيجون.</li>
                </ul>
              </section>
              <div class="py-3">
                <h2 class="text-secondary-foreground">السعرات الحرارية:</h2>
              <p>- 153 سعرة حرارية.</p>
              </div>
              <section class="py-1">
                <h2 class=" text-secondary-foreground">شريحة الزبادي اليوناني:</h2>
                <ol class="">
                  <li>- 30 جم زبادي يوناني بالتوت قليل الدسم.</li>
                  <li>
                    - 24 جم زبادي يوناني سادة قليل الدسم.
                  </li>
                </ol>
              </section>
              <div class="py-2">
                <h2 class="text-secondary-foreground">السعرات الحرارية:</h2>
              <p>- 113 سعرة حرارية.</p>
              </div>
              
            </div>
            <div></div>
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
            )}"
          >
            بانكيك غير</Dialog.Trigger
          >
          <Dialog.Content class=" bg-secondary shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >بانكيك زبدة الفول السوداني
              </Dialog.Title>
              
            </Dialog.Header>
            <div class="  lg:text-sm text-xs">
              <section>
                <h2 class="text-secondary-foreground">المكونات:</h2>
                <ul>
                  <li>- كوب شوفان مطحون.</li>
                  <li>- ملعقة كبيرة عسل.</li>
                  <li>- ملعقة كبيرة زبدة فول سوداني.</li>
                  <li>- بيضة.</li>
                  <li>- ربع كوب حليب (تقريبًا).
                  </li>
                  <li>- ملعقة صغيرة قرفة.</li>
                  <li>- ملعقة صغيرة بايكنج باودر.</li>
                </ul>
              </section>
              <section class="py-3">
                <h2 class=" text-secondary-foreground">الطريقة:</h2>
                <ol>
                  <li>
                    1. اخلط جميع المكونات معًا حتى تتجانس.

                  </li>
                  <li>
                    2. أضف الحليب تدريجيًا حتى تحصل على قوام شبه ثقيل ومتجانس.

                  </li>
                  <li>
                    3. اطهُ البانكيك على مقلاة غير لاصقة حتى ينضج من الجانبين.

                  </li>
                  
                </ol>
                
              </section>
              <h2 class="text-secondary-foreground">السعرات الحرارية:</h2>
              <p>-430 سعرة حرارية.</p>
              
            </div>
            <div></div>
            <div></div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
  </div>
</div>
