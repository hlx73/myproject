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
                    <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
                    <h2 class=" text-secondary-foreground">
                      1. تحضير الروبيان:
                    </h2>
                    <ol class="">
                      <li>
                        - أضف فص ثوم مفروم وفلفل (بعد إزالة البذور) وقلِّب حتى
                        يتحمر الثوم.
                      </li>
                      <li>- أضف البصل المفروم وحمِّسه حتى يذوب ويتكرمل.</li>
                      <li>- أضف قليل من الماء إذا لزم الأمر لذوبان البصل.</li>
                      <li>
                        - التوابل: ملح، الفلفل الأسود، الكمون، والبهارات
                        المشكلة.
                      </li>
                      <li>- أضف ملعقة كبيرة من الكريمة وامزج جيداً.</li>
                      <li>- اعصر ليمونة فوق الخليط قبل الانتهاء.</li>
                    </ol>
                  </section>
                  <section class="py-3">
                    <h2 class=" text-secondary-foreground py-1">
                      2. تحضير الصامولي:
                    </h2>
                    <ol class="">
                      <li></li>
                      <li>- فرغ الصامولي من الداخل.</li>
                      <li>- ضع فيه طبقة من الخس والبقدونس.</li>
                      <li>- أضف خليط الروبيان فوق الخضار.</li>
                    </ol>
                  </section>
                  <section class="py-4">
                    <h2 class="text-secondary-foreground py-1">
                      السعرات الحرارية:
                    </h2>
                    <p>-371 سعرة حرارية</p>
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
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}">بيتزا خضار</Dialog.Trigger
          >
          <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >بيتزا خضار
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
                      <li>
                        - عجينة جاهزة (Deli Sun Pizza Base أو خبز تورتيلا): 252
                        سعرة
                      </li>
                      <li>- صدر دجاج مقطع قطع صغيرة: 87 جرام</li>
                      <li>- جبنة فيتا لايت: 35 جرام</li>
                      <li>
                        - سبانخ مفروم مجمد أو طازج: 35 جرام (يمكن استبدالها
                        بريحان إذا لم تفضلها)
                      </li>
                      <li>- جبنة موزاريلا خالي الدسم أو لايت: 30 جرام</li>
                      <li>- زيتون شرائح: 15 جرام</li>
                      <li>
                        - بهارات إيطالية (أوريغانو، فلفل أسود، فلفل أحمر مجروش):
                        حسب الذوق
                      </li>

                      <li>- جبن بارميزان (اختياري): 7 جرام (15 سعرة إضافية)</li>
                    </ul>
                  </section>
                  <section class="py-3">
                    <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
                    <h2 class="py-2 text-secondary-foreground">
                      1. تحضير الدجاج:
                    </h2>
                    <ol class="">
                      <li>- شوي الدجاج في مقلاة حتى ينضج تماماً.</li>
                      <li class="py-2 text-secondary-foreground">
                        2. تحضير المكونات الأخرى:
                      </li>
                      <li>
                        - إذا كنت تستخدم سبانخ مجمد، ذوبه في المايكروويف أو قم
                        بإعداده مسبقاً.
                      </li>
                      <li class="py-2 text-secondary-foreground">
                        3. تجميع البيتزا:
                      </li>
                      <li>
                        - إذا كنت تستخدم خبز التورتيلا، قم بخبزه في فرن مسخن
                        مسبقاً على درجة حرارة 200 درجة مئوية لمدة 8 دقائق، أو
                        اتبع التعليمات الموجودة على غلاف العجينة الجاهزة.
                      </li>
                      <li>
                        - ضع على العجينة الجاهزة أو خبز التورتيلا طبقة من جبنة
                        الفيتا، ثم أضف الدجاج، السبانخ، جبنة الموزاريلا،
                        والزيتون.
                      </li>
                      <li>
                        - رش البهارات الإيطالية والجبن البارميزان (إذا كنت
                        تستخدمه) على الوجه.
                      </li>
                      <li class="py-2 text-secondary-foreground">4. الخبز:</li>
                      <li>
                        - أعد البيتزا إلى الفرن واخبزها على درجة حرارة 200 مئوية
                        حتى تذوب الجبنة وتصبح العجينة مقرمشة.
                      </li>
                    </ol>
                  </section>

                  <h2 class="text-secondary-foreground py-1">
                    السعرات الحرارية:
                  </h2>
                  <p>-481 سعرة حرارية</p>
                </div>
              </ScrollArea>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/m3.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}">فاهيتا الدجاج</Dialog.Trigger
          >
          <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >فاهيتا الدجاج
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
                      <li>- صدري دجاج: 215 جرام</li>
                      <li>- فلفل رومي ملون: 160 جرام</li>
                      <li>- جبنة فيتا لايت: 35 جرام</li>
                      <li>- بصل: 30 جرام</li>
                      <li>- ثوم: 10 جرام</li>
                      <li>- زبادي يوناني: 90 جرام</li>
                      <li>- موزاريلا لايت: 10 جرام</li>

                      <li>- تورتيلا واحدة: 40 جرام</li>
                    </ul>
                  </section>
                  <section class="py-3">
                    <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
                    <h2 class="pt-2 text-secondary-foreground">
                      1. تحضير الدجاج:
                    </h2>
                    <ol class="">
                      <li>- قطع صدور الدجاج إلى شرائح طويلة.</li>
                      <li>
                        - سخّن التاوة وأضف إليها الدجاج مع الثوم المهروس والبصل.
                      </li>
                      <li>
                        - أضف البهارات: فلفل أسود، ملح، بودرة ثوم وبصل،
                        وبابريكا.
                      </li>
                      <li class="pt-2 text-secondary-foreground">
                        2. إضافة الزبادي:
                      </li>
                      <li>
                        - بعد نضج الدجاج وذبول البصل، أضف الزبادي اليوناني واترك
                        الخليط قليلاً على النار.
                      </li>
                      <li class="pt-2 text-secondary-foreground">
                        3. تحضير التورتيلا:
                      </li>
                      <li>- ضع خليط الدجاج فوق التورتيلا.</li>
                      <li>- رشّ الموزاريلا على الوجه.</li>

                      <li class="pt-2 text-secondary-foreground">
                        4. التحميص:
                      </li>
                      <li>
                        - حمّص التورتيلا على الصاج حتى تذوب الجبنة وتصبح ذهبية.
                      </li>
                    </ol>
                  </section>

                  <h2 class="text-secondary-foreground pt-2">ملاحظات:</h2>
                  <p>
                    - يمكن استبدال التورتيلا بمكونات أخرى مثل الأرز، البطاطس
                    دجز، المهروسة، المكرونة، التوست، أو بف باستري، ويجب حساب
                    السعرات بناءً على المكون المستخدم.
                  </p>
                  <h2 class="text-secondary-foreground pt-3">
                    السعرات الحرارية:
                  </h2>
                  <p>-509 سعرة حرارية</p>
                </div>
              </ScrollArea>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/m4.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}">سبرينغ رول</Dialog.Trigger
          >
          <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >سبرينغ رول
              </Dialog.Title>
            </Dialog.Header>
            <div class="flex justify-center items-center">
              <ScrollArea
                class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4"
              >
                <div class=" text-sm">
                  <section>
                    <h2 class="text-secondary-foreground pb-1">المكونات:</h2>
                    <ul>
                      <li>- بصل: حبة صغيرة (36 جرام)</li>
                      <li>- فلفل رومي: حبة وسط (80 جرام)</li>
                      <li>- صدور دجاج: 217 جرام (صدرين)</li>
                      <li>- زبادي سائل يوناني: نصف كوب تقريباً (100 جرام)</li>
                      <li>- موزاريلا: ملعقة (15 جرام)</li>
                      <li>- سبرنج رول: 4 حبات</li>
                    </ul>
                  </section>
                  <section class="pt-2">
                    <h2 class=" text-secondary-foreground pb-1">الطريقة:</h2>
                    <h2 class=" text-secondary-foreground">1. تحضير الحشوة:</h2>
                    <ol class="">
                      <li>- سخن الصاج وأضف الدجاج، البصل، والفلفل الرومي.</li>
                      <li>
                        - أضف البهارات (ملح، فلفل أسود، بابريكا، بهارات إيطالية)
                        واطبخ حتى ينضج الدجاج ويذبل البصل والفلفل.
                      </li>
                      <li class="pt-2 text-secondary-foreground">
                        2. تجهيز السبرنج رول:
                      </li>
                      <li>- افرد السبرنج رول واملأه بالحشوة.</li>
                      <li>- رشّ الموزاريلا فوق الحشوة ولفّ السبرنج رول.</li>
                      <li class="pt-2 text-secondary-foreground">3. الخبز:</li>
                      <li>- رصّ السبرنج رول المحشو في صينية خبز.</li>
                      <li>- صبّ الزبادي فوق السبرنج رول.</li>
                      <li>
                        - اخبز في فرن مسبق التسخين على درجة حرارة 180 مئوية من
                        فوق ومن تحت لمدة 7 دقائق.
                      </li>
                    </ol>
                  </section>

                  <h2 class="text-secondary-foreground pb-1">
                    السعرات الحرارية:
                  </h2>
                  <p>-377 سعرة حرارية</p>
                </div>
              </ScrollArea>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/m5.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}"
            >زنجر
          </Dialog.Trigger>
          <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >زنجر
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
                      <li>- صدر دجاج: 240 جرام</li>
                      <li>- نصف بيضة: 25 جرام</li>
                      <li>- كورنفلكس: 15 جرام</li>
                      <li>- شريحة جبن قليلة الدسم: 19 جرام</li>
                      <li>- صوص رانش خالي الدهون: 17 جرام</li>
                      <li>- صوص فرنسي خالي الدهون: 17 جرام</li>
                      <li>- مايونيز قليل السعرات: 17 جرام</li>
                      <li>- بطاطس: حبة متوسطة إلى صغيرة (137 جرام)</li>
                    </ul>
                  </section>
                  <section class="py-3">
                    <h2 class=" text-secondary-foreground py-1">
                      طريقة التحضير:
                    </h2>
                    <h2 class=" text-secondary-foreground">1. تحضير البرجر:</h2>
                    <ol class="">
                      <li>- سخّن القلاية الهوائية أو الفرن مسبقاً.</li>
                      <li>- اضغط صدر الدجاج ليصبح رقيقاً.</li>
                      <li>
                        - تبّل الدجاج بالملح، الفلفل الأسود، البابريكا، الفلفل
                        الحار، وبودرة الثوم والبصل.
                      </li>
                      <li>
                        - اغمس الدجاج في نصف البيضة ثم في الكورنفلكس المكسّر
                        والمضاف إليه نفس البهارات.
                      </li>
                      <li>
                        - اطبخ الدجاج في القلاية الهوائية على درجة حرارة 190
                        مئوية لمدة 15 دقيقة، أو حتى ينضج.
                      </li>
                    </ol>
                  </section>
                  <section class="py-3">
                    <h2 class=" text-secondary-foreground py-1">
                      2. تحضير الصوص:
                    </h2>
                    <ol class="">
                      <li>
                        - امزج البابريكا الحارة، صوص رانش، صلصة فرنسية،
                        والمايونيز قليل السعرات.
                      </li>
                    </ol>
                  </section>
                  <section class="py-3">
                    <h2 class=" text-secondary-foreground py-1">
                      3. تحضير البطاطس:
                    </h2>
                    <ol class="">
                      <li>- قشر البطاطس وقطعها.</li>
                      <li>- سلّق البطاطس في المايكروويف لمدة 4 دقائق.</li>
                      <li>
                        - ثم اطبخها في القلاية الهوائية على درجة حرارة 200 مئوية
                        لمدة 14 دقيقة.
                      </li>
                    </ol>
                  </section>
                  <section class="py-3">
                    <h2 class=" text-secondary-foreground py-1">4. التقديم:</h2>
                    <ol class="">
                      <li>
                        - استخدم الخبز المفضل لديك، وضيف صوص، خس، الدجاج
                        المقرمش، الجبن، وبقية الصوصات.
                      </li>
                    </ol>
                  </section>
                  <section class="py-4">
                    <h2 class="text-secondary-foreground py-1">
                      السعرات الحرارية:
                    </h2>
                    <p>-554 سعرة حرارية</p>
                  </section>
                </div>
              </ScrollArea>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/m6.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}"
            >كلوب ديلوكس
          </Dialog.Trigger>
          <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >كلوب ديلوكس
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
                      <li>- شريحة تورتيلا أسمر: 37 جرام (شركة يومي)</li>
                      <li>- بياض بيضتين: 60 جرام</li>
                      <li>- بيضة: 53 جرام</li>
                      <li>- شرائح ديك رومي مدخن قليل الدسم: 65 جرام</li>
                      <li>- ثلاث أرباع شريحة جبن قليلة الدسم: 12 جرام</li>
                      <li>- ملعقة رانش خالية الدهون: 12 جرام</li>
                      <li>- سيراشا: حوالي 5 جرام</li>
                    </ul>
                  </section>
                  <section class="py-3">
                    <h2 class=" text-secondary-foreground py-1">
                      طريقة البطاطس:
                    </h2>
                    <ol>
                      <li>
                        - ضع الشرائح في المايكروويف لمدة دقائق قليلة حتى تنضج
                        جزئيًا.
                      </li>
                      <li>
                        - بهّر الشرائح بالملح، الفلفل الأسود، البابريكا المدخنة،
                        البهارات الإيطالية، وبودرة الثوم.
                      </li>
                      <li>
                        - ضع الشرائح في القلاية الهوائية على درجة حرارة 200
                        مئوية لمدة 8 دقائق حتى تصبح مقرمشة.
                      </li>
                    </ol>
                  </section>
                  <section class="py-3">
                    <h2 class=" text-secondary-foreground py-1">
                      طريقة تحضير الوجبة:
                    </h2>
                    <h2 class=" text-secondary-foreground py-1">
                      1.تحضير التورتيلا:
                    </h2>
                    <ol class="">
                      <li>
                        - ضع شريحة التورتيلا في مقلاة أو على صاج التسخين قليلاً.
                      </li>
                    </ol>
                  </section>
                  <section class="py-2">
                    <h2 class=" text-secondary-foreground py-1">
                      2.إعداد الحشوة:
                    </h2>
                    <ol class="">
                      <li>
                        - في وعاء، اخلط بياض البيض والبيضة بالكامل، ثم اسكب
                        الخليط على التورتيلا.
                      </li>
                      <li>- أضف شرائح الديك الرومي المدخن فوق الخليط.</li>
                      <li>- رش الجبن قليلة الدسم فوق الخليط.</li>
                    </ol>
                  </section>
                  <section class="py-3">
                    <h2 class=" text-secondary-foreground py-1">3. الطهي:</h2>
                    <ol class="">
                      <li>
                        - اطبخ الوجبة على نار هادئة حتى ينضج البيض ويذوب الجبن.
                      </li>
                    </ol>
                  </section>
                  <section class="py-3">
                    <h2 class=" text-secondary-foreground py-1">4. التقديم:</h2>
                    <ol class="">
                      <li>
                        - أضف ملعقة رانش خالية الدهون وسيراشا حسب الرغبة على
                        الوجه.
                      </li>
                    </ol>
                  </section>
                  <section class="py-3">
                    <h2 class=" text-secondary-foreground py-1">نصائح:</h2>
                    <ol class="">
                      <li>
                        - يمكنك إضافة خضروات مثل الفلفل أو الطماطم إلى الحشوة
                        للحصول على نكهة إضافية
                      </li>
                      <li />
                    </ol>
                  </section>
                  <section class="py-4">
                    <h2 class="text-secondary-foreground py-1">
                      السعرات الحرارية:
                    </h2>
                    <p>-389 سعرة حرارية</p>
                  </section>
                </div>
              </ScrollArea>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/m7.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}"
          >
            صحن فاهيتا
          </Dialog.Trigger>
          <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
              >
                صحن فاهيتا
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
                      <li>- صدرين دجاج (200 جرام)</li>
                      <li>- فلفل رومي حبة صغيرة (70 جرام)</li>
                      <li>- بصل أحمر حبة صغيرة (30 جرام)</li>
                      <li>
                        - خبز عربي أو تورتيلا (54 جرام، استخدمت خبز عربي عالي
                        بالبروتين وقليل الكارب)
                      </li>
                      <li>- زبادي يوناني (50 جرام، ملعقتين كبيرة)</li>
                    </ul>
                  </section>
                  <section class="py-3">
                    <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
                    <h2 class=" text-secondary-foreground py-1">
                      1.تحضير الخبز:
                    </h2>
                    <ol>
                      <li>
                        - ضع الخبز في صحن عميق أو صينية (يفضل إذا لديك صينية)
                        واضعه في القلاية الهوائية على درجة حرارة 200 مئوية لمدة
                        4 دقائق. يمكنك استخدام الفرن أيضًا. استخدم قصدير لتجنب
                        انتفاخ الخبز.
                      </li>
                    </ol>
                  </section>
                  <section class="py-3">
                    <h2 class=" text-secondary-foreground py-1">
                      2.تحضير الدجاج:
                    </h2>
                    <ol class="">
                      <li>
                        - قطع الدجاج إلى مربعات وتبّله بالملح، الفلفل الأسود،
                        البابريكا، البهارات الإيطالية، وبودرة الثوم.
                      </li>
                      <li>
                        - اطبخ الدجاج في القلاية الهوائية على درجة حرارة 200
                        مئوية لمدة 13 دقيقة.
                      </li>
                    </ol>
                  </section>
                  <section class="py-2">
                    <h2 class=" text-secondary-foreground py-1">
                      3.تحضير الخضروات:
                    </h2>
                    <ol class="">
                      <li>
                        - ضع البصل والفلفل الرومي على صاج أو مقلاة حتى يذبلوا،
                        ثم أضف الدجاج المطبوخ وأضف نفس البهارات المستخدمة بدون
                        ملح.
                      </li>
                    </ol>
                  </section>
                  <section class="py-3">
                    <h2 class=" text-secondary-foreground py-1">
                      4. تحضير الصوص:
                    </h2>
                    <ol class="">
                      <li>
                        - اخلط الزبادي اليوناني مع نفس البهارات المستخدمة، أضف
                        الفلفل الأبيض والشبت المجفف حسب الذوق.
                      </li>
                    </ol>
                  </section>
                  <section class="py-3">
                    <h2 class=" text-secondary-foreground py-1">5. التقديم:</h2>
                    <ol class="">
                      <li>
                        - ضع طبقة من الخس أولاً، ثم أضف الدجاج والخضروات،
                        وأخيرًا الصوص
                      </li>
                    </ol>
                  </section>

                  <section class="py-4">
                    <h2 class="text-secondary-foreground py-1">
                      السعرات الحرارية:
                    </h2>
                    <p>441 سعرة حرارية</p>
                  </section>
                </div>
              </ScrollArea>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/m9.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}"
          >
            صينية بطاطس
          </Dialog.Trigger>
          <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
              >
                صينية بطاطس
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
                      <li>- بطاطس: 280 جرام (حبتين متوسطة)</li>
                      <li>- صدور دجاج: 260 جرام (صدرين كبيرين أو 3 صغار)</li>
                      <li>- حليب قليل الدسم: 50 جرام (ربع كوب)</li>
                      <li>- موزاريلا لايت: 33 جرام (ملعقتين كبيرتين)</li>
                      <li>- كريمة طبخ: 100 جرام (ثلاثة أرباع الكوب)</li>
                      <li>- بصل: 49 جرام (حبة صغيرة)</li>
                      <li>- ثوم: 4 جرام (فص واحد كبير)</li>
                      <li>- صلصة طماطم: 15 جرام</li>
                    </ul>
                  </section>
                  <section class="py-3">
                    <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
                    <h2 class=" text-secondary-foreground py-1">
                      1. تحضير الدجاج:
                    </h2>
                    <ol>
                      <li>- قطّع صدور الدجاج إلى قطع صغيرة.</li>
                      <li>
                        - قم بطهي الدجاج في صاج مع بصل، فلفل رومي، ثوم، ومعجون
                        طماطم.
                      </li>
                      <li>
                        - أضف بهارات: ملح، بابريكا، وفلفل أسود إلى الخليط واتركه
                        ينضج.
                      </li>
                    </ol>
                  </section>
                  <section class="py-3">
                    <h2 class=" text-secondary-foreground py-1">
                      2. تحضير البطاطس:
                    </h2>
                    <ol class="">
                      <li>
                        - قشّر البطاطس وقطعها إلى مكعبات صغيرة، ثم اغليها حتى
                        تنضج.
                      </li>
                      <li>
                        - بعد النضج، هرّس البطاطس مع الحليب حتى تصبح ناعمة.
                      </li>
                    </ol>
                  </section>
                  <section class="py-2">
                    <h2 class=" text-secondary-foreground py-1">
                      3. تجميع الطبق:
                    </h2>
                    <ol class="">
                      <li>- ضع خليط الدجاج في صينية خبز.</li>
                      <li>- كوّر البطاطس المهروسة فوق خليط الدجاج.</li>
                      <li>- أضف الكريمة على الوجه وزد عليها 50 مل من الماء.</li>
                      <li>- رشّ الموزاريلا فوق الطبقة الأخيرة.</li>
                    </ol>
                  </section>
                  <section class="py-3">
                    <h2 class=" text-secondary-foreground py-1">4.الخبز:</h2>
                    <ol class="">
                      <li>
                        - ضع الصينية في الفرن على حرارة من الأعلى حتى تذوب
                        الجبنة وتتحمر.
                      </li>
                    </ol>
                  </section>

                  <section class="py-4">
                    <h2 class="text-secondary-foreground py-1">
                      السعرات الحرارية:
                    </h2>
                    <p>السعرات الحرارية للصينية كاملة: 817 سعرة حرارية</p>
                  </section>
                </div>
              </ScrollArea>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/m10.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}"
          >
            معكرونة باللحم
          </Dialog.Trigger>
          <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
              >
                معكرونة باللحم
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
                      <li>- 100 جرام لحم مفروم</li>
                      <li>- 150 جرام خضار مجمدة (جزر، بازيلاء، ذرة)</li>
                      <li>- نصف ملعقة صغيرة زيت زيتون (30 سعرة)</li>
                      <li>- 100 جرام معكرونة مسلوقة (158 سعرة)</li>
                      <li>- بهارات (ملح، فلفل أسود، زعتر بري)</li>
                      <li>- حبة طماطم مبشورة أو ملعقة معجون طماطم</li>
                      <li>- بصلة</li>
                      <li>- سلطة خضار (طماطم، خيار، ملفوف أحمر)</li>
                    </ul>
                  </section>
                  <section class="py-3">
                    <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>

                    <ol>
                      <li>
                        1. في مقلاة، سخن الزيت وأضف البصلة المفرومة حتى تدبل.
                      </li>
                      <li>2. أضف اللحم المفروم وقلِّب حتى ينضج ويتغير لونه.</li>
                      <li>3. أضف الخضار المجمدة وقلِّب لمدة دقيقة.</li>
                      <li>
                        4. أضف المعكرونة والطماطم المبشورة أو معجون الطماطم، ثم
                        البهارات.
                      </li>
                      <li>
                        5. اخلط جيداً واطبخ لمدة دقيقتين حتى تتجانس النكهات.
                      </li>
                    </ol>
                  </section>

                  <section class="py-4">
                    <h2 class="text-secondary-foreground py-1">
                      السعرات الحرارية:
                    </h2>
                    <p>492 سعرة حرارية</p>
                  </section>
                </div>
              </ScrollArea>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/m11.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}"
          >
            بيتزا الشوفان
          </Dialog.Trigger>
          <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
              >
                بيتزا الشوفان
              </Dialog.Title>
            </Dialog.Header>
            <div class="flex justify-center items-center">
              <ScrollArea
                class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4"
              >
                <div class=" text-sm">
                  <section>
                    <h2 class="text-secondary-foreground py-1">المكونات:</h2>
                    <h2 class="text-secondary-foreground py-1">للعجينة:</h2>
                    <ul>
                      <li>- كوب شوفان مطحون</li>
                      <li>- كوب طحين أسمر</li>
                      <li>- ملعقة طعام خميرة</li>
                      <li>- ملعقة طعام عسل</li>
                      <li>- ملعقتين زيت زيتون أو زيت نباتي</li>
                      <li>- نصف كوب ماء دافئ</li>
                    </ul>
                  </section>
                  <section class="py-3">
                    <h2 class=" text-secondary-foreground py-1">للتزيين:</h2>

                    <ol>
                      <li>- دجاج: 11 جرام</li>
                      <li>- خضروات: فلفل أخضر، طماطم</li>
                      <li>- جبن موزاريلا: 45 جرام</li>
                    </ol>
                  </section>
                  <section class="py-3">
                    <h2 class=" text-secondary-foreground py-1">
                      لصلصة البيتزا:
                    </h2>
                    <ol class="">
                      <li>- ملعقتين طعام كاتشب</li>
                      <li>- 16 جرام معجون طماطم</li>
                      <li>- قليلاً من الشطة السائلة</li>
                    </ol>
                  </section>
                  <section class="py-2">
                    <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
                    <h2 class=" text-secondary-foreground py-1">
                      1. تحضير العجينة:
                    </h2>
                    <ol class="">
                      <li>
                        - اخلط الخميرة والماء الدافئ والعسل حتى تتفاعل الخميرة.
                      </li>
                      <li>- أضف الطحين، الشوفان، وزيت الزيتون إلى الخليط.</li>
                      <li>- اعجن حتى تصبح العجينة متماسكة.</li>
                      <li>- اترك العجينة لترتاح لمدة ساعة.</li>
                    </ol>
                  </section>
                  <section class="py-3">
                    <h2 class=" text-secondary-foreground py-1">
                      2. تحضير الصلصة:
                    </h2>
                    <ol class="">
                      <li>- اخلط الكاتشب، معجون الطماطم، والشطة السائلة.</li>
                    </ol>
                  </section>
                  <section class="py-3">
                    <h2 class=" text-secondary-foreground py-1">
                      3. تحضير البيتزا:
                    </h2>
                    <ol class="">
                      <li>- ادهن القالب بقليل من الزيت.</li>
                      <li>- افرد العجينة على القالب.</li>
                      <li>- وزّع الصلصة على العجينة.</li>
                      <li>- أضف الدجاج، الخضروات، والجبن.</li>
                      <li>
                        - اخبز في الفرن مسبق التسخين على حرارة 180 درجة مئوية
                        لمدة 20 إلى 30 دقيقة حتى تنضج.
                      </li>
                    </ol>

                    <section class="py-4">
                      <h2 class="text-secondary-foreground py-1">
                        السعرات الحرارية:
                      </h2>
                      <p>- لكل البيتزا: 1194 سعرة حرارية</p>
                      <p>- لكل قطعة (من 8 قطع): 149 سعرة حرارية</p>
                    </section>
                  </section>
                </div>
              </ScrollArea>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/main dishes .jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}">فطيرة البطاطس</Dialog.Trigger
          >
          <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >فطيرة البطاطس
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
                      <li>- 150 جرام بطاطس</li>
                      <li>- 2 بيض</li>
                      <li>- ملح وفلفل أسود وشيلي فليكس (شطة حمراء مجففة)</li>
                      <li>- 30 جرام جبن موتزاريلا (اختياري)</li>
                    </ul>
                  </section>
                  <section class="py-3">
                    <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>

                    <ol class="">
                      <li>1. ابشر البطاطس وصفيها جيداً من الماء.</li>
                      <li>
                        2. اخلط البطاطس المبشورة مع البيض والتوابل (ملح، فلفل
                        أسود، وشيلي فليكس). أضف ملعقة كبيرة من البقدونس المفروم.
                      </li>
                      <li>
                        3. في مقلاة مدهونة ببخاخ زيت، افرد الخليط بسمك متساوي.
                      </li>
                      <li>
                        4. غطِّ المقلاة واتركها على نار متوسطة لمدة 3 دقائق حتى
                        يتحمر الوجه السفلي.
                      </li>
                      <li>
                        5. قلب الخليط على الجانب الآخر واستمر في الطهي حتى يتحمر
                        جيداً.
                      </li>
                    </ol>
                  </section>
                  <section class="py-3">
                    <h2 class=" text-secondary-foreground py-1">اختياري:</h2>
                    <p>أضف الجبن والفلفل الرومي بعد القلب النهائي.</p>
                  </section>
                  <section class="py-4">
                    <h2 class="text-secondary-foreground py-1">
                      السعرات الحرارية:
                    </h2>
                    <p>-301  سعرة حرارية</p>
                  </section>
                </div>
              </ScrollArea>
            </div>
          </Dialog.Content>
        </Dialog.Root>
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
