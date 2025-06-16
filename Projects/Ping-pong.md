# Loyiha: Ping Pong (2-o‘yinchi uchun) 🏓

## Loyiha Sharhi

Ushbu loyihada o‘quvchilar klassik Pong o‘yini kabi **2-o‘yinchi uchun Ping Pong** o‘yinini yaratadilar. Ushbu o‘yinda ikki o‘yinchi ekraning har ikki tomonida joylashgan paddlarni boshqarib, to‘pni bir-biriga urib o‘ynaydi. Maqsad — to‘pni doim o‘yinda saqlash va raqibning paddini o‘tkazib, ochko olish.

Loyiha o‘quvchilarga **ko‘p o‘yinchili interaktivlik** tushunchasini o‘rgatadi, ikki boshqaruv tizimini qo‘llash, bir nechta paddlar bilan **to‘qnashuvni aniqlash** va har ikkala o‘yinchi uchun **hisobni boshqarishni** o‘rgatadi.

## Asosiy Tushunchalar

- **Spritelar o‘zaro ta’siri**: ikki padd va sakrayotgan to‘p o‘rtasidagi o‘zaro ta’sirlarni boshqarish.
- **Harakatni boshqarish**: ikkala padd uchun klaviatura boshqaruvini tashkil qilish.
- **To‘qnashuvni aniqlash**: to‘p paddlarga yoki ekran chetlariga tegishini aniqlash.
- **Hisob tizimi**: har bir o‘yinchi ochkolarini hisoblash uchun o‘zgaruvchi yaratish.

## Batafsil Reja

1. **Kirish (10-15 daqiqa)**
   - Loyihaning asosiy maqsadini tushuntirish: ikki o‘yinchi o‘rtasida Ping Pong o‘yini, o‘yinchilar to‘pni raqibining paddidan o‘tkazib ochko olishga harakat qilishadi.
   - Asosiy tushunchalarni muhokama qilish: spritelar o‘zaro ta’siri, to‘qnashuvni aniqlash, ko‘p boshqaruv tizimlari.
   - Harakat, to‘qnashuv va hisoblash uchun kerakli bloklarni tanishtirish.

2. **Bosqichma-bosqich ko‘rsatmalar**

   - **1-bosqich**: Fon va paddlarni yaratish:
     - Har bir o‘yinchi uchun ikkita **padd** yaratib, sahnaning qarama-qarshi tomonlariga joylashtiring.
     - To‘pni sahnaning markaziga qo‘ying.
   - **2-bosqich**: Paddlarni boshqarish:
     - Birinchi padd uchun `when key pressed` bloklaridan foydalaning (masalan, 1-o‘yinchi uchun W va S tugmalari).
     - Ikkinchi padd uchun esa yuqori va pastga o‘q tugmalari (Up va Down arrow keys).
     - Tugma bosilganda `change y by` bloklari yordamida paddlarni yuqoriga yoki pastga harakatlantiring.
   - **3-bosqich**: To‘pni harakatlantirish va to‘qnashuvni aniqlash:
     - To‘pni `glide` bloki bilan harakatlantiring. To‘p doimiy ravishda sahna yuqori va past chegarasidan sakrashi kerak.
     - `if <touching [padd]> then` bloklari yordamida to‘p paddlarga teganda sakrashini ta’minlang.
   - **4-bosqich**: Hisobni qo‘shish:
     - Har ikkala o‘yinchi uchun **hisob** o‘zgaruvchisini yarating.
     - To‘p sahnaning chap yoki o‘ng chetidan chiqsa, raqib o‘yinchi hisobini oshiring.
     - Har ikkala o‘yinchi hisobini ekranda ko‘rsating.
   - **5-bosqich**: O‘yinni qayta boshlash:
     - O‘yinchi ochko olgandan so‘ng, to‘pni markazga qaytaring va o‘yin davom etsin.

3. **O‘qituvchiga Maslahatlar**

- Ikkala o‘yinchi va to‘p o‘rtasidagi **muvofiqlik**ni ta’kidlang. Paddlarning to‘p bilan qanday o‘zaro ta’sir qilishi va to‘pning sakrash yo‘nalishini tushuntiring.
- To‘p va paddlar harakatini uzluksiz boshqarish uchun **repeat** yoki **forever** sikllaridan foydalanishni ko‘rsatish.
- O‘quvchilarni o‘z o‘yinlarini tez-tez **sinab ko‘rish va xatolarini tuzatishga** undang.
- Agar paddlarning harakati bilan muammo bo‘lsa, boshqaruv bloklarini silliq harakat uchun sozlashga yordam bering.

4. **Ko‘p uchraydigan muammolar**

- Muammo: Paddlar juda tez yoki sekin harakatlanmoqda.
  - Yechim: `change y by` blokidagi qiymatlarni sozlang va turli qiymatlarni sinab ko‘ring.
- Muammo: To‘p paddga to‘g‘ri sakramaydi yoki ushlanib qoladi.
  - Yechim: `if <touching [padd]> then` blokining to‘g‘ri ishlashini tekshiring va to‘pning sakrash burchagini to‘g‘rilang.
- Muammo: Ochko qo‘shilmayapti yoki hisob qayta tiklanmayapti.
  - Yechim: Ochko olishdan keyin hisobni to‘g‘ri yangilash va to‘p markazga qaytishini ta’minlang.

5. **Qo‘shimcha G‘oyalar**

- To‘p paddga teganda yoki ochko olganda **ovoz effektlarini** qo‘shish.
- O‘yinni qiyinlashtirish uchun to‘p tezligini o‘yinda oshirish orqali turli darajalar yaratish.
- O‘yinni vaqt bilan cheklab, vaqt tugagach g‘olibni e’lon qilish uchun **taymer** qo‘shish.
- Paddlarni va fonlarni o‘zgartirish uchun **maxsus dizaynlar** yaratish.
- Bitta o‘yinchi uchun **kompyuter boshqaruvidagi o‘yinchi** variantini qo‘shish.

## Xulosa

Ushbu loyiha orqali o‘quvchilar qiziqarli va interaktiv 2-o‘yinchi uchun Ping Pong o‘yinini yaratadilar, bu ularga ko‘p boshqaruvni boshqarishni, to‘qnashuvni aniqlashni va hisobni yuritishni o‘rgatadi. Shuningdek, o‘yin dizayni, spritelar o‘zaro ta’siri va xatolarni tuzatish bo‘yicha amaliy ko‘nikmalar hosil qiladi.

---

### **Eslatma**: **Ping Pong o‘yini** o‘quvchilarga sprite boshqaruvi, to‘qnashuv aniqlash va hisoblash kabi asosiy tushunchalarni mustahkamlashga yordam beradi. Bu ko‘p o‘yinchili o‘yin logikasiga kirish bo‘lib, ikki o‘yinchi o‘rtasidagi o‘zaro ta’sirlarni yaratishga imkon beradi.
