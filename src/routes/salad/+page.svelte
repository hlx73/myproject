<script lang="ts">
  import { buttonVariants } from "$lib/components/ui/button";
  import Button from "$lib/components/ui/button/button.svelte";
  import * as Dialog from "$lib/components/ui/dialog";
  import { ScrollArea } from "$lib/components/ui/scroll-area/index.js";
</script>

<div class="flex flex-col items-center pb-20">
  <div
    class="lg:h-fit w-[80vw] lg:p-10 lg:gap-16 lg:gap-y-4  bg-gradient-to-r from-background/90 to-primary/50 dark:bg-primary shadow-[0_20px_60px_-15px_rgba(0,0,0,0.7)] ring-1 ring-secondary
     
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
            class=" w-[70vw] h-[90vh] lg:h-[95vh]  shadow-md"
          >
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center "
                >سلطة دجاج
              </Dialog.Title>
            </Dialog.Header>
            <ScrollArea class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4"
            >
            <div class=" text-sm">
              <section>
                <h2 class="text-primary font-bold py-1">المكونات:</h2>
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
              <section class="pt-3">
                <h2 class=" text-primary font-bold ">للصوص:</h2>
                <ol class="">
                  <li>- 59 جم زبادي.</li>
                  <li>- ملعقة صغيرة صوص تتبيلة فرنسية.</li>
                  <li>- عصير ليمونة.</li>
                </ol>
              </section>
              <section class="pt-3">
                <h2 class=" text-primary font-bold ">الطريقة:</h2>
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
              <section class="pt-3">
                <h2 class="text-primary font-bold ">
                  السعرات الحرارية:
                </h2>
                <p>-203 سعرة حرارية</p>
              </section>
            </div>
          </ScrollArea>
            <div class="flex justify-end items-end text-xs">
              <Button variant="ghost" href="https://www.instagram.com/daity_2?igsh=anEydm1uNXFpcmp5">
               
                <p class="px-1">
                  daity_2@</p>
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
      <img src="/l2.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              { variant: 'outline' },
            )}">سلطة التونة</Dialog.Trigger
          >
          <Dialog.Content
            class=" w-[70vw] h-[90vh] lg:h-[95vh]  shadow-md"
          >
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-primary font-bold"
                >سلطة التونة والباذنجان
              </Dialog.Title>
            </Dialog.Header>
            <ScrollArea class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4">
            <div class=" text-sm">
              <section>
                <h2 class="text-primary font-bold py-1">المكونات:</h2>
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
              <section class="pt-3">
                <h2 class=" text-primary font-bold ">الطريقة:</h2>
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
              <section class="pt-3">
                <h2 class="text-primary font-bold ">
                  السعرات الحرارية:
                </h2>
                <p>
                  - ما بين 200-300 سعرة حرارية، حسب كمية الزيت والمايونيز
                  والتونة. الخضار لا تُحسب إذا كانت الكمية قليلة.
                </p>
              </section>
            </div>
          </ScrollArea>
            <div class="flex justify-end items-end text-xs">
              <Button variant="ghost" href="https://www.instagram.com/hanaz45_35?igsh=MXc2MmN6MGJuMTN5bg==">
               
                <p class="px-1">
                  hanaz45_35@</p>
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
      <img src="/l3.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              { variant: 'outline' },
            )}">سلطة الباذنجان</Dialog.Trigger
          >
          <Dialog.Content
            class=" w-[70vw] h-[90vh] lg:h-[95vh]   shadow-md"
          >
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center "
                >سلطة الباذنجان
              </Dialog.Title>
            </Dialog.Header>
            <ScrollArea class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4">
            <div class="text-sm">
              <section>
                <h2 class="text-primary font-bold py-1">المكونات:</h2>
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
              <section class="pt-3">
                <h2 class=" text-primary font-bold ">للصوص:</h2>
                <ol class="">
                  <li>- 100 جم زبادي.</li>
                  <li>- عصرة ليمون.</li>
                  <li>- ملعقة كبيرة طحينية.</li>
                  <li>- ملح وفلفل أسود.</li>
                </ol>
              </section>
              <section class="pt-3">
                <h2 class=" text-primary font-bold ">للزينة:</h2>
                <ol class="">
                  <li>- رشة سماق.</li>
                </ol>
              </section>
              <section class="pt-3">
                <h2 class=" text-primary font-bold ">الطريقة:</h2>
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
              <section class="pt-3">
                <h2 class="text-primary font-bold ">
                  السعرات الحرارية:
                </h2>
                <p>- 390 سعرة حرارية.</p>
              </section>
            </div>
            </ScrollArea>
            <div class="flex justify-end items-end text-xs">
              <Button variant="ghost" href="https://www.instagram.com/healthrab?igsh=OG9vM3pqaGRxOTR3">
               
                <p class="px-1">
                  healthrab@</p>
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
      <img src="/l4.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              { variant: 'outline' },
            )}">سلطة منعشة</Dialog.Trigger
          >
          <Dialog.Content
            class=" w-[70vw] h-[90vh] lg:h-[95vh]  shadow-md"
          >
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center "
              >
                سلطة منعشة
              </Dialog.Title>
            </Dialog.Header>
            <ScrollArea class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4">

            <div class="  text-sm">
              <section>
                <h2 class="text-primary font-bold py-1">المكونات:</h2>
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
              <section class="pt-3">
                <h2 class=" text-primary font-bold">الطريقة:</h2>
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
              <section class="pt-3">
                <h2 class="text-primary font-bold ">
                  السعرات الحرارية:
                </h2>
                <p>- 271 سعرة حرارية.</p>
              </section>
            </div>
          </ScrollArea>
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
      <img src="/l5.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              { variant: 'outline' },
            )}">سلطة البطاطس</Dialog.Trigger
          >
          <Dialog.Content
            class=" w-[70vw] h-[90vh] lg:h-[95vh]  shadow-md"
          >
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center "
              >
                سلطة البطاطس
              </Dialog.Title>
            </Dialog.Header>
            <ScrollArea class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4">

            <div class=" text-sm">
              <section>
                <h2 class="text-primary font-bold py-1">المكونات:</h2>
                <ul>
                  <li>- 200 جم زبادي يوناني خال الدسم.</li>
                  <li>- 10 جم طحينية سائلة.</li>
                  <li>- نعناع مجفف.</li>
                  <li>- ملح.</li>
                  <li>- فلفل أسود.</li>
                  <li>- بطاطس صغيرة بقشرتها.</li>
                </ul>
              </section>
              <section class="pt-3">
                <h2 class=" text-primary font-bold ">الطريقة:</h2>
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
              <section class="pt-3">
                <h2 class="text-primary font-bold ">ملاحظة:</h2>
                <p>-يمكن إضافة سلطة من اختيارك ورمان إلى الطبق.</p>
              </section>
              <section class="pt-3">
                <h2 class="text-primary font-bold">
                  السعرات الحرارية:
                </h2>
                <p>- 349 سعرة حرارية.</p>
              </section>
            </div>
          </ScrollArea>
            <div class="flex justify-end items-end text-xs">
              <Button variant="ghost" href="https://www.instagram.com/i_smr?igsh=MXY2ejAxanlrcXZqOQ==">
               
                <p class="px-1">
                  i_smr@</p>
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
      <img src="/l6.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              { variant: 'outline' },
            )}">سلطة آسيوية</Dialog.Trigger
          >
          <Dialog.Content
            class=" w-[70vw] h-[90vh] lg:h-[90vh]   shadow-md"
          >
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center "
                >سلطة آسيوية
              </Dialog.Title>
            </Dialog.Header>
            <div class="flex justify-center items-center">
              <ScrollArea
                class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4"
              >
                <div class="  text-sm">
                  <section>
                    <h2 class="text-primary font-bold py-1">المكونات:</h2>
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
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold ">للصوص:</h2>
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
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold">الطريقة:</h2>
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
                  <section class="pt-3">
                    <h2 class="text-primary font-bold ">
                      السعرات الحرارية:
                    </h2>
                    <p>- 333 سعرة حرارية.</p>
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
      <img src="/l7.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              { variant: 'outline' },
            )}">سلطة البروكلي</Dialog.Trigger
          >
          <Dialog.Content
            class=" w-[70vw] h-[90vh] lg:h-[90vh]  shadow-md"
          >
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center "
                >سلطة البروكلي
              </Dialog.Title>
            </Dialog.Header>
            <div class="flex justify-center items-center">
              <ScrollArea
                class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4"
              >
                <div class="  text-sm">
                  <section>
                    <h2 class="text-primary font-bold pb-1">المكونات:</h2>
                    <ul>
                      <li>- رأس بروكلي.</li>
                      <li>- رأس خس.</li>
                      <li>- نصف كوب ذرة.</li>
                      <li>- 2 صدر دجاج مسحب.</li>
                    </ul>
                  </section>
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold">للصوص:</h2>
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
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold">الطريقة:</h2>
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
                  <section class="pt-3">
                    <h2 class="text-primary font-bold">
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
            <div class="flex justify-end items-end text-xs">
              <Button variant="ghost" href="https://www.instagram.com/healthymindq8?igsh=YW0ydmxwcDI2cDQ2">
               
                <p class="px-1">
                  healthymindq8@</p>
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
      <img src="/l8.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              { variant: 'outline' },
            )}">سلطة كينوا</Dialog.Trigger
          >
          <Dialog.Content
            class=" w-[70vw] h-[90vh] lg:h-[90vh]  shadow-md"
          >
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center "
                >سلطة كينوا
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
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold ">للصوص:</h2>
                    <ol class="">
                      <li>- زبادي (مخفف بماء).</li>
                      <li>- ملح.</li>
                      <li>- شوية طحينة سائلة.</li>
                    </ol>
                  </section>
                  <section class="pt-3">
                    <h2 class=" text-primary font-bold ">الطريقة:</h2>
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
                  <section class="pt-3">
                    <h2 class="text-primary font-bold ">ملاحظة:</h2>
                    <p>
                      يمكن إضافة قطع دجاج مشوية لزيادة كمية البروتين وتعزيز
                      الشبع.
                    </p>
                    <section />
                  </section>
                  <section class="pt-3">
                    <h2 class="text-primary font-bold">
                      السعرات الحرارية:
                    </h2>
                    <p>- 333 سعرة حرارية.</p>
                  </section>
                </div>
              </ScrollArea>
            </div>
            <div class="flex justify-end items-end text-xs">
              <Button variant="ghost" href="https://www.instagram.com/thedhuhaa?igsh=ODh4MXduamQ4OHlo">
               
                <p class="px-1">
                  thedhuhaa@</p>
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
