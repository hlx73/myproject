<script lang="ts">
  import { buttonVariants } from "$lib/components/ui/button";
  import Button from "$lib/components/ui/button/button.svelte";
  import * as Dialog from "$lib/components/ui/dialog";
  import { ScrollArea } from "$lib/components/ui/scroll-area/index.js";
  import Mybutton from "$lib/components/mybutton.svelte";
</script>

<div class="flex flex-col items-center pb-20">
  <div
    class="lg:h-fit w-[80vw] lg:p-10  bg-gradient-to-r from-background/90 to-primary/50 dark:bg-primary shadow-[0_20px_60px_-15px_rgba(0,0,0,0.7)] ring-1 ring-secondary
     rounded-xl grid grid-cols-4 gap-5 p-4 px-2 "
  >
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/m1.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[16vw] w-[18vw] lg:h-fit h-[5vh]  {buttonVariants(
              {
                variant: 'outline',
              },
            )}">ساندوتش روبيان
            </Dialog.Trigger>
          <Dialog.Content class=" w-[70vw] h-[90vh]  shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center"
                >ساندوتش روبيان
              </Dialog.Title>
            </Dialog.Header>
            <div class="flex justify-center items-center">
              <ScrollArea
                class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4"
              >
                <div class=" text-sm">
                  <section>
                    <h2 class="text-primary font-bold pb-1">المكونات:</h2>
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
                    <h2 class=" text-primary font-bold ">الطريقة:</h2>
                    <h2 class=" text-primary font-bold">
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
                    <h2 class=" text-primary font-bold ">
                      2. تحضير الصامولي:
                    </h2>
                    <ol class="">
                      <li></li>
                      <li>- فرغ الصامولي من الداخل.</li>
                      <li>- ضع فيه طبقة من الخس والبقدونس.</li>
                      <li>- أضف خليط الروبيان فوق الخضار.</li>
                    </ol>
                  </section>
                  <section class="py-3">
                    <h2 class="text-primary font-bold ">
                      السعرات الحرارية:
                    </h2>
                    <p>-371 سعرة حرارية تقريباً</p>
                  </section>
                </div>
              </ScrollArea>
            </div>
            <div class="flex justify-end items-end text-xs">
              <Button variant="ghost" href="https://www.instagram.com/nanv.healthy?igsh=MWVxc2o4cXRwZG51MQ==">
               
                <p class="px-1">
                  nanv.healthy@</p>
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
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/m2.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[16vw] w-[18vw] lg:h-fit h-[5vh]  {buttonVariants(
              {
                variant: 'outline',
              },
            )}">بيتزا خضار
            </Dialog.Trigger>
          <Dialog.Content class=" w-[70vw] h-[90vh] shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center "
                >بيتزا خضار
              </Dialog.Title>
            </Dialog.Header>
            <div class="flex justify-center items-center">
              <ScrollArea
                class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4"
              >
                <div class=" text-sm">
                  <section>
                    <h2 class="text-primary font-bold py-1">المكونات:</h2>
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
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold ">الطريقة:</h2>
                    <h2 class=" text-primary font-bold">
                      1. تحضير الدجاج:
                    </h2>
                    <ol class="">
                      <li>-اشوي الدجاج في مقلاة حتى ينضج تماما</li>
                      <li>- اضف عليه البهارات (فلفل أسود, رشة بهار مخلوط, ملح وأوريغانو)</li>
                      <li class="pt-2 text-primary font-bold">
                        2. تحضير المكونات الأخرى:
                      </li>
                      <li>- في وعاء ضع جبن الفيتا والسبانخ المفرومة والبهارات الايطالية واخلطهم جيداً</li>
                      <li class="pt-2 text-primary font-bold">
                        3. تجميع البيتزا:
                      </li>
                      <li>-ادهن عجينة البيتزا بخليط الجبن والسبانخ</li>
                      <li>- اضف جبن البارميزان والموزاريلا والدجاج والزيتون</li>
                      <li class="pt-2 text-primary font-bold">4. الخبز:</li>
                      <li>-اخبز البيتزا حسب تعليمات العجينة الجاهزة </li>
                    </ol>
                  </section>

                  <h2 class="text-primary font-bold pt-3">
                    السعرات الحرارية:
                  </h2>
                  <p>-481 سعرة حرارية</p>
                </div>
              </ScrollArea>
            </div>
            <div class="flex justify-end items-end text-xs">
              <Button variant="ghost" href="https://www.instagram.com/azm_halth55?igsh=MTUzOWV2OHhpZGYzbA==">
               
                <p class="px-1">
                  azm_halth55@</p>
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
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/m3.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
          class="text-xs lg:w-[16vw] w-[18vw] lg:h-fit h-[5vh]  {buttonVariants(
            {
              variant: 'outline',
            },
          )}">فاهيتا الدجاج
          </Dialog.Trigger>
          <Dialog.Content class=" w-[70vw] h-[90vh]  shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center "
                >فاهيتا الدجاج
              </Dialog.Title>
            </Dialog.Header>
            <div class="flex justify-center items-center">
              <ScrollArea
                class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4"
              >
                <div class=" text-sm">
                  <section>
                    <h2 class="text-primary font-bold py-1">المكونات:</h2>
                    <ul>
                      <li>- صدري دجاج: 215 جرام</li>
                      <li>- فلفل رومي ملون: 160 جرام</li>
                      <li>- بصل: 30 جرام</li>
                      <li>- ثوم: 10 جرام</li>
                      <li>- زبادي يوناني: 90 جرام</li>
                      <li>- موزاريلا لايت: 10 جرام</li>

                      <li>- تورتيلا واحدة: 40 جرام</li>
                    </ul>
                  </section>
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold ">الطريقة:</h2>
                    <h2 class=" text-primary font-bold">
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
                      <li class="pt-2 text-primary font-bold">
                        2. إضافة الزبادي:
                      </li>
                      <li>
                        - بعد نضج الدجاج وذبول البصل، أضف الزبادي اليوناني واترك
                        الخليط قليلاً على النار.
                      </li>
                      <li class="pt-2 text-primary font-bold">
                        3. تحضير التورتيلا:
                      </li>
                      <li>- ضع خليط الدجاج فوق التورتيلا.</li>
                      <li>- رشّ الموزاريلا على الوجه.</li>

                      <li class="pt-2 text-primary font-bold">
                        4. التحميص:
                      </li>
                      <li>
                        - حمّص التورتيلا على الصاج حتى تذوب الجبنة وتصبح ذهبية.
                      </li>
                    </ol>
                  </section>

                  <h2 class="text-primary font-bold pt-2">ملاحظات:</h2>
                  <p>
                    - يمكن استبدال التورتيلا بمكونات أخرى مثل الأرز، البطاطس
                     المهروسة، المكرونة، التوست، أو بف باستري، ويجب حساب
                    السعرات بناءً على المكون المستخدم.
                  </p>
                  <h2 class="text-primary font-bold pt-3">
                    السعرات الحرارية:
                  </h2>
                  <p>-509 سعرة حرارية</p>
                </div>
              </ScrollArea>
            </div>
            <div class="flex justify-end items-end text-xs">
              <Button variant="ghost" href="https://www.instagram.com/healthy_shody?igsh=NG5kY28yamt0amk3">
               
                <p class="px-1">
                  healthy_shody@</p>
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
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/m4.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[16vw] w-[18vw] lg:h-fit h-[5vh]  {buttonVariants(
              {
                variant: 'outline',
              },
            )}">سبرينغ رول
            </Dialog.Trigger>
          
          <Dialog.Content class=" w-[70vw] h-[90vh]  shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center "
                >سبرينغ رول
              </Dialog.Title>
            </Dialog.Header>
            <div class="flex justify-center items-center">
              <ScrollArea
                class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4"
              >
                <div class=" text-sm">
                  <section>
                    <h2 class="text-primary font-bold py-1">المكونات:</h2>
                    <ul>
                      <li>- بصل: حبة صغيرة (36 جرام)</li>
                      <li>- فلفل رومي: حبة وسط (80 جرام)</li>
                      <li>- صدور دجاج: 217 جرام </li>
                      <li>- زبادي سائل يوناني: نصف كوب تقريباً (100 جرام)</li>
                      <li>- موزاريلا: ملعقة (15 جرام)</li>
                      <li>- سبرنج رول: 4 حبات</li>
                    </ul>
                  </section>
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold ">الطريقة:</h2>
                    <h2 class=" text-primary font-bold">1. تحضير الحشوة:</h2>
                    <ol class="">
                      <li>- سخن الصاج وأضف الدجاج، البصل، والفلفل الرومي.</li>
                      <li>
                        - أضف البهارات (ملح، فلفل أسود، بابريكا، بهارات إيطالية)
                        واطبخ حتى ينضج الدجاج ويذبل البصل والفلفل.
                      </li>
                      <li class="pt-2 text-primary font-bold">
                        2. تجهيز السبرنج رول:
                      </li>
                      <li>- افرد السبرنج رول واملأه بالحشوة.</li>
                      <li>- رشّ الموزاريلا فوق الحشوة ولفّ السبرنج رول.</li>
                      <li class="pt-2 text-primary font-bold">3. الخبز:</li>
                      <li>- رصّ السبرنج رول المحشو في صينية خبز.</li>
                      <li>- صبّ الزبادي فوق السبرنج رول.</li>
                      <li>
                        - اخبز في فرن مسبق التسخين على درجة حرارة 180 مئوية من
                        فوق ومن تحت لمدة 7 دقائق.
                      </li>
                    </ol>
                  </section>

                  <h2 class="text-primary font-bold pt-3">
                    السعرات الحرارية:
                  </h2>
                  <p>-377 سعرة حرارية</p>
                </div>
              </ScrollArea>
            </div>
            <div class="flex justify-end items-end text-xs">
              <Button variant="ghost" href="https://www.instagram.com/healthy_shody?igsh=NG5kY28yamt0amk3">
               
                <p class="px-1">
                  healthy_shody@</p>
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
          <Dialog.Content class=" w-[70vw] h-[90vh]  shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center "
                >زنجر
              </Dialog.Title>
            </Dialog.Header>
            <div class="flex justify-center items-center">
              <ScrollArea
                class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4"
              >
                <div class=" text-sm">
                  <section>
                    <h2 class="text-primary font-bold py-1">المكونات:</h2>
                    <ul>
                      <li>- صدر دجاج: 240 جرام</li>
                      <li>- نصف بيضة: 25 جرام</li>
                      <li>- كورنفلكس: 15 جرام</li>
                      <li>- شريحة جبن قليلة الدسم: 19 جرام</li>
                      <li>- صوص رانش خالي الدهون: 17 جرام</li>
                      <li>- صوص فرنسي خالي الدهون: 17 جرام</li>
                      <li>- مايونيز قليل السعرات: 17 جرام</li>
                      <li>- بطاطس: حبة متوسطة إلى صغيرة (137 جرام)</li>
                      <li>- خبز لوزين برغر 24 جرام</li>
                    </ul>
                  </section>
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold ">
                      طريقة التحضير:
                    </h2>
                    <h2 class=" text-primary font-bold">1. تحضير البرجر:</h2>
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
                    <h2 class=" text-primary font-bold pt-2">
                      2. تحضير الصوص:
                    </h2>
                    <ol class="">
                      <li>
                        - امزج البابريكا الحارة، صوص رانش، صلصة فرنسية،
                        والمايونيز قليل السعرات.
                      </li>
                    </ol>
                  </section>
                  <section class="pt-2">
                    <h2 class=" text-primary font-bold ">
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
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold py-1">4. التقديم:</h2>
                    <ol class="">
                      <li>
                        - ضف الى الخبز الصوص، خس، الدجاج
                        المقرمش، الجبن.
                      </li>
                    </ol>
                  </section>
                  <section class="pt-3">
                    <h2 class="text-primary font-bold ">
                      السعرات الحرارية:
                    </h2>
                    <p>-554 سعرة حرارية</p>
                  </section>
                </div>
              </ScrollArea>
            </div>
            <div class="flex justify-end items-end text-xs">
              <Button variant="ghost" href="https://www.instagram.com/healthy_shody?igsh=NG5kY28yamt0amk3">
               
                <p class="px-1">
                  healthy_shody@</p>
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
          <Dialog.Content class=" w-[70vw] h-[90vh]  shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center "
                >كلوب ديلوكس
              </Dialog.Title>
            </Dialog.Header>
            <div class="flex justify-center items-center">
              <ScrollArea
                class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4"
              >
                <div class=" text-sm">
                  <section>
                    <h2 class="text-primary font-bold py-1">المكونات:</h2>
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
                  
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold ">
                      طريقة تحضير الوجبة:
                    </h2>
                    <h2 class=" text-primary font-bold ">
                      1.تحضير التورتيلا:
                    </h2>
                    <ol class="">
                      <li>
                        - ضع شريحة التورتيلا في مقلاة أو على صاج التسخين قليلاً.
                      </li>
                    </ol>
                  </section>
                  <section class="pt-2">
                    <h2 class=" text-primary font-bold ">
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
                  <section class="pt-2">
                    <h2 class=" text-primary font-bold ">3. الطهي:</h2>
                    <ol class="">
                      <li>
                        - اطبخ الوجبة على نار هادئة حتى ينضج البيض ويذوب الجبن.
                      </li>
                    </ol>
                  </section>
                  <section class="pt-2">
                    <h2 class=" text-primary font-bold ">4. التقديم:</h2>
                    <ol class="">
                      <li>
                        - أضف ملعقة رانش خالية الدهون وسيراشا حسب الرغبة على
                        الوجه.
                      </li>
                    </ol>
                  </section>
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold ">نصائح:</h2>
                    <ol class="">
                      <li>
                        - يمكنك إضافة خضروات مثل الفلفل أو الطماطم إلى الحشوة
                        للحصول على نكهة إضافية
                      </li>
                      <li />
                    </ol>
                  </section>
                  <section class="pt-3">
                    <h2 class="text-primary font-bold ">
                      السعرات الحرارية:
                    </h2>
                    <p>-389 سعرة حرارية</p>
                  </section>
                </div>
              </ScrollArea>
            </div>
            <div class="flex justify-end items-end text-xs">
              <Button variant="ghost" href="https://www.instagram.com/healthy_shody?igsh=NG5kY28yamt0amk3">
               
                <p class="px-1">
                  healthy_shody@</p>
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
          <Dialog.Content class=" w-[70vw] h-[90vh] shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center "
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
                    <h2 class="text-primary font-bold py-1">المكونات:</h2>
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
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold ">الطريقة:</h2>
                    <h2 class=" text-primary font-bold ">
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
                  <section class="pt-2">
                    <h2 class=" text-primary font-bold ">
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
                  <section class="pt-2">
                    <h2 class=" text-primary font-bold ">
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
                  <section class="pt-2">
                    <h2 class=" text-primary font-bold ">
                      4. تحضير الصوص:
                    </h2>
                    <ol class="">
                      <li>
                        - اخلط الزبادي اليوناني مع نفس البهارات المستخدمة، أضف
                        الفلفل الأبيض والشبت المجفف حسب الذوق.
                      </li>
                    </ol>
                  </section>
                  <section class="pt-2">
                    <h2 class=" text-primary font-bold ">5. التقديم:</h2>
                    <ol class="">
                      <li>
                        - ضع طبقة من الخس أولاً، ثم أضف الدجاج والخضروات،
                        وأخيرًا الصوص
                      </li>
                    </ol>
                  </section>

                  <section class="pt-3">
                    <h2 class="text-primary font-bold ">
                      السعرات الحرارية:
                    </h2>
                    <p>441 سعرة حرارية</p>
                  </section>
                </div>
              </ScrollArea>
            </div>
            <div class="flex justify-end items-end text-xs">
              <Button variant="ghost" href="https://www.instagram.com/healthy_shody?igsh=NG5kY28yamt0amk3">
               
                <p class="px-1">
                  healthy_shody@</p>
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
          <Dialog.Content class=" w-[70vw] h-[90vh] shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center "
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
                    <h2 class="text-primary font-bold py-1">المكونات:</h2>
                    <ul>
                      <li>- بطاطس: 280 جرام (حبتين متوسطة)</li>
                      <li>- صدور دجاج: 260 جرام (صدرين كبيرين أو 3 صغار)</li>
                      <li>- حليب قليل الدسم: 50 جرام (ربع كوب)</li>
                      <li>- موزاريلا لايت: 33 جرام (ملعقتين كبيرتين)</li>
                      <li>- كريمة طبخ: 100 جرام (ثلاثة أرباع الكوب)</li>
                      <li>- بصل: 49 جرام (حبة صغيرة)</li>
                      <li>- فلفل رومي 89 جرام  (حبة متوسطة) </li>
                      <li>- ثوم: 4 جرام (فص واحد كبير)</li>
                      <li>- صلصة طماطم: 15 جرام</li>
                    </ul>
                  </section>
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold ">الطريقة:</h2>
                    <h2 class=" text-primary font-bold ">
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
                  <section class="pt-2">
                    <h2 class=" text-primary font-bold ">
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
                  <section class="pt-2">
                    <h2 class=" text-primary font-bold ">
                      3. تجميع الطبق:
                    </h2>
                    <ol class="">
                      <li>- ضع خليط الدجاج في صينية خبز.</li>
                      <li>- كوّر البطاطس المهروسة فوق خليط الدجاج.</li>
                      <li>- أضف الكريمة على الوجه .</li>
                      <li>- رشّ الموزاريلا فوق الطبقة الأخيرة.</li>
                    </ol>
                  </section>
                  <section class="pt-2">
                    <h2 class=" text-primary font-bold ">4.الخبز:</h2>
                    <ol class="">
                      <li>
                        - ضع الصينية في الفرن على حرارة من الأعلى حتى تذوب
                        الجبنة وتتحمر.
                      </li>
                    </ol>
                  </section>

                  <section class="pt-3">
                    <h2 class="text-primary font-bold ">
                      السعرات الحرارية:
                    </h2>
                    <p>السعرات الحرارية للصينية كاملة: 817 سعرة حرارية</p>
                  </section>
                </div>
              </ScrollArea>
            </div>
            <div class="flex justify-end items-end text-xs">
              <Button variant="ghost" href="https://www.instagram.com/healthy_shody?igsh=NG5kY28yamt0amk3">
               
                <p class="px-1">
                  healthy_shody@</p>
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
          <Dialog.Content class=" w-[70vw] h-[90vh]  shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center"
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
                    <h2 class="text-primary font-bold py-1">المكونات:</h2>
                    <ul>
                      <li>- 100 جرام لحم مفروم مع بقدونس مهروس (اختياري)</li>
                      <li>- 150 جرام خضار مجمدة (جزر، بازيلاء، ذرة)</li>
                      <li>- نصف ملعقة صغيرة زيت زيتون (30 سعرة)</li>
                      <li>- 100 جرام معكرونة مسلوقة (158 سعرة)</li>
                      <li>- بهارات (ملح، فلفل أسود، زعتر بري)</li>
                      <li>- حبة طماطم مبشورة أو ملعقة معجون طماطم</li>
                      <li>- بصلة</li>
                      <li>- سلطة خضار (طماطم، خيار، ملفوف أحمر) 25 سعرة </li>
                    </ul>
                  </section>
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold ">الطريقة:</h2>

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

                  <section class="pt-3">
                    <h2 class="text-primary font-bold ">
                      السعرات الحرارية:
                    </h2>
                    <p>492 سعرة حرارية</p>
                  </section>
                </div>
              </ScrollArea>
            </div>
            <div class="flex justify-end items-end text-xs">
              <Button variant="ghost" href="https://www.instagram.com/azm_halth55?igsh=MTUzOWV2OHhpZGYzbA==">
               
                <p class="px-1">
                  azm_halth55@</p>
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
          <Dialog.Content class=" w-[70vw] h-[90vh]  shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center "
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
                    <h2 class="text-primary font-bold ">المكونات:</h2>
                    <h2 class="text-primary font-bold ">للعجينة:</h2>
                    <ul>
                      <li>- كوب شوفان مطحون </li>
                      <li>- كوب طحين اسمر بر</li>
                      <li>- ملعقة طعام خميرة</li>
                      <li>- ملعقة طعام عسل</li>
                      <li>- ملعقتين زيت زيتون أو زيت نباتي</li>
                      <li>- نصف كوب ماء دافئ</li>
                    </ul>
                  </section>
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold ">للتزيين:</h2>

                    <ol>
                      <li>- دجاج: 66 جرام</li>
                      <li>- خضروات: فلفل أخضر، طماطم</li>
                      <li>- جبن موزاريلا: 45 جرام</li>
                    </ol>
                  </section>
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold ">
                      لصلصة البيتزا:
                    </h2>
                    <ol class="">
                      <li>- ملعقتين طعام كاتشب</li>
                      <li>- 16 جرام معجون طماطم</li>
                      <li>- قليلاً من الشطة السائلة</li>
                    </ol>
                  </section>
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold ">الطريقة:</h2>
                    <h2 class=" text-primary font-bold ">
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
                  <section class="pt-2">
                    <h2 class=" text-primary font-bold ">
                      2. تحضير الصلصة:
                    </h2>
                    <ol class="">
                      <li>- اخلط الكاتشب، معجون الطماطم، والشطة السائلة.</li>
                    </ol>
                  </section>
                  <section class="pt-2">
                    <h2 class=" text-primary font-bold ">
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

                    <section class="pt-3">
                      <h2 class="text-primary font-bold py-1">
                        السعرات الحرارية:
                      </h2>
                      <p>- لكل البيتزا: 1194 سعرة حرارية</p>
                      <p>- لكل قطعة (من 8 قطع): 149 سعرة حرارية</p>
                    </section>
                  </section>
                </div>
              </ScrollArea>
            </div>
            <div class="flex justify-end items-end text-xs">
              <Button variant="ghost" href="https://www.instagram.com/fatima_diet04?igsh=cXRianEyajc1Nmow">
               
                <p class="px-1">
                  fatima.diet04@</p>
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
          <Dialog.Content class=" w-[70vw] h-[90vh]  shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center "
                >فطيرة البطاطس
              </Dialog.Title>
            </Dialog.Header>
            <div class="flex justify-center items-center">
              <ScrollArea
                class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4"
              >
                <div class=" text-sm">
                  <section>
                    <h2 class="text-primary font-bold py-1">المكونات:</h2>
                    <ul>
                      <li>- 150 جرام بطاطس</li>
                      <li>- 2 بيض</li>
                      <li>- ملح وفلفل أسود وشيلي فليكس (شطة حمراء مجففة)</li>
                      <li>- 10 جرام جبن موتزاريلا (اختياري)</li>
                    </ul>
                  </section>
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold ">الطريقة:</h2>

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
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold ">اختياري:</h2>
                    <p>أضف الجبن والفلفل  بعد القلب النهائي.</p>
                  </section>
                  <section class="pt-3">
                    <h2 class="text-primary font-bold ">
                      السعرات الحرارية:
                    </h2>
                    <p>-301  سعرة حرارية</p>
                  </section>
                </div>
              </ScrollArea>
            </div>
            <div class="flex justify-end items-end text-xs">
              <Button variant="ghost" href="https://www.instagram.com/amanymona22_healthy?igsh=ZXhtYzcwN2YzbXdh">
               
                <p class="px-1">
                  amanymona22_healthy@</p>
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
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/m12.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}"
            >معكرونة بالصلصة
          </Dialog.Trigger>
          <Dialog.Content class=" w-[70vw] h-[90vh] shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center "
                >معكرونة بالصلصة
              </Dialog.Title>
            </Dialog.Header>
            <div class="flex justify-center items-center">
              <ScrollArea
                class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4"
              >
                <div class=" text-sm">
                  <section>
                    <h2 class="text-primary font-bold ">المكونات:</h2>
                    <ul>
                      <li>- صدر دجاج: 137 جرام</li>
                      <li>- بصل أحمر: 23 جرام</li>
                      <li>- بروكلي: 54 جرام</li>
                      <li>- فلفل رومي: 30 جرام</li>
                      <li>- صلصة طماطم: 25 جرام (مخففة بـ 40 مل ماء)</li>
                      <li>- لبن سائل قليل الدسم: 50 مل</li>
                      <li>- مكرونة بالدقيق الأسمر أو مكرونة قليلة الكربوهيدرات</li>
                     </ul>
                  </section>
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold ">
                      البهارات:                    </h2>
                    <ol class="">
                      <li>- ملح</li>
                      <li>- فلفل أسود وأبيض</li>
                      <li>- بودرة بصل وثوم</li>
                      <li>- بابريكا</li>
                      <li>- بهارات إيطالية</li>
                      </ol>
                  </section>
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold ">
                      الطريقة:                    </h2>
                      <h2 class=" text-primary font-bold ">
                        1. تحضير الدجاج:</h2>
                    <ol class="">
                      <li>   - قطّع صدر الدجاج إلى قطع صغيرة.
                      </li>
                      <li>   - في مقلاة، اقلي الدجاج حتى ينضج ويأخذ لوناً ذهبياً. أضف البصل الأحمر، الفلفل الرومي، والبروكلي واستمر في الطهي حتى تنضج الخضروات.</li>
                    </ol>
                  </section>
                  <section class="pt-2">
                    <h2 class=" text-primary font-bold ">
                      2. إعداد الصلصة:                    </h2>
                    <ol class="">
                      <li>   - أضف صلصة الطماطم المخففة بالماء إلى المقلاة.</li>
                      <li>   - أضف البهارات: الملح، الفلفل الأسود والأبيض، بودرة البصل والثوم، البابريكا، والبهارات الإيطالية. اترك الصلصة تغلي حتى تتكاثف وتصبح القوام المطلوب.</li>
                    </ol>
                  </section>
                  <section class="pt-2">
                    <h2 class=" text-primary font-bold ">3. إعداد المكرونة:</h2>
                    <ol class="">
                      <li>   - اطبخ المكرونة حسب التعليمات على العبوة. صفيها وأضفها إلى المقلاة مع الدجاج والخضار. اخلط جيداً حتى تمتزج المكونات.
                      </li> 
                    </ol>
                  </section>
                  <section class="pt-2">
                    <h2 class=" text-primary font-bold ">4. إضافة اللبن:</h2>
                    <ol class="">
                      <li>   - أضف اللبن السائل إلى المقلاة واتركه ليدفأ مع التحريك. </li> 
                    </ol>
                  </section>
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold ">التقديم:</h2>
                  <p>- قدم الطبق ساخناً واستمتع به.
                  </p>
                  </section>
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold ">نصائح</h2>
                  <p>
                    <p>- يمكن استبدال اللبن بالكريمة قليلة الدسم إذا رغبت في إضافة قوام كريمي أكثر.</p>
                  </section>
                  <section class="pt-3">
                    <h2 class="text-primary font-bold ">
                      السعرات الحرارية:
                    </h2>
                    <p>-432  سعرة حرارية</p>
                  </section>
                </div>
              </ScrollArea>
            </div>
            <div class="flex justify-end items-end text-xs">
              <Button variant="ghost" href="https://www.instagram.com/healthy_shody?igsh=NG5kY28yamt0amk3">
               
                <p class="px-1">
                  healthy_shody@</p>
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
