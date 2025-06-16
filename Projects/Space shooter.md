# Space Shooter 🚀🌑

## Loyihaning Tavsifi

Ushbu loyihada talabalar **Space Shooter** o‘yinini yaratadilar, bunda o‘yinchi kosmik raketkani boshqaradi va tushayotgan toshlardan qochishi kerak bo‘ladi. O‘yin vertikal aylantirishga ega bo‘lib, o‘yinchi to‘siqlardan qocharkan, ekran pastga harakatlanadi. O‘yinning maqsadi – tushayotgan toshlardan imkon qadar uzoqroq yashab qolish va har soniya uchun ball olish.

Bu o‘yin talabalar uchun hozirgacha o‘rgangan barcha **kod bloklari**ni takrorlash va takomillashtirish mashqi bo‘ladi, jumladan:

- **Harakat va boshqarish**: Raketkani strelka tugmalari bilan harakatlantirish.
- **Tasodifiylik**: Toshlarning tasodifiy joylashuvi va tezlikda tushishi.
- **To‘qnashuvni aniqlash**: Raketka va tosh o‘rtasida to‘qnashuvni aniqlash.
- **Ball tizimi**: O‘yinchi qancha vaqt yashab qolganini hisoblash.
- **Klonlash**: Ko‘p toshlarni yaratish.

## Asosiy Tushunchalar

- **Harakat**: Raketkani strelka tugmalari yordamida boshqarish uchun `when key pressed` bloklaridan foydalanish.
- **Tasodifiylik**: Toshlarning tezligi, joylashuvi va paydo bo‘lish tezligini tasodifiylashtirish uchun `pick random` blokidan foydalanish.
- **To‘qnashuvni aniqlash**: `if <touching [rock]>` bloklari yordamida to‘qnashuvni aniqlash.
- **Klonlash**: Ko‘p toshlarni yaratish uchun klonlashdan foydalanish.
- **Ball tizimi**: O‘yinchi yashab qolgan vaqtni hisoblash.
- **O‘yin jarayoni**: Raketka toshga teganda o‘yinni to‘xtatish va **Game Over** ko‘rsatish.

## Batafsil Reja

### 1. Kirish (10-15 daqiqa)
- O‘yin maqsadini tushuntirish: raketkani boshqarib, tushayotgan toshlardan qochish.
- O‘yinda **harakat**, **to‘qnashuvni aniqlash**, **tasodifiylik** va **klonlash** qanday ishlashini tushuntirish.

### 2. Qadam-baqadam ko‘rsatmalar

#### Qadam 1: Raketka sprite’ini yaratish
- O‘yinchi boshqaradigan **raketka sprite**ini yaratish.
- Raketkani chap va o‘ngga harakatlantirish uchun `when key pressed` bloklaridan foydalanish.
- Raketkaning vertikal harakatini `y` pozitsiyasini cheklash orqali o‘yin maydonida ushlab turish.

#### Qadam 2: Tosh sprite’ini yaratish
- Ekranning yuqorisidan tushadigan **tosh sprite**ini yaratish.
- `create clone of [myself]` blokini ishlatib ko‘p toshlarni yaratish.
- `go to x: [pick random] y: [pick random]` bloklari yordamida toshlarni tasodifiy gorizontal joylashuvda va ekran tashqarisidagi vertikal balandliklarda paydo qilish.

#### Qadam 3: Toshlarni tushirish
- Toshlarni tushirish uchun `glide` yoki `change y by` bloklaridan foydalanish.
- Har bir toshning tezligini `pick random` bloklari yordamida tasodifiylashtirish (masalan, `pick random -5 dan -10 gacha`).

#### Qadam 4: To‘qnashuvni aniqlash va o‘yin tugashi
- Raketka toshga teganda `if <touching [rock]>` blokidan foydalanish.
- To‘qnashuv aniqlansa, o‘yinni to‘xtatib, **Game Over** xabarini ko‘rsatish.

#### Qadam 5: Ball tizimini yaratish
- O‘yinchi yashab qolgan vaqtni hisoblash uchun **score** o‘zgaruvchisini yaratish.
- Har soniya ballni 1 taga oshirish uchun `wait 1 second` blokini ichida sikl ishlatish.
- Raketka toshga tegganda ball oshishini to‘xtatib, yakuniy ballni ko‘rsatish.

#### Qadam 6: Ko‘p toshlar uchun klonlashdan foydalanish
- Turli joylarda bir nechta toshlar yaratish uchun `create clone of [myself]` blokidan foydalanish.
- Har bir klon tasodifiy tezlikda tushadi va ekran pastiga yetganda o‘chiriladi yoki qayta paydo bo‘ladi.

### 3. O‘qituvchi uchun maslahatlar
- **Harakat**: Raketkaning harakati faqat gorizontal bo‘lishi kerakligini eslatish, `if` bloklari yordamida raketkani o‘yin maydonidan chiqib ketishining oldini olish.
- **Tasodifiylik**: `pick random` blokidan qanday foydalanishni va o‘yinga tasodifiylik qo‘shishni tushuntirish.
- **Klonlash**: Talabalarga klonlashni yaxshi tushuntirish va klon toshlarni ekran tashqarisiga chiqqanda qayta sozlashni o‘rgatish.

### 4. Ko‘p uchraydigan muammolar va yechimlar

- **Muammo**: Raketka ekran tashqarisiga chiqib ketadi.
  - **Yechim**: `if <x position > [qiymat]>` va `if <x position < [qiymat]>` bloklari yordamida raketkaning gorizontal harakatini cheklash.

- **Muammo**: Toshlar to‘g‘ri tushmayapti yoki juda tez.
  - **Yechim**: `pick random` blokini sozlash orqali tushish tezligini moslashtirish, turli diapazonlarni sinab ko‘rish.

- **Muammo**: Ball noto‘g‘ri oshmoqda.
  - **Yechim**: Ball oshishi uchun sikl ichida va faqat o‘yin davomida hisoblanishini ta’minlash, to‘xtash holatini to‘g‘ri sozlash.

### 5. Qo‘shimcha g‘oyalar

- Raketka harakatida, toshga tegilganda va o‘yin tugaganda tovush effektlari qo‘shish.
- Tasodifiy paydo bo‘ladigan himoya yoki tezlik oshiruvchi power-up’lar qo‘shish.
- O‘yin davomida toshlar tezligini oshirib, qiyinchilikni ko‘tarish.
- Orqa fon musiqasi qo‘shib, o‘yin tajribasini yaxshilash.
- Turli darajalar yaratib, toshlar turli tezlikda tushishini yoki yangi to‘siqlar qo‘shilishini ta’minlash.

## Xulosa

Ushbu loyiha oxirida talabalar tushayotgan toshlardan qochish maqsadida raketkani boshqaradigan **Space Shooter** o‘yinini yaratadilar. Ular **harakat**, **to‘qnashuvni aniqlash**, **tasodifiylik**, **klonlash** va **ball tizimi** kabi muhim tushunchalarni qayta ko‘rib chiqib, amalda qo‘llaydilar. Bu loyiha o‘yin dizayni va hodisalarni boshqarish ko‘nikmalarini mustahkamlash uchun ajoyib imkoniyatdir.

---

### **Eslatma**: **Space Shooter** o‘yini ilgari o‘rgangan ko‘plab tushunchalarni mukammal takrorlash va mustahkamlash imkonini beradi. Talabalar tasodifiy hodisalar, sprite’lar o‘zaro ta’siri va o‘yin jarayonini boshqarish bo‘yicha yanada ko‘proq tajriba orttiradilar, bu esa o‘yin ishlab chiqishda juda muhimdir.
