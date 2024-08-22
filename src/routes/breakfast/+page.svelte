<script lang="ts">
	import { dictionary } from './../../../.svelte-kit/generated/client/app.js';
  import { buttonVariants } from "$lib/components/ui/button";
  import Button from "$lib/components/ui/button/button.svelte";
  import * as Dialog from "$lib/components/ui/dialog";
    import { ScrollArea } from "$lib/components/ui/scroll-area/index.js";

</script>

<div class="flex flex-col items-center  pb-20">
  <div
    class=" min-w-[18rem]  lg:gap-8 bg-gradient-to-r from-background/90 to-primary/50 dark:bg-primary shadow-[0_30px_80px_-15px_rgba(0,0,0,0.4)] 
       ring-1 ring-secondary
     rounded-xl grid grid-cols-3 gap-9 p-6  "
  >
    <div class=" max-w-[5rem] lg:max-w-[12rem] h-auto rounded-xl"> 
      <img src="/b3.PNG" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[20vw]   {buttonVariants(
              { variant: 'outline' },
            )}">سكرمبل الشوفان</Dialog.Trigger
          >
          <Dialog.Content
          >
            <Dialog.Header >
              <Dialog.Title
                class="flex justify-center "
                >سكرمبل الشوفان
              </Dialog.Title>
            </Dialog.Header>
           <ScrollArea class=" w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh] rounded-md p-4">
            <div class=" text-sm">
              <section>
                <h2 class="text-primary font-bold  py-1">المكونات:</h2>
                <ul>
                  <li>- 30 جم شوفان (أو 4 ملاعق).</li>
                  <li>- 180 جم زبادي يوناني (أو 4 ملاعق كبيرة ممتلئة).</li>
                  <li>-71 جم بياض بيض</li>
                  <li>
                    - 18 جم صفار بيض =(من بيضتين: بياض بيضة كاملة وصفار بيضة)
                  </li>
                  <li>-محلي فانيليا</li>
                  <li>-100 جم  توت</li>
                  <li>
                    - (اختياري) 12 جم زبدة فول سوداني قليلة السعرات (أو ملعقة
                    صغيرة)
                  </li>
                </ul>
              </section>
              <section class="py-3">
                <h2 class=" text-primary font-bold py-1">الطريقة:</h2>
                <ol class="">
                  <li>
                    1. في وعاء، اخلط البيض، الشوفان، 30 جم من الزبادي اليوناني،
                    القرفة، والمحلي.
                  </li>
                  <li>
                    2. اطبخ الخليط على الصاج من الجهتين، ثم قطّعه إلى قطع
                    عشوائية.
                  </li>
                  <li>
                    3. في صحن التقديم، ضع 150 جم زبادي يوناني مع محلي حسب
                    الرغبة.
                  </li>
                  <li>
                    4. أضف قطع الشوفان التي حضرتها، والفواكه، وزبدة الفول
                    السوداني إذا كنت تستخدمها.
                  </li>
                </ol>
              </section>
              <section class="py-4">
                <h2 class="text-primary font-bold py-1">
                  السعرات الحرارية:
                </h2>
                <p>-388 سعرة حرارية</p>
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
    <div class=" max-w-[5rem] lg:max-w-[12rem] h-auto  rounded-xl">
      <img src="/b4.JPG" alt="" class=" rounded-xl " />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:h-fit  {buttonVariants(
              { variant: 'outline' },
            )}">شكشوكة تركية</Dialog.Trigger
          >
          <Dialog.Content class="  shadow-md">
            <Dialog.Header>
              <Dialog.Title
                class="flex justify-center "
                >شكشوكة تركية
              </Dialog.Title>
            </Dialog.Header>
            <ScrollArea class=" w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh] rounded-md p-4">

            <div class=" text-sm ">
              <section>
                <h2 class="text-primary font-bold  ">المكونات:</h2>
                <ul>
                  <li>- 120 جم طماطم حجم وسط.</li>
                  <li>- 25 جم بصل (ربع بصلة).</li>
                  <li>- 16 جم معجون طماطم.</li>
                  <li>- 44 جم بيضة.</li>
                  <li>- 1 شريحة توست عالية بالبروتين (185 سعرة حرارية).</li>
                </ul>
              </section>
              <section class="py-2">
                <h2 class=" text-primary font-bold">الطريقة:</h2>
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
                <h2 class="text-primary font-bold">السعرات الحرارية :</h2>
                -292 سعرة حرارية
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

    <div class=" max-w-[5rem] lg:max-w-[12rem] h-auto rounded-xl">
      <img src="/b1.PNG" alt="" class=" rounded-xl" />

      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit  {buttonVariants(
              { variant: 'outline' },
            )}"
          >
            شوفان وبروتين</Dialog.Trigger
          >
          <Dialog.Content class="  shadow-md">
            <Dialog.Header>
              <Dialog.Title>شوفان وبروتين</Dialog.Title>
            </Dialog.Header>
            <ScrollArea>
            <div class="  text-sm">
              <section>
                <h2 class="text-primary font-bold">المكونات:</h2>
                <ul>
                  <li>- 40 جم شوفان كامل الحبة.</li>
                  <li>- 30 جم بروتين باودر.</li>
                  <li>- 3 جم كاكاو باودر.</li>
                  <li>- 38 جم توت.</li>
                  <li>- 20 جم زبادي يوناني.</li>
                </ul>
              </section>
              <section class="py-2">
                <h2 class=" text-primary font-bold">الطريقة:</h2>
                <ol class="">
                  <li>
                    1.ضع الشوفان في وعاء وأضف ضعف الكمية ماء. سخنه في الميكروويف
                    لمدة دقيقة.
                  </li>
                  <li>
                    2. في وعاء آخر، اخلط البروتين باودر، كاكاو باودر، وسكر
                    ستيفيا و (بنفس كمية البروتين) أضف 30 مل ماء واخلط جيدًا
                  </li>
                  <li>3. أضف الخليط إلى الشوفان وامزج جيدًا.</li>
                  <li>4. زين الطبق بالزبادي اليوناني والتوت الأحمر.</li>
                </ol>
              </section>
              <section class="">
                <h2 class="text-primary font-bold">السعرات الحرارية:</h2>
                <p>- 320 سعرة حرارية.</p>
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
    <div class=" max-w-[5rem] lg:max-w-[12rem] h-auto rounded-xl">
      <img src="/b7.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit  {buttonVariants(
              { variant: 'outline' },
            )}"
          >
            فرنش توست</Dialog.Trigger
          >
          <Dialog.Content class=" shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center "
                >فرنش توست مالح
              </Dialog.Title>
            </Dialog.Header>
          <ScrollArea>
            <div class=" text-sm">
              <section>
                <h2 class="text-primary font-bold">المكونات:</h2>
                <ul>
                  <li>- 3 شرائح توست (90 جم).</li>
                  <li>
                    - بيضتين (واحدة بياض بيضة والأخرى كاملة) [66 جم بياض، 20 جم
                    صفار].
                  </li>
                  <li>
                    - ربع كوب (50 جم) حليب بروتين أو أي حليب متوفر (استخدمت حليب
                    نادك السادة عالي البروتين).
                  </li>
                  <li>- 60 جم حلوم.</li>
                  <li>- ملعقتين (20 جم) جبن موزاريلا لايت.</li>
                </ul>
              </section>
              <section class="py-3">
                <h2 class=" text-primary font-bold">الطريقة:</h2>
                <ol class="">
                  <li>1. اخفق البيض مع الحليب، وأضف الزعتر والملح.</li>
                  <li>
                    2. غمس شرائح التوست في خليط البيض والحليب، ثم اطهها على
                    الصاج من جميع الجوانب.
                  </li>
                  <li>
                    3. حمّص الحلوم في مقلاة أو اسلقه حسب تفضيلك، أو يمكنك وضعه
                    على التوست الساخن حتى يذوب.
                  </li>
                  <li>
                    4. رشّ الجبن الموزاريلا على التوست الساخن واتركه يذوب.
                  </li>
                  <li>5. زين الطبق بالطماطم والنعناع.</li>
                </ol>
              </section>
              <h2 class="text-primary font-bold">السعرات الحرارية:</h2>
              <p>- 555 سعرة حرارية.</p>
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
    <div class=" max-w-[5rem] lg:max-w-[12rem] h-auto rounded-xl">
      <img src="/b5.JPG" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit  {buttonVariants(
              { variant: 'outline' },
            )}"
          >
            ساندوتش بيض
          </Dialog.Trigger>
          <Dialog.Content class="  shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center "
                >ساندوتش بيض
              </Dialog.Title>
            </Dialog.Header>
          <ScrollArea>
            <div class=" text-sm">
              <section>
                <h2 class="text-primary font-bold">المكونات:</h2>
                <ul>
                  <li>-58 جم توست أسمر.</li>
                  <li>- 148 جم بياض 4 بيضات أو 2 بيض كامل.</li>
                  <li>- 50 جم  بيضة.</li>
                  <li>- 19 جم شريحة جبن قليل الدسم.</li>
                  <li>- 60 جم سبانخ.</li>
                  <li>- 2 فص ثوم.</li>
                  <li>
                    - (اختياري) 60 جم سبانخ إضافية، 35 جم طماطم، 32 جم جزر.
                  </li>
                </ul>
              </section>
              <section class="py-3">
                <h2 class=" text-primary font-bold">الطريقة:</h2>
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
              <h2 class="text-primary font-bold">السعرات الحرارية:</h2>
              <p>- 377 سعرة حرارية.</p>
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
    <div class=" max-w-[5rem] lg:max-w-[12rem] h-auto rounded-xl">
      <img src="/b2.JPG" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit  {buttonVariants(
              { variant: 'outline' },
            )}"
          >
            بانكيك
          </Dialog.Trigger>
          <Dialog.Content class="  shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center "
                >بانكيك
              </Dialog.Title>
            </Dialog.Header>
            <ScrollArea
                class="w-[65vw] h-[70vh] lg:w-[35vw] lg-h[90vh]  rounded-md p-4"
              >
            <div class=" text-sm">
              <section>
                <h2 class="text-primary font-bold">المكونات:</h2>
                <ul>
                  <li>- 50 جم شوفان مطحون (حوالي 5 ملاعق).</li>
                  <li>- ربع ملعقة صغيرة باكينج باودر (3 جم).</li>
                  <li>- 150 مل لبن سائل (علبة صغيرة).</li>
                  <li>- 37 جم بياض بيضة.</li>
                  <li>- ربع ملعقة صغيرة باكينج باودر (3 جم).</li>
                  <li>- سكوب وربع بروتين فانيليا</li>
                </ul> 
              </section>
              <section class="py-3">
                <h2 class=" text-primary font-bold">الطريقة:</h2>
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
                  <h2 class=" text-primary font-bold">الإضافات:</h2>
                  <h3 class=" text-primary font-bold">الصوص الأبيض:</h3>
                  <p>-
                    زبادي يوناني + محلي فانيلا خالي السعرات أو ظرف سكر ستيفيا.
                    الطعم يشبه الطبقة البيضاء في التشيز كيك.
                  </p>
                  <p>- 34 جم توت أزرق</p>
                </section>
              </section>
              <h2 class="text-primary font-bold">السعرات الحرارية:</h2>
              <p>- بدون الإضافات: 411 سعرة حرارية.</p>
              <p>- مع الإضافات: 472 سعرة حرارية.</p>
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
          </ScrollArea>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
    <div class=" max-w-[5rem] lg:max-w-[12rem] h-auto rounded-xl">
      <img src="/b6.JPG" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit  {buttonVariants(
              { variant: 'outline' },
            )}">أفكار للتوست</Dialog.Trigger
          >
          <Dialog.Content class=" shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center"
                >أفكار للتوست
              </Dialog.Title>
            </Dialog.Header>
            <ScrollArea>
            <div class="  text-sm">
              <section>
                <h2 class="text-primary font-bold">شريحة البيض:</h2>
                <ul>
                  <li>- 30 جم زبادي يوناني سادة قليل الدسم.</li>
                  <li>- 42 جم بيض مسلوق أو بطريقة بنديكت.</li>
                  <li>- 2 جم فص ثوم.</li>
                  <li>- 2 جم فلفل هلابينو (حبة صغيرة).</li>
                  <li>- بهارات: فلفل مجروش، فلفل أسود، وكيجون.</li>
                </ul>
              </section>
              <div class="py-3">
                <h2 class="text-primary font-bold">السعرات الحرارية:</h2>
                <p>- 153 سعرة حرارية.</p>
              </div>
              <section class="py-1">
                <h2 class=" text-primary font-bold">
                  شريحة الزبادي اليوناني:
                </h2>
                <ol class="">
                  <li>- 30 جم زبادي يوناني بالتوت قليل الدسم.</li>
                  <li>- 24 جم زبادي يوناني سادة قليل الدسم.</li>
                </ol>
              </section>
              <div class="py-2">
                <h2 class="text-primary font-bold">السعرات الحرارية:</h2>
                <p>- 113 سعرة حرارية.</p>
              </div>
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
    <div class=" max-w-[5rem] lg:max-w-[12rem] h-auto rounded-xl">
      <img src="/b8.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit  {buttonVariants(
              { variant: 'outline' },
            )}"
          >
            بانكيك غير</Dialog.Trigger
          >
          <Dialog.Content class="  shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center -"
                >بانكيك زبدة الفول السوداني
              </Dialog.Title>
            </Dialog.Header>
          <ScrollArea>
            <div class="text-sm ">
              <section>
                <h2 class="text-primary font-bold">المكونات:</h2>
                <ul>
                  <li>- كوب شوفان مطحون.</li>
                  <li>- ملعقة كبيرة عسل.</li>
                  <li>- ملعقة كبيرة زبدة فول سوداني.</li>
                  <li>- بيضة.</li>
                  <li>- ربع كوب حليب (تقريبًا).</li>
                  <li>- ملعقة صغيرة قرفة.</li>
                  <li>- ملعقة صغيرة بايكنج باودر.</li>
                </ul>
              </section>
              <section class="py-3">
                <h2 class=" text-primary font-bold">الطريقة:</h2>
                <ol>
                  <li>1. اخلط جميع المكونات معًا حتى تتجانس.</li>
                  <li>
                    2. أضف الحليب تدريجيًا حتى تحصل على قوام شبه ثقيل ومتجانس.
                  </li>
                  <li>
                    3. اطهُ البانكيك على مقلاة غير لاصقة حتى ينضج من الجانبين.
                  </li>
                  <li>
                    4.أضف عسل حسب الرغبة واحسب سعراته مع المجموع
                  </li>
                </ol>
              </section>
              <h2 class="text-primary font-bold">السعرات الحرارية:</h2>
              <p>-570 سعرة حرارية .</p>
            </div>
          </ScrollArea>
           
            <div class="flex justify-end items-end text-xs">
              
            </div>
          </Dialog.Content>
        </Dialog.Root>
      </span>
    </div>
  </div>
</div>
