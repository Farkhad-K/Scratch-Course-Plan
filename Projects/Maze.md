# Loyiha: Labirint O‘yini 🌀

## Loyiha Sharhi

**Labirint O‘yini** kursdagi eng murakkab va qiyin o‘yinlardan biridir. U kurs oxirida, o‘quvchilar Scratch va uning imkoniyatlarini yaxshi o‘zlashtirgach bajarilishi uchun mo‘ljallangan. Ushbu loyihada o‘quvchilar labirint yaratib, qahramon bilan uni aylanib o‘tib, to‘siqlardan qochib, oxirgi nuqtaga yetib borishni amalga oshiradilar.

Bu o‘yinda bir nechta tushunchalar birlashtiriladi: **to‘qnashuvni aniqlash**, **daraja dizayni**, **sprite harakati** va **o‘yin mantiqi**. Loyihaning maqsadi o‘quvchilarga Scratch yordamida murakkab va interaktiv o‘yinlar yaratishni ko‘rsatishdir. O‘quvchilar to‘liq ishlaydigan labirint yaratadilar, darajalarni sozlashlari, shuningdek, vaqt o‘lchagich, ball tizimi va quvvatlar kabi qo‘shimcha funksiyalarni qo‘shishlari mumkin.

## Asosiy Tushunchalar

- **To‘qnashuvni aniqlash**: O‘yinchi bilan devorlar orasidagi to‘qnashuvlarni aniqlash va o‘yinchi labirint chegaralariga tegsa qanday harakat qilishini boshqarish.
- **Harakatni boshqarish**: Qahramonni labirint bo‘ylab o‘q tugmalari (yoki WASD) yordamida harakatlantirish.
- **Daraja dizayni**: Labirintni devorlar, yo‘llar va boshlanish/oxir nuqtalari bilan yaratish.
- **O‘yin mantiqi**: G‘alaba shartlarini (oxiriga yetish), vaqt chegarasini va ball hisobini qo‘llash.

## Batafsil Reja

1. **Kirish (15-20 daqiqa)**
   - Loyihaning maqsadini tushuntiring: o‘quvchilar labirint o‘yini yaratadilar, qahramon labirint bo‘ylab harakat qilib, oxirgi nuqtaga yetib borishi kerak.
   - **To‘qnashuvni aniqlash** qanday ishlashini tushuntiring (o‘yinchi devorlarga teganda).
   - **Harakatni boshqarish** tizimini, ya’ni qahramonni klaviaturadagi o‘q tugmalari yoki boshqa tugmalar yordamida qanday harakatlantirishni tushuntiring.
   - Labirint dizayni va undagi **aniq yo‘llar** hamda **to‘siqlar**ning ahamiyatini ta’kidlang.

2. **Bosqichma-bosqich ko‘rsatmalar**

   - **1-bosqich**: Labirint yaratish:
     - Labirintni chizish uchun **fon rasmi**dan foydalaning yoki **rasm muharriri** yordamida devorlarni yarating.
     - Sahnaga har bir devor uchun alohida **devor sprite’lari** qo‘shing yoki oddiy fon bilan devorlar bilan to‘qnashuvni aniqlang.
   - **2-bosqich**: Qahramonni tayyorlash:
     - Foydalanuvchi boshqaradigan **o‘yinchi sprite’ini** yarating.
     - Sprite’ni labirintdagi **boshlanish nuqtasiga** joylashtiring.
     - Harakat uchun **o‘q tugmalari** yoki **WASD tugmalari** (`when key pressed` bloki) dan foydalaning.
   - **3-bosqich**: Harakat mantiqi:
     - Klaviatura kirishlariga asoslanib, qahramonning harakatini boshqarish uchun **`change x by`** va **`change y by`** bloklaridan foydalaning.
     - Qahramon devorlardan o‘tmasligi uchun harakatni cheklang (to‘qnashuvni aniqlash).
   - **4-bosqich**: To‘qnashuvni aniqlash:
     - `if <touching [wall]> then` blokidan foydalanib, o‘yinchini devorga teganda to‘xtating.
     - Istalgan holda, devorga urilganda ko‘rinish yoki ovoz effektlarini qo‘shishingiz mumkin.
   - **5-bosqich**: G‘alaba sharti:
     - Maxsus **yakun nuqtasi** (hudud yoki sprite) yarating.
     - `if <touching [finish]> then` blokidan foydalanib, o‘yinchi oxiriga yetganda g‘alaba xabarini ko‘rsating yoki ovoz chalishni sozlang.
   - **6-bosqich**: Vaqt va ball hisoblash:
     - O‘yinchi labirintni qancha vaqtda tugatishini kuzatish uchun **vaqt o‘lchagich** qo‘shing.
     - Vaqt o‘tishi bilan kamayadigan va tez tugatganlarga ball beradigan **ball o‘zgaruvchisi** yarating.
   - **7-bosqich**: Qo‘shimcha funksiyalar (ixtiyoriy):
     - Murakkabligi oshadigan bir nechta darajalar qo‘shing (katta labirintlar, ko‘proq to‘siqlar yoki vaqt cheklovlari).
     - O‘yinchini vaqtinchalik buzilmas yoki tezroq harakatlantiradigan **quvvatlar** qo‘shing.
     - O‘yinni yanada qiziqarli qilish uchun musiqa va ovoz effektlari qo‘shing.

3. **O‘qituvchiga Maslahatlar**

- **Boshlanishda oddiyroq** bo‘ling: Avval asosiy mexanizmlarni o‘rnatib, keyin qo‘shimcha funksiyalar qo‘shing.
- **To‘qnashuvni aniqlash juda muhim**: O‘yinchi devorlardan o‘tmasligini ta’minlang va devor hamda yakun nuqtalari sprite’lari to‘g‘ri sozlanganini tekshiring.
- O‘quvchilarni **darajalar bilan tajriba o‘tkazishga** rag‘batlantiring: Qancha ijodiy yondashsalar, o‘yin shuncha qiziqarli va qiyin bo‘ladi.
- Darajalar o‘rtasida yoki o‘yin tugaganda **broadcast xabarlaridan** foydalaning.
- Devorga urilishdagi muammolarni tuzatishda yordam bering — qahramon sprite’ining chegaralar ichida qolishini tekshiring.

4. **Ko‘p uchraydigan muammolar**

- **Muammo**: O‘yinchi devorlardan o‘tib ketmoqda.
  - **Yechim**: `if <touching [wall]> then` blokining to‘g‘ri ishlashini tekshiring va o‘yinchini to‘xtatish mexanizmini qayta ko‘rib chiqing.
- **Muammo**: O‘yinchi harakati silliq emas.
  - **Yechim**: `change x by` va `change y by` bloklarining to‘g‘ri ishlashini tekshiring, harakat tezligini moslashtiring.
- **Muammo**: Yakun nuqtasi aniqlanmayapti.
  - **Yechim**: Yakun hududi to‘g‘ri sozlanganligiga va `touching [finish point]` blokidan to‘g‘ri foydalanilayotganiga ishonch hosil qiling.

5. **Qo‘shimcha G‘oyalar**

- O‘quvchilar tanlay oladigan bir nechta **labirint dizaynlarini** yarating.
- Har darajadan so‘ng tasodifiy yaratiladigan **labirintlar** qo‘shing.
- Labirint bo‘ylab harakatlanuvchi dushmanlar yoki to‘siqlar qo‘shing, bu o‘yinni qiyinlashtiradi.
- O‘yinchilarga labirintni ma’lum vaqt ichida tugatishni talab qiluvchi **vaqt o‘lchagich** qo‘shing.
- Har bir darajani tugatganda ball beruvchi va yuqori ballarni yozib boruvchi **ball tizimi** yaratish.

## Xulosa

Ushbu loyiha yakunida o‘quvchilar Scratch’da murakkab o‘zaro ta’sirlar va o‘yin mexanizmlarini yaratish qobiliyatini namoyish qiluvchi to‘liq ishlaydigan labirint o‘yinini yaratadilar. Ular **to‘qnashuvni aniqlash**, **harakatni boshqarish**, **daraja dizayni** va **o‘yin mantiqi** kabi asosiy ko‘nikmalarga ega bo‘ladilar — bu ko‘nikmalar keyingi rivojlangan o‘yinlarni yaratishda juda foydali bo‘ladi.

---

### **Eslatma**: **Labirint O‘yini** kurs davomida o‘rganilgan barcha ko‘nikmalarning mukammal yakunidir. U o‘quvchilardan ijodkorlik va muammolarni hal qilish ko‘nikmalarini ishga solishni talab qiladi hamda Scratch yordamida murakkab va real o‘yinlarni yaratish imkoniyatlarini ko‘rsatadi.
