# Poyga O'yini 🏎️🏁

## Loyihaning Tavsifi

Ushbu loyihada talabalar o'zlari barcha sprite’larni (mashinalar, yo'l, to'siqlar) va fon rasmlarini yaratadilar. O'yinchi poyga mashinasini boshqarib, bir nechta yo'llardan o'tadi, to'siqlardan qochadi va belgilangan vaqt ichida poygani yakunlashga harakat qiladi. O'yinchi oldinga siljigan sari o'yinda **darajalar** paydo bo'ladi, har bir yangi daraja oldingisidan qiyinroq bo'ladi.

Ushbu loyiha talabalar ijodkorligi va dasturlash ko'nikmalarini namoyish etish imkonini beradi, shuningdek, **sprite yaratish**, **darajalarni oshirish**, **to'qnashuvni aniqlash**, va **o'yin oqimini boshqarish** kabi tushunchalarni amaliyotda qo'llashga yordam beradi.

## Asosiy Tushunchalar

- **Sprite yaratish**: Talabalar o'zlari uchun **poyga mashinasi sprite’ini**, **yo'l sprite’ini**, va o'yinda paydo bo'ladigan **to'siqlar** yoki **quvvatlar**ni yaratadilar.
- **Darajalarni oshirish**: Har bir darajada o'yin qiyinlashadi: yo'l murakkablashadi, mashina yoki to'siqlar tezlashadi, poyga uchun berilgan vaqt qisqaradi.
- **Harakat**: Talabalar poyga mashinasini **strelka tugmalari** yoki **tilt boshqaruvi** yordamida harakatlantiradilar.
- **To'qnashuvni aniqlash**: Mashina yo'ldagi to'siqlardan qochishi kerak, to'qnashsa o'yin tugaydi yoki vaqt kamayadi.
- **Ball tizimi**: Ball o'yinchi har bir darajani qancha tez tugatganiga va necha darajadan o'tganiga qarab hisoblanadi.

## Batafsil Reja

### 1. Kirish (15-20 daqiqa)
- O'yinning maqsadini tushuntiring: Poyga mashinasini boshqarish, to'siqlardan qochish va har bir poygani belgilangan vaqtda yakunlash.
- Talabalar o'zlari sprite’larni yaratishlari va har bir daraja uchun fon rasmini chizishlari haqida gapiring.
- **Darajalarni oshirish** tushunchasini tanishtiring — har bir muvaffaqiyatli poygadan so'ng o'yin qiyinlashadi.

### 2. Qadam-baqadam Ko'rsatmalar

#### Qadam 1: Poyga mashinasi sprite’ini yaratish
- Talabalar Scratch chizish vositalari yordamida yoki rasm import qilib, o'z poyga mashinalarini yaratadilar.
- `when key pressed` bloklari orqali mashinani yuqoriga, pastga, chapga, o'ngga harakatlantirish uchun kod yoziladi. Tilt boshqaruvi uchun sensor bloklari ishlatilishi mumkin.

#### Qadam 2: Yo'l va to'siqlarni yaratish
- Talabalar poyga uchun **yo'l sprite’ini** yoki bir nechta yo'l sprite’larini yaratadilar, unda boshlanish chizig'i, tugash chizig'i va burilishlar bo'ladi.
- To'siqlar (masalan, konuslar, toshlar yoki boshqa mashinalar) sprite’lari chiziladi va yo'lda joylashtiriladi.

#### Qadam 3: Darajalarni oshirish va qiyinchiliklarni ko'paytirish
- Yo'l murakkablashadi (yaqin burilishlar, ko'proq to'siqlar, tor yo'llar).
- Mashinaning tezligi yoki to'siqlarning harakat tezligi oshadi.
- Har bir daraja uchun vaqt cheklovi qo'yiladi. Vaqt tugasa o'yin tugaydi.
- Har bir darajadan so'ng `level` o'zgaruvchisi oshiriladi va o'yin qiyinlashadi.

#### Qadam 4: To'qnashuvni aniqlashni amalga oshirish
- `if <touching [to'siq]>` bloklari yordamida mashina to'siqqa teganda o'yin tugashi yoki vaqt/ball kamayishi kodlanadi.
- Yo'ldan chiqmaslik uchun chegara tekshiruvi — agar mashina chegara tashqarisiga chiqsa, o'yin tugaydi yoki qayta boshlanadi.

#### Qadam 5: Ball tizimini yaratish
- `score` o'zgaruvchisi yaratilib, o'yinchi natijasi qayd etiladi.
- Darajani tugatganda vaqt va daraja asosida ball oshiriladi.

#### Qadam 6: Taymer va o'yinni tugatish shartlari
- Har bir daraja uchun taymer qo'shiladi, ekranda ko'rsatiladi.
- Vaqt tugaganda **Game Over** ekrani chiqadi va yakuniy ball ko'rsatiladi.

### 3. O'qituvchi uchun maslahatlar
- Talabalarni yo'l dizayni va to'siqlar joylashtirishda ijodkor bo'lishga undang.
- To'qnashuvni aniqlash tizimi o'yinni qiziqarli va qiyin qilishda muhim.
- Darajalarni oshirish qiyinchilik darajasini tabiiy ravishda oshirishga yordam beradi — tezlik oshishi, ko'proq to'siq, yo'l o'zgarishi.

### 4. Ko'p uchraydigan muammolarni hal qilish

- **Muammo**: Mashina juda tez yoki sekin harakatlanmoqda.
  - **Yechim**: Harakat kodidagi qiymatlarni (`change x by`, `change y by`) o'zgartiring yoki vaqt bilan tezlik oshirishni qo'shing.
  
- **Muammo**: To'siqlar noto'g'ri harakatlanmoqda yoki klonlashda xato bor.
  - **Yechim**: To'siqlarning harakat yo'nalishi va tezligini tekshiring, `glide` yoki `move steps` bloklarini qo'llang.

- **Muammo**: Taymer har darajadan keyin qayta boshlanmayapti.
  - **Yechim**: Har yangi daraja boshida taymerni to'g'ri qiymatga tiklang.

### 5. Qo'shimcha g'oyalar

- **Quvvatlar**: Mashinaning tezligini oshiruvchi yoki himoya qiluvchi quvvatlar qo'shing.
- **Bir nechta yo'llar**: Har bir daraja uchun turli yo'l dizaynlari va fonlari yarating.
- **Reyting jadvali**: O'yinchi eng yuqori ballini saqlovchi va ko'rsatadigan leaderboard yarating.
- **Ko'p o'yinchi rejimi**: Ikkinchi o'yinchiga boshqariladigan mashina qo'shing, ular bir-biriga qarshi poyga qilishi mumkin.

## Xulosa

Ushbu loyiha orqali talabalar o'zlari yaratgan yo'lda poyga mashinasini boshqarib, to'siqlardan qochish, qiyinlashib boruvchi darajalarni bosib o'tish orqali **sprite yaratish**, **darajalarni oshirish**, **harakat**, **to'qnashuvni aniqlash** va **o'yin oqimini boshqarish** kabi asosiy tushunchalarni mustahkamlaydilar. Bu loyiha shuningdek, ularning ijodkorligini ko'rsatish imkonini beradi.

---
