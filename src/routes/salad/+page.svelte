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
      <img src="/l1.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              { variant: 'outline' },
            )}">سلطة دجاج</Dialog.Trigger
          >
          <Dialog.Content
            class=" w-[70vw] h-[90vh] lg:h-[95vh]  bg-secondary shadow-md"
          >
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >سلطة دجاج
              </Dialog.Title>
            </Dialog.Header>
            <div class=" lg:text-sm text-xs">
              <section>
                <h2 class="text-secondary-foreground py-1">المكونات:</h2>
                <ul>
                  <li>
                    - 98 جم صدر دجاج، مَتبّل بملعقة خردل، ملح، كركم، وبهارات
                    مشكلة، ثم شوّح في مقلاة حتى ينضج.
                  </li>
                  <li>- 33 جم فلفل رومي (مقطع مكعبات صغيرة).</li>
                  <li>- 499 جم ملفوف أبيض (مقطع مكعبات صغيرة).</li>
                  <li>- 47 جم خيار (مقطع مكعبات صغيرة).</li>
                  <li></li>
                  <li>- بقدونس (مفروم، حسب الرغبة).</li>
                </ul>
              </section>
              <section class="py-3">
                <h2 class=" text-secondary-foreground py-1">للصوص:</h2>
                <ol class="">
                  <li>- 59 جم زبادي.</li>
                  <li>- ملعقة صغيرة صوص تتبيلة فرنسية.</li>
                  <li>- عصير ليمونة.</li>
                </ol>
              </section>
              <section class="py-3">
                <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
                <ol class="">
                  <li>1. شوّح الدجاج في مقلاة حتى ينضج.</li>
                  <li>
                    2. اخلط الخضار المقطعة (الفلفل الرومي، الملفوف الأبيض،
                    الخيار) مع البقدونس في وعاء كبير.
                  </li>
                  <li>
                    3. في وعاء صغير، اخلط الزبادي مع صوص التتبيلة الفرنسية وعصير
                    الليمون.
                  </li>
                  <li>4. أضف الدجاج إلى الخضار، ثم أضف الصوص وامزج جيدًا.</li>
                </ol>
              </section>
              <section class="py-4">
                <h2 class="text-secondary-foreground py-1">
                  السعرات الحرارية:
                </h2>
                <p>-203 سعرة حرارية</p>
              </section>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/l2.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              { variant: 'outline' },
            )}">سلطة التونة</Dialog.Trigger
          >
          <Dialog.Content
            class=" w-[70vw] h-[90vh] lg:h-[95vh] bg-secondary shadow-md"
          >
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >سلطة التونة والباذنجان
              </Dialog.Title>
            </Dialog.Header>
            <div class=" lg:text-sm text-xs">
              <section>
                <h2 class="text-secondary-foreground py-1">المكونات:</h2>
                <ul>
                  <li>- فلفل رومي.</li>
                  <li>- خيار.</li>
                  <li>- خس.</li>
                  <li>- أي خضار تفضلها (مثل جزر، طماطم، أو بصل).</li>
                  <li>- 1 حبة باذنجان، مقطعة إلى مربعات.</li>
                  <li>- 2 ملعقة كبيرة زيت.</li>
                  <li>- 1 ملعقة صغيرة فلفل حار مطحون (بدون ملح).</li>
                  <li>- مخلل فلفل.</li>
                  <li>- زيتون مقطع.</li>
                  <li>- 2 ملعقة كبيرة مايونيز.</li>
                  <li>- 1 علبة تونة صغيرة (بالماء، مصفاة).</li>
                </ul>
              </section>
              <section class="py-2">
                <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
                <ol class="">
                  <li>1. قطع الخضار إلى قطع صغيرة وضعها جانبا</li>
                  <li>
                    2. قطع الباذنجان إلى مربعات، تبّلها بالفلفل الحار المطحون،
                    ثم أضف الزيت.
                  </li>
                  <li>
                    3. اطبخ الباذنجان في القلاية الهوائية على حرارة 20 درجة
                    مئوية لمدة 20 دقيقة.
                  </li>
                  <li>4. في وعاء كبير، اخلط المخلل، الزيتون، والمايونيز.</li>
                  <li>5. أضف الخضار المقطعة والتونة المصفاة، ثم اخلط جيدًا.</li>
                </ol>
              </section>
              <section class="py-4">
                <h2 class="text-secondary-foreground py-1">
                  السعرات الحرارية:
                </h2>
                <p>
                  - ما بين 200-300 سعرة حرارية، حسب كمية الزيت والمايونيز
                  والتونة. الخضار لا تُحسب إذا كانت الكمية قليلة.
                </p>
              </section>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/l3.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              { variant: 'outline' },
            )}">سلطة الباذنجان</Dialog.Trigger
          >
          <Dialog.Content
            class=" w-[70vw] h-[90vh] lg:h-[95vh]   bg-secondary shadow-md"
          >
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >سلطة الباذنجان
              </Dialog.Title>
            </Dialog.Header>
            <div class=" lg:text-sm text-xs">
              <section>
                <h2 class="text-secondary-foreground pb-1">المكونات:</h2>
                <ul>
                  <li>
                    - حبة بطاطس (مقطعة مكعبات ومقلية في القلاية الهوائية).
                  </li>
                  <li>
                    - حبة باذنجان (مقطعة مكعبات ومقلية في القلاية الهوائية).
                  </li>
                  <li>- بقدونس (مفروم).</li>
                  <li>- 50 جم حمص.</li>
                </ul>
              </section>
              <section class="pb-2">
                <h2 class=" text-secondary-foreground py-1">للصوص:</h2>
                <ol class="">
                  <li>- 100 جم زبادي.</li>
                  <li>- عصرة ليمون.</li>
                  <li>- ملعقة كبيرة طحينية.</li>
                  <li>- ملح وفلفل أسود.</li>
                </ol>
              </section>
              <section class="pb-2">
                <h2 class=" text-secondary-foreground py-1">للزينة:</h2>
                <ol class="">
                  <li>- رشة سماق.</li>
                </ol>
              </section>
              <section class="pلا-2">
                <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
                <ol class="">
                  <li>
                    1. قلِّ البطاطس والباذنجان في القلاية الهوائية حتى تنضج
                    وتصبح مقرمشة.
                  </li>
                  <li>
                    2. في وعاء، اخلط الزبادي، عصرة الليمون، الطحينية، الملح،
                    والفلفل الأسود.
                  </li>
                  <li>
                    3. ضع البطاطس والباذنجان في طبق التقديم، ثم رشّ البقدونس
                    والحمص.
                  </li>
                  <li>4. أضف الصوص فوق الخضار ورشّ السماق على الوجه.</li>
                </ol>
              </section>
              <section class="py-2">
                <h2 class="text-secondary-foreground py-1">
                  السعرات الحرارية:
                </h2>
                <p>- 390 سعرة حرارية.</p>
              </section>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/l4.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              { variant: 'outline' },
            )}">سلطة منعشة</Dialog.Trigger
          >
          <Dialog.Content
            class=" w-[70vw] h-[90vh] lg:h-[95vh] bg-secondary shadow-md"
          >
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
              >
                سلطة منعشة
              </Dialog.Title>
            </Dialog.Header>
            <div class=" lg:text-sm text-xs">
              <section>
                <h2 class="text-secondary-foreground py-1">المكونات:</h2>
                <ul>
                  <li>- 170 جم دجاج.</li>
                  <li>- ورقيات: خس وجرجير.</li>
                  <li>- 60 جم زبادي يوناني.</li>
                  <li>- 15 جم مايونيز قليل السعرات.</li>
                  <li>- 20 جم جبن كريمي قليل الدسم.</li>
                  <li>- 35 جم طماطم كرزية.</li>
                  <li>- تباسكو الأخضر (اختياري).</li>
                  <li>- خل أسود.</li>
                  <li>- عصير ليمون.</li>
                  <li>- سكر ستيفيا.</li>
                  <li>- 1 جم مايونيز الترافل (اختياري).</li>
                </ul>
              </section>
              <section class="py-2">
                <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
                <ol class="">
                  <li>
                    1. تبل الدجاج بالملح، الفلفل الأسود، بودرة البصل، والثوم.
                    اشويه على التاوه مع إضافة نقطة ماء وتغطية المقلاة حتى تنضج
                    البهارات.
                  </li>
                  <li>
                    2. لتحضير الصوص: اخلط الزبادي اليوناني، المايونيز قليل
                    السعرات، الجبن الكريمي، تباسكو الأخضر (إذا كنت تستخدمه)،
                    الخل الأسود، عصير الليمون، سكر ستيفيا، ومايونيز الترافل (إذا
                    كنت تستخدمه) في وعاء حتى تتجانس المكونات.
                  </li>
                  <li>3. امزج الصوص مع الخضار والدجاج المقطع.</li>
                </ol>
              </section>
              <section class="py-4">
                <h2 class="text-secondary-foreground py-1">
                  السعرات الحرارية:
                </h2>
                <p>- 271 سعرة حرارية.</p>
              </section>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/l5.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              { variant: 'outline' },
            )}">سلطة البطاطس</Dialog.Trigger
          >
          <Dialog.Content
            class=" w-[70vw] h-[90vh] lg:h-[95vh] bg-secondary shadow-md"
          >
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
              >
                سلطة البطاطس
              </Dialog.Title>
            </Dialog.Header>
            <div class=" lg:text-sm text-xs">
              <section>
                <h2 class="text-secondary-foreground py-2">المكونات:</h2>
                <ul>
                  <li>- 200 جم زبادي يوناني خال الدسم.</li>
                  <li>- 10 جم طحينية سائلة.</li>
                  <li>- نعناع مجفف.</li>
                  <li>- ملح.</li>
                  <li>- فلفل أسود.</li>
                  <li>- بطاطس صغيرة بقشرتها.</li>
                </ul>
              </section>
              <section class="py-2">
                <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
                <ol class="">
                  <li>
                    1. اخلط الزبادي اليوناني مع الطحينية، النعناع المجفف، الملح،
                    والفلفل الأسود.
                  </li>
                  <li>
                    2. اسلق البطاطس بقشرتها، ثم اضغط عليها برفق حتى تنفتح
                    قليلاً.
                  </li>
                  <li>
                    3. تبّل البطاطس بالملح، الفلفل الأسود، بودرة الثوم،
                    والبابريكا.
                  </li>
                  <li>
                    4. ضع البطاطس في الفرن وحمّرها من الأعلى حتى تصبح ذهبية
                    ومقرمشة.
                  </li>
                </ol>
              </section>
              <section class="py-2">
                <h2 class="text-secondary-foreground py-1">ملاحظة:</h2>
                <p>-يمكن إضافة سلطة من اختيارك ورمان إلى الطبق.</p>
              </section>
              <section class="py-2">
                <h2 class="text-secondary-foreground py-1">
                  السعرات الحرارية:
                </h2>
                <p>- 349 سعرة حرارية.</p>
              </section>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/l6.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              { variant: 'outline' },
            )}">سلطة آسيوية</Dialog.Trigger
          >
          <Dialog.Content
            class=" w-[70vw] h-[90vh] lg:h-[90vh]  bg-secondary shadow-md"
          >
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >سلطة آسيوية
              </Dialog.Title>
            </Dialog.Header>
            <div class="flex justify-center items-center">
              <ScrollArea
                class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4"
              >
                <div class=" lg:text-sm text-xs">
                  <section>
                    <h2 class="text-secondary-foreground pb-1">المكونات:</h2>
                    <ul>
                      <li>- 45 جم كينوا.</li>
                      <li>- أوراق كيل (سعراتها شبه معدومة، لا تحسب).</li>
                      <li>- 210 جم قرع (مقطع مكعبات).</li>
                      <li>- 36 جم إدامامي (مجمد ومقشر).</li>
                      <li>- 1 جم بودرة فول سوداني.</li>
                      <li>- 3 جم زبدة فول سوداني.</li>
                      <li>- 3 جم ثوم (مفروم).</li>
                      <li>- 3 جم عسل.</li>
                      <li>- خردل (حسب الرغبة، لا تحسب سعراته).</li>
                    </ul>
                  </section>
                  <section class="pb-2">
                    <h2 class=" text-secondary-foreground py-1">للصوص:</h2>
                    <ol class="">
                      <li>- 3 جم زبدة فول سوداني.</li>
                      <li>- 1 جم بودرة فول سوداني.</li>
                      <li>- عصير ليمون.</li>
                      <li>- خردل.</li>
                      <li>- ثوم مهروس.</li>
                      <li>- ظرف ستيفيا.</li>
                      <li>- عسل.</li>
                      <li>- ملح.</li>
                    </ol>
                  </section>
                  <section class="pb-2">
                    <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
                    <ol class="">
                      <li>
                        1. قطّع أوراق الكيل، اغسلها جيدًا، ثم أضف إليها نصف
                        ليمون وامزجها لمدة دقيقتين. إذا تفضل زيت الزيتون، يمكنك
                        استبدال الليمون به وحسابه ضمن احتياجك.
                      </li>
                      <li>2. سلُق الكينوا حتى تنضج.</li>
                      <li>
                        3. قطع القرع إلى مكعبات، واطبخه في القلاية الهوائية على
                        درجة حرارة 200 مئوية لمدة 15 دقيقة، مع التحقق من استوائه
                        كل فترة.
                      </li>
                      <li>
                        4. أذب زبدة الفول السوداني، ثم أضف بودرة فول السوداني،
                        عصير الليمون، خردل، الثوم المهروس، ستيفيا، العسل،
                        والملح. اخلط جيدًا.
                      </li>
                      <li>
                        5. اخلط الكينوا، القرع، الإدامامي، وأوراق الكيل، ثم أضف
                        الصوص فوق الخليط وامزج جيدًا.
                      </li>
                    </ol>
                  </section>
                  <section class="py-2">
                    <h2 class="text-secondary-foreground py-1">
                      السعرات الحرارية:
                    </h2>
                    <p>- 333 سعرة حرارية.</p>
                  </section>
                </div>
              </ScrollArea>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/l7.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              { variant: 'outline' },
            )}">سلطة البروكلي</Dialog.Trigger
          >
          <Dialog.Content
            class=" w-[70vw] h-[90vh] lg:h-[90vh]  bg-secondary shadow-md"
          >
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >سلطة البروكلي
              </Dialog.Title>
            </Dialog.Header>
            <div class="flex justify-center items-center">
              <ScrollArea
                class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4"
              >
                <div class=" lg:text-sm text-xs">
                  <section>
                    <h2 class="text-secondary-foreground pb-1">المكونات:</h2>
                    <ul>
                      <li>- رأس بروكلي.</li>
                      <li>- رأس خس.</li>
                      <li>- نصف كوب ذرة.</li>
                      <li>- 2 صدر دجاج مسحب.</li>
                    </ul>
                  </section>
                  <section class="pb-2">
                    <h2 class=" text-secondary-foreground py-1">للصوص:</h2>
                    <ol class="">
                      <li>- حبة أفوكادو.</li>
                      <li>- عصير ليمونة.</li>
                      <li>- ملعقتين كبار روب يوناني.</li>
                      <li>- مغلف بهارات رانش (من مركز سلطان).</li>
                      <li>- حفنة كزبرة طازجة.</li>
                      <li>- ملعقة كبيرة خل أبيض.</li>
                      <li>- ملح وفلفل أسود.</li>
                    </ol>
                  </section>
                  <section class="pb-2">
                    <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
                    <ol class="">
                      <li>
                        1. اطبخ صدور الدجاج حتى تنضج، ثم قطعها إلى قطع صغيرة.
                      </li>
                      <li>
                        2. اغسل البروكلي جيدًا وقطّعه إلى زهرات صغيرة، ثم اسلقه
                        أو بخّره حتى ينضج.
                      </li>
                      <li>3. اغسل الخس وقطّعه.</li>
                      <li>
                        4. في وعاء كبير، امزج البروكلي، الخس، الذرة، وقطع
                        الدجاج.
                      </li>
                      <li>
                        5. لتحضير الصوص، اخلط الأفوكادو، عصير الليمون، الروب
                        اليوناني، بهارات الرانش، الكزبرة، الخل، الملح، والفلفل
                        الأسود في الخلاط حتى يصبح ناعمًا.
                      </li>
                      <li>6. أضف الصوص إلى السلطة وامزج جيدًا.</li>
                    </ol>
                  </section>
                  <section class="py-2">
                    <h2 class="text-secondary-foreground py-1">
                      السعرات الحرارية:
                    </h2>
                    <p>
                      - تم تقسيم الكمية إلى قسمين، وكل قسم يحتوي على 325 سعرة
                      حرارية.
                    </p>
                  </section>
                </div>
              </ScrollArea>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/l8.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              { variant: 'outline' },
            )}">سلطة كينوا</Dialog.Trigger
          >
          <Dialog.Content
            class=" w-[70vw] h-[90vh] lg:h-[90vh]  bg-secondary shadow-md"
          >
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >سلطة كينوا
              </Dialog.Title>
            </Dialog.Header>
            <div class="flex justify-center items-center">
              <ScrollArea
                class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4"
              >
                <div class=" lg:text-sm text-xs">
                  <section>
                    <h2 class="text-secondary-foreground pb-1">المكونات:</h2>
                    <ul>
                      <li>- كينوا مطبوخة.</li>
                      <li>- خس (مقطع)</li>
                      <li>- خيار (مقطع).</li>
                      <li>- فلفل رومي أحمر (مقطع).</li>
                      <li>
                        - حمص محمص بالفرن (جاهز، مُضاف له بهارات ملح، فلفل أسود،
                        بابريكا، ومحمص في الفرن حتى يصبح مقرمش).
                      </li>
                    </ul>
                  </section>
                  <section class="pb-2">
                    <h2 class=" text-secondary-foreground py-1">للصوص:</h2>
                    <ol class="">
                      <li>- زبادي (مخفف بماء).</li>
                      <li>- ملح.</li>
                      <li>- شوية طحينة سائلة.</li>
                    </ol>
                  </section>
                  <section class="pb-2">
                    <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
                    <ol class="">
                      <li>
                        1. امزج الكينوا المطبوخة مع الخس المفروم، الخيار المقطع،
                        والفلفل الرومي.
                      </li>
                      <li>2. أضف الحمص المحمص إلى الخليط.</li>
                      <li>
                        3. لتحضير الصوص، اخلط الزبادي مع الماء والملح، ثم أضف
                        الطحينة السائلة واخلط جيدًا.
                      </li>
                      <li>4. أضف الصوص إلى السلطة وامزج جيدًا.</li>
                    </ol>
                  </section>
                  <section class="py-2">
                    <h2 class="text-secondary-foreground py-1">ملاحظة:</h2>
                    <p>
                      يمكن إضافة قطع دجاج مشوية لزيادة كمية البروتين وتعزيز
                      الشبع.
                    </p>
                    <section />
                  </section>
                  <section class="py-2">
                    <h2 class="text-secondary-foreground py-1">
                      السعرات الحرارية:
                    </h2>
                    <p>- 333 سعرة حرارية.</p>
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
