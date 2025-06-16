# Loyiha: Flappy Bird 🐦

## Loyiha Sharhi

Ushbu loyihada o‘quvchilar **Flappy Bird** o‘yinining soddalashtirilgan versiyasini yaratadilar, unda qush to‘siqlar (trubkalar) orasidan o‘tishi kerak bo‘ladi. Loyihaning asosiy e’tibori **gravitatsiyani (tortish kuchini)** simulyatsiya qilishga qaratilgan. Shuningdek, oddiy **to‘qnashuvni aniqlash** va **hisob tizimi** ham o‘rganiladi.

Bu loyiha **qo‘shimcha loyiha** sifatida asosiy kursdagi boshqa o‘yinlar bilan birga yoki ularning o‘rniga foydalanilishi mumkin. O‘qituvchi o‘yin asoslarini tushuntiradi, so‘ng o‘quvchilar uni kengaytirish va o‘zlashtirish imkoniyatiga ega bo‘ladilar. Bu loyiha o‘quvchilarga 2D o‘yinlarda gravitatsiya qanday ishlashini tushunishga yordam beradi.

## Asosiy Tushunchalar

- **Gravitatsiyani simulyatsiya qilish**: Qushni pastga tortadigan doimiy kuch orqali gravitatsiyani ko‘rsatish.
- **Harakat**: Qush yuqoriga harakat qilishi uchun oddiy fizika asosidagi boshqaruvni ishlatish.
- **To‘qnashuvni aniqlash**: Qush trubkalarga yoki yerga tegsa, buni aniqlash.
- **Hisob tizimi**: Qush trubkalar orasidan o‘tganda ochko yig‘ish.

## Batafsil Reja

### 1. Kirish (10–15 daqiqa)

- Loyihaning maqsadini tushuntiring: o‘quvchilar trubkalar orasidan uchib o‘tadigan qush ishtirokidagi o‘yin yaratadilar.
- O‘yinlarda **gravitatsiya** nima ekanligini tushuntiring — qush harakat qilmasa, pastga tushadi.
- Qushning vertikal harakati qanday qilib **klaviatura tugmalari** orqali boshqarilishini muhokama qiling.

### 2. Bosqichma-bosqich Yo‘riqnoma

#### 1-bosqich: Asosiy o‘yin elementlarini yarating:
- **Qush sprajti** qo‘shing va uning boshlang‘ich holatini belgilang.
- **Trubka sprajtlarini** qo‘shing va ularni ekranda tasodifiy joylashtiring (vertikal holatda).
- **Fon rasmi** qo‘shing va uni doimiy harakatlantiring — bu qush uchayotganini ko‘rsatadi.

#### 2-bosqich: Gravitatsiyani simulyatsiya qiling:
- `change y by [qiymat]` blokidan foydalanib qushning harakatini sozlang.
- Qushning **y koordinatasi**ni doimiy ravishda kamaytirib, gravitatsiyani yarating.
- O‘yinchi **bo‘sh joy tugmasini (space)** bossada, qush **yuqoriga sakrash** kerak (`change y by [qiymat]` yordamida).

#### 3-bosqich: Trubkalarni harakatlantiring:
- Trubkalar doimiy ravishda o‘ngdan chapga qarab harakatlanishi kerak.
- `forever` sikli bilan `change x by [qiymat]` blokini ishlatib trubkalarni harakatlantiring.
- Trubka ekran chetidan chiqqach, yangi tasodifiy joyga tiklang (`go to x: [qiymat], y: [qiymat]`).

#### 4-bosqich: To‘qnashuvni aniqlang:
- `if <touching [pipe]> then` blokidan foydalanib qush trubkaga tekkanda aniqlang.
- Qush trubkaga yoki yerga tegsa — o‘yin to‘xtasin yoki qaytadan boshlansin.

#### 5-bosqich: Hisob tizimini yarating:
- Har safar qush trubkalar orasidan o‘tsa, ochko oshiring.
- **Score (hisob)** o‘zgaruvchisini yarating va qush trubkadan muvaffaqiyatli o‘tganda 1 taga oshiring.

#### 6-bosqich: Ovoz va animatsiya qo‘shing:
- Qush sakraganda, yerga tushganda yoki to‘qnashganda ovoz effektlari qo‘shing.
- Ixtiyoriy: Qush sakraganda qanotlarini qoqayotgan animatsiya qo‘shing.

### 3. O‘qituvchiga Maslahatlar

- Loyihaning asosiy elementi — **gravitatsiya**. Qush doimiy pastga harakatlanadi, **bo‘sh joy tugmasi** esa vaqtincha yuqoriga harakatni keltirib chiqaradi.
- O‘quvchilar **doimiy harakatlar** uchun `forever` siklidan qanday foydalanishni tushunishlari kerak.
- O‘yin murakkabligini sozlash uchun **tezlik bilan tajriba qilishni** tavsiya qiling — gravitatsiya yoki trubka tezligini o‘zgartirish mumkin.

### 4. Muammolar va Yechimlar

- **Muammo**: Qush juda tez yoki sekin harakat qiladi.
  - **Yechim**: `change y by [qiymat]` blokidagi qiymatni moslashtiring.
- **Muammo**: Trubkalar ekrandan chiqqach tiklanmayapti.
  - **Yechim**: Trubkalar ekran chetidan chiqqach, `go to x: [qiymat], y: [qiymat]` bloklari bilan yangi joyga ko‘chirishni tekshiring.
- **Muammo**: Qush trubkaga tegishi bilan o‘yin darhol tugaydi.
  - **Yechim**: To‘qnashuv aniqlash bloklari to‘g‘ri joylashtirilganini va o‘yin faqat kerakli vaqtda tugashini ta’minlang.

### 5. Qo‘shimcha G‘oyalar

- **Turli darajalar** qo‘shing: Tezroq trubkalar yoki ko‘proq to‘siqlar bilan murakkablikni oshiring.
- **Eng yuqori natijani** ko‘rsatadigan tizim yarating.
- **Qush dizaynini** o‘zgartiring: Turli ko‘rinishlar (skins) yoki kostyumlar bilan.
- **Qo‘shimcha imkoniyatlar** (power-ups) qo‘shing: Masalan, vaqtincha uchish balandligini oshirish yoki trubkalarni sekinlashtirish.

## Xulosa

Loyiha yakunida o‘quvchilar asosiy **Flappy Bird** o‘yinini yaratadilar va unda **gravitatsiya simulyatsiyasi** ishlatiladi. Ular oddiy fizika tushunchalarini (gravitatsiya va sakrash mexanikasi) o‘zlashtiradilar. Bu loyiha orqali o‘quvchilar **harakat**, **to‘qnashuvni aniqlash**, va **hisob yuritish** bo‘yicha tajriba orttiradilar va murakkabroq o‘yinlar yaratishga tayyorlanadilar.

---

### **Eslatma**: **Flappy Bird** loyihasi Scratch’da o‘yin fizikasini tushuntirish uchun juda qulay. Bu o‘quvchilarga o‘yinlarda gravitatsiya qanday ishlashini tushunishga va oddiy to‘qnashuv hamda ball tizimlarini joriy qilishga imkon beradi.
