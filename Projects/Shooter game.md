# Loyiha: Shooter O'yini 🦅🔫

## Loyihaning Tavsifi

Ushbu loyihada talabalar qushlarni ovlash maqsadida **shooter o'yini** yaratadilar. O'yinda Scratch dasturida **broadcasting** (xabar yuborish) va **qabul qilish** tushunchalari qo'llaniladi. O'yinchi o'q otuvchi sprite’ni boshqaradi, u ekran bo'ylab uchib o'tayotgan qushlarga o'q uzadi. Qush urilganda, u yo'qoladi va o'yinchi ball oladi.

Bu oddiy **ov o'yini** bo‘lib, talabalar unda **sprite’lar o‘zaro muloqoti**, **broadcasting** va **klonlash** tushunchalarini amaliy qo‘llaydilar. O'yin jarayonini boshqarish, yangi raund boshlash, ballarni hisoblash va ekran yangilash kabi mavzular uchun yaxshi kirishdir.

## Asosiy Tushunchalar

- **Broadcasting**: Sprite’lar orasida xabarlar yuborish va qabul qilishni o‘rgatish (masalan, qush urilganda uni yo‘q qilish).
- **Klonlash**: Bir nechta qushlarni yaratish va ularni ekran bo‘ylab uchirish uchun klonlashdan foydalanish.
- **To‘qnashuvni aniqlash**: Oq otgan paytda o‘q qushga tegishini aniqlash va kerakli harakatlarni bajarish.
- **Ball tizimi**: O‘yinchi qancha qushni urganini hisoblash uchun ball tizimini yaratish.

## Batafsil Reja

1. **Kirish (10-15 daqiqa)**
   - O'yinning maqsadini tushuntirish: ekranda uchib o'tayotgan qushlarni o'q bilan ovlash.
   - **broadcast** va **receive** bloklarini tanishtirish, sprite’lar o‘rtasida muloqot qanday amalga oshishini ko‘rsatish.
   - Klonlash va to‘qnashuvni aniqlash qanday ishlashini tushuntirish.

2. **Qadam-baqadam ko‘rsatmalar**
   - **Qadam 1**: Shooter va qush sprite’larini yaratish:
     - O‘yinni boshqaruvchi **shooter sprite** yaratish.
     - Ekranda uchib yuradigan **qush sprite** yaratish.
   - **Qadam 2**: Shooter sprite’ini boshqarish:
     - `when key pressed` bloklari yordamida shooterni chap va o‘ngga harakatlantirish (masalan, chap va o‘ng strelka tugmalari).
     - `when space key pressed` blokidan foydalanib o‘q otish.
   - **Qadam 3**: O‘q sprite’ini yaratish:
     - Oddiy o‘q sprite’ini yaratish.
     - Space tugmasi bosilganda o‘q tepaga harakat qilishi.
     - `if <touching [qush]>` bloklari yordamida o‘q qushga tegishini aniqlash.
   - **Qadam 4**: Broadcasting o‘rnatish:
     - O‘q qushga teganda `broadcast [Bird Hit]` blokini ishlatib, qush urilgani haqida xabar yuborish.
     - Qush sprite’ida `when I receive [Bird Hit]` bloki yordamida qushni yashirish va ballni oshirish.
   - **Qadam 5**: Ball tizimini yaratish:
     - O‘yinchi ballini hisoblash uchun **score** o‘zgaruvchisini yaratish.
     - Qush urilganda `change score by 1` blokini ishlatib ballni oshirish.
   - **Qadam 6**: Bir nechta qushlar uchun klonlashdan foydalanish:
     - `create clone of [myself]` blokini qo‘llab yangi qushlarni yaratish.
     - Har bir klon tasodifiy yo‘nalishda harakat qilishi.
     - `when I start as a clone` bloki yordamida har bir klon ishga tushirilganda pozitsiyasi va harakati belgilanadi.

3. **O‘qituvchi uchun maslahatlar**
   - Turli sprite’lar birgalikda ishlashi uchun **broadcasting**dan foydalanishni urg‘u bering (masalan, o‘q qushga teganda qushni yo‘q qilish).
   - Talabalarga **klonlash**ni yaxshi tushuntiring, ayniqsa ko‘p qushlarni yaratish va ularni ekranda harakatlantirish uchun.
   - Agar talabalar broadcasting va xabar qabul qilishda qiynalsa, oddiy misol bilan ko‘rsatib bering: bir sprite xabar yuboradi, boshqasi esa uni qabul qilib, amal bajaradi.
   - To‘qnashuvni aniqlash (`if <touching [qush]>`) to‘g‘ri ishlashiga e'tibor bering.

4. **Ko‘p uchraydigan muammolar va yechimlar**
   - **Muammo**: O‘q qushga tegganda yo‘qolmaydi.
     - **Yechim**: O‘q kodi ichida qushga tegganda `hide` bloki borligiga va `broadcast [Bird Hit]` to‘g‘ri ishlatilganiga ishonch hosil qiling.
   - **Muammo**: Qushlar klonlanmaydi yoki tasodifiy harakatlanmaydi.
     - **Yechim**: `create clone of [myself]` bloki to‘g‘ri joyda (odatda sikl ichida) ekanligini, klonlar tasodifiy joyga borishi va `glide` bloklari ishlatilayotganini tekshiring.
   - **Muammo**: Ball qush urilganda yangilanmaydi.
     - **Yechim**: `change score by 1` bloki `when I receive [Bird Hit]` blokida ekanligini va to‘g‘ri ishlashini tekshiring.

5. **Qo‘shimcha g‘oyalar**
   - O‘q uzishda va qush urilganda tovush effektlarini qo‘shish.
   - O‘yin vaqtini cheklovchi **taymer** qo‘shish va vaqt tugaganda g‘olibni e’lon qilish.
   - O‘yin qiyinlashishi uchun qushlarning tezligini oshirish yoki ularning ko‘payishini darajalarga bo‘lish.
   - Ko‘p qushni o'tkazib yuborilganda yoki vaqt tugagach **Game Over** ekrani ko‘rsatish.
   - Orqa fon musiqasi yoki ball jadvali (scoreboard) qo‘shish.

## Xulosa

Ushbu loyiha oxirida talabalar **broadcasting** va **klonlash** yordamida qushlarni ovlaydigan shooter o‘yinini yaratadilar. Ular sprite’lar orasida xabarlar almashish va ko‘p dushmanlarni boshqarish uchun klonlashdan foydalanishni o‘rganadilar. Bu loyiha o‘yin oqimini boshqarish, hodisalar bilan ishlash va ball tizimini yaratish kabi muhim ko‘nikmalarni mustahkamlashga yordam beradi.

---

### **Eslatma**: **Shooter O'yini** talabalarga yanada murakkab sprite o‘zaro ta’siri va voqea asosida dasturlashga kirish uchun yaxshi poydevor yaratadi.
