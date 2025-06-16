# Loyiha: Baliq va Qurbaqa 🐟🐸

## Loyiha Sharhi

Ushbu loyihada o‘quvchilar **baliq** va **qurbaqa** ishtirokidagi interaktiv o‘yin yaratadilar. Loyihaning asosiy maqsadi — o‘quvchilarga **sprajt yo‘nalishini (direction)** tushuntirish, chunki bu birinchi marta sprajtlarning harakat yo‘nalishi boshqariladi. O‘quvchilar `point in direction` va `turn` bloklari yordamida sprajt yo‘nalishini qanday boshqarishni o‘rganadilar. O‘yinda shuningdek, oddiy **to‘qnashuv aniqlash** va **harakat** mexanizmlari ishlatiladi.

Bu loyiha orqali o‘quvchilar Scratch’da yo‘nalish qanday ishlashini tushunib olishadi va oddiy mantiqdan foydalanib sprajtlar o‘rtasidagi qiziqarli interaksiyalarni yaratadilar.

## Asosiy Tushunchalar

- **Sprajt yo‘nalishi**: Sprajtlarning harakat yo‘nalishini boshqarish (`point in direction` va `turn` bloklari yordamida).
- **To‘qnashuvni aniqlash**: Baliq va qurbaqa bir-biriga tegsa yoki yaqinlashsa, bu holatni aniqlash.
- **Harakat**: Baliq va qurbaqani klaviatura tugmalari yordamida harakatlantirish va yo‘nalishini boshqarish.

## Batafsil Reja

### 1. Kirish (10–15 daqiqa)

- Loyihaning maqsadini tushuntiring: o‘quvchilar baliq va qurbaqa ishtirokidagi oddiy o‘yin yaratadilar.
- **Yo‘nalish** tushunchasini kiriting — sprajtlar qanday aylantiriladi va `point in direction` orqali harakat yo‘nalishi qanday nazorat qilinadi.
- `turn`, `move`, va `point in direction` bloklarining harakatga qanday ta’sir qilishini misollar bilan ko‘rsating.

### 2. Bosqichma-bosqich Yo‘riqnoma

#### 1-bosqich: Ikki ta sprajt yarating:
- **Baliq**: Ekran bo‘ylab harakatlanadigan sprajt.
- **Qurbaqa**: O‘yinchi tomonidan klaviatura orqali boshqariladigan sprajt.

#### 2-bosqich: Baliq sprajti sozlanishi:
- `when green flag clicked` blokidan foydalanib o‘yinni boshlang.
- `go to [x: 0, y: 0]` yordamida baliqning boshlang‘ich joylashuvini belgilang.

#### 3-bosqich: Baliq yo‘nalishini boshqarish:
- `point in direction [90]` yordamida baliqni ma’lum yo‘nalishga qarating.
- Turli yo‘nalishlarni sinab ko‘ring (masalan, `point in direction [180]` — chapga, `90` — o‘ngga qarash uchun).
- Baliq ekran chetiga tegsa, `if <touching edge>` yordamida yo‘nalishini o‘zgartiring.

#### 4-bosqich: Qurbaqa sprajti sozlanishi:
- Qurbaqa **o‘yinchi tomonidan** klaviatura tugmalari orqali boshqariladi.
- `when [right arrow] key pressed` va `when [left arrow] key pressed` bloklaridan foydalanib qurbaqani o‘ngga yoki chapga harakatlantiring.

#### 5-bosqich: Ovozi va animatsiya qo‘shish:
- Qurbaqa baliqni tutganda `play sound [sound] until done` bloki yordamida ovozli effekt qo‘shing.
- Ixtiyoriy ravishda to‘qnashuv vaqtida baliq rangini o‘zgartirish yoki qurbaqani “sakratish” kabi animatsiyalar qo‘shing.

### 3. O‘qituvchiga Maslahatlar

- Bu loyihaning eng muhim qismi **yo‘nalishni boshqarish** hisoblanadi — o‘quvchilarga `point in direction` yordamida yo‘nalishni qanday boshqarishni yaxshi tushuntiring.
- Harakat faqat bir yo‘nalishda emasligini tushuntiring — o‘quvchilar turli yo‘nalishlarda harakat qilishni sinab ko‘rishlari kerak.

### 4. Muammolar va Yechimlar

- **Muammo**: Baliq ekran chetiga tegsa yo‘nalishni o‘zgartirmaydi.
  - **Yechim**: `if <touching edge>` bloki to‘g‘ri joylashtirilganligini va `point in direction` bloki ishlatilganligini tekshiring.
- **Muammo**: Qurbaqa juda tez harakat qiladi.
  - **Yechim**: `change x by [qiymat]` blokidagi qiymatni kamaytirib, harakatni sekinlashtiring.
- **Muammo**: Baliq qurbaqani “tuta olmaydi”.
  - **Yechim**: `if <touching [frog]>` bloki to‘g‘ri joyda ekanligini va kerakli sprajt tanlanganligini tekshiring.

### 5. Qo‘shimcha G‘oyalar

- **Taymer** qo‘shing: Vaqt tugagach o‘yin tugaydi.
- **Darajalar (levels)** kiriting: Har bir bosqichda baliq tezroq harakatlanadi.
- **Yangi qahramonlar yoki to‘siqlar** qo‘shing: Masalan, qurbaqa boshqa mavjudotlardan qochishi kerak.
- **Ovoz effektlari** kiriting: Qurbaqa baliqni tutganda yoki baliq qochib ketganda tovushlar eshittiring.

## Xulosa

Loyiha yakunida o‘quvchilar sprajtlarning **yo‘nalishini boshqarish**ni o‘rganadilar (`point in direction` bloki yordamida), bu esa dinamik va interaktiv o‘yinlar yaratish uchun juda muhim ko‘nikmadir. Ular shuningdek **sprajt harakati**, **to‘qnashuv aniqlash** va **klaviatura orqali boshqarish** kabi asosiy dasturlash tushunchalarini ham amalda qo‘llaydilar. Ushbu loyiha kelgusidagi murakkab o‘yin mexanizmlariga tayyorgarlik vazifasini bajaradi.

---

### **Eslatma**: **Fish & Frog** loyihasi — sprajt harakati va yo‘nalishini mashq qilish uchun juda mos. O‘yinning o‘zi oddiy bo‘lsa ham, sprajtlar yo‘nalishini boshqarishni tushunish — o‘quvchilarning dasturlashda keyingi bosqichga o‘tishini osonlashtiradi.
