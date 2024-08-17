<script>
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
      <img src="/sweets.jpg" alt="" class=" rounded-xl" />
      
      <span class="flex justify-center py-2 pr-2">
        <Dialog.Root>
          <Dialog.Trigger
            class="text-xs lg:w-[20vw] w-[18vw] lg:h-fit h-[5vh] {buttonVariants(
              { variant: 'outline' },
            )}">بودينج الشوكولاتة</Dialog.Trigger
          >
          <Dialog.Content class=" w-[70vw] h-[90vh] bg-secondary shadow-md">
            <Dialog.Header class="">
              <Dialog.Title
                class="flex justify-center text-secondary-foreground"
                >بودينج الشوكولاتة
              </Dialog.Title>
            </Dialog.Header>
            <div class=" lg:text-sm text-xs">
              <section>
                <h2 class="text-secondary-foreground py-1">المكونات:</h2>
                <p  class="text-secondary-foreground py-1">للكيك:</p>
                <ul>
                  <li>- شوفان أو دقيق أبيض: 30 جرام</li>
                  <li>- بروتين باودر: 20 جرام (أو حليب بروتين 70 جرام مع بيضة إذا رغبت في زيادة البروتين)</li>
                  <li>- باكينج باودر: 2 جرام (ربع ملعقة صغيرة)</li>
                  <li>
                    - كاكاو بودرة: 8 جرام (ملعقة صغيرة)
                  </li>
                  <li>- سكر ستيفيا: 3 أظرف</li>
                  <li>- نشا: 5 جرام</li>
                  <li>
                    - حليب خالي الدسم: ثلاث أرباع كوب تقريباً
                  </li>
                  <li>- نسكافيه: 1 جرام</li>
                  <li>- فواكه: فراولة ومزيج توت 100 جرام (نصف كوب)</li>
                  <li>- بيكان: 1 حبة</li>
                  <li>- لوز مبشور: 3 جرام</li>
                </ul>
              </section>
              <section class="py-3">
                <h2 class=" text-secondary-foreground py-1">لطريقة البودينغ:</h2>
                <ol class="">
                  <li>- كاكاو: 3 جرام
                  </li>
                  <li>- حليب: مقدار كافٍ
                  </li>
                  <li>- نسكافيه: كمية حسب الرغبة</li>
                  <li>- سكر ستيفيا: حسب الرغبة
                  </li>
                  <li>- نشا: مذاب في ماء</li>
                </ol>
              </section>
              <section class="py-3">
                <h2 class=" text-secondary-foreground py-1">الطريقة:</h2>
                <p  class="text-secondary-foreground py-1">الكيك:</p>

                <ol class="">
                  <li></li>
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
      <img src="/sw1.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class=" text-secondary-foreground text-xs w-[18vw] h-7 lg:h-fit "
        >
          ميني بانكيك
        </Button>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/sw2.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class=" text-secondary-foreground text-xs w-[20vw] h-7 lg:h-fit "
        >
          كوكيز
        </Button>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/sw3.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class=" text-secondary-foreground text-xs w-[18vw] h-7 lg:h-fit "
        >
          فاكتوريا كيك
        </Button>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/sw4.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class=" text-secondary-foreground text-xs w-[18vw] h-7 lg:h-fit "
        >
          حلى بارد
        </Button>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/sw5.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class=" text-secondary-foreground text-xs w-[18vw] h-7 lg:h-fit "
        >
          حلى الأوريو
        </Button>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/sw6.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class=" text-secondary-foreground text-xs w-[18vw] h-7 lg:h-fit "
        >
          حلى الايسكريم
        </Button>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/sw7.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class=" text-secondary-foreground text-xs w-[18vw] h-7 lg:h-fit "
        >
          مافن
        </Button>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/sw8.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class=" text-secondary-foreground text-xs  w-[18vw] h-7 lg:h-fit "
        >
          ايسكريم التوت
        </Button>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/sw9.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class=" text-secondary-foreground text-xs w-[18vw] h-7 lg:h-fit "
        >
          حلى الجيلي
        </Button>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/sw10.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class=" text-secondary-foreground text-xs w-[20vw] h-7 lg:h-fit "
        >
          لافا كيك
        </Button>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/sw11.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class=" text-secondary-foreground text-xs w-[18vw] h-7 lg:h-fit "
        >
          سينابون بانكيك
        </Button>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/sw12.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class=" text-secondary-foreground text-xs w-[18vw] h-7 lg:h-fit "
        >
          كيكة كندر
        </Button>
      </span>
    </div>
    <div class=" w-[15vw] h-auto rounded-xl">
      <img src="/sw14.jpg" alt="" class=" rounded-xl" />
      <span class="flex justify-center py-2">
        <Button
          variant="outline"
          href="/breakfast"
          class=" text-secondary-foreground text-xs w-[18vw] h-7 lg:h-fit ring"
        >
          كيكة ليمون و توت
        </Button>
      </span>
    </div>
  </div>
</div>
