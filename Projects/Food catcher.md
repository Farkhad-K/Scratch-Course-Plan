# Loyiha: Food Catcher 🍎🍔

## Loyiha Sharhi

Ushbu loyihada o‘quvchilar **Food Catcher** deb nomlangan qiziqarli o‘yin yaratadilar, unda o‘yinchi tushayotgan ovqatlarni ushlab oladigan savat (sprite) boshqaradi. O‘yin o‘quvchilarga Scratch dasturida **klonlash**, **sprite harakati**, **to‘qnashuvni aniqlash** va **hisob yuritish** kabi muhim tushunchalarni o‘rgatadi. Bu kursdagi birinchi o‘yin loyihasi bo‘lib, o‘quvchilarni Scratch bilan tanishtirish uchun yaxshi imkoniyatdir.

Loyihaning maqsadi — o‘quvchilarga klaviatura orqali sprite boshqarish, to‘qnashuvlarni aniqlash va obyektlarni klonlash kabi dasturlash asoslarini o‘rgatish.

## Asosiy Tushunchalar

- **Klonlash**: Tushayotgan ovqat elementlarining nusxalarini yaratishni o‘rgating.
- **Klaviatura boshqaruvi**: O‘yinchi sprite’sini (savatni) chap va o‘ngga harakatlantirish uchun o‘q tugmalaridan foydalaning.
- **Sensorlar**: Savat tushayotgan ovqatga tegganini **`touching`** bloki yordamida aniqlang.
- **Hisobni saqlash**: Ochko yig‘ish uchun o‘zgaruvchilar yaratish va ekranda ko‘rsatish.

## Batafsil Reja

### 1. Kirish (10–15 daqiqa)
- Loyihaning maqsadini tushuntiring: o‘quvchilar tushayotgan ovqatlarni ushlash uchun savat boshqaradilar.
- **Scratch interfeysi** bilan tanishtiring va asosiy bloklar — `when green flag clicked`, `move`, `if <touching?>` haqida qisqacha tushuntiring.
- **Klonlash**, **klaviatura boshqaruvi** va **to‘qnashuvni aniqlash** haqida gapiring.

### 2. Bosqichma-bosqich ko‘rsatmalar

#### 1-bosqich: Ikkita sprite yarating
- O‘yinchi boshqaradigan **savat** sprite’si.
- Ekran yuqorisidan tushadigan **ovqat** sprite’si (masalan, olma yoki gamburger).

#### 2-bosqich: Savatni sozlash
- `when green flag clicked` blokini o‘yinni boshlash uchun qo‘llang.
- `go to x: [qiymat] y: [qiymat]` bloki bilan savatni ekranning pastki qismiga joylashtiring.
- Chap va o‘ngga harakat uchun klaviatura boshqaruvini qo‘shing: `when [left arrow] key pressed`, `when [right arrow] key pressed` bloklari va `change x by [qiymat]` blokidan foydalaning.

#### 3-bosqich: Ovqat klonlarini qo‘shing
- `create clone of [food]` bloki yordamida ovqat klonlarini yarating.
- Klonlar tasodifiy x koordinatalardan boshlanib, pastga tushadi.
- Ovqat doimiy tushishi uchun `forever` siklidan foydalaning.
- Ovqat kloni ekran pastiga yetganda yoki savatga tegsa, yo‘qolishi kerak.

#### 4-bosqich: To‘qnashuvlarni boshqarish
- `if <touching [basket]> then` bloki yordamida ovqat savatga tegishini aniqlang.
- Tegsa, ochkoni oshiring va klonni o‘chirib yuboring.
- Agar ovqat pastga tushib, ushlanmasa, ochkoni kamaytirish yoki "miss" hisoblagichini oshirish mumkin.

#### 5-bosqich: Hisobni qo‘shish
- Ovqatlarni ushlash sonini saqlash uchun **o‘zgaruvchi** (masalan, "Score") yarating.
- `change [Score] by [1]` blokidan ochko oshirish uchun foydalaning.
- Ekranda ochkoni ko‘rsatish uchun `show variable [Score]` blokini qo‘shing.

#### 6-bosqich: Ovoz effektlarini qo‘shing
- Savat ovqatni ushlaganda yoki ovqat yerga teganda ovoz chiqaring.

### 3. O‘qituvchiga Maslahatlar

- Asosiy tushunchalarga e’tibor qarating: **sprite harakati**, **klonlash** va **sensorlar**.
- Klonlarning nima ekanligi va ular yordamida bir nechta nusxalar yaratilishini tushuntiring.
- O‘quvchilarni **`forever`** va **`if`** sikllaridan foydalangan holda o‘yin doimiy ishlashini ta’minlashga rag‘batlantiring.

### 4. Ko‘p uchraydigan muammolar va ularning yechimlari

- **Muammo**: Savat silliq harakat qilmayapti.
  - **Yechim**: Harakat boshqaruvlarini tekshirib, savat faqat mos tugma bosilganda harakat qilayotganiga ishonch hosil qiling.
- **Muammo**: Ovqat kloni tushmayapti yoki yo‘qolmayapti.
  - **Yechim**: Klonning boshlang‘ich joylashuvi to‘g‘ri belgilangani va `change y by [qiymat]` bloki `forever` ichida ishlatilayotganini tekshiring.
  - Klon ushlanganda yoki pastga tushganda `delete this clone` blokidan foydalaning.
- **Muammo**: Hisob yangilanmayapti.
  - **Yechim**: `change [Score] by [1]` bloki to‘qnashuvdan keyin ishlayotganiga e’tibor bering.

### 5. Qo‘shimcha G‘oyalar

- O‘yinga **darajalar** qo‘shing: ochko oshgani sari ovqat tezroq tushsin.
- Turli xil ovqatlar qo‘shing: ba’zilari ochko qo‘shadi, boshqalari ochkoni kamaytiradi yoki hayotni olib qo‘yadi.
- O‘yin uchun **timer** qo‘shing va berilgan vaqt ichida qancha ovqat ushlash mumkinligini sinab ko‘ring.
- Ovqat ushlash, ushlamaslik yoki o‘yin tugashi uchun **ovoz effektlari** qo‘shing.
- Belgilangan soni ushlanmagan ovqatdan so‘ng **o‘yin tugadi** ekranini yaratib, o‘yin qayta boshlanishini taklif qiling.

## Xulosa

Loyiha oxirida o‘quvchilar to‘liq ishlaydigan **Food Catcher** o‘yinini yaratadilar, unda asosiy Scratch tushunchalari — klonlash, klaviatura yordamida sprite harakati, to‘qnashuvni aniqlash va hisob yuritish qo‘llaniladi. Bu loyiha Scratch’da interaktiv o‘yin yaratishni o‘rgatish uchun juda yaxshi kirish hisoblanadi va keyingi murakkab loyihalar uchun poydevor yaratadi.

---

### **Eslatma**: Ushbu loyiha o‘quvchilarga Scratch dasturining turli muhim tushunchalarini amalda o‘rganish imkonini beradi va qiziqarli o‘yinni yaratishga yo‘naltirilgan. Bu birinchi o‘yin loyihasi sifatida juda mos keladi, chunki ko‘plab muhim funksiyalarni qamrab oladi, lekin murakkab emas.
