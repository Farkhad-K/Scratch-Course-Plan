# Loyiha: Paddle O‘yini 🏓

## Loyiha Sharhi

Ushbu loyihada o‘quvchilar oddiy **Pong o‘yiniga o‘xshash o‘yin** yaratadilar, unda ular paddle (raketka) yordamida to‘pni tepib o‘ynaydilar. Bu loyiha kursda o‘rganilgan bir nechta muhim tushunchalarni, masalan, **sprite harakati**, **klaviatura boshqaruvi**, **to‘qnashuvni aniqlash** va **ballarni hisoblash uchun o‘zgaruvchilar**ni mustahkamlashga qaratilgan. O‘yin juda murakkab bo‘lmasligi mumkin, ammo o‘quvchilar o‘zlarining hozirgacha o‘rgangan ko‘nikmalarini amaliyotda sinashlari uchun juda yaxshi mashqdir.

Bu loyiha asoslarni qayta ko‘rib chiqish va mustahkamlash uchun ajoyib imkoniyat bo‘lib, shu bilan birga o‘ynashni ham qiziqarli qiladi!

## Asosiy Tushunchalar

- **Sprite harakati**: Paddle’ni klaviatura yordamida harakatlantirish.
- **To‘qnashuvni aniqlash**: To‘p paddle va ekran chegaralariga tegishini aniqlash.
- **Ballarni hisoblash**: Ball o‘zgaruvchisiga qiymat qo‘shish va yangilash.
- **Takroriy tsikllar**: O‘yinni doimiy ishlatish va harakatlarni takrorlash uchun tsikllardan foydalanish.
- **Yo‘nalishni boshqarish**: To‘p devorlar va paddle’dan sakrash orqali yo‘nalishini boshqarish.

## Batafsil Reja

1. **Kirish (10-15 daqiqa)**
   - Loyihaning maqsadini tushuntirish: o‘quvchilar paddle yordamida to‘pni tepib o‘ynaydigan oddiy Pong o‘yini yaratadilar.
   - Foydalaniladigan asosiy tushunchalarni ko‘rib chiqish: **sprite harakati**, **klaviatura boshqaruvi**, **sensor bloklari**, **to‘qnashuvni aniqlash**, va **o‘zgaruvchilar**.
   - Scratch interfeysi va muhim bloklarning joylashuvi haqida qisqacha ma’lumot berish.

2. **Bosqichma-bosqich ko‘rsatmalar**

   - **1-bosqich**: Ikki sprite yaratish:
     - O‘yinchi boshqaradigan **paddle** sprite’i.
     - Ekranda sakraydigan **to‘p** sprite’i.
   - **2-bosqich**: Paddle’ni sozlash:
     - O‘yinni boshlash uchun `when green flag clicked` blokidan foydalanish.
     - Paddle’ni ekran pastki qismiga joylashtirish (`go to x: [qiymat] y: [qiymat]`).
     - Paddle’ni chap va o‘ngga harakatlantirish uchun `when [left arrow] key pressed` va `when [right arrow] key pressed` bloklarini qo‘shish, harakatni `change x by [qiymat]` bloki bilan boshqarish.
   - **3-bosqich**: To‘pni sozlash:
     - Oddiy to‘p sprite’ini yaratib, ekran markaziga joylashtirish.
     - To‘pni doimiy harakatlantirish uchun `forever` tsikli ichida `glide` blokidan foydalanish.
     - Boshlanishda to‘p uchun **tasodifiy yo‘nalish**ni `point in direction` blok yordamida berish.
   - **4-bosqich**: Paddle bilan to‘qnashuvni aniqlash:
     - `if <touching [paddle]> then` blokidan foydalanib, to‘p paddle’ga teganda tekshirish.
     - To‘p paddle’ga teganda uning **y-yo‘nalishini teskari o‘zgartirish** (`point in direction` bloki yordamida).
   - **5-bosqich**: Chegara shartlarini qo‘shish:
     - To‘p ekran yuqori qismiga tegsa, yo‘nalishini teskari o‘zgartirish (`if <y position > [qiymat]> then`).
     - To‘p ekran pastki qismiga tushsa, ball yo‘qotish yoki o‘yin tugashi holatini yaratish (`if <y position < [qiymat]> then`).
   - **6-bosqich**: Ballarni hisoblash:
     - Har safar to‘p paddle’ga teganda oshadigan **ball o‘zgaruvchisi** yaratish.
     - Ballarni ekranda ko‘rsatish uchun `show variable [score]` blokidan foydalanish.
     - To‘p paddle ostidan tushganda ballni kamaytiruvchi **missed ball** hisoblagichini qo‘shish.
   - **7-bosqich**: Ovoz effektlarini qo‘shish:
     - To‘p paddle yoki ekran yuqori qismiga teganda ovoz chiqarish.
     - Istalgan holatda to‘p paddle’dan o'tganda ham ovoz effektini qo‘shish mumkin.

3. **O‘qituvchiga Maslahatlar**

- To‘qnashuvni aniqlash uchun **sensor bloklari**dan foydalanishni ta’kidlang.
- To‘pning yo‘nalishini teskari o‘zgartirish uchun `point in direction` blokidan qanday foydalanishni o‘rgating.
- Doimiy tekshirish va shartlarni bajarish uchun **forever tsikl** ishlatishni tavsiya qiling.
- Agar to‘p to‘g‘ri sakramayotgan yoki paddle harakati kutilganidek bo‘lmasa, kodni qanday tuzatishni ko‘rsatib bering.

4. **Ko‘p uchraydigan muammolar**

- **Muammo**: To‘p paddle ga teganda sakramaydi.
  - **Yechim**: `if <touching [paddle]> then` bloki va `point in direction` bloki to‘g‘ri ishlayotganini tekshirish.
- **Muammo**: Paddle juda tez yoki juda sekin harakatlanadi.
  - **Yechim**: `change x by [qiymat]` blokining qiymatini moslashtirish.
- **Muammo**: To‘p juda tez harakatlanadi yoki noto‘g‘ri sakraydi.
  - **Yechim**: To‘pning `glide` tezligini tekshirish va sozlash. Sakrash effektini to‘g‘ri vaqtda bajarishni ta’minlash.

5. **Qo‘shimcha G‘oyalar**

- O‘yinga **darajalar** qo‘shing: Har balldan keyin to‘p tezligini oshiring yoki vaqtga qarab tezlashtiring.
- Bir nechta **paddle’lar** yoki 2 o‘yinchi rejimini qo‘shing.
- **Hayotlar** tizimini joriy eting: O‘yinchiga ma’lum son hayot berilsin, to‘p paddle ostidan tushganda hayot kamayadi va hayot tugasa o‘yin tugaydi.
- **Vaqt o‘lchagich** qo‘shing: O‘yinni vaqt cheklovi bilan o‘ynash va oxirida yakuniy ballarni ko‘rsatish.

## Xulosa

Ushbu loyiha oxirida o‘quvchilar oddiy, ammo ishlaydigan **Pong o‘yiniga o‘xshash o‘yin** yaratadilar. Ular sprite harakati, to‘qnashuvni aniqlash, ballarni hisoblash va o‘zgaruvchilar bilan ishlash kabi muhim dasturlash tushunchalarini mustahkamlashadi. Bu loyiha Scratch’ning asosiy bloklarini tushunishni mustahkamlash va keyinchalik murakkab o‘yinlarni yaratish uchun mustahkam poydevor yaratadi.

---

### **Eslatma**: Paddle o‘yini loyihasi o‘quvchilarga kurs davomida o‘rganilgan bilimlarni amalda sinash uchun ajoyib imkoniyatdir. Mexanika oddiy bo‘lsa-da, o‘quvchilar qo‘shimcha funksiyalar qo‘shish va o‘yinni o‘z didlariga moslashtirish orqali ijodiy yondashuvni rivojlantira oladilar.
