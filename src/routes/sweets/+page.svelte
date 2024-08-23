<script lang="ts">
  import { buttonVariants } from "$lib/components/ui/button";
  import Button from "$lib/components/ui/button/button.svelte";
  import * as Dialog from "$lib/components/ui/dialog";
  import { ScrollArea } from "$lib/components/ui/scroll-area/index.js";
</script>

<div class="flex flex-col items-center pb-20">
  <div
    class="  min-w-[18rem]  lg:gap-8 h-auto
     bg-gradient-to-r from-background/90 to-primary/50 dark:bg-primary shadow-[0_20px_60px_-15px_rgba(0,0,0,0.7)] ring-1 ring-secondary
     rounded-xl grid grid-cols-3 gap-9 p-6 "
  >
    <div class="max-w-[5rem] lg:max-w-[12rem] h-auto rounded-xl">
      <img src="/sweets.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}">بودينج الشوكولاتة</Dialog.Trigger
          >
          <Dialog.Content>
            <Dialog.Header class="">
              <Dialog.Title class="flex justify-center "
                >بودينج الشوكولاتة
              </Dialog.Title>
            </Dialog.Header>
              <ScrollArea
              >
                <div class=" text-sm">
                  <section>
                    <h2 class="text-primary font-bold py-1">المكونات:</h2>
                    <ul>
                      <li>- شوفان أو دقيق أبيض: 30 جرام</li>
                      <li>
                        - بروتين باودر: 20 جرام (أو حليب بروتين 70 جرام مع بيضة
                        إذا رغبت في زيادة البروتين)
                      </li>
                      <li>- بايكنج باودر: 2 جرام (ربع ملعقة صغيرة)</li>
                      <li>- كاكاو بودرة: 5 جرام (ملعقة صغيرة)</li>
                      <li>- سكر ستيفيا: 3 أظرف</li>
                      <li>- فواكه: فراولة ومزيج توت 100 جرام (نصف كوب)</li>
                      <li>- بيكان: 1 حبة</li>
                      <li>- لوز مبشور: 3 جرام</li>
                    </ul>
                  </section>
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold">مكونات البودينغ:</h2>
                    <ol class="">
                      <li>- كاكاو: 3 جرام</li>
                      <li>- حليب خالي الدسم: ثلاث أرباع كوب تقريباً</li>
                      <li>- نسكافيه: 1 جرام</li>
                      <li>- سكر ستيفيا: حسب الرغبة</li>
                      <li>- نشا 5 جرام مذاب في ماء</li>
                    </ol>
                  </section>
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold">الطريقة:</h2>
                    <p class="text-primary font-bold">الكيك:</p>

                    <ol class="">
                      <li></li>
                      <li>
                        1. في وعاء، اخلط الشوفان, البروتين, البايكنج
                        باودر , الكاكاو والمحلي +(70 مل ماء في حالة عدم
                        اضافة حليب البروتين).
                      </li>
                      <li>
                        2.اخبز الخليط في الفرن لمدة 15 دقيقة على درجة حرارة 180
                        من تحت
                      </li>
                    </ol>
                  </section>
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold">طريقة البودينغ:</h2>
                    <ol class="">
                      <li>- اخلط مكونات البودينغ فوق النار الى أن يثقل </li>
                      <li>- ادخل الخليط الى الثلاجة الى أن يبرد </li>

                    </ol>
                  </section>
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold"> التقديم:</h2>
                    <ol class="">
                      <li>- فتت الكيك بعد أن يخبز وضعه في طبق التقديم</li>
                      <li>- اضف المكسرات والفواكه والبودينغ</li>

                    </ol>
                  </section>
                  <section class="pt-3">
                    <h2 class="text-primary font-bold">  السعرات الحرارية:</h2>
                    <p>-362 سعرة حرارية</p>
                  </section>
                </div>
              </ScrollArea>

            <div class="flex justify-end items-end text-xs">
              <Button
                variant="ghost"
                href="https://www.instagram.com/healthy_shody?igsh=NG5kY28yamt0amk3"
              >
                <p class="px-1">healthy_shody@</p>
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="1em"
                  height="1em"
                  viewBox="0 0 256 256"
                  ><g fill="none"
                    ><rect
                      width="256"
                      height="256"
                      fill="url(#skillIconsInstagram0)"
                      rx="60"
                    /><rect
                      width="256"
                      height="256"
                      fill="url(#skillIconsInstagram1)"
                      rx="60"
                    /><path
                      fill="#fff"
                      d="M128.009 28c-27.158 0-30.567.119-41.233.604c-10.646.488-17.913 2.173-24.271 4.646c-6.578 2.554-12.157 5.971-17.715 11.531c-5.563 5.559-8.98 11.138-11.542 17.713c-2.48 6.36-4.167 13.63-4.646 24.271c-.477 10.667-.602 14.077-.602 41.236s.12 30.557.604 41.223c.49 10.646 2.175 17.913 4.646 24.271c2.556 6.578 5.973 12.157 11.533 17.715c5.557 5.563 11.136 8.988 17.709 11.542c6.363 2.473 13.631 4.158 24.275 4.646c10.667.485 14.073.604 41.23.604c27.161 0 30.559-.119 41.225-.604c10.646-.488 17.921-2.173 24.284-4.646c6.575-2.554 12.146-5.979 17.702-11.542c5.563-5.558 8.979-11.137 11.542-17.712c2.458-6.361 4.146-13.63 4.646-24.272c.479-10.666.604-14.066.604-41.225s-.125-30.567-.604-41.234c-.5-10.646-2.188-17.912-4.646-24.27c-2.563-6.578-5.979-12.157-11.542-17.716c-5.562-5.562-11.125-8.979-17.708-11.53c-6.375-2.474-13.646-4.16-24.292-4.647c-10.667-.485-14.063-.604-41.23-.604zm-8.971 18.021c2.663-.004 5.634 0 8.971 0c26.701 0 29.865.096 40.409.575c9.75.446 15.042 2.075 18.567 3.444c4.667 1.812 7.994 3.979 11.492 7.48c3.5 3.5 5.666 6.833 7.483 11.5c1.369 3.52 3 8.812 3.444 18.562c.479 10.542.583 13.708.583 40.396s-.104 29.855-.583 40.396c-.446 9.75-2.075 15.042-3.444 18.563c-1.812 4.667-3.983 7.99-7.483 11.488c-3.5 3.5-6.823 5.666-11.492 7.479c-3.521 1.375-8.817 3-18.567 3.446c-10.542.479-13.708.583-40.409.583c-26.702 0-29.867-.104-40.408-.583c-9.75-.45-15.042-2.079-18.57-3.448c-4.666-1.813-8-3.979-11.5-7.479s-5.666-6.825-7.483-11.494c-1.369-3.521-3-8.813-3.444-18.563c-.479-10.542-.575-13.708-.575-40.413s.096-29.854.575-40.396c.446-9.75 2.075-15.042 3.444-18.567c1.813-4.667 3.983-8 7.484-11.5s6.833-5.667 11.5-7.483c3.525-1.375 8.819-3 18.569-3.448c9.225-.417 12.8-.542 31.437-.563zm62.351 16.604c-6.625 0-12 5.37-12 11.996c0 6.625 5.375 12 12 12s12-5.375 12-12s-5.375-12-12-12zm-53.38 14.021c-28.36 0-51.354 22.994-51.354 51.355s22.994 51.344 51.354 51.344c28.361 0 51.347-22.983 51.347-51.344c0-28.36-22.988-51.355-51.349-51.355zm0 18.021c18.409 0 33.334 14.923 33.334 33.334c0 18.409-14.925 33.334-33.334 33.334s-33.333-14.925-33.333-33.334c0-18.411 14.923-33.334 33.333-33.334"
                    /><defs
                      ><radialGradient
                        id="skillIconsInstagram0"
                        cx="0"
                        cy="0"
                        r="1"
                        gradientTransform="matrix(0 -253.715 235.975 0 68 275.717)"
                        gradientUnits="userSpaceOnUse"
                        ><stop stop-color="#fd5" /><stop
                          offset=".1"
                          stop-color="#fd5"
                        /><stop offset=".5" stop-color="#ff543e" /><stop
                          offset="1"
                          stop-color="#c837ab"
                        /></radialGradient
                      ><radialGradient
                        id="skillIconsInstagram1"
                        cx="0"
                        cy="0"
                        r="1"
                        gradientTransform="matrix(22.25952 111.2061 -458.39518 91.75449 -42.881 18.441)"
                        gradientUnits="userSpaceOnUse"
                        ><stop stop-color="#3771c8" /><stop
                          offset=".128"
                          stop-color="#3771c8"
                        /><stop
                          offset="1"
                          stop-color="#60f"
                          stop-opacity="0"
                        /></radialGradient
                      ></defs
                    ></g
                  ></svg
                >
              </Button>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class="max-w-[5rem] lg:max-w-[12rem] h-auto rounded-xl">
      <img src="/sw1.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[15vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}">ميني بانكيك</Dialog.Trigger
          >
          <Dialog.Content >
            <Dialog.Header class="">
              <Dialog.Title class="flex justify-center "
                >ميني بانكيك
              </Dialog.Title>
            </Dialog.Header>
              <ScrollArea
              >
                <div class=" text-sm">
                  <section>
                    <h2 class="text-primary font-bold py-1">المكونات:</h2>
                    <p class="text-primary font-bold">1. خليط الشوفان:</p>
                    <ul>
                      <li>- شوفان مطحون: 50 جرام (5 ملاعق)</li>
                      <li>- ماء: 70 مل</li>
                      <li>- باكينج بودر: 3 جرام (ربع ملعقة صغيرة)</li>
                      <li>- بياض بيضتين: 71 جرام (أو بيضة واحدة: 30 جرام)</li>
                      <li>- سكوب بروتين: 25 جرام (اختياري)</li>
                    </ul>
                  </section>
                 
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold">للكاسترد:</h2>
                    <p>- 60 مل من الحليب قليل الدسم</p>
                    <p>- 5 جرام من مسحوق الكاسترد</p>
                    <p>- ظرف سكر ستيفيا</p>
                    <p>- نقطة من نكهة الموز (تعطي طعم رائع)</p>
                    
                  </section>
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold">سعرات خليط الشوفان:</h2>
                    <p>- 325 سعرة حرارية (بدون كاسترد)</p>
                    <p>- مع الكاسترد: 366 سعرة حرارية</p>
                  </section>
                  <section>
                    <h2 class="text-primary font-bold pt-2">إضافات الفاكهة:</h2>
                    <ul>
                      <li>
                        - خليط الفراولة:أضف 24 جرام من الفراولة إلى نصف خليط الكاسترد
                      </li>
                      <li>-السعرات:28 سعرة حرارية</li>

                      <li>
                        -خليط التفاح:أضف 10 جرام من التفاح إلى النصف الآخر
                      </li>
                      <li>-السعرات:24 سعرة حرارية</li>
                    </ul>
                  </section>
                  <section class="pt-3">
                    <h2 class="text-primary font-bold">
                      2. بانكيك الموز واللوز:
                    </h2>
                    <ul>
                      <li>- زبدة اللوز: 4 جرام</li>
                      <li>- بروتين باودر: 4 جرام (اختياري)</li>
                      <li>- موز: 11 جرام</li>
                      <li>- شرائح اللوز: نصف جرام</li>
                      <li>- ماء: 6 جرام (إذا استخدمت بروتين باودر)</li>
                      <li class="">-السعرات:51 سعرة حرارية</li>
                      <li></li>
                    </ul>
                  </section>
                  <section class="pt-3">
                    <h2 class="text-primary font-bold">3. بانكيك المانجو:</h2>
                    <ul>
                      <li>- زبادي يوناني: 22 جرام</li>
                      <li>- بروتين باودر: 6 جرام (اختياري)</li>
                      <li>- مانجو: 16 جرام</li>
                      <li>-السعرات:47 سعرة حرارية</li>
                    </ul>
                  </section>
                  <section class="pt-3">
                    <h2 class="text-primary font-bold">4. بانكيك التمر:</h2>
                    <ul>
                      <li>
                        - تمر: 10 جرام (حبة مقسمة إلى نصفين، نصف للتزيين ونصف
                        لحشو البانكيك)
                      </li>
                      <li>- جبن فيتا: 2 جرام</li>
                      <li>-السعرات:49 سعرة حرارية</li>
                    </ul>
                  </section>
                </div>
              </ScrollArea>
            <div class="flex justify-end items-end text-xs">
              <Button
                variant="ghost"
                href="https://www.instagram.com/healthy_shody?igsh=NG5kY28yamt0amk3"
              >
                <p class="px-1">healthy_shody@</p>
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="1em"
                  height="1em"
                  viewBox="0 0 256 256"
                  ><g fill="none"
                    ><rect
                      width="256"
                      height="256"
                      fill="url(#skillIconsInstagram0)"
                      rx="60"
                    /><rect
                      width="256"
                      height="256"
                      fill="url(#skillIconsInstagram1)"
                      rx="60"
                    /><path
                      fill="#fff"
                      d="M128.009 28c-27.158 0-30.567.119-41.233.604c-10.646.488-17.913 2.173-24.271 4.646c-6.578 2.554-12.157 5.971-17.715 11.531c-5.563 5.559-8.98 11.138-11.542 17.713c-2.48 6.36-4.167 13.63-4.646 24.271c-.477 10.667-.602 14.077-.602 41.236s.12 30.557.604 41.223c.49 10.646 2.175 17.913 4.646 24.271c2.556 6.578 5.973 12.157 11.533 17.715c5.557 5.563 11.136 8.988 17.709 11.542c6.363 2.473 13.631 4.158 24.275 4.646c10.667.485 14.073.604 41.23.604c27.161 0 30.559-.119 41.225-.604c10.646-.488 17.921-2.173 24.284-4.646c6.575-2.554 12.146-5.979 17.702-11.542c5.563-5.558 8.979-11.137 11.542-17.712c2.458-6.361 4.146-13.63 4.646-24.272c.479-10.666.604-14.066.604-41.225s-.125-30.567-.604-41.234c-.5-10.646-2.188-17.912-4.646-24.27c-2.563-6.578-5.979-12.157-11.542-17.716c-5.562-5.562-11.125-8.979-17.708-11.53c-6.375-2.474-13.646-4.16-24.292-4.647c-10.667-.485-14.063-.604-41.23-.604zm-8.971 18.021c2.663-.004 5.634 0 8.971 0c26.701 0 29.865.096 40.409.575c9.75.446 15.042 2.075 18.567 3.444c4.667 1.812 7.994 3.979 11.492 7.48c3.5 3.5 5.666 6.833 7.483 11.5c1.369 3.52 3 8.812 3.444 18.562c.479 10.542.583 13.708.583 40.396s-.104 29.855-.583 40.396c-.446 9.75-2.075 15.042-3.444 18.563c-1.812 4.667-3.983 7.99-7.483 11.488c-3.5 3.5-6.823 5.666-11.492 7.479c-3.521 1.375-8.817 3-18.567 3.446c-10.542.479-13.708.583-40.409.583c-26.702 0-29.867-.104-40.408-.583c-9.75-.45-15.042-2.079-18.57-3.448c-4.666-1.813-8-3.979-11.5-7.479s-5.666-6.825-7.483-11.494c-1.369-3.521-3-8.813-3.444-18.563c-.479-10.542-.575-13.708-.575-40.413s.096-29.854.575-40.396c.446-9.75 2.075-15.042 3.444-18.567c1.813-4.667 3.983-8 7.484-11.5s6.833-5.667 11.5-7.483c3.525-1.375 8.819-3 18.569-3.448c9.225-.417 12.8-.542 31.437-.563zm62.351 16.604c-6.625 0-12 5.37-12 11.996c0 6.625 5.375 12 12 12s12-5.375 12-12s-5.375-12-12-12zm-53.38 14.021c-28.36 0-51.354 22.994-51.354 51.355s22.994 51.344 51.354 51.344c28.361 0 51.347-22.983 51.347-51.344c0-28.36-22.988-51.355-51.349-51.355zm0 18.021c18.409 0 33.334 14.923 33.334 33.334c0 18.409-14.925 33.334-33.334 33.334s-33.333-14.925-33.333-33.334c0-18.411 14.923-33.334 33.333-33.334"
                    /><defs
                      ><radialGradient
                        id="skillIconsInstagram0"
                        cx="0"
                        cy="0"
                        r="1"
                        gradientTransform="matrix(0 -253.715 235.975 0 68 275.717)"
                        gradientUnits="userSpaceOnUse"
                        ><stop stop-color="#fd5" /><stop
                          offset=".1"
                          stop-color="#fd5"
                        /><stop offset=".5" stop-color="#ff543e" /><stop
                          offset="1"
                          stop-color="#c837ab"
                        /></radialGradient
                      ><radialGradient
                        id="skillIconsInstagram1"
                        cx="0"
                        cy="0"
                        r="1"
                        gradientTransform="matrix(22.25952 111.2061 -458.39518 91.75449 -42.881 18.441)"
                        gradientUnits="userSpaceOnUse"
                        ><stop stop-color="#3771c8" /><stop
                          offset=".128"
                          stop-color="#3771c8"
                        /><stop
                          offset="1"
                          stop-color="#60f"
                          stop-opacity="0"
                        /></radialGradient
                      ></defs
                    ></g
                  ></svg
                >
              </Button>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class="max-w-[5rem] lg:max-w-[12rem] h-auto rounded-xl">
      <img src="/sw2.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}">كوكيز</Dialog.Trigger
          >
          <Dialog.Content >
            <Dialog.Header class="">
              <Dialog.Title class="flex justify-center ">كوكيز</Dialog.Title>
            </Dialog.Header>
              <ScrollArea
              >
                <div class=" text-sm">
                  <section>
                    <h2 class="text-primary font-bold py-1">المكونات:</h2>
                    <ul>
                      <li>- 30 جرام زبدة فول سوداني</li>
                      <li>- صفار بيضة</li>
                      <li>- 3 أظرف سكر ستيفيا</li>
                      <li>- رشة فانيلا</li>
                      <li>- 2 جرام باكينج باودر</li>
                      <li>- رشة بيكربونات الصوديوم</li>
                      <li>- 40 جرام دقيق أو شوفان مطحون</li>
                      <li>- رشة ملح</li>
                      <li>- 15 جرام شوكولاتة</li>
                    </ul>
                  </section>
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold">الطريقة:</h2>
                    <ol class="">
                      <li>
                        1. ذوّب زبدة الفول السوداني في المايكروويف واتركها لتبرد
                        قليلاً.
                      </li>
                      <li>
                        2. أضف صفار البيضة وسكر ستيفيا إلى الزبدة وامزجهم جيداً.
                      </li>
                      <li>
                        3. أضف الدقيق (أو الشوفان المطحون)، البيكينج باودر،
                        البيكربونات، والملح وامزج حتى تتجانس المكونات.
                      </li>
                      <li>
                        4. إذا كان الخليط جافاً، أضف 10 مل من الماء تدريجياً حتى
                        يصبح الخليط قابلاً للتشكيل.
                      </li>
                      <li>
                        5. أضف الشوكولاتة المقطعة إلى الخليط واخلطها
                        جيداً.
                      </li>
                      <li>
                        6. قسم الخليط إلى 4 قطع وضعه في صينية مدهونة أو مبطنة
                        بورق زبدة.
                      </li>
                      <li>
                        7. اخبزه في فرن مسبق التسخين على حرارة 180 درجة مئوية
                        لمدة 7 دقائق من الأسفل ودقيقتين من الأعلى.
                      </li>
                    </ol>
                  </section>
                  <section class="py-3">
                    <h2 class="text-primary font-bold">السعرات الحرارية:</h2>
                    <p>-109 سعرة حرارية</p>
                  </section>
                </div>
              </ScrollArea>
            <div class="flex justify-end items-end text-xs">
              <Button
                variant="ghost"
                href="https://www.instagram.com/healthy_shody?igsh=NG5kY28yamt0amk3"
              >
                <p class="px-1">healthy_shody@</p>
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="1em"
                  height="1em"
                  viewBox="0 0 256 256"
                  ><g fill="none"
                    ><rect
                      width="256"
                      height="256"
                      fill="url(#skillIconsInstagram0)"
                      rx="60"
                    /><rect
                      width="256"
                      height="256"
                      fill="url(#skillIconsInstagram1)"
                      rx="60"
                    /><path
                      fill="#fff"
                      d="M128.009 28c-27.158 0-30.567.119-41.233.604c-10.646.488-17.913 2.173-24.271 4.646c-6.578 2.554-12.157 5.971-17.715 11.531c-5.563 5.559-8.98 11.138-11.542 17.713c-2.48 6.36-4.167 13.63-4.646 24.271c-.477 10.667-.602 14.077-.602 41.236s.12 30.557.604 41.223c.49 10.646 2.175 17.913 4.646 24.271c2.556 6.578 5.973 12.157 11.533 17.715c5.557 5.563 11.136 8.988 17.709 11.542c6.363 2.473 13.631 4.158 24.275 4.646c10.667.485 14.073.604 41.23.604c27.161 0 30.559-.119 41.225-.604c10.646-.488 17.921-2.173 24.284-4.646c6.575-2.554 12.146-5.979 17.702-11.542c5.563-5.558 8.979-11.137 11.542-17.712c2.458-6.361 4.146-13.63 4.646-24.272c.479-10.666.604-14.066.604-41.225s-.125-30.567-.604-41.234c-.5-10.646-2.188-17.912-4.646-24.27c-2.563-6.578-5.979-12.157-11.542-17.716c-5.562-5.562-11.125-8.979-17.708-11.53c-6.375-2.474-13.646-4.16-24.292-4.647c-10.667-.485-14.063-.604-41.23-.604zm-8.971 18.021c2.663-.004 5.634 0 8.971 0c26.701 0 29.865.096 40.409.575c9.75.446 15.042 2.075 18.567 3.444c4.667 1.812 7.994 3.979 11.492 7.48c3.5 3.5 5.666 6.833 7.483 11.5c1.369 3.52 3 8.812 3.444 18.562c.479 10.542.583 13.708.583 40.396s-.104 29.855-.583 40.396c-.446 9.75-2.075 15.042-3.444 18.563c-1.812 4.667-3.983 7.99-7.483 11.488c-3.5 3.5-6.823 5.666-11.492 7.479c-3.521 1.375-8.817 3-18.567 3.446c-10.542.479-13.708.583-40.409.583c-26.702 0-29.867-.104-40.408-.583c-9.75-.45-15.042-2.079-18.57-3.448c-4.666-1.813-8-3.979-11.5-7.479s-5.666-6.825-7.483-11.494c-1.369-3.521-3-8.813-3.444-18.563c-.479-10.542-.575-13.708-.575-40.413s.096-29.854.575-40.396c.446-9.75 2.075-15.042 3.444-18.567c1.813-4.667 3.983-8 7.484-11.5s6.833-5.667 11.5-7.483c3.525-1.375 8.819-3 18.569-3.448c9.225-.417 12.8-.542 31.437-.563zm62.351 16.604c-6.625 0-12 5.37-12 11.996c0 6.625 5.375 12 12 12s12-5.375 12-12s-5.375-12-12-12zm-53.38 14.021c-28.36 0-51.354 22.994-51.354 51.355s22.994 51.344 51.354 51.344c28.361 0 51.347-22.983 51.347-51.344c0-28.36-22.988-51.355-51.349-51.355zm0 18.021c18.409 0 33.334 14.923 33.334 33.334c0 18.409-14.925 33.334-33.334 33.334s-33.333-14.925-33.333-33.334c0-18.411 14.923-33.334 33.333-33.334"
                    /><defs
                      ><radialGradient
                        id="skillIconsInstagram0"
                        cx="0"
                        cy="0"
                        r="1"
                        gradientTransform="matrix(0 -253.715 235.975 0 68 275.717)"
                        gradientUnits="userSpaceOnUse"
                        ><stop stop-color="#fd5" /><stop
                          offset=".1"
                          stop-color="#fd5"
                        /><stop offset=".5" stop-color="#ff543e" /><stop
                          offset="1"
                          stop-color="#c837ab"
                        /></radialGradient
                      ><radialGradient
                        id="skillIconsInstagram1"
                        cx="0"
                        cy="0"
                        r="1"
                        gradientTransform="matrix(22.25952 111.2061 -458.39518 91.75449 -42.881 18.441)"
                        gradientUnits="userSpaceOnUse"
                        ><stop stop-color="#3771c8" /><stop
                          offset=".128"
                          stop-color="#3771c8"
                        /><stop
                          offset="1"
                          stop-color="#60f"
                          stop-opacity="0"
                        /></radialGradient
                      ></defs
                    ></g
                  ></svg
                >
              </Button>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class="max-w-[5rem] lg:max-w-[12rem] h-auto rounded-xl">
      <img src="/sw3.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}">فاكتوريا كيك</Dialog.Trigger
          >
          <Dialog.Content>
            <Dialog.Header class="">
              <Dialog.Title class="flex justify-center "
                >فاكتوريا كيك
              </Dialog.Title>
            </Dialog.Header>
              <ScrollArea
              >
                <div class=" text-sm">
                  <section>
                    <h2 class="text-primary font-bold py-1">المكونات:</h2>
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
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold">الطريقة:</h2>
                    <p class=" text-primary font-bold">1. تحضير الكيك:</p>
                    <ol class="">
                      <li>
                        - اخلط الشوفان المطحون، باكينج باودر، بروتين باودر (إذا
                        استخدمته)، وزبادي يوناني. أضف محلي فانيلا أو سكر دايت مع
                        فانيلا سائلة أو بودرة.
                      </li>
                      <li>- أضف ماء بكمية 60 مل.</li>
                      <li>
                        - صب الخليط في قالب واخبزه في فرن مسبق التسخين على درجة
                        حرارة 180 مئوية. ثم، ازل الكيك من الفرن
                        واتركه ليبرد في الفريزر لمدة 15 دقيقة.
                      </li>
                    </ol>
                  </section>
                  <section class="pt-2">
                    <h2 class=" text-primary font-bold">
                      2. تحضير الكريمة البيضاء:
                    </h2>
                    <p>- اخلط زبادي يوناني مع جبن فيلادلفيا لايت.</p>
                  </section>
                  <section class="pt-2">
                    <h2 class=" text-primary font-bold">
                      3. تحضير مربى التوت:
                    </h2>
                    <p>
                      - ضع مزيج التوت على النار مع سكر دايت وأضف قليل من الماء
                      لمنع احتراقه.
                    </p>
                    <p>
                      - أضف نشا مذوب في 20 مل من الماء، وخلط جيداً حتى يتماسك.
                    </p>
                  </section>
                  <section class="pt-2">
                    <h2 class="text-primary font-bold">4. التجميع:</h2>
                    <ul>
                      <li>
                        - بين كل طبقة من الكيك، ضع طبقة من الكريمة البيضاء ومربى
                        التوت.
                      </li>
                      <li>- زين الوجه بالفراولة، التوت، ونعناع إذا رغبت.</li>
                    </ul>
                  </section>
                  <section class="pt-3">
                    <h2 class="text-primary font-bold">السعرات الحرارية:</h2>
                    <p>-422 سعرة حرارية</p>
                  </section>
                </div>
              </ScrollArea>
            <div class="flex justify-end items-end text-xs">
              <Button
                variant="ghost"
                href="https://www.instagram.com/healthy_shody?igsh=NG5kY28yamt0amk3"
              >
                <p class="px-1">healthy_shody@</p>
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="1em"
                  height="1em"
                  viewBox="0 0 256 256"
                  ><g fill="none"
                    ><rect
                      width="256"
                      height="256"
                      fill="url(#skillIconsInstagram0)"
                      rx="60"
                    /><rect
                      width="256"
                      height="256"
                      fill="url(#skillIconsInstagram1)"
                      rx="60"
                    /><path
                      fill="#fff"
                      d="M128.009 28c-27.158 0-30.567.119-41.233.604c-10.646.488-17.913 2.173-24.271 4.646c-6.578 2.554-12.157 5.971-17.715 11.531c-5.563 5.559-8.98 11.138-11.542 17.713c-2.48 6.36-4.167 13.63-4.646 24.271c-.477 10.667-.602 14.077-.602 41.236s.12 30.557.604 41.223c.49 10.646 2.175 17.913 4.646 24.271c2.556 6.578 5.973 12.157 11.533 17.715c5.557 5.563 11.136 8.988 17.709 11.542c6.363 2.473 13.631 4.158 24.275 4.646c10.667.485 14.073.604 41.23.604c27.161 0 30.559-.119 41.225-.604c10.646-.488 17.921-2.173 24.284-4.646c6.575-2.554 12.146-5.979 17.702-11.542c5.563-5.558 8.979-11.137 11.542-17.712c2.458-6.361 4.146-13.63 4.646-24.272c.479-10.666.604-14.066.604-41.225s-.125-30.567-.604-41.234c-.5-10.646-2.188-17.912-4.646-24.27c-2.563-6.578-5.979-12.157-11.542-17.716c-5.562-5.562-11.125-8.979-17.708-11.53c-6.375-2.474-13.646-4.16-24.292-4.647c-10.667-.485-14.063-.604-41.23-.604zm-8.971 18.021c2.663-.004 5.634 0 8.971 0c26.701 0 29.865.096 40.409.575c9.75.446 15.042 2.075 18.567 3.444c4.667 1.812 7.994 3.979 11.492 7.48c3.5 3.5 5.666 6.833 7.483 11.5c1.369 3.52 3 8.812 3.444 18.562c.479 10.542.583 13.708.583 40.396s-.104 29.855-.583 40.396c-.446 9.75-2.075 15.042-3.444 18.563c-1.812 4.667-3.983 7.99-7.483 11.488c-3.5 3.5-6.823 5.666-11.492 7.479c-3.521 1.375-8.817 3-18.567 3.446c-10.542.479-13.708.583-40.409.583c-26.702 0-29.867-.104-40.408-.583c-9.75-.45-15.042-2.079-18.57-3.448c-4.666-1.813-8-3.979-11.5-7.479s-5.666-6.825-7.483-11.494c-1.369-3.521-3-8.813-3.444-18.563c-.479-10.542-.575-13.708-.575-40.413s.096-29.854.575-40.396c.446-9.75 2.075-15.042 3.444-18.567c1.813-4.667 3.983-8 7.484-11.5s6.833-5.667 11.5-7.483c3.525-1.375 8.819-3 18.569-3.448c9.225-.417 12.8-.542 31.437-.563zm62.351 16.604c-6.625 0-12 5.37-12 11.996c0 6.625 5.375 12 12 12s12-5.375 12-12s-5.375-12-12-12zm-53.38 14.021c-28.36 0-51.354 22.994-51.354 51.355s22.994 51.344 51.354 51.344c28.361 0 51.347-22.983 51.347-51.344c0-28.36-22.988-51.355-51.349-51.355zm0 18.021c18.409 0 33.334 14.923 33.334 33.334c0 18.409-14.925 33.334-33.334 33.334s-33.333-14.925-33.333-33.334c0-18.411 14.923-33.334 33.333-33.334"
                    /><defs
                      ><radialGradient
                        id="skillIconsInstagram0"
                        cx="0"
                        cy="0"
                        r="1"
                        gradientTransform="matrix(0 -253.715 235.975 0 68 275.717)"
                        gradientUnits="userSpaceOnUse"
                        ><stop stop-color="#fd5" /><stop
                          offset=".1"
                          stop-color="#fd5"
                        /><stop offset=".5" stop-color="#ff543e" /><stop
                          offset="1"
                          stop-color="#c837ab"
                        /></radialGradient
                      ><radialGradient
                        id="skillIconsInstagram1"
                        cx="0"
                        cy="0"
                        r="1"
                        gradientTransform="matrix(22.25952 111.2061 -458.39518 91.75449 -42.881 18.441)"
                        gradientUnits="userSpaceOnUse"
                        ><stop stop-color="#3771c8" /><stop
                          offset=".128"
                          stop-color="#3771c8"
                        /><stop
                          offset="1"
                          stop-color="#60f"
                          stop-opacity="0"
                        /></radialGradient
                      ></defs
                    ></g
                  ></svg
                >
              </Button>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class="max-w-[5rem] lg:max-w-[12rem] h-auto rounded-xl">
      <img src="/sw4.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}">تشيز كيك الفراولة</Dialog.Trigger
          >
          <Dialog.Content >
            <Dialog.Header class="">
              <Dialog.Title class="flex justify-center"
                >تشيز كيك فراولة
              </Dialog.Title>
            </Dialog.Header>
              <ScrollArea
              >
                <div class=" text-sm">
                  <section>
                    <h2 class="text-primary font-bold py-1">المكونات:</h2>
                    <ul>
                      <li>- 50 جرام من بسكويت سانتفيري خالي من السكر</li>
                      <li>- 25 جرام من جبنة فيلادلفيا لايت</li>
                      <li>- 80 جرام من الزبادي اليوناني خالي الدسم</li>
                      <li>- 4 جرام من النشا</li>
                      <li>- 45 جرام من البيض </li>
                      <li>- 100 جرام من الفراولة</li>
                    </ul>
                  </section>
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold">الطريقة:</h2>
                    <p class=" text-primary font-bold">
                      1. تحضير الطبقة الأولى:
                    </p>
                    <ol>
                      <li>- اطحن البسكويت وأضف إليه 7 مل من الماء.</li>
                      <li>
                        - ضع 8 جرامات من خليط البسكويت في قوالب الكب كيك واضغط
                        عليه باستخدام كوب أو ملعقة صغيرة.
                      </li>
                    </ol>
                  </section>
                  <section class="pt-2">
                    <h2 class=" text-primary font-bold">
                      2. تحضير الطبقة الثانية:
                    </h2>
                    <p>
                      - اخلط جبنة فيلادلفيا، الزبادي، 2 جرام من النشا، البيضة،
                      ومحلي خالٍ من السعرات أو ستيفيا.
                    </p>
                    <p>- ضع 24 جرامًا من هذا الخليط فوق طبقة البسكويت.</p>
                    <h2 class=" text-primary font-bold pt-2">3. الخبز:</h2>
                    <p>- سخن الفرن على درجة حرارة 170 درجة مئوية.</p>
                    <p>
                      - اخبز القوالب لمدة 10 دقائق من كل جهة. إذا كنت بحاجة إلى
                      وقت أكثر أو أقل، راقب القوالب واضغط عليها بطرف الملعقة.
                      إذا لم تلتصق، فهي جاهزة.
                    </p>
                  </section>
                  
                  <section>
                    <h2 class="text-primary font-bold pt-2">4. التبريد:</h2>
                    <ul>
                      <li>
                        - ضع القوالب في الفريزر لمدة ساعة ثم أخرجها من القوالب.
                      </li>
                    </ul>
                  </section>
                  <section class="pt-2">
                    <h2 class="text-primary font-bold">
                      5. تحضير الطبقة الأخيرة (صلصة الفراولة):
                    </h2>
                    <ul>
                      <li>
                        - اعصر الفراولة في الخلاط، ثم أضف 2 جرام من النشا، 6 مل
                        من الماء، ونقطتين من المحلي (يمكن استعمال العسل واضافة
                        سعراته للمجموع).
                      </li>
                      <li>
                        - ضع الخليط على النار و استمر بالتقليب حتى تذبل الفراولة
                        وتصبح لديك الصلصة جاهزة
                      </li>
                      <li>- زين الطبقة الأخيرة حسب رغبتك.</li>
                    </ul>
                  </section>
                  <section class="pt-3">
                    <h2 class="text-primary font-bold">السعرات الحرارية:</h2>
                    <p>الحبة 65 سعرة</p>
                  </section>
                </div>
              </ScrollArea>
            <div class="flex justify-end items-end text-xs">
              <Button
                variant="ghost"
                href="https://www.instagram.com/healthy_shody?igsh=NG5kY28yamt0amk3"
              >
                <p class="px-1">healthy_shody@</p>
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="1em"
                  height="1em"
                  viewBox="0 0 256 256"
                  ><g fill="none"
                    ><rect
                      width="256"
                      height="256"
                      fill="url(#skillIconsInstagram0)"
                      rx="60"
                    /><rect
                      width="256"
                      height="256"
                      fill="url(#skillIconsInstagram1)"
                      rx="60"
                    /><path
                      fill="#fff"
                      d="M128.009 28c-27.158 0-30.567.119-41.233.604c-10.646.488-17.913 2.173-24.271 4.646c-6.578 2.554-12.157 5.971-17.715 11.531c-5.563 5.559-8.98 11.138-11.542 17.713c-2.48 6.36-4.167 13.63-4.646 24.271c-.477 10.667-.602 14.077-.602 41.236s.12 30.557.604 41.223c.49 10.646 2.175 17.913 4.646 24.271c2.556 6.578 5.973 12.157 11.533 17.715c5.557 5.563 11.136 8.988 17.709 11.542c6.363 2.473 13.631 4.158 24.275 4.646c10.667.485 14.073.604 41.23.604c27.161 0 30.559-.119 41.225-.604c10.646-.488 17.921-2.173 24.284-4.646c6.575-2.554 12.146-5.979 17.702-11.542c5.563-5.558 8.979-11.137 11.542-17.712c2.458-6.361 4.146-13.63 4.646-24.272c.479-10.666.604-14.066.604-41.225s-.125-30.567-.604-41.234c-.5-10.646-2.188-17.912-4.646-24.27c-2.563-6.578-5.979-12.157-11.542-17.716c-5.562-5.562-11.125-8.979-17.708-11.53c-6.375-2.474-13.646-4.16-24.292-4.647c-10.667-.485-14.063-.604-41.23-.604zm-8.971 18.021c2.663-.004 5.634 0 8.971 0c26.701 0 29.865.096 40.409.575c9.75.446 15.042 2.075 18.567 3.444c4.667 1.812 7.994 3.979 11.492 7.48c3.5 3.5 5.666 6.833 7.483 11.5c1.369 3.52 3 8.812 3.444 18.562c.479 10.542.583 13.708.583 40.396s-.104 29.855-.583 40.396c-.446 9.75-2.075 15.042-3.444 18.563c-1.812 4.667-3.983 7.99-7.483 11.488c-3.5 3.5-6.823 5.666-11.492 7.479c-3.521 1.375-8.817 3-18.567 3.446c-10.542.479-13.708.583-40.409.583c-26.702 0-29.867-.104-40.408-.583c-9.75-.45-15.042-2.079-18.57-3.448c-4.666-1.813-8-3.979-11.5-7.479s-5.666-6.825-7.483-11.494c-1.369-3.521-3-8.813-3.444-18.563c-.479-10.542-.575-13.708-.575-40.413s.096-29.854.575-40.396c.446-9.75 2.075-15.042 3.444-18.567c1.813-4.667 3.983-8 7.484-11.5s6.833-5.667 11.5-7.483c3.525-1.375 8.819-3 18.569-3.448c9.225-.417 12.8-.542 31.437-.563zm62.351 16.604c-6.625 0-12 5.37-12 11.996c0 6.625 5.375 12 12 12s12-5.375 12-12s-5.375-12-12-12zm-53.38 14.021c-28.36 0-51.354 22.994-51.354 51.355s22.994 51.344 51.354 51.344c28.361 0 51.347-22.983 51.347-51.344c0-28.36-22.988-51.355-51.349-51.355zm0 18.021c18.409 0 33.334 14.923 33.334 33.334c0 18.409-14.925 33.334-33.334 33.334s-33.333-14.925-33.333-33.334c0-18.411 14.923-33.334 33.333-33.334"
                    /><defs
                      ><radialGradient
                        id="skillIconsInstagram0"
                        cx="0"
                        cy="0"
                        r="1"
                        gradientTransform="matrix(0 -253.715 235.975 0 68 275.717)"
                        gradientUnits="userSpaceOnUse"
                        ><stop stop-color="#fd5" /><stop
                          offset=".1"
                          stop-color="#fd5"
                        /><stop offset=".5" stop-color="#ff543e" /><stop
                          offset="1"
                          stop-color="#c837ab"
                        /></radialGradient
                      ><radialGradient
                        id="skillIconsInstagram1"
                        cx="0"
                        cy="0"
                        r="1"
                        gradientTransform="matrix(22.25952 111.2061 -458.39518 91.75449 -42.881 18.441)"
                        gradientUnits="userSpaceOnUse"
                        ><stop stop-color="#3771c8" /><stop
                          offset=".128"
                          stop-color="#3771c8"
                        /><stop
                          offset="1"
                          stop-color="#60f"
                          stop-opacity="0"
                        /></radialGradient
                      ></defs
                    ></g
                  ></svg
                >
              </Button>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class="max-w-[5rem] lg:max-w-[12rem] h-auto rounded-xl">
      <img src="/sw5.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}">حلى الاوريو</Dialog.Trigger
          >
          <Dialog.Content
          >
            <Dialog.Header class="">
              <Dialog.Title class="flex justify-center"
                >حلى الاوريو
              </Dialog.Title>
            </Dialog.Header>
            <!-- svelte-ignore missing-declaration -->
            <ScrollArea
            >
              <div class="text-sm">
                <section>
                  <h2 class="text-primary font-bold py-1">المكونات:</h2>
                  <ul>
                    <li>
                      - حبتان أوريو (واحدة بكريمة وواحدة بدون)، تساوي 16 جرام
                      (أربعة حبات).
                    </li>
                    <li>- حليب قليل الدسم: ملعقة ونصف كبيرة، 15 مل.</li>
                    <li>- كريم كراميل باودر: ملعقة ونصف، 15 جرام.</li>
                    <li>- ظرف سكر ستيفيا.</li>
                    <li>- جبن فيلادلفيا لايت: ملعقتين كبيرتين، 55 جرام.</li>
                    <li>- بسكويت ماري: حبة واحدة، 5 جرام.</li>
                    <li>- قطعة شوكولاتة بالحليب: 10 جرام.</li>
                  </ul>
                </section>
                <section class="pt-3">
                  <h2 class=" text-primary font-bold">الطريقة:</h2>
                  <ol class="">
                    <li>1. الطبقة الأولى, ضع حبتان أوريو في وعاء، ثم اغمسها في 10 مل حليب .</li>
                    <li>
                      2.  الطبقة الثانية، اخلط 40 جرام من فيلادلفيا مع
                      ملعقة ونصف من كريم كراميل باودر، سكر ستيفيا، و5 مل حليب.
                      أضف نقطة ماء إذا لزم الأمر، وامزج حتى يتجانس.
                    </li>
                    <li>3. الطبقة الثالثة, اغمس بسكويت ماري في الكمية المتبقية من الحليب.</li>
                    <li>
                      4. الطبقة الرابعة, ذوب قطعة الشوكولاتة بالحليب في حمام مائي، ثم أضف إليها
                      15 جرام من فيلادلفيا لايت.
                    </li>
                    <li>
                      5. ضع الحبة الأخيرة من الأوريو في الأعلى،   
                       .
                    </li>
                  </ol>
                </section>
                <section class="pt-3">
                  <h2 class="text-primary font-bold py-1">السعرات الحرارية:</h2>
                  <p>-249 سعرة حرارية</p>
                </section>
              </div>
            </ScrollArea>
            <div class="flex justify-end items-end text-xs">
              <Button
                variant="ghost"
                href="https://www.instagram.com/healthy_shody?igsh=NG5kY28yamt0amk3"
              >
                <p class="px-1">healthy_shody@</p>
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="1em"
                  height="1em"
                  viewBox="0 0 256 256"
                  ><g fill="none"
                    ><rect
                      width="256"
                      height="256"
                      fill="url(#skillIconsInstagram0)"
                      rx="60"
                    /><rect
                      width="256"
                      height="256"
                      fill="url(#skillIconsInstagram1)"
                      rx="60"
                    /><path
                      fill="#fff"
                      d="M128.009 28c-27.158 0-30.567.119-41.233.604c-10.646.488-17.913 2.173-24.271 4.646c-6.578 2.554-12.157 5.971-17.715 11.531c-5.563 5.559-8.98 11.138-11.542 17.713c-2.48 6.36-4.167 13.63-4.646 24.271c-.477 10.667-.602 14.077-.602 41.236s.12 30.557.604 41.223c.49 10.646 2.175 17.913 4.646 24.271c2.556 6.578 5.973 12.157 11.533 17.715c5.557 5.563 11.136 8.988 17.709 11.542c6.363 2.473 13.631 4.158 24.275 4.646c10.667.485 14.073.604 41.23.604c27.161 0 30.559-.119 41.225-.604c10.646-.488 17.921-2.173 24.284-4.646c6.575-2.554 12.146-5.979 17.702-11.542c5.563-5.558 8.979-11.137 11.542-17.712c2.458-6.361 4.146-13.63 4.646-24.272c.479-10.666.604-14.066.604-41.225s-.125-30.567-.604-41.234c-.5-10.646-2.188-17.912-4.646-24.27c-2.563-6.578-5.979-12.157-11.542-17.716c-5.562-5.562-11.125-8.979-17.708-11.53c-6.375-2.474-13.646-4.16-24.292-4.647c-10.667-.485-14.063-.604-41.23-.604zm-8.971 18.021c2.663-.004 5.634 0 8.971 0c26.701 0 29.865.096 40.409.575c9.75.446 15.042 2.075 18.567 3.444c4.667 1.812 7.994 3.979 11.492 7.48c3.5 3.5 5.666 6.833 7.483 11.5c1.369 3.52 3 8.812 3.444 18.562c.479 10.542.583 13.708.583 40.396s-.104 29.855-.583 40.396c-.446 9.75-2.075 15.042-3.444 18.563c-1.812 4.667-3.983 7.99-7.483 11.488c-3.5 3.5-6.823 5.666-11.492 7.479c-3.521 1.375-8.817 3-18.567 3.446c-10.542.479-13.708.583-40.409.583c-26.702 0-29.867-.104-40.408-.583c-9.75-.45-15.042-2.079-18.57-3.448c-4.666-1.813-8-3.979-11.5-7.479s-5.666-6.825-7.483-11.494c-1.369-3.521-3-8.813-3.444-18.563c-.479-10.542-.575-13.708-.575-40.413s.096-29.854.575-40.396c.446-9.75 2.075-15.042 3.444-18.567c1.813-4.667 3.983-8 7.484-11.5s6.833-5.667 11.5-7.483c3.525-1.375 8.819-3 18.569-3.448c9.225-.417 12.8-.542 31.437-.563zm62.351 16.604c-6.625 0-12 5.37-12 11.996c0 6.625 5.375 12 12 12s12-5.375 12-12s-5.375-12-12-12zm-53.38 14.021c-28.36 0-51.354 22.994-51.354 51.355s22.994 51.344 51.354 51.344c28.361 0 51.347-22.983 51.347-51.344c0-28.36-22.988-51.355-51.349-51.355zm0 18.021c18.409 0 33.334 14.923 33.334 33.334c0 18.409-14.925 33.334-33.334 33.334s-33.333-14.925-33.333-33.334c0-18.411 14.923-33.334 33.333-33.334"
                    /><defs
                      ><radialGradient
                        id="skillIconsInstagram0"
                        cx="0"
                        cy="0"
                        r="1"
                        gradientTransform="matrix(0 -253.715 235.975 0 68 275.717)"
                        gradientUnits="userSpaceOnUse"
                        ><stop stop-color="#fd5" /><stop
                          offset=".1"
                          stop-color="#fd5"
                        /><stop offset=".5" stop-color="#ff543e" /><stop
                          offset="1"
                          stop-color="#c837ab"
                        /></radialGradient
                      ><radialGradient
                        id="skillIconsInstagram1"
                        cx="0"
                        cy="0"
                        r="1"
                        gradientTransform="matrix(22.25952 111.2061 -458.39518 91.75449 -42.881 18.441)"
                        gradientUnits="userSpaceOnUse"
                        ><stop stop-color="#3771c8" /><stop
                          offset=".128"
                          stop-color="#3771c8"
                        /><stop
                          offset="1"
                          stop-color="#60f"
                          stop-opacity="0"
                        /></radialGradient
                      ></defs
                    ></g
                  ></svg
                >
              </Button>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class="max-w-[5rem] lg:max-w-[12rem] h-auto rounded-xl">
      <img src="/sw6.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}">حلى الآيسكريم</Dialog.Trigger
          >
          <Dialog.Content
          >
            <Dialog.Header class="">
              <Dialog.Title class="flex justify-center "
                >حلى الآيسكريم
              </Dialog.Title>
            </Dialog.Header>
            <div class="  text-sm">
              <section>
                <h2 class="text-primary font-bold py-1">المكونات:</h2>
                <ul>
                  <li>- قطعتان من كعك الأرز، 14 جرام.</li>
                  <li>- نصف قطعة شوكولاتة داكنة, 5 جرام.</li>
                  <li>- قطعة كاملة شوكولاتة بالحليب، 10 جرام.</li>
                  <li>- ملعقة كبيرة من آيس كريم فانيلا لايت، 35 جرام.</li>
                  <li>- للتزيين: توت أحمر مجمد، 2 جرام.</li>
                </ul>
              </section>
              <section class="pt-3">
                <h2 class=" text-primary font-bold">الطريقة:</h2>
                <ol class="">
                  <li>
                    1. ذوّب الشوكولاتة الداكنة وشوكولاتة الحليب في حمام مائي.
                  </li>
                  <li>
                    2. ضع ملعقة كبيرة من الآيس كريم على إحدى قطع كعك الأرز.
                  </li>
                  <li></li>
                  <li>3. غطِّها بقطعة أخرى من كعك الأرز.</li>
                  <li>
                    4. صب الشوكولاتة المذابة فوق الكعك وزينه بالتوت الأحمر.
                  </li>
                  <li>5. اتركه في الفريزر ليجمد لمدة 10 دقائق على الأقل.</li>
                </ol>
              </section>
              <section class="pt-3">
                <h2 class="text-primary font-bold">السعرات الحرارية:</h2>
                <p>-158 سعرة حرارية</p>
              </section>
            </div>
            <div class="flex justify-end items-end text-xs">
              <Button
                variant="ghost"
                href="https://www.instagram.com/healthy_shody?igsh=NG5kY28yamt0amk3"
              >
                <p class="px-1">healthy_shody@</p>
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="1em"
                  height="1em"
                  viewBox="0 0 256 256"
                  ><g fill="none"
                    ><rect
                      width="256"
                      height="256"
                      fill="url(#skillIconsInstagram0)"
                      rx="60"
                    /><rect
                      width="256"
                      height="256"
                      fill="url(#skillIconsInstagram1)"
                      rx="60"
                    /><path
                      fill="#fff"
                      d="M128.009 28c-27.158 0-30.567.119-41.233.604c-10.646.488-17.913 2.173-24.271 4.646c-6.578 2.554-12.157 5.971-17.715 11.531c-5.563 5.559-8.98 11.138-11.542 17.713c-2.48 6.36-4.167 13.63-4.646 24.271c-.477 10.667-.602 14.077-.602 41.236s.12 30.557.604 41.223c.49 10.646 2.175 17.913 4.646 24.271c2.556 6.578 5.973 12.157 11.533 17.715c5.557 5.563 11.136 8.988 17.709 11.542c6.363 2.473 13.631 4.158 24.275 4.646c10.667.485 14.073.604 41.23.604c27.161 0 30.559-.119 41.225-.604c10.646-.488 17.921-2.173 24.284-4.646c6.575-2.554 12.146-5.979 17.702-11.542c5.563-5.558 8.979-11.137 11.542-17.712c2.458-6.361 4.146-13.63 4.646-24.272c.479-10.666.604-14.066.604-41.225s-.125-30.567-.604-41.234c-.5-10.646-2.188-17.912-4.646-24.27c-2.563-6.578-5.979-12.157-11.542-17.716c-5.562-5.562-11.125-8.979-17.708-11.53c-6.375-2.474-13.646-4.16-24.292-4.647c-10.667-.485-14.063-.604-41.23-.604zm-8.971 18.021c2.663-.004 5.634 0 8.971 0c26.701 0 29.865.096 40.409.575c9.75.446 15.042 2.075 18.567 3.444c4.667 1.812 7.994 3.979 11.492 7.48c3.5 3.5 5.666 6.833 7.483 11.5c1.369 3.52 3 8.812 3.444 18.562c.479 10.542.583 13.708.583 40.396s-.104 29.855-.583 40.396c-.446 9.75-2.075 15.042-3.444 18.563c-1.812 4.667-3.983 7.99-7.483 11.488c-3.5 3.5-6.823 5.666-11.492 7.479c-3.521 1.375-8.817 3-18.567 3.446c-10.542.479-13.708.583-40.409.583c-26.702 0-29.867-.104-40.408-.583c-9.75-.45-15.042-2.079-18.57-3.448c-4.666-1.813-8-3.979-11.5-7.479s-5.666-6.825-7.483-11.494c-1.369-3.521-3-8.813-3.444-18.563c-.479-10.542-.575-13.708-.575-40.413s.096-29.854.575-40.396c.446-9.75 2.075-15.042 3.444-18.567c1.813-4.667 3.983-8 7.484-11.5s6.833-5.667 11.5-7.483c3.525-1.375 8.819-3 18.569-3.448c9.225-.417 12.8-.542 31.437-.563zm62.351 16.604c-6.625 0-12 5.37-12 11.996c0 6.625 5.375 12 12 12s12-5.375 12-12s-5.375-12-12-12zm-53.38 14.021c-28.36 0-51.354 22.994-51.354 51.355s22.994 51.344 51.354 51.344c28.361 0 51.347-22.983 51.347-51.344c0-28.36-22.988-51.355-51.349-51.355zm0 18.021c18.409 0 33.334 14.923 33.334 33.334c0 18.409-14.925 33.334-33.334 33.334s-33.333-14.925-33.333-33.334c0-18.411 14.923-33.334 33.333-33.334"
                    /><defs
                      ><radialGradient
                        id="skillIconsInstagram0"
                        cx="0"
                        cy="0"
                        r="1"
                        gradientTransform="matrix(0 -253.715 235.975 0 68 275.717)"
                        gradientUnits="userSpaceOnUse"
                        ><stop stop-color="#fd5" /><stop
                          offset=".1"
                          stop-color="#fd5"
                        /><stop offset=".5" stop-color="#ff543e" /><stop
                          offset="1"
                          stop-color="#c837ab"
                        /></radialGradient
                      ><radialGradient
                        id="skillIconsInstagram1"
                        cx="0"
                        cy="0"
                        r="1"
                        gradientTransform="matrix(22.25952 111.2061 -458.39518 91.75449 -42.881 18.441)"
                        gradientUnits="userSpaceOnUse"
                        ><stop stop-color="#3771c8" /><stop
                          offset=".128"
                          stop-color="#3771c8"
                        /><stop
                          offset="1"
                          stop-color="#60f"
                          stop-opacity="0"
                        /></radialGradient
                      ></defs
                    ></g
                  ></svg
                >
              </Button>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class="max-w-[5rem] lg:max-w-[12rem] h-auto rounded-xl">
      <img src="/sw7.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}">مافن</Dialog.Trigger
          >
          <Dialog.Content
          >
            <Dialog.Header class="">
              <Dialog.Title class="flex justify-center ">مافن</Dialog.Title>
            </Dialog.Header>
              <ScrollArea
              >
                <div class="text-sm">
                  <section>
                    <h2 class="text-primary font-bold py-1">المكونات:</h2>
                    <ul>
                      <li>- شوفان مطحون أو دقيق: 50 جرام</li>
                      <li>- بروتين باودر: 32 جرام</li>
                      <li>- بايكنج باودر: 6 جرام</li>
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
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold">الطريقة:</h2>
                    <ol class="">
                      <li>
                        1. اخلط جميع المكونات في الخلاط الكهربائي ما عدا الفواكه
                      </li>
                      <li>
                        2. أضف ظرفين من سكر ستيفيا وامزج حتى يتجانس الخليط.
                      </li>
                      <li>
                        3. صب الخليط في قوالب المافن وزينه بقطع التفاح والتوت.
                      </li>
                      <li>
                        4. اخبزه في فرن مسبق التسخين على درجة حرارة 200 مئوية
                        لمدة 10 دقائق من الأسفل ثم 5 دقائق من الأعلى حتى ينضج.
                      </li>
                      <li>
                        5. بعد أن يبرد، حضر صوص الفول السوداني بخلط بودرة الفول
                        السوداني مع ضعف الكمية ماء وسكر ستيفيا، ثم زين المافن
                        بالصوص.
                      </li>
                    </ol>
                  </section>
                  <section class="pt-3">
                    <h2 class="text-primary font-bold">السعرات الحرارية:</h2>
                    <p>-499 سعرة حرارية</p>
                  </section>
                </div>
              </ScrollArea>
            <div class="flex justify-end items-end text-xs">
              <Button
                variant="ghost"
                href="https://www.instagram.com/healthy_shody?igsh=NG5kY28yamt0amk3"
              >
                <p class="px-1">healthy_shody@</p>
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="1em"
                  height="1em"
                  viewBox="0 0 256 256"
                  ><g fill="none"
                    ><rect
                      width="256"
                      height="256"
                      fill="url(#skillIconsInstagram0)"
                      rx="60"
                    /><rect
                      width="256"
                      height="256"
                      fill="url(#skillIconsInstagram1)"
                      rx="60"
                    /><path
                      fill="#fff"
                      d="M128.009 28c-27.158 0-30.567.119-41.233.604c-10.646.488-17.913 2.173-24.271 4.646c-6.578 2.554-12.157 5.971-17.715 11.531c-5.563 5.559-8.98 11.138-11.542 17.713c-2.48 6.36-4.167 13.63-4.646 24.271c-.477 10.667-.602 14.077-.602 41.236s.12 30.557.604 41.223c.49 10.646 2.175 17.913 4.646 24.271c2.556 6.578 5.973 12.157 11.533 17.715c5.557 5.563 11.136 8.988 17.709 11.542c6.363 2.473 13.631 4.158 24.275 4.646c10.667.485 14.073.604 41.23.604c27.161 0 30.559-.119 41.225-.604c10.646-.488 17.921-2.173 24.284-4.646c6.575-2.554 12.146-5.979 17.702-11.542c5.563-5.558 8.979-11.137 11.542-17.712c2.458-6.361 4.146-13.63 4.646-24.272c.479-10.666.604-14.066.604-41.225s-.125-30.567-.604-41.234c-.5-10.646-2.188-17.912-4.646-24.27c-2.563-6.578-5.979-12.157-11.542-17.716c-5.562-5.562-11.125-8.979-17.708-11.53c-6.375-2.474-13.646-4.16-24.292-4.647c-10.667-.485-14.063-.604-41.23-.604zm-8.971 18.021c2.663-.004 5.634 0 8.971 0c26.701 0 29.865.096 40.409.575c9.75.446 15.042 2.075 18.567 3.444c4.667 1.812 7.994 3.979 11.492 7.48c3.5 3.5 5.666 6.833 7.483 11.5c1.369 3.52 3 8.812 3.444 18.562c.479 10.542.583 13.708.583 40.396s-.104 29.855-.583 40.396c-.446 9.75-2.075 15.042-3.444 18.563c-1.812 4.667-3.983 7.99-7.483 11.488c-3.5 3.5-6.823 5.666-11.492 7.479c-3.521 1.375-8.817 3-18.567 3.446c-10.542.479-13.708.583-40.409.583c-26.702 0-29.867-.104-40.408-.583c-9.75-.45-15.042-2.079-18.57-3.448c-4.666-1.813-8-3.979-11.5-7.479s-5.666-6.825-7.483-11.494c-1.369-3.521-3-8.813-3.444-18.563c-.479-10.542-.575-13.708-.575-40.413s.096-29.854.575-40.396c.446-9.75 2.075-15.042 3.444-18.567c1.813-4.667 3.983-8 7.484-11.5s6.833-5.667 11.5-7.483c3.525-1.375 8.819-3 18.569-3.448c9.225-.417 12.8-.542 31.437-.563zm62.351 16.604c-6.625 0-12 5.37-12 11.996c0 6.625 5.375 12 12 12s12-5.375 12-12s-5.375-12-12-12zm-53.38 14.021c-28.36 0-51.354 22.994-51.354 51.355s22.994 51.344 51.354 51.344c28.361 0 51.347-22.983 51.347-51.344c0-28.36-22.988-51.355-51.349-51.355zm0 18.021c18.409 0 33.334 14.923 33.334 33.334c0 18.409-14.925 33.334-33.334 33.334s-33.333-14.925-33.333-33.334c0-18.411 14.923-33.334 33.333-33.334"
                    /><defs
                      ><radialGradient
                        id="skillIconsInstagram0"
                        cx="0"
                        cy="0"
                        r="1"
                        gradientTransform="matrix(0 -253.715 235.975 0 68 275.717)"
                        gradientUnits="userSpaceOnUse"
                        ><stop stop-color="#fd5" /><stop
                          offset=".1"
                          stop-color="#fd5"
                        /><stop offset=".5" stop-color="#ff543e" /><stop
                          offset="1"
                          stop-color="#c837ab"
                        /></radialGradient
                      ><radialGradient
                        id="skillIconsInstagram1"
                        cx="0"
                        cy="0"
                        r="1"
                        gradientTransform="matrix(22.25952 111.2061 -458.39518 91.75449 -42.881 18.441)"
                        gradientUnits="userSpaceOnUse"
                        ><stop stop-color="#3771c8" /><stop
                          offset=".128"
                          stop-color="#3771c8"
                        /><stop
                          offset="1"
                          stop-color="#60f"
                          stop-opacity="0"
                        /></radialGradient
                      ></defs
                    ></g
                  ></svg
                >
              </Button>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>

    <div class="max-w-[5rem] lg:max-w-[12rem] h-auto rounded-xl">
      <img src="/sw9.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}">حلى منعش</Dialog.Trigger
          >
          <Dialog.Content >
            <Dialog.Header class="">
              <Dialog.Title class="flex justify-center ">حلى منعش</Dialog.Title>
            </Dialog.Header>
              <ScrollArea
              >
                <div class=" text-sm">
                  <section>
                    <h2 class="text-primary font-bold py-1">المكونات:</h2>
                    <ul>
                      <li>- 5 حبات توست أبيض (مقطع الحواف).</li>
                      <li>- 50 جم حليب قليل الدسم (لتغميس التوست).</li>
                    </ul>
                  </section>
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold">للكريمة:</h2>
                    <ol>
                      <li>- 24 جم دريم ويب.</li>
                      <li>- ملعقة صغيرة فانيلا.</li>
                      <li>- ظرفين سكر ستيفيا.</li>
                      <li>- 80 جم ماء بارد.</li>
                      <li>- علبتين زبادي بالفراولة (اكتيفيا).</li>
                    </ol>
                  </section>
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold">للجلي:</h2>
                    <p>- 23 جم جيلي.</p>
                    <p>-115 جرام ماء.</p>
                  </section>

                  <section>
                    <h2 class="text-primary font-bold pt-3">الطريقة:</h2>
                    <ul>
                      <li>
                        1. في وعاء، اخفق الدريم ويب مع الماء البارد حتى يتكون
                        قوام شبه كريمي (5-7 دقائق تقريباً).
                      </li>
                      <li>
                        2. أضف الفانيلا، الزبادي، وسكر ستيفيا، ثم استمر في الخفق
                        حتى تمتزج المكونات جيداً.
                      </li>
                      <li>
                        3. في صحن تقديم، رص التوست واغمره في الحليب. ضع طبقة من
                        الكريمة فوق التوست. كرر الطبقات حتى ينفد التوست.
                      </li>
                      <li>
                        4. لتحضير الجلي، اخلط الجيلي مع الماء المغلي حتى يذوب.
                        اتركه ليبرد قليلاً ثم اسكبه فوق آخر طبقة من الكريمة.
                      </li>
                      <li>
                        5. اتركه في الثلاجة حتى يتماسك الجلي، ثم زينه بالفراولة.
                      </li>
                    </ul>
                  </section>

                  <section class="pt-3">
                    <h2 class="text-primary font-bold">السعرات الحرارية:</h2>
                    <p>- لكل الكمية: 794 سعرة حرارية.</p>
                    <p>- لكل قطعة (من أصل 6 قطع): 133 سعرة حرارية.</p>
                  </section>
                </div>
              </ScrollArea>
            <div class="flex justify-end items-end text-xs">
              <Button
                variant="ghost"
                href="https://www.instagram.com/nada_helthy?igsh=b3RzM2V4dzY3NmFx"
              >
                <p class="px-1">nada_helthy@</p>
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="1em"
                  height="1em"
                  viewBox="0 0 256 256"
                  ><g fill="none"
                    ><rect
                      width="256"
                      height="256"
                      fill="url(#skillIconsInstagram0)"
                      rx="60"
                    /><rect
                      width="256"
                      height="256"
                      fill="url(#skillIconsInstagram1)"
                      rx="60"
                    /><path
                      fill="#fff"
                      d="M128.009 28c-27.158 0-30.567.119-41.233.604c-10.646.488-17.913 2.173-24.271 4.646c-6.578 2.554-12.157 5.971-17.715 11.531c-5.563 5.559-8.98 11.138-11.542 17.713c-2.48 6.36-4.167 13.63-4.646 24.271c-.477 10.667-.602 14.077-.602 41.236s.12 30.557.604 41.223c.49 10.646 2.175 17.913 4.646 24.271c2.556 6.578 5.973 12.157 11.533 17.715c5.557 5.563 11.136 8.988 17.709 11.542c6.363 2.473 13.631 4.158 24.275 4.646c10.667.485 14.073.604 41.23.604c27.161 0 30.559-.119 41.225-.604c10.646-.488 17.921-2.173 24.284-4.646c6.575-2.554 12.146-5.979 17.702-11.542c5.563-5.558 8.979-11.137 11.542-17.712c2.458-6.361 4.146-13.63 4.646-24.272c.479-10.666.604-14.066.604-41.225s-.125-30.567-.604-41.234c-.5-10.646-2.188-17.912-4.646-24.27c-2.563-6.578-5.979-12.157-11.542-17.716c-5.562-5.562-11.125-8.979-17.708-11.53c-6.375-2.474-13.646-4.16-24.292-4.647c-10.667-.485-14.063-.604-41.23-.604zm-8.971 18.021c2.663-.004 5.634 0 8.971 0c26.701 0 29.865.096 40.409.575c9.75.446 15.042 2.075 18.567 3.444c4.667 1.812 7.994 3.979 11.492 7.48c3.5 3.5 5.666 6.833 7.483 11.5c1.369 3.52 3 8.812 3.444 18.562c.479 10.542.583 13.708.583 40.396s-.104 29.855-.583 40.396c-.446 9.75-2.075 15.042-3.444 18.563c-1.812 4.667-3.983 7.99-7.483 11.488c-3.5 3.5-6.823 5.666-11.492 7.479c-3.521 1.375-8.817 3-18.567 3.446c-10.542.479-13.708.583-40.409.583c-26.702 0-29.867-.104-40.408-.583c-9.75-.45-15.042-2.079-18.57-3.448c-4.666-1.813-8-3.979-11.5-7.479s-5.666-6.825-7.483-11.494c-1.369-3.521-3-8.813-3.444-18.563c-.479-10.542-.575-13.708-.575-40.413s.096-29.854.575-40.396c.446-9.75 2.075-15.042 3.444-18.567c1.813-4.667 3.983-8 7.484-11.5s6.833-5.667 11.5-7.483c3.525-1.375 8.819-3 18.569-3.448c9.225-.417 12.8-.542 31.437-.563zm62.351 16.604c-6.625 0-12 5.37-12 11.996c0 6.625 5.375 12 12 12s12-5.375 12-12s-5.375-12-12-12zm-53.38 14.021c-28.36 0-51.354 22.994-51.354 51.355s22.994 51.344 51.354 51.344c28.361 0 51.347-22.983 51.347-51.344c0-28.36-22.988-51.355-51.349-51.355zm0 18.021c18.409 0 33.334 14.923 33.334 33.334c0 18.409-14.925 33.334-33.334 33.334s-33.333-14.925-33.333-33.334c0-18.411 14.923-33.334 33.333-33.334"
                    /><defs
                      ><radialGradient
                        id="skillIconsInstagram0"
                        cx="0"
                        cy="0"
                        r="1"
                        gradientTransform="matrix(0 -253.715 235.975 0 68 275.717)"
                        gradientUnits="userSpaceOnUse"
                        ><stop stop-color="#fd5" /><stop
                          offset=".1"
                          stop-color="#fd5"
                        /><stop offset=".5" stop-color="#ff543e" /><stop
                          offset="1"
                          stop-color="#c837ab"
                        /></radialGradient
                      ><radialGradient
                        id="skillIconsInstagram1"
                        cx="0"
                        cy="0"
                        r="1"
                        gradientTransform="matrix(22.25952 111.2061 -458.39518 91.75449 -42.881 18.441)"
                        gradientUnits="userSpaceOnUse"
                        ><stop stop-color="#3771c8" /><stop
                          offset=".128"
                          stop-color="#3771c8"
                        /><stop
                          offset="1"
                          stop-color="#60f"
                          stop-opacity="0"
                        /></radialGradient
                      ></defs
                    ></g
                  ></svg
                >
              </Button>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class="max-w-[5rem] lg:max-w-[12rem] h-auto rounded-xl">
      <img src="/sw11.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}">بانكيك السينابون</Dialog.Trigger
          >
          <Dialog.Content >
            <Dialog.Header class="">
              <Dialog.Title class="flex justify-center "
                >بانكيك السينابون
              </Dialog.Title>
            </Dialog.Header>
              <ScrollArea
              >
                <div class="  text-sm">
                  <section>
                    <h2 class="text-primary font-bold py-1">المكونات:</h2>
                    <ul>
                      <li>- 50 جم بيضة.</li>
                      <li>
                        - 60 جم زبادي يوناني (أو أي نوع متوفر، حتى لو سائل).
                      </li>
                      <li>- 40 جم دقيق أبيض أو شوفان مطحون.</li>
                      <li>- 3 جم بايكنج باودر.</li>
                      <li>
                        - 25 جم بروتين باودر شوكولاتة بيضاء (اختياري) = 99 سعرة
                        حرارية.
                      </li>
                      <li>- 10 جم جبن فيلادلفيا لايت.</li>
                      <li>- 10 مل ميبل سيرب أو عسل.</li>
                    </ul>
                  </section>

                  <section>
                    <h2 class="text-primary font-bold pt-3">الطريقة:</h2>
                    <ul>
                      <li>
                        1. اخلط البيضة، الزبادي اليوناني، ومحلي الفانيلا أو سكر
                        ستيفيا مع الفانيليا حتى تمتزج المكونات جيدًا.
                      </li>
                      <li>
                        2. أضف المكونات الجافة (الدقيق، الباكينج باودر، وبروتين
                        البودرة) إلى الخليط، ثم أضف ملعقتين كبيرتين من الماء إذا
                        لزم الأمر.
                      </li>
                    </ul>
                  </section>
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold">لتحضير الصوص:</h2>
                    <p>
                      - اخلط القرفة مع ميبل سيرب وظرف سكر ستيفيا. استخدم كيس
                      حلواني لتشكيل الصوص بشكل حلزوني.
                    </p>
                    <p>-
                      اضف الصوص الى الخليط ثم اخبزه 
                    </p>
                    <h2 class=" text-primary font-bold pt-3">
                      لتحضير الصوص الأبيض (اختياري):
                    </h2>
                    <p>
                      - اخلط جبن فيلادلفيا لايت مع ماء وسكر ستيفيا حتى تحصل على
                      القوام المناسب.
                    </p>
                  </section>
                  <section class="pt-3">
                    <h2 class="text-primary font-bold py-1">
                      السعرات الحرارية:
                    </h2>
                    <p>- 379 سعرة حرارية.</p>
                  </section>
                </div>
              </ScrollArea>
            <div class="flex justify-end items-end text-xs">
              <Button
                variant="ghost"
                href="https://www.instagram.com/healthy_shody?igsh=NG5kY28yamt0amk3"
              >
                <p class="px-1">healthy_shody@</p>
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="1em"
                  height="1em"
                  viewBox="0 0 256 256"
                  ><g fill="none"
                    ><rect
                      width="256"
                      height="256"
                      fill="url(#skillIconsInstagram0)"
                      rx="60"
                    /><rect
                      width="256"
                      height="256"
                      fill="url(#skillIconsInstagram1)"
                      rx="60"
                    /><path
                      fill="#fff"
                      d="M128.009 28c-27.158 0-30.567.119-41.233.604c-10.646.488-17.913 2.173-24.271 4.646c-6.578 2.554-12.157 5.971-17.715 11.531c-5.563 5.559-8.98 11.138-11.542 17.713c-2.48 6.36-4.167 13.63-4.646 24.271c-.477 10.667-.602 14.077-.602 41.236s.12 30.557.604 41.223c.49 10.646 2.175 17.913 4.646 24.271c2.556 6.578 5.973 12.157 11.533 17.715c5.557 5.563 11.136 8.988 17.709 11.542c6.363 2.473 13.631 4.158 24.275 4.646c10.667.485 14.073.604 41.23.604c27.161 0 30.559-.119 41.225-.604c10.646-.488 17.921-2.173 24.284-4.646c6.575-2.554 12.146-5.979 17.702-11.542c5.563-5.558 8.979-11.137 11.542-17.712c2.458-6.361 4.146-13.63 4.646-24.272c.479-10.666.604-14.066.604-41.225s-.125-30.567-.604-41.234c-.5-10.646-2.188-17.912-4.646-24.27c-2.563-6.578-5.979-12.157-11.542-17.716c-5.562-5.562-11.125-8.979-17.708-11.53c-6.375-2.474-13.646-4.16-24.292-4.647c-10.667-.485-14.063-.604-41.23-.604zm-8.971 18.021c2.663-.004 5.634 0 8.971 0c26.701 0 29.865.096 40.409.575c9.75.446 15.042 2.075 18.567 3.444c4.667 1.812 7.994 3.979 11.492 7.48c3.5 3.5 5.666 6.833 7.483 11.5c1.369 3.52 3 8.812 3.444 18.562c.479 10.542.583 13.708.583 40.396s-.104 29.855-.583 40.396c-.446 9.75-2.075 15.042-3.444 18.563c-1.812 4.667-3.983 7.99-7.483 11.488c-3.5 3.5-6.823 5.666-11.492 7.479c-3.521 1.375-8.817 3-18.567 3.446c-10.542.479-13.708.583-40.409.583c-26.702 0-29.867-.104-40.408-.583c-9.75-.45-15.042-2.079-18.57-3.448c-4.666-1.813-8-3.979-11.5-7.479s-5.666-6.825-7.483-11.494c-1.369-3.521-3-8.813-3.444-18.563c-.479-10.542-.575-13.708-.575-40.413s.096-29.854.575-40.396c.446-9.75 2.075-15.042 3.444-18.567c1.813-4.667 3.983-8 7.484-11.5s6.833-5.667 11.5-7.483c3.525-1.375 8.819-3 18.569-3.448c9.225-.417 12.8-.542 31.437-.563zm62.351 16.604c-6.625 0-12 5.37-12 11.996c0 6.625 5.375 12 12 12s12-5.375 12-12s-5.375-12-12-12zm-53.38 14.021c-28.36 0-51.354 22.994-51.354 51.355s22.994 51.344 51.354 51.344c28.361 0 51.347-22.983 51.347-51.344c0-28.36-22.988-51.355-51.349-51.355zm0 18.021c18.409 0 33.334 14.923 33.334 33.334c0 18.409-14.925 33.334-33.334 33.334s-33.333-14.925-33.333-33.334c0-18.411 14.923-33.334 33.333-33.334"
                    /><defs
                      ><radialGradient
                        id="skillIconsInstagram0"
                        cx="0"
                        cy="0"
                        r="1"
                        gradientTransform="matrix(0 -253.715 235.975 0 68 275.717)"
                        gradientUnits="userSpaceOnUse"
                        ><stop stop-color="#fd5" /><stop
                          offset=".1"
                          stop-color="#fd5"
                        /><stop offset=".5" stop-color="#ff543e" /><stop
                          offset="1"
                          stop-color="#c837ab"
                        /></radialGradient
                      ><radialGradient
                        id="skillIconsInstagram1"
                        cx="0"
                        cy="0"
                        r="1"
                        gradientTransform="matrix(22.25952 111.2061 -458.39518 91.75449 -42.881 18.441)"
                        gradientUnits="userSpaceOnUse"
                        ><stop stop-color="#3771c8" /><stop
                          offset=".128"
                          stop-color="#3771c8"
                        /><stop
                          offset="1"
                          stop-color="#60f"
                          stop-opacity="0"
                        /></radialGradient
                      ></defs
                    ></g
                  ></svg
                >
              </Button>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class="max-w-[5rem] lg:max-w-[12rem] h-auto rounded-xl">
      <img src="/sw12.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}">كيكة الكندر</Dialog.Trigger
          >
          <Dialog.Content >
            <Dialog.Header class="">
              <Dialog.Title class="flex justify-center "
                >كيكة الكندر
              </Dialog.Title>
            </Dialog.Header>
              <ScrollArea
              >
                <div class="  text-sm">
                  <section>
                    <h2 class="text-primary font-bold py-1">المكونات:</h2>
                    <ul>
                      <li>- شوفان مطحون: 30 جرام</li>
                      <li></li>
                      <li>- بايكنج باودر: 4 جرام ( نصف ملعقة صغيرة)</li>
                      <li>
                        - زبادي يوناني خالي الدسم: 25 جرام (ملعقة كبيرة)
                      </li>
                      <li>- كاكاو بودرة: 5 جرام (ملعقة كبيرة)</li>
                      <li>- سكر ستيفيا أو أي سكر دايت: ظرفين</li>
                      <li>- قهوة: 50 مل</li>
                      <li>- كندر: 21 جرام</li>
                    </ul>
                  </section>

                  <section>
                    <h2 class="text-primary font-bold pt-3">الطريقة:</h2>
                    <ul>
                      <li>
                        1. اخلط الشوفان المطحون، البايكنج باودر، الزبادي، كاكاو
                        بودرة، سكر ستيفيا، والقهوة في وعاء حتى تتجانس المكونات.
                      </li>
                      <li>2. صب الخليط في قوالب مخصصة للقلاية الهوائية.</li>
                      <li>
                        3. سخن القلاية الهوائية مسبقاً، ثم ضع القوالب داخلها.
                      </li>
                      <li>4. اخبزه على درجة حرارة 180 مئوية لمدة 10 دقائق.</li>
                      <li>
                        5. بعد انتهاء الطهي، أضف الكندر المقطّع إلى الأعلى، ثم
                        قدمه.
                      </li>
                    </ul>
                  </section>
                  <section class="pt-3">
                    <h2 class="text-primary font-bold">السعرات الحرارية:</h2>
                    <p>- 266 سعرة حرارية.</p>
                  </section>
                </div>
              </ScrollArea>
            <div class="flex justify-end items-end text-xs">
              <Button
                variant="ghost"
                href="https://www.instagram.com/healthy_shody?igsh=NG5kY28yamt0amk3"
              >
                <p class="px-1">healthy_shody@</p>
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="1em"
                  height="1em"
                  viewBox="0 0 256 256"
                  ><g fill="none"
                    ><rect
                      width="256"
                      height="256"
                      fill="url(#skillIconsInstagram0)"
                      rx="60"
                    /><rect
                      width="256"
                      height="256"
                      fill="url(#skillIconsInstagram1)"
                      rx="60"
                    /><path
                      fill="#fff"
                      d="M128.009 28c-27.158 0-30.567.119-41.233.604c-10.646.488-17.913 2.173-24.271 4.646c-6.578 2.554-12.157 5.971-17.715 11.531c-5.563 5.559-8.98 11.138-11.542 17.713c-2.48 6.36-4.167 13.63-4.646 24.271c-.477 10.667-.602 14.077-.602 41.236s.12 30.557.604 41.223c.49 10.646 2.175 17.913 4.646 24.271c2.556 6.578 5.973 12.157 11.533 17.715c5.557 5.563 11.136 8.988 17.709 11.542c6.363 2.473 13.631 4.158 24.275 4.646c10.667.485 14.073.604 41.23.604c27.161 0 30.559-.119 41.225-.604c10.646-.488 17.921-2.173 24.284-4.646c6.575-2.554 12.146-5.979 17.702-11.542c5.563-5.558 8.979-11.137 11.542-17.712c2.458-6.361 4.146-13.63 4.646-24.272c.479-10.666.604-14.066.604-41.225s-.125-30.567-.604-41.234c-.5-10.646-2.188-17.912-4.646-24.27c-2.563-6.578-5.979-12.157-11.542-17.716c-5.562-5.562-11.125-8.979-17.708-11.53c-6.375-2.474-13.646-4.16-24.292-4.647c-10.667-.485-14.063-.604-41.23-.604zm-8.971 18.021c2.663-.004 5.634 0 8.971 0c26.701 0 29.865.096 40.409.575c9.75.446 15.042 2.075 18.567 3.444c4.667 1.812 7.994 3.979 11.492 7.48c3.5 3.5 5.666 6.833 7.483 11.5c1.369 3.52 3 8.812 3.444 18.562c.479 10.542.583 13.708.583 40.396s-.104 29.855-.583 40.396c-.446 9.75-2.075 15.042-3.444 18.563c-1.812 4.667-3.983 7.99-7.483 11.488c-3.5 3.5-6.823 5.666-11.492 7.479c-3.521 1.375-8.817 3-18.567 3.446c-10.542.479-13.708.583-40.409.583c-26.702 0-29.867-.104-40.408-.583c-9.75-.45-15.042-2.079-18.57-3.448c-4.666-1.813-8-3.979-11.5-7.479s-5.666-6.825-7.483-11.494c-1.369-3.521-3-8.813-3.444-18.563c-.479-10.542-.575-13.708-.575-40.413s.096-29.854.575-40.396c.446-9.75 2.075-15.042 3.444-18.567c1.813-4.667 3.983-8 7.484-11.5s6.833-5.667 11.5-7.483c3.525-1.375 8.819-3 18.569-3.448c9.225-.417 12.8-.542 31.437-.563zm62.351 16.604c-6.625 0-12 5.37-12 11.996c0 6.625 5.375 12 12 12s12-5.375 12-12s-5.375-12-12-12zm-53.38 14.021c-28.36 0-51.354 22.994-51.354 51.355s22.994 51.344 51.354 51.344c28.361 0 51.347-22.983 51.347-51.344c0-28.36-22.988-51.355-51.349-51.355zm0 18.021c18.409 0 33.334 14.923 33.334 33.334c0 18.409-14.925 33.334-33.334 33.334s-33.333-14.925-33.333-33.334c0-18.411 14.923-33.334 33.333-33.334"
                    /><defs
                      ><radialGradient
                        id="skillIconsInstagram0"
                        cx="0"
                        cy="0"
                        r="1"
                        gradientTransform="matrix(0 -253.715 235.975 0 68 275.717)"
                        gradientUnits="userSpaceOnUse"
                        ><stop stop-color="#fd5" /><stop
                          offset=".1"
                          stop-color="#fd5"
                        /><stop offset=".5" stop-color="#ff543e" /><stop
                          offset="1"
                          stop-color="#c837ab"
                        /></radialGradient
                      ><radialGradient
                        id="skillIconsInstagram1"
                        cx="0"
                        cy="0"
                        r="1"
                        gradientTransform="matrix(22.25952 111.2061 -458.39518 91.75449 -42.881 18.441)"
                        gradientUnits="userSpaceOnUse"
                        ><stop stop-color="#3771c8" /><stop
                          offset=".128"
                          stop-color="#3771c8"
                        /><stop
                          offset="1"
                          stop-color="#60f"
                          stop-opacity="0"
                        /></radialGradient
                      ></defs
                    ></g
                  ></svg
                >
              </Button>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class="max-w-[5rem] lg:max-w-[12rem] h-auto rounded-xl">
      <img src="/sw14.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}">كيكة ليمون بالتوت</Dialog.Trigger
          >
          <Dialog.Content >
            <Dialog.Header class="">
              <Dialog.Title class="flex justify-center"
                >كيكة ليمون بالتوت
              </Dialog.Title>
            </Dialog.Header>
              <ScrollArea
              >
                <div class="  text-sm">
                  <section>
                    <h2 class="text-primary font-bold py-1">المكونات:</h2>
                    <ul>
                      <li>- 10 جم بروتين فانيلا (اختياري).</li>
                      <li>- 150 جم زبادي يوناني خال الدسم.</li>
                      <li>- توت مشكل.</li>
                      <li>- بيضة.</li>
                      <li>- ملعقة صغيرة باكينج باودر.</li>
                      <li>- عصرة ليمون.</li>
                      <li>- 40 جم دقيق أبيض.</li>
                      <li>- 6 جم بسكوت بدون سكر.</li>
                      <li>- ظرف سكر ستيفيا.</li>
                    </ul>
                  </section>

                  <section>
                    <h2 class="text-primary font-bold pt-3">الطريقة:</h2>
                    <ul>
                      <li>1. في وعاء، اخلط الزبادي، البيضة، وسكر ستيفيا.</li>
                      <li>2. قسم الخليط إلى قسمين:</li>
                      <li>
                        - اخلط القسم الأول مع جميع المكونات ما عدا التوت ثم اسكب 
                        الخليط في الصينية.
                      </li>
                      <li>
                        - اخلط القسم الثاني مع التوت المشكل، ثم اسكبه فوق الخليط
                        الأول في الصينية.
                      </li>
                    </ul>
                  </section>
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold">الصينية</h2>
                    <p>
                      - اخبز الخليط في فرن مُسخن مسبقًا على حرارة 180 درجة
                      مئوية حتى ينضج (من الأعلى والأسفل).
                    </p>
                  </section>
                  <section class="pt-3">
                    <h2 class="text-primary font-bold">السعرات الحرارية:</h2>
                    <p>- 384 سعرة حرارية.</p>
                  </section>
                </div>
              </ScrollArea>
            <div class="flex justify-end items-end text-xs">
              <Button
                variant="ghost"
                href="https://www.instagram.com/i_smr?igsh=MXY2ejAxanlrcXZqOQ=="
              >
                <p class="px-1">i_smr@</p>
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="1em"
                  height="1em"
                  viewBox="0 0 256 256"
                  ><g fill="none"
                    ><rect
                      width="256"
                      height="256"
                      fill="url(#skillIconsInstagram0)"
                      rx="60"
                    /><rect
                      width="256"
                      height="256"
                      fill="url(#skillIconsInstagram1)"
                      rx="60"
                    /><path
                      fill="#fff"
                      d="M128.009 28c-27.158 0-30.567.119-41.233.604c-10.646.488-17.913 2.173-24.271 4.646c-6.578 2.554-12.157 5.971-17.715 11.531c-5.563 5.559-8.98 11.138-11.542 17.713c-2.48 6.36-4.167 13.63-4.646 24.271c-.477 10.667-.602 14.077-.602 41.236s.12 30.557.604 41.223c.49 10.646 2.175 17.913 4.646 24.271c2.556 6.578 5.973 12.157 11.533 17.715c5.557 5.563 11.136 8.988 17.709 11.542c6.363 2.473 13.631 4.158 24.275 4.646c10.667.485 14.073.604 41.23.604c27.161 0 30.559-.119 41.225-.604c10.646-.488 17.921-2.173 24.284-4.646c6.575-2.554 12.146-5.979 17.702-11.542c5.563-5.558 8.979-11.137 11.542-17.712c2.458-6.361 4.146-13.63 4.646-24.272c.479-10.666.604-14.066.604-41.225s-.125-30.567-.604-41.234c-.5-10.646-2.188-17.912-4.646-24.27c-2.563-6.578-5.979-12.157-11.542-17.716c-5.562-5.562-11.125-8.979-17.708-11.53c-6.375-2.474-13.646-4.16-24.292-4.647c-10.667-.485-14.063-.604-41.23-.604zm-8.971 18.021c2.663-.004 5.634 0 8.971 0c26.701 0 29.865.096 40.409.575c9.75.446 15.042 2.075 18.567 3.444c4.667 1.812 7.994 3.979 11.492 7.48c3.5 3.5 5.666 6.833 7.483 11.5c1.369 3.52 3 8.812 3.444 18.562c.479 10.542.583 13.708.583 40.396s-.104 29.855-.583 40.396c-.446 9.75-2.075 15.042-3.444 18.563c-1.812 4.667-3.983 7.99-7.483 11.488c-3.5 3.5-6.823 5.666-11.492 7.479c-3.521 1.375-8.817 3-18.567 3.446c-10.542.479-13.708.583-40.409.583c-26.702 0-29.867-.104-40.408-.583c-9.75-.45-15.042-2.079-18.57-3.448c-4.666-1.813-8-3.979-11.5-7.479s-5.666-6.825-7.483-11.494c-1.369-3.521-3-8.813-3.444-18.563c-.479-10.542-.575-13.708-.575-40.413s.096-29.854.575-40.396c.446-9.75 2.075-15.042 3.444-18.567c1.813-4.667 3.983-8 7.484-11.5s6.833-5.667 11.5-7.483c3.525-1.375 8.819-3 18.569-3.448c9.225-.417 12.8-.542 31.437-.563zm62.351 16.604c-6.625 0-12 5.37-12 11.996c0 6.625 5.375 12 12 12s12-5.375 12-12s-5.375-12-12-12zm-53.38 14.021c-28.36 0-51.354 22.994-51.354 51.355s22.994 51.344 51.354 51.344c28.361 0 51.347-22.983 51.347-51.344c0-28.36-22.988-51.355-51.349-51.355zm0 18.021c18.409 0 33.334 14.923 33.334 33.334c0 18.409-14.925 33.334-33.334 33.334s-33.333-14.925-33.333-33.334c0-18.411 14.923-33.334 33.333-33.334"
                    /><defs
                      ><radialGradient
                        id="skillIconsInstagram0"
                        cx="0"
                        cy="0"
                        r="1"
                        gradientTransform="matrix(0 -253.715 235.975 0 68 275.717)"
                        gradientUnits="userSpaceOnUse"
                        ><stop stop-color="#fd5" /><stop
                          offset=".1"
                          stop-color="#fd5"
                        /><stop offset=".5" stop-color="#ff543e" /><stop
                          offset="1"
                          stop-color="#c837ab"
                        /></radialGradient
                      ><radialGradient
                        id="skillIconsInstagram1"
                        cx="0"
                        cy="0"
                        r="1"
                        gradientTransform="matrix(22.25952 111.2061 -458.39518 91.75449 -42.881 18.441)"
                        gradientUnits="userSpaceOnUse"
                        ><stop stop-color="#3771c8" /><stop
                          offset=".128"
                          stop-color="#3771c8"
                        /><stop
                          offset="1"
                          stop-color="#60f"
                          stop-opacity="0"
                        /></radialGradient
                      ></defs
                    ></g
                  ></svg
                >
              </Button>
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
  </div>
</div>
