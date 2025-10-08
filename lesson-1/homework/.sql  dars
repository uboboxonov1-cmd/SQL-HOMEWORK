EASY
1. 	DATA –bu faktlar, raqamlar, so‘zlar yoki kuzatishlar bo‘lib, ular kompyuterda saqlanadi, tahlil qilinadi va ishlov beriladi. Ma’lumotlar yoki raqamlar to‘plami bo‘lib, tahlil qilish, saqlash va uzatish uchun ishlatiladi. Informatika, statistik tahlil va ilmiy tadqiqotlarda keng qo‘llaniladi
Database — bu ma’lumotlarni tartibli saqlash, boshqarish va yangilash uchun mo‘ljallangan tizim.
Ya’ni, bu joyda siz turli ma’lumotlarni (ism, telefon raqam, narx, mahsulot, talaba baholari va hokazo) saqlaysiz.
Relational database — bu ma’lumotlar jadval (table) ko‘rinishida saqlanadigan va ular bir-biri bilan aloqada bo‘ladigan ma’lumotlar bazasi turidir.
TABLE — bu ma’lumotlarni tartibli va tuzilgan holda saqlaydigan jadvaldir. Ma’lumotlar bazasida (database) ma’lumotlarni ustunlar (columns) va satrlar (rows) ko‘rinishida saqlovchi tuzilma (structure).. 
2. 
1.Relatsion ma’lumotlar bazasi boshqaruvi (RDBMS) 
SQL Server — bu relatsion ma’lumotlar bazasi boshqaruv tizimi, ya’ni ma’lumotlar jadval (table) ko‘rinishida saqlanadi va ular kalitlar (primary key, foreign key) orqali o‘zaro bog‘langan bo‘ladi.

2.Yuqori darajadagi xavfsizlik (Security)
SQL Server’da ma’lumotlarni himoya qilish juda kuchli.
3.Zaxira nusxa olish va tiklash (Backup & Restore)
SQL Server sizga ma’lumotlar bazasining zaxira nusxasini (backup) olish va kerak bo‘lganda tiklash (restore) imkonini beradi.
4.Ma’lumotlarni tahlil qilish va hisobot tayyorlash vositalari
SQL Server quyidagi vositalarni o‘z ichiga oladi:
•	SSIS – ma’lumotlarni ko‘chirish va avtomatlashtirish uchun
•	SSAS – ma’lumotlarni tahlil qilish uchun
•	SSRS – hisobot (report) tayyorlash uchun
5.Yuqori tezlik va kengayuvchanlik (Performance & Scalability) -SQL Server katta hajmdagi ma’lumotlar bilan tez ishlay oladi
3.
1. Windows Authentication	Bu rejimda foydalanuvchi Windows tizimidagi login va parol orqali tizimga kiradi. Ya’ni, Windows foydalanuvchisi avtomatik tarzda SQL Server’da tan olinadi.	Bu eng xavfsiz usul hisoblanadi, chunki foydalanuvchi Windows tizimi orqali tasdiqlanadi.
2. SQL Server Authentication	Bu rejimda foydalanuvchi SQL Server uchun alohida login va parol yaratadi (masalan: login = admin, password = 1234).	Bu usul SQL Server’ga kirishni Windows tizimidan mustaqil ravishda amalga oshirish imkonini beradi.

  MEDIUM
1. create database SChoolIDB
2. CREATE TABLE STUDENTS
3. Windows Authentication → Windows foydalanuvchi hisobidan kirish.
HARD
1. DQL (Data Query Language) — Ma’lumotlarni so‘rash tili
Vazifasi: Ma’lumotlar bazasidan ma’lumotlarni so‘rab olish uchun ishlatiladi.
DML (Data Manipulation Language) — Ma’lumotlarni boshqarish tili
Vazifasi: Jadvaldagi ma’lumotlarni qo‘shish, o‘zgartirish, o‘chirish uchun ishlatiladi.
DDL (Data Definition Language) — Ma’lumotlar tuzilmasini aniqlash tili Vazifasi: Jadval, ma’lumotlar bazasi yoki ustunlarning tuzilmasini yaratish, o‘zgartirish, o‘chirish uchun ishlatiladi.
SQL Server Authentication → SQL Server’ning o‘z login va paroli orqali kirish.
2. INSERT INTO Students (ID, Name, Age)
VALUES
(1, 'Ali_Karimov', 20),
(2, 'Dilnoza_Rahimova', 19),
(3, 'Jasur_Ismoilov', 21);
3.
  AdventureWorksDW2022 faylini yuklab olamiz va  Start Menu → SQL Server Management Studio (SSMS) ni ishga tushiramiz.Serverga Windows Authentication yoki SQL Server Authentication orqali ulanamiz. Databases” bo‘limiga o‘tish
•	Chap tomonda Object Explorer oynasida “Databases” papkasini topish.
•	“Databases” ustiga o‘ng tugma (Right-click) bosish.
•	So‘ng Restore Database… ni tanlash.
________________________________________
 “Restore Database” oynasida manbani tanlash
•	“Source” bo‘limidan Device ni tanlash.
•	So‘ng […] tugmasini bosish.
________________________________________
 Backup faylni tanlash(.bak fayl)
•	Yangi oynada Add tugmasini bosish.
•	Sizda mavjud AdventureWorksDW2022.bak fayl joylashgan papkani tanlash.
Masalan:
•	C:\Backups\AdventureWorksDW2022.bak
•	Faylni tanlab, OK bosish.
________________________________________
 Tiklash turini tanlash
•	“Restore plan” bo‘limida Restore katakchasini belgilaymiz (✅).
•	Fayl tanlanganidan so‘ng, u avtomatik ravishda “Database” nomini ko‘rsatadi.
(Masalan: AdventureWorksDW2022)
________________________________________
 Destination (joylashuv) ni tekshirish
•	“Destination Database” nomi to‘g‘riligini tekshiramiz 
•	Masalan, nomi: AdventureWorksDW2022
________________________________________Files yoki Options bo‘limini sozlash
•	Chap tomonda Options bo‘limiga kirish
   Tiklashni boshlash 
•	Hamma sozlamalar to‘g‘ri bo‘lsa → OK tugmasini bosish.
•	Tiklash jarayoni boshlanadi va 1–2 daqiqada tugaydi.
________________________________________ 9.Tugaganini tekshirish
•	Jarayon tugagach, xabar chiqadi:
✅ “Database 'AdventureWorksDW2022' restored successfully.”
•	Endi Object Explorer → Databases papkasida yangi baza paydo bo‘ladi:
AdventureWorksDW2022





