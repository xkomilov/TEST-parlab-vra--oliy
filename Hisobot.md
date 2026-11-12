# Hisobot — Parazitologiya bo'yicha mavzu testlari (001–050)

Rol: test tuzuvchi, Parazitologiya bo'yicha oliy toifali shifokor.
Manba: `Мавзу.zip` (121 ta `NNN.docx`). Natija papkasi: `Тест/`. Shablon: `shablon.xlsx`.
Bajarilgan: 001–050 mavzulari (10 partiya × 5 mavzu). 051–121 mavzulari hali bajarilmagan.

## 1. Fayllar va savollar soni
- Fayllar: 50 ta (`Тест/001.xlsx` … `Тест/050.xlsx`).
- Savollar: 500 ta (har faylda 10 ta). Har savolda 5 variant (A–E), bitta to'g'ri javob, izoh — mavzu matnidan «» ichida aynan iqtibos.
- QA (`build_tests.js`, qat'iy rejim): xato 0. Qayta o'qish (jszip): savollar soni, harf taqsimoti, ketma-ket 3 ta bir xil harf yo'qligi, izohda iqtibos borligi, kirill aralashmasi yo'qligi — barchasi o'tdi (xato fayl 0).

## 2. A/B/C/D/E taqsimoti
A = 100, B = 100, C = 100, D = 100, E = 100.

## 3. To'g'ri javob 10% dan uzun bo'lgan savollar ulushi
73 ta savol (14,6%). Ular QA'da ogohlantirish sifatida chiqdi; 30% dan uzun hech biri yo'q.

## 4. Mavzu matnlari o'rtasidagi farqlar va nomuvofiqliklar
Bir xil matnli mavzular (savollar bir-biridan farqli jihatlar bo'yicha yozildi):
1. 011 va 012: matnlar so'zma-so'z bir xil (saskob usuli, enterobioz). 012 sarlavhasi «so'roq usuli» haqida, lekin matnda so'roq usuli yo'q.
2. 004 va 013: matnlar bir xil (lambliya joylashishi).
3. 007 va 023: matnlar deyarli bir xil (teniarinxozni davolash dorilari).
4. 016 va 027: matnlar bir xil (ostritsaning oxirgi xo'jayini).
5. 009, 030 va 050: matnlar bir xil (bezgak yuqishi). 030 va 050 sarlavhalari 009 dan farq qiladi, lekin matni o'sha.
6. 014 va 049: matnlar bir xil (askaridozning yuqishi va profilaktikasi).
7. 022 va 035: matnlar bir xil (P. falciparum shizogoniyasi).
8. 034 va 046: matnlar bir xil (mikroskopni saqlash).
9. 037 va 044: matnlar bir xil (nefrotik sindrom).

Sarlavha va matn orasidagi farqlar:
10. 047 sarlavhasi «so'nggi bo'shlig'i» deb yozilgan, matn esa askaridaning oxirgi xo'jayini haqida. 032 sarlavhasi «Buqa tizmasining oxirgi boshlig'i», matnda «Xo'kiz tizmasi». 045 sarlavhasi aniq harorat haqida, matnda esa aniq qiymat «tasdiqlanishi kerak» deb qoldirilgan.

Ichki va mavzular aro ziddiyatlar (bu fikrlar savol qilinmadi):
11. 006 (primakin odatda 14 kun) va 025 (14 kunlik «qisqa muddatli» yoki uzoqroq sxema, ba'zi mamlakatlarda haftalik qisqa sxema): primakin kursi muddati talqini farq qiladi. Savollarda faqat «odatda 14 kun» iqtibosi ishlatildi.
12. 004/013 («sabzavot va mevalarni oqar suvda yaxshilab yuvish») va 019 («oziq-ovqatni sovuq suv emas, iliq toza suvda yuvish»): yuvish bo'yicha tavsiyalar mos kelmaydi.
13. 021: «suv bilan eritilmasdan bo'yash» va «bo'yoqsiz holatda qon eritrotsitlardan tozalanmaydi, parazit osonroq ko'rinadi» — tayyorlash texnikasi tavsifi ichki ziddiyatli.
14. 016/027: «tuxumlar ingichka ichakda chiqmaydi, lichinka yo'g'on ichakda voyaga yetadi» — odatdagi hayot sikli tavsifidan farq qiladi.
15. 009/030/050: sovuq mavsumda «bemor kontaktlaridan yuqtirishi» haqidagi gap bezgakning vektor orqali yuqishi bilan ziddiyatli.
16. 007/023 («Taeniarhynchus saginatus»), 024 va 032 («Taenia saginata»): lotincha nom turlicha yozilgan.
17. 022/035: tropik bezgakda eritrotsitar sikl «taxminan 48 soat» deb yozilgan, ayni paytda isitma «ketma-ket va uzoqroq» kechishi aytilgan. 002 da tropik bezgakda isitma «kundalik» deb yozilgan.
18. 028: bolalar muassasasiga qaytish uchun «tekshiruv natijasi ijobiy ekanligi tasdiqlanadi» deb yozilgan. Mantiqan manfiy natija kutiladi. Bu gap savol qilinmadi.
19. 033 (lichinka jigarga va yurakka, so'ngra o'pkaga boradi) va 014/047/049 (jigar va yurak ko'rsatilmasdan, qon bilan o'pkaga boradi): migratsiya yo'li turlicha tasvirlangan.
20. 045: Kirishda «15–16 daraja atrofida yetarli emas», asosiy qismda esa «16–18 daraja va undan yuqori bo'lganda rivojlanish sezilarli davom etadi» deyilgan. Ikkinchi raqam `[tasdiqlanmagan]` bilan belgilangan.
21. Imlo: 006 va 025 «xlorokin», 022/035 «xloroxin»; 019 sarlavhasida «Lyamblya», matnda «Lamblya», 004/013 da «Lamblia». Iqtiboslar matndagi yozuv bilan olindi.

## 5. `[tasdiqlanmagan]` belgili faktlar
Hech biri savolning to'g'ri javobi yoki variantiga kiritilmadi.
- 006: aniq dozalar, kuzatuv jadvali (kun va oy hisobi).
- 010: dispanser kuzatuvining aniq muddati.
- 011 va 012: ostritsa tuxumi o'lchami (50–60 mikrometr).
- 016 va 027: bitta urg'ochi ostritsa qo'yadigan tuxum soni.
- 017: sog'lom organizmni zararlash uchun zarur sporozoit soni.
- 042: urg'ochi askarida kuniga qo'yadigan tuxum soni (ikki yuz mingdan ortiq).
- 045: P. vivax uchun o'rtacha sutkalik harorat (16–18 daraja).
- Faqat adabiyotlar ro'yxatida belgilangan mavzular: 001–005, 007, 009, 013, 014, 019, 020, 023–025, 028, 029 va boshqalar.

## Eslatma
Tibbiy mazmun (dozalar, muddatlar, me'yorlar) mutaxassis tomonidan tekshirilishi kerak. Skript faqat matn mosligini tekshiradi.
