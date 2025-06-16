# Project : Jump Chick 🐣

## Loyiha Sharhi

Ushbu loyihada o‘quvchilar oddiy sakrovchi o‘yin yaratadilar, unda asosiy qahramon — tovuqcha, ekranning yuqorisidan tushayotgan tuxumlardan sakrab o‘tishi kerak bo‘ladi. O‘yin **Chrome Dino** o‘yinidan ilhomlangan, lekin ancha sodda. Loyihaning maqsadi — **to‘qnashuvni aniqlash**, **klaviatura tugmalariga javob berish** va **harakat nazorati** kabi asosiy o‘yin mexanizmlarini **Scratch** orqali o‘rgatishdir.

O‘quvchilar **`forever`**, **`if`**, va **`key [space] pressed`** bloklaridan foydalanishni o‘rganib, o‘yinni yanada jonli qilishadi. Loyiha, shuningdek, **sprite’lar**dan samarali foydalanishga urg‘u beradi — tovuqcha va tuxum o‘yinning asosiy interaktiv elementlari bo‘ladi.

## Asosiy Tushunchalar

- **Forever sikli**: O‘quvchilarga o‘yinni doimiy ishlashi uchun `forever` blokidan foydalanishni o‘rgating.
- **If sharti**: Tovuqchaning bo‘sh joy tugmasini bosib, sakrashini aniqlash uchun `if` blokidan foydalaning.
- **To‘qnashuvni aniqlash**: Tovuqcha bilan tuxum to‘qnashganini aniqlashni ko‘rsating.
- **Bo‘sh joy tugmasi bosilganda**: Tovuqchaning sakrashi uchun `key [space] pressed?` (sensing blokidan) blokini tanishtiring.

## Batafsil Reja

1. **Kirish (10-15 daqiqa)**
   - Loyihaning maqsadini tushuntiring: tovuqcha tuxumlardan sakrab o‘tishi kerak bo‘lgan o‘yin yaratish.
   - O‘yin mexanizmlari — sakrash va tuxum bilan to‘qnashuvni aniqlash haqida gapiring.
   - Scratch’dagi **forever sikli** va **if shartlari**ni tanishtiring.

2. **Bosqichma-bosqich ko‘rsatmalar**

   - **1-bosqich**: Ikki sprite yarating:
     - Yuqoriga-pastga harakatlanadigan **tovuqcha** sprite’i.
     - Ekranning yuqorisidan tushadigan **tuxum** sprite’i.
   - **2-bosqich**: Tovuqcha va tuxumni boshlang‘ich joylariga joylashtiring.
     - Tovuqchani ekran pastiga qo‘ying.
     - Tuxumni ekranning yuqorisida tasodifiy joyda qo‘ying.
   - **3-bosqich**: Tovuqchaning sakrash mexanizmini sozlang:
     - `forever` sikli ichida `if <key [space] pressed?> then` blokidan foydalanib, bo‘sh joy tugmasi bosilganda tovuqchani yuqoriga harakatlantiring.
     - `change y by [qiymat]` blokidan foydalanib, sakrashni simulyatsiya qiling.
     - `forever` va `if` bloklari kombinatsiyasining `when [space] key pressed` blokidan tezroq ishlashini tushuntiring.
   - **4-bosqich**: Tuxumni tushiring:
     - Tuxum doimiy tushishi uchun `forever` siklidan foydalaning.
     - `change y by [-10]` blokini tuxumni pastga harakatlantirish uchun qo‘llang.
     - Tuxum yerga teganda, uni yana yuqoriga, tasodifiy joyga qaytarib qo‘ying.
   - **5-bosqich**: To‘qnashuvni aniqlash:
     - `if <touching [chick]> then` blokidan tuxum bilan tovuqchaning to‘qnashishini aniqlash uchun foydalaning.
     - To‘qnashuv aniqlansa, o‘yinni tugating yoki "Game Over" xabarini ko‘rsating.
   - **6-bosqich**: Oddiy ball hisobini qo‘shing:
     - Tovuqcha nechta tuxumdan muvaffaqiyatli qochganini hisoblash uchun o‘zgaruvchi yarating.
     - Har safar tuxum o‘tib ketganda ballni oshiring.

3. **O‘qituvchiga Maslahatlar**

- Loyihada **forever siklining** qanday ishlashini va nima uchun `key [space] pressed` blokini `when [space] key pressed` blokidan ustunroq ishlatish kerakligini tushuntiring.
- O‘quvchilarga **to‘qnashuvni aniqlash**ning o‘yin uchun ahamiyatini tushuntiring.
- Tuxumning tushish tezligi, tovuqchaning sakrash balandligini va o‘yin qiyinligini o‘zgartirib ko‘rishga rag‘batlantiring.

4. **Ko‘p uchraydigan muammolar**

- **Muammo**: Tovuqcha sekin sakrayapti yoki kech javob bermoqda.
  - **Yechim**: `forever` va `if` bloklari kombinatsiyasi `when [space] key pressed` blokidan tezroq ekanini ko‘rsating va sakrash tezligini oshiring.
- **Muammo**: Tuxum to‘g‘ri tushmayapti yoki tiklanmayapti.
  - **Yechim**: Tuxum sprite’ining boshlang‘ich joyi to‘g‘ri o‘rnatilganini va pastga yetganda tasodifiy joyga qaytarilayotganini tekshiring.
- **Muammo**: Tovuqcha tuxum bilan to‘qnashuvni aniqlamayapti.
  - **Yechim**: To‘qnashuvni aniqlash bloki (`if touching [egg] then`) to‘g‘ri ishlashiga va tuxum sprite’i tovuqchaga tegishiga ishonch hosil qiling.

5. **Qo‘shimcha G‘oyalar**

- Tovuqcha tuxum ustidan sakraganida ball oshadigan **ball hisoblagich** qo‘shing.
- Tuxum tushish tezligi oshib boradigan **bir nechta darajalar** qo‘shing.
- Tovuqcha sakraganda yoki o‘yin tugaganda **ovoz effektlari** qo‘shing.
- Tovuqchaning o‘ng va chapga harakatlanishini **o‘q tugmalari** yordamida qo‘shing, shunda tuxumlardan yaxshiroq qochish mumkin bo‘ladi.

## Xulosa

Ushbu loyiha oxirida o‘quvchilar oddiy va qiziqarli sakrovchi o‘yin yaratgan bo‘ladilar, unda tovuqchaning sakrashini nazorat qilib, tushayotgan tuxumlardan qochish mumkin bo‘ladi. Loyihada **forever sikli**, **if shartlari** va klaviatura tugmalari hodisalari orqali interaktiv o‘yin yaratish o‘rgatiladi. Shuningdek, o‘quvchilar to‘qnashuvni aniqlash va asosiy o‘yin mexanizmlari haqida chuqurroq bilimga ega bo‘ladilar.

---
