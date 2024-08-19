<script lang="ts">
  import { buttonVariants } from "$lib/components/ui/button";
  import Button from "$lib/components/ui/button/button.svelte";
  import * as Dialog from "$lib/components/ui/dialog";
  import { ScrollArea } from "$lib/components/ui/scroll-area/index.js";
</script>

<div class="flex flex-col items-center pb-20">
  <div
    class="
    lg:h-fit w-auto ring-1 ring-secondary  lg:p-10 lg:gap-16 lg:gap-y-4  bg-gradient-to-r from-background/90 to-primary/50 dark:bg-primary shadow-[0_20px_60px_-15px_rgba(0,0,0,0.7)] rounded-xl
      p-6 grid grid-cols-3 gap-5 gap-y-6
     justify-items-center"
  >
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/snacks.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}">كرات التمر</Dialog.Trigger
          >
          <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >كرات التمر
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
                      <li>- 160 جم تمر معجون.</li>
                      <li>- 30 جم كاجو.</li>
                      <li>- 20 جم جوز هند.</li>
                      <li>- ملعقة كبيرة زبدة فول سوداني (حوالي 32 جم).</li>
                      <li>- رشة هيل مطحون.</li>
                      <li></li>
                      <li>- 40 جرام دقيق أو شوفان مطحون</li>
                      <li>- رشة ملح</li>
                      <li>- 15 جرام شوكولاتة</li>
                    </ul>
                  </section>
                  <section class="py-2">
                    <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
                    <ol class="">
                      <li>
                        1. ضع جميع المكونات في محضرة الطعام واخلطها حتى تتجانس.
                      </li>
                      <li>
                        2. شكّل الخليط إلى كرات متساوية الحجم. يمكنك صنع حوالي
                        16 كرة.
                      </li>
                      <li>3. زين الكرات بزبدة الفول السوداني وجوز الهند.</li>
                    </ol>
                  </section>
                  <section class="py-2">
                    <h2 class="text-secondary-foreground py-1">
                      السعرات الحرارية:
                    </h2>
                    <p>- السعرات الحرارية لكل كرة: 58 سعرة حرارية.</p>
                    <p>- السعرات الحرارية للكمية الكاملة: 937 سعرة حرارية.</p>
                  </section>
                </div>
              </ScrollArea>
            </div>
            <div class="flex justify-end items-end text-xs">
              <Button variant="ghost" href="https://www.instagram.com/diet.marwa.2018?igsh=MTVzZmUwMnAxczRk">
               
                <p class="px-1">
                  diet.marwa.2018@</p>
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
      <img src="/s5.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[14vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}">كرات الحلوى</Dialog.Trigger
          >
          <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >كرات الحلوى
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
                      <li>- شوفان مطحون.</li>
                      <li>- زبدة فول سوداني.</li>
                      <li>- جوز هند مبشور.</li>
                      <li>- شوكولاتة داكنة.</li>
                      <li>- سكر ستيفيا أو عسل.</li>
                    </ul>
                  </section>
                  <section class="py-2">
                    <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
                    <ol class="">
                      <li>1. اخلط جميع المكونات معًا حتى تتجانس.</li>
                      <li>2. شكّل الخليط إلى كرات صغيرة.</li>
                      <li>
                        3. زين الكرات بالشوكولاتة الداكنة أو نوتيلا صحية.
                        البيكربونات، والملح وامزج حتى تتجانس المكونات.
                      </li>
                    </ol>
                  </section>
                  <section class="py-2">
                    <h2 class="text-secondary-foreground py-1">ملاحظة :</h2>
                    <p>
                      يمكنك تعديل كميات المكونات حسب رغبتك للحصول على الكمية
                      التي تريدها.
                    </p>
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
      <img src="/s4.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[14vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}">شوكولاتة دارك</Dialog.Trigger
          >
          <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >شوكولاتة دارك
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
                        - 21 حبة مكسرات (اخترت 3 أنواع: 7 حبات من كل نوع).
                      </li>
                      <li>- جوز.</li>
                      <li>- بيكان.</li>
                      <li>- لوز.</li>
                      <li>- شوكولاتة داكنة.</li>
                      <li>- رشة ملح.</li>
                    </ul>
                  </section>
                  <section class="py-2">
                    <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
                    <ol class="">
                      <li>
                        1. ذوّب الشوكولاتة في الميكروويف لمدة دقيقة ونصف. تأكد
                        من إخراجها كل 30 ثانية لتحريكها.
                      </li>
                      <li>2. غطِّ حبات الجوز بالشوكولاتة، ثم ضعها في صحن.</li>
                      <li>
                        3. غطِّ حبات البيكان بالشوكولاتة وأضفها إلى الجوز.
                      </li>
                      <li>
                        4. أخيرًا، غطِّ حبات اللوز بالشوكولاتة وأضفها إلى باقي
                        المكسرات.
                      </li>
                      <li>5. كرر العملية حتى تنتهي الكمية.</li>
                      <li>6. في النهاية، رشّ الملح على المكسرات.</li>
                      <li>
                        7. ضعها في الفريزر أو الثلاجة لبضع دقائق حتى تتماسك
                        أكثر.
                      </li>
                    </ol>
                  </section>
                  <section class="py-2">
                    <h2 class="text-secondary-foreground py-1">
                      السعرات الحرارية: :
                    </h2>
                    <p>
                      - سعرات المجموعة الواحدة (3 حبات مكسرات): 50 - 60 سعرة
                      حرارية، حسب نوع المكسرات والشوكولاتة المستخدمة.
                    </p>
                  </section>
                </div>
              </ScrollArea>
            </div>
            <div class="flex justify-end items-end text-xs">
              <Button variant="ghost" href="https://www.instagram.com/360better?igsh=d3ZhcXNlZTNtMzJ5">
               
                <p class="px-1">
                  360better@</p>
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
      <img src="/s2.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[14vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}">بليلة</Dialog.Trigger
          >
          <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >بليلة
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
                      <li>- نصف كوب حمص مسلوق.</li>
                      <li>- بهارات (ملح / فلفل أسود / كمون).</li>
                      <li>- ملعقة كبيرة خل.</li>
                      <li>- عصرة ليمون.</li>
                      <li>- كوب ماء.</li>
                      <li>
                        - كمية صغيرة من ملون الطعام أو قطع شمندر للحصول على
                        اللون.
                      </li>
                    </ul>
                  </section>
                  <section class="py-2">
                    <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
                    <ol class="">
                      <li>1. قطع الخيار وضعه في صحن.</li>
                      <li>
                        2. أضف الماء، ملون الطعام (أو الشمندر)، الخل، وعصرة
                        الليمون إلى الخيار.
                      </li>
                      <li>
                        3. اترك الخليط في الثلاجة لمدة 7 إلى 10 ساعات ليتخلل.
                      </li>
                      <li>
                        4. عند التقديم، ضع الحمص المسلوق في صحن، ثم أضف الخيار
                        المخلل فوقه.
                      </li>
                      <li>5. رش البهارات وأضف عصرة ليمون إضافية إذا رغبت.</li>
                    </ol>
                  </section>
                </div>
              </ScrollArea>
            </div>
            <div class="flex justify-end items-end text-xs">
              <Button variant="ghost" href="https://www.instagram.com/nada_helthy?igsh=b3RzM2V4dzY3NmFx">
               
                <p class="px-1">
                  nada_helthy@</p>
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
      <img src="/s7.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[14vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}">بطاطس</Dialog.Trigger
          >
          <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >بطاطس
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
                      <li>- 228 جم بطاطس.</li>
                    </ul>
                  </section>
                  <section class="py-2">
                    <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
                    <ol class="">
                      <li>1. قشر البطاطس وقطعها بالشكل الذي تريده.</li>
                      <li>2. اسلق البطاطس لمدة 7-10 دقائق</li>
                      <li>
                        3. صفِّ البطاطس إذا كنت قد سلقته، ثم أضف التوابل التي
                        تفضلها. يُفضل استخدام بودرة الثوم والبصل لإضافة قرمشة
                        رائعة.
                      </li>
                      <li>
                        4. ضع البطاطس في القلاية الهوائية لمدة 15 دقيقة على درجة
                        حرارة 200 مئوية. في منتصف الوقت، اخرج البطاطس وقلبها،
                        خاصة إذا كانت القلاية الهوائية لا تدور، لضمان نضوجها من
                        جميع الجهات. ثم أعدها لتكمل الوقت المتبقي.
                      </li>
                    </ol>
                  </section>
                  <section class="py-2">
                    <h2 class="text-secondary-foreground py-1">
                      السعرات الحرارية: :
                    </h2>
                    <p>- إجمالي السعرات: 182 سعرة حرارية.</p>
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
      <img src="/s3.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[17vw] lg:h-fit h-[5vh] {buttonVariants(
              {
                variant: 'outline',
              },
            )}">شوكولاتة و فراولة</Dialog.Trigger
          >
          <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >شوكولاتة و فراولة
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
                      <li>- 141 جم توت أو فراولة، أي نوع متوفر.</li>
                      <li>- علبة زبادي يوناني قليل الدسم (149 جم).</li>
                      <li>- 33 جم شوكولاتة غامقة (3 قطع).</li>
                      <li>- 36 مل حليب قليل الدسم.</li>
                    </ul>
                  </section>
                  <section class="py-2">
                    <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
                    <ol class="">
                      <li>
                        1. أضف ظرف سكر ستيفيا إلى علبة الزبادي اليوناني.                      </li>
                      <li>
                        2. أضف التوت أو الفراولة إلى الزبادي، وقلّب الخليط جيدًا.
                      </li>
                      <li>
                        3. ضع الخليط في صينية مغطاة بورق زبدة، ثم قسمه إلى قطع.
                      </li>
                      <li>
                        4. ضع الصينية في الفريزر حتى تتجمد القطع. </li>
                    </ol>
                  </section>
                  <section class="py-2">
                    <h2 class="text-secondary-foreground py-1">
                      السعرات الحرارية: :
                    </h2>
                    <p>- إجمالي السعرات: 368  سعرة حرارية.</p>
                    <p>- السعرات الحرارية لكل قطعة: 74 سعرة حرارية.</p>
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
