# Loyiha: So'z Animatsiyasi ✨

## Loyiha Sharhi

Ushbu loyihada o‘quvchilar so‘zdagi har bir harfni (masalan, "ILMHUB") ekranda harakatlanayotgan animatsiya sifatida yaratadilar. Bu oddiy loyiha orqali o‘quvchilar **`glide`** blokidan foydalanib, harflarni alohida-alohida animatsiya qilishni va bir nechta sprite’larning (harflarning) harakatini muvofiqlashtirishni o‘rganadilar. Shuningdek, ular so‘zni harflarga ajratib, har birini ketma-ket animatsiya qilish va so‘zning butunlay harakatlanayotganini ko‘rsatishni bilib oladilar.

## Asosiy Tushunchalar

- **Glide bloki**: `glide [x] soniya davomida x: [x] y: [y]` blokidan foydalanib, harflarni ekranda silliq harakatlantirishni o‘rgating.
- **Sprite joylashuvi**: `go to x: [x] y: [y]` bloki yordamida harflarni boshlang‘ich joylariga qo‘yish.

## Batafsil Reja

1. **Kirish (10-15 daqiqa)**
   - Loyihaning maqsadini tushuntiring: "ILMHUB" so‘zidagi har bir harfni ketma-ket ekranda harakatlantirish.
   - **Glide bloki**ni tanishtiring va uning sprite’ni belgilangan vaqt ichida yangi joyga silliq olib borishini tushuntiring.
   - O‘quvchilarga so‘zni harflarga ajratib, ularni ketma-ket animatsiya qilish usulini tushuntiring.

2. **Bosqichma-bosqich ko‘rsatmalar**

   - **1-bosqich**: "ILMHUB" so‘zining har bir harfi uchun alohida sprite yarating.
     - Har bir harf uchun alohida sprite yaratish yoki bitta sprite’ni klonlash mumkin.
   - **2-bosqich**: Har bir harfni boshlang‘ich joyiga qo‘ying.
     - `go to x: [x] y: [y]` blokidan foydalanib, harflarni ekranda turli joylarga joylashtiring.
   - **3-bosqich**: Harflarni **`glide`** bloki yordamida animatsiya qiling.
     - Masalan: `glide 2 soniya davomida x: [yangi x] y: [yangi y]` blokidan harflarni keyingi joyga silliq harakatlantirish uchun foydalaning.
   - **4-bosqich**: Animatsiyani ketma-ket bajarish uchun **broadcast** blokidan foydalaning.
     - Har bir harf o‘z navbatida xabarni olgach, yangi joyga harakat qiladi.
   - **5-bosqich**: Har bir harakat orasiga kichik to‘xtash qo‘shing.
     - Harflarning harakat vaqtlari orasida `wait [vaqt] soniya` blokidan foydalanib, ketma-ketlikni nazorat qiling.

3. **O‘qituvchiga Maslahatlar**

- Animatsiyani silliq qilish uchun **glide** blokidan foydalanishga urg‘u bering va o‘quvchilarga har xil vaqt qiymatlarini sinab ko‘rishni tavsiya qiling.
- O‘quvchilarga so‘zni harflarga bo‘lib, har birini alohida sprite sifatida ishlatishni tushuntiring.
- Yaratishda ijodkorlikka undang! Ular so‘zni o‘z ismlari yoki sevimli so‘zlari bilan almashtirishlari yoki rang, o‘lcham o‘zgarishi kabi qo‘shimcha effektlar qo‘shishlari mumkin.

4. **Ko‘p uchraydigan muammolar**

- **Muammo**: Harflar harakat qilmayapti  
  - **Yechim**: `glide` blokining to‘g‘ri joylashganini va broadcast xabarlari ketma-ketligini tekshiring.
