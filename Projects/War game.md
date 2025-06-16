# War game ⚔️🎮

## Loyihaning Tavsifi

Ushbu loyihada talabalar **otishma urush o‘yini** yaratadilar, bunda o‘yinchi belgi yoki transport vositasini boshqarib, dushman to‘lqinlariga qarshi kurashadi. O‘yinning maqsadi – dushman sprite’larini otib tushirish va ulardan zararlanishdan qochishdir. Loyihada **sprite’lar o‘zaro ta’siri**, **tasodifiylik**, **to‘qnashuvni aniqlash** va **o‘yin jarayonini boshqarish** tushunchalari joriy etiladi.

Bu loyiha biroz murakkabroq bo‘lib, talabalar uchun **o‘yin mexanikasi**ni chuqurroq tushunishni ta’minlaydi, ayniqsa **if-else** bayonotlari yordamida qaror qabul qilish va **pick random** bloklari yordamida kutilmagan hodisalarni yaratish bo‘yicha.

## Asosiy Tushunchalar

- **If-Else Bayonotlari**: Talabalarga qaror qabul qilish uchun **if-else** bloklaridan qanday foydalanishni o‘rgatish (masalan, o‘q dushmanga tegsa yoki o‘yinchining hayoti nolga yetganda).
- **Pick Random**: Dushmanlarning harakatlari, paydo bo‘lish va hujum uslublarini tasodifiylashtirish uchun **pick random** blokidan foydalanishni ko‘rsatish.
- **To‘qnashuvni Aniqlash**: O‘q dushmanga tegsa, nima bo‘lishini aniqlash, masalan, dushman yo‘qolishi va o‘yinchining ball olishini ta’minlash.
- **Hayot Tizimi**: O‘yinchining hayotini boshqarish; dushman tegsa hayot kamayadi, power-up orqali hayot tiklanadi.
- **Ball Tizimi**: O‘yinchi nechta dushmanni yo‘q qilganini hisoblash.

## Batafsil Reja

### 1. Kirish (15-20 daqiqa)
- **Urush o‘yini** g‘oyasini tanishtirish: o‘yinchi belgini yoki transport vositasini boshqaradi, dushmanlarga qarshi kurashadi.
- Turli o‘yin hodisalarini boshqarishda **if-else** bayonotlarining ahamiyatini tushuntirish.
- Dushmanlarning tasodifiy harakatlari va paydo bo‘lishini yaratishda **pick random** blokidan foydalanishni tushuntirish.

### 2. Qadam-baqadam ko‘rsatmalar

#### Qadam 1: O‘yinchi va dushman sprite’larini yaratish
- **O‘yinchi sprite**: o‘yinchi boshqaradigan tank, kosmik kemasi yoki askar sprite’ini yaratish.
- **Dushman sprite**: ekranda harakatlanadigan va o‘yinchiga tegishga harakat qiladigan bir nechta dushman sprite’larini yaratish.

#### Qadam 2: O‘yinchini boshqarish
- `when key pressed` bloklari yordamida o‘yinchini yuqoriga, pastga, chapga va o‘ngga harakatlantirish.
- `when space key pressed` bloklari yordamida o‘q otish.

#### Qadam 3: O‘q sprite’ini yaratish
- Oddiy o‘q sprite’ini yaratish va o‘yinchi space tugmasini bosganda o‘qni yuqoriga (yoki belgi yo‘nalishida) harakatlantirish.
- **If-else** bloklari yordamida o‘q dushmanga tegishini aniqlash.
  - Agar o‘q dushmanga tegsa, dushman yo‘qolishi va ball oshishi kerak.

#### Qadam 4: Dushmanlarning tasodifiy harakatini yaratish
- `pick random` blokini ishlatib, dushmanlar tasodifiy yo‘nalishda harakatlanishi, tasodifiy vaqt oralig‘ida paydo bo‘lishi yoki tasodifiy hujum uslubini tanlashi.
- Dushmanlarning harakat tezligi yoki sonini ham `pick random` orqali tasodifiylashtirish.

#### Qadam 5: Ball va hayot tizimini yaratish
- **Ball**: o‘yinchi nechta dushmanni yo‘q qilganini hisoblovchi o‘zgaruvchi yaratish va dushman o‘ldirilganda ballni oshirish.
- **Hayot**: o‘yinchining hayot o‘zgaruvchisini yaratish. Dushman tegsa, hayotni kamaytirish. Hayot nolga yetganda o‘yin tugaydi.

#### Qadam 6: O‘yin tugashi va g‘alaba shartlarini qo‘shish
- O‘yinchining hayoti nolga yetganda **Game Over** ekrani va yakuniy ballni ko‘rsatish.
- Belgilangan dushmanlar sonini yo‘q qilganda yoki missiyani bajarganda g‘alaba shartini yaratish.

### 3. O‘qituvchi uchun maslahatlar
- O‘yinda qaror qabul qilish uchun **if-else** bloklarining ahamiyatini ta’kidlash (masalan, o‘q dushmanga tegadimi yoki hayot nolga yetdimi).
- Tasodifiy harakatlar va hodisalar yaratishda **pick random** blokidan foydalanishni tushuntirish.
- Turli tasodifiy qiymatlarni sinab ko‘rishni rag‘batlantirish.

### 4. Ko‘p uchraydigan muammolar va yechimlar

- **Muammo**: O‘qlar dushmanga tegganda yo‘qolmaydi.
  - **Yechim**: O‘q sprite’ida to‘qnashuvdan keyin `hide` va `broadcast [Enemy Hit]` bloklari ishlatilganligini tekshirish.
  
- **Muammo**: Dushmanlar juda tez yoki juda sekin paydo bo‘ladi.
  - **Yechim**: `pick random` blokidagi diapazonni o‘zgartirish yoki paydo bo‘lish oralig‘ini `wait` bloki yordamida boshqarish.
  
- **Muammo**: O‘yinchi dushman teganda hayot yo‘qotmayapti.
  - **Yechim**: To‘qnashuvni aniqlash mantiqini qayta tekshirish va `change health by -1` bloki ishlashini ta’minlash.

### 5. Qo‘shimcha g‘oyalar

- O‘yinchini davolaydigan yoki vaqtinchalik kuchaytiradigan **power-up** lar qo‘shish.
- Ko‘p urinishlarni talab qiladigan **bosh dushmanlar** yaratish.
- Otish, dushmanga tegish va o‘yin tugashi uchun **tovush effektlari** qo‘shish.
- Har darajada dushmanlar soni, tezligi yoki hujum uslublari o‘zgaradigan **darajalar tizimi** yaratish.
- Har daraja uchun turli muhitlarni ifodalovchi **orqa fonlar** yaratish (masalan, jang maydoni, kosmos yoki o‘rmon).

## Xulosa

Ushbu loyiha oxirida talabalar dushmanlarga qarshi kurashadigan **otishma urush o‘yini** yaratadilar. Ular **if-else** bayonotlarini qaror qabul qilish uchun, **tasodifiy hodisalarni** o‘yinga kiritish uchun, **to‘qnashuvni aniqlash**, **ball tizimi** va o‘yin tugashi shartlarini yaratishni o‘rganadilar. Bu loyiha talabalarni **o‘yin dizayni**, **hodisalarni boshqarish** va **tasodifiylik** bo‘yicha mustahkam ko‘nikmalar bilan ta’minlaydi.

---

### **Eslatma**: **Urush o‘yini** murakkabroq mantiq va tasodifiylikni joriy etib, talabalarni ko‘p o‘zgaruvchilar, qaror qabul qilish va o‘yin jarayonini boshqarishga tayyorlaydi.
