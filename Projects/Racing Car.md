# Poyga Moshinasi 🚗

## Loyiha Sharhi

**Poyga Moshinasi** — bu o‘quvchilarga Scratch dasturlashda oldin o‘rganilgan asosiy tushunchalarni takrorlash va amaliyot qilish uchun mo‘ljallangan **takrorlash loyihasi**. Ushbu loyihada o‘quvchilar poyga mashinasini boshqarib, to‘siqlardan qochib, yo‘lda harakatlanadigan o‘yin yaratadilar. Maqsad — **sprite yaratish**, **harakatlanish**, **to‘qnashuvni aniqlash**, **o‘zgaruvchilar** va **darajalar** kabi tushunchalarni mustahkamlash.

Bu loyiha o‘quvchilarning hozirgacha o‘rgangan barcha bilimlarini amalda qo‘llashga yo‘naltirilgan. Unda **harakat boshqaruvi**, **shart operatorlari (if-else)**, **tsikllar** va **taymer tizimlari** kabi ko‘nikmalar mustahkamlanadi va to‘liq ishlaydigan poyga o‘yini yaratiladi.

## Asosiy Tushunchalar

- **Sprite yaratish**: O‘quvchilar o‘zlari poyga mashinasi va yo‘l sprite’larini yaratadilar.
- **Harakatlanish**: Klaviatura yordamida mashinani harakatlantirish (masalan, o‘q tugmalari bilan).
- **To‘qnashuvni aniqlash**: Mashina to‘siqlarga yoki yo‘l chegarasiga urilganda aniqlash.
- **O‘zgaruvchilar**: Hisob, vaqt va darajani kuzatish uchun o‘zgaruvchilar yaratish.
- **Darajalar**: O‘yinchi oldinga o‘tgani sayin qiyinchilik darajasini oshirish.
- **Taymer**: O‘yinchi yo‘lni qancha vaqtda bosib o‘tganini hisoblash.
- **O‘yin jarayoni**: O‘yin boshlanishi, darajalar o‘tishi va tugashini boshqarish.

## Batafsil Reja

### 1. Kirish (10-15 daqiqa)
- Loyihaning maqsadini tushuntirish: ilgari o‘rganilgan tushunchalar asosida **Poyga Moshinasi o‘yinini** yaratish.
- Ushbu loyiha **takrorlash** sifatida, o‘rgangan tushunchalarni, jumladan **harakat**, **to‘qnashuvni aniqlash**, va **darajalar**ni mustahkamlash vazifasini bajaradi.
- Hisob va darajani kuzatish uchun **o‘zgaruvchilarning ahamiyati**, shuningdek poyga davomida vaqtni hisoblash uchun **taymer**ning roli haqida tushuntirish.

### 2. Bosqichma-bosqich ko‘rsatmalar

#### 1-bosqich: Poyga Mashinasi sprite’ini yaratish
- **Mashina dizayni**: O‘quvchilar o‘zlari yaratgan yoki import qilgan poyga mashinasi sprite’ini tayyorlaydilar.
- **Mashina boshqaruvi**: `when key pressed` bloklari yordamida mashinani boshqarish:
  - Chap o‘q: chapga harakat
  - O‘ng o‘q: o‘ngga harakat
  - Yuqori o‘q: oldinga harakat
  - Pastki o‘q: orqaga harakat (ixtiyoriy)

#### 2-bosqich: Yo‘lni dizaynlash
- **Yo‘l sprite’i**: O‘quvchilar oddiy yo‘lni fon yoki maxsus sprite sifatida yaratadilar. Yo‘l chegaralari va to‘siqlar ko‘rinadigan bo‘lishi kerak.
- **Chegaralarni belgilash**: Mashina yo‘ldan chiqmasligi uchun to‘qnashuvni aniqlashni qo‘llash. Yo‘ldan chiqqanda o‘yin tugashi yoki o‘yinchi hayoti kamayishi kerak.

#### 3-bosqich: To‘siqlarni qo‘shish
- **To‘siq sprite’lari**: O‘quvchilar to‘siq — konuslar, toshlar yoki boshqa mashinalar kabi sprite’lar yaratadilar.
- **To‘qnashuvni aniqlash**: `if <touching [to‘siq]>` bloki yordamida o‘yin tugashi yoki o‘yinchiga jarima berilishi.

#### 4-bosqich: Darajalar va qiyinchilikni oshirish
- **Darajalar yaratish**: Har bir daraja tugagach, keyingi darajaga o‘tish. Har yangi daraja qiyinlashishi uchun mashina tezligini oshirish, ko‘proq to‘siq qo‘shish yoki yo‘lni o‘zgartirish.
- **Daraja o‘zgaruvchisi**: `level` nomli o‘zgaruvchi yaratib, hozirgi darajani kuzatish va daraja tugagach, uni oshirish.

#### 5-bosqich: Taymer va hisob
- **Taymer**: O‘yinchi darajani qancha vaqtda tugatishini o‘lchash uchun taymer o‘zgaruvchisi yaratish. `wait` yoki `forever` bloklari yordamida vaqtni kamaytirish.
- **Hisob**: `score` nomli o‘zgaruvchi yaratib, o‘yinchining natijasini, masalan, darajani tez tugatishi yoki to‘siqlardan qochishi asosida hisoblash.

#### 6-bosqich: O‘yin jarayoni
- **Boshlash ekrani**: O‘yin boshlanishi uchun bosish mumkin bo‘lgan start ekrani yaratish.
- **O‘yin tugadi ekrani**: Mashina to‘siqqa urilganda yoki yo‘ldan chiqqanda "O‘yin tugadi" ekrani ko‘rsatish. O‘yin qayta boshlash yoki boshlang‘ich ekranga qaytish imkoniyatlari bilan.
- **Darajalar orasidagi o‘tish**: O‘yinchi darajani muvaffaqiyatli tugatgach, keyingi darajaga o‘tish, yo‘l va qiyinchilikni yangilash, darajani oshirish.

### 3. O‘qituvchiga Maslahatlar
- **Tushunchalarni takrorlash**: Loyiha o‘quvchilarga oldin o‘rgangan bilimlarni mustahkamlashga yordam beradi. Ularni **o‘zgaruvchilar**, **to‘qnashuv aniqlash**, va **tsikllar**ni faol ishlatishga undang.
- **Dizaynga e’tibor**: O‘quvchilarni sprite dizayni va yo‘l chizmalari bilan ijodkorlik qilishga rag‘batlantiring.
- **Xatolarni tuzatish**: Muammolar yuzaga kelsa, birinchi navbatda **to‘qnashuvni aniqlash**, **daraja o‘tishi** va **taymer** tizimini tekshirishni tavsiya eting.

### 4. Ko‘p uchraydigan muammolar

- Muammo: Mashina juda tez yoki juda sekin harakatlanadi.
  - Yechim: `change x by` yoki `change y by` qiymatlarini sozlash, harakatlar orasidagi kechikishni o‘zgartirish.
- Muammo: To‘siqlar mashinaga to‘g‘ri urilmayapti.
  - Yechim: `if <touching [to‘siq]>` blokining to‘g‘ri ishlashini va to‘siq yashirin emasligini tekshirish.
- Muammo: Daraja to‘g‘ri yangilanmayapti.
  - Yechim: Daraja boshlanishida `level` o‘zgaruvchisini qayta tiklash, darajani oshirish blokini to‘g‘ri qo‘llash.

### 5. Qo‘shimcha G‘oyalar

- **Quvvat berishlar**: Masalan, tezlik oshirish yoki qalqon kabi quvvat berishlar qo‘shish.
- **Ko‘p yo‘llar**: Turli yo‘l dizaynlari, to‘siqlar va fonlar bilan bir nechta darajalar yaratish.
- **Eng yuqori natija**: Barcha darajalar bo‘yicha eng yuqori natijani saqlash va o‘yin oxirida ko‘rsatish.
- **Ko‘p o‘yinchi rejimi**: Ikkinchi o‘yinchi uchun boshqa mashina qo‘shib, split-screen poygasini yaratish.

## Xulosa

Ushbu loyiha davomida o‘quvchilar Scratch dasturlashdagi asosiy tushunchalarni mustahkamlab, o‘zlarining **Poyga Moshinasi o‘yinini** yaratadilar. Bu orqali ular **sprite yaratish**, **harakat boshqaruvi**, **to‘qnashuvni aniqlash**, **taymer funksiyalari** va **darajalarni o‘zgartirish** kabi ko‘nikmalarni amalda qo‘llash imkoniyatiga ega bo‘ladilar. Loyihaning amaliy yo‘nalishi, ijodkorlik va muammolarni hal qilish ko‘nikmalarini rivojlantirishga xizmat qiladi.

---
