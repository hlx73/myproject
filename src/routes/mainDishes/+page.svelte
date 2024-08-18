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
                      <li>
                        - بصل: حبة صغيرة (36 جرام)
                      </li>
                      <li>
                        - فلفل رومي: حبة وسط (80 جرام)                      </li>
                      <li>
                        - صدور دجاج: 217 جرام (صدرين)                      </li>
                      <li>
                        - زبادي سائل يوناني: نصف كوب تقريباً (100 جرام)

                      </li>
                      <li>
                        - موزاريلا: ملعقة (15 جرام)                      </li>
                      <li>- سبرنج رول: 4 حبات</li>
                       </ul>
                  </section>
                  <section class="pt-2">
                    <h2 class=" text-secondary-foreground pb-1">الطريقة:</h2>
                    <h2 class=" text-secondary-foreground">
                      1. تحضير الحشوة:                    </h2>
                    <ol class="">
                      <li>   - سخن الصاج وأضف الدجاج، البصل، والفلفل الرومي.</li>
                      <li>   - أضف البهارات (ملح، فلفل أسود، بابريكا، بهارات إيطالية) واطبخ حتى ينضج الدجاج ويذبل البصل والفلفل.</li>
                      <li class="pt-2 text-secondary-foreground">
                        2. تجهيز السبرنج رول:                      </li>
                      <li>
                        - افرد السبرنج رول واملأه بالحشوة.
                      </li>
                      <li>   - رشّ الموزاريلا فوق الحشوة ولفّ السبرنج رول.
                      </li>
                      <li class="pt-2 text-secondary-foreground">
                        3. الخبز:                      </li>
                      <li>
                        - رصّ السبرنج رول المحشو في صينية خبز.
                      </li>
                      <li>
                        - صبّ الزبادي فوق السبرنج رول.

                      </li>
                      <li>
                        - اخبز في فرن مسبق التسخين على درجة حرارة 180 مئوية من فوق ومن تحت لمدة 7 دقائق.
                      </li>
                      
                    </ol>
                  </section>

                  <h2 class="text-secondary-foreground pb-1">
                    السعرات الحرارية:
                  </h2>
                  <p>-377  سعرة حرارية</p>
                </div>
              </ScrollArea>
            </div>
          </Dialog.Content>
        </Dialog.Root>
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
