# Hisobot — Parazitologiya bo'yicha mavzu testlari (1-etap: 001–025)

Rol: test tuzuvchi, Parazitologiya bo'yicha oliy toifali shifokor.
Manba: `Мавзу.zip` (121 ta `NNN.docx`). Natija papkasi: `Тест/`. Shablon: `shablon.xlsx`.
Bu etapda 001–025 mavzulari bajarildi (5 partiya × 5 mavzu). 026–121 mavzulari hali bajarilmagan.

## 1. Fayllar va savollar soni
- Fayllar: 25 ta (`Тест/001.xlsx` … `Тест/025.xlsx`).
- Savollar: 250 ta (har faylda 10 ta). Har savolda 5 variant (A–E), bitta to'g'ri javob, izoh — mavzu matnidan «» ichida aynan iqtibos.
- QA (`build_tests.js`, qat'iy rejim): xato 0. Qayta o'qish (jszip): savollar soni, harf taqsimoti, ketma-ket 3 ta bir xil harf yo'qligi, izohda iqtibos borligi, kirill aralashmasi yo'qligi — barchasi o'tdi (xato fayl 0).

## 2. A/B/C/D/E taqsimoti
A = 50, B = 50, C = 50, D = 50, E = 50.

## 3. To'g'ri javob 10% dan uzun bo'lgan savollar ulushi
37 ta savol (14,8%). Ular QA'da ogohlantirish sifatida chiqdi; 30% dan uzun hech biri yo'q.

## 4. Mavzu matnlari o'rtasidagi farqlar va nomuvofiqliklar
1. 011 va 012: matnlar so'zma-so'z bir xil (saskob usuli, enterobioz). 012 sarlavhasi «so'roq usuli» haqida, lekin matnda so'roq usuli yo'q. 012 savollari matnning boshqa bo'limlaridan tuzildi (011 savollari bilan takrorlanmaydi).
2. 004 va 013: matnlar bir xil (lambliya joylashishi). 013 savollari 004 dan farqli jihatlar bo'yicha yozildi.
3. 007 va 023: matnlar deyarli bir xil (teniarinxozni davolash dorilari), faqat bitta iqtibos belgisi farq qiladi. 023 savollari 007 dan farqli jihatlar bo'yicha yozildi.
4. 006 (primakin odatda 14 kun) va 025 (14 kunlik «qisqa muddatli» yoki uzoqroq sxema, ba'zi mamlakatlarda haftalik qisqa sxema): primakin kursi muddati talqini farq qiladi. Savollarda faqat «odatda 14 kun» iqtibosi ishlatildi.
5. 004/013 («sabzavot va mevalarni oqar suvda yaxshilab yuvish») va 019 («oziq-ovqatni sovuq suv emas, iliq toza suvda yuvish»): yuvish bo'yicha tavsiyalar bir-biriga mos kelmaydi. Bu savol qilinmadi.
6. 021: «suv bilan eritilmasdan bo'yash» va «bo'yoqsiz holatda qon eritrotsitlardan tozalanmaydi, parazit osonroq ko'rinadi» — tayyorlash texnikasi tavsifi ichki ziddiyatli. Bu savol qilinmadi.
7. 016: «tuxumlar ingichka ichakda chiqmaydi, lichinka yo'g'on ichakda voyaga yetadi» — odatdagi hayot sikli tavsifidan farq qiladi. Bu savol qilinmadi.
8. 009: sovuq mavsumda «bemor kontaktlaridan yuqtirishi» haqidagi gap bezgakning vektor orqali yuqishi bilan ziddiyatli. Bu savol qilinmadi.
9. 007/023 («Taeniarhynchus saginatus») va 024 («Taenia saginata»): lotincha nom turlicha yozilgan. 024 da «Taenia saginata» iqtibosi o'zgartirilmadi.
10. 022: tropik bezgakda eritrotsitar sikl «taxminan 48 soat» deb yozilgan, ayni paytda isitma «ketma-ket va uzoqroq» kechishi aytilgan. 002 da tropik bezgakda isitma «kundalik» deb yozilgan. 022 dagi 48 soatlik band savol qilinmadi.
11. Imlo: 006 va 025 «xlorokin», 022 «xloroxin»; 019 sarlavhasida «Lyamblya», matnda «Lamblya», 004/013 da «Lamblia». Iqtiboslar matndagi yozuv bilan olindi.

## 5. `[tasdiqlanmagan]` belgili faktlar
Hech biri savolning to'g'ri javobi yoki variantiga kiritilmadi.
- 006: aniq dozalar, kuzatuv jadvali (kun va oy hisobi); adabiyotlar ro'yxatidagi 3-manba.
- 010: dispanser kuzatuvining aniq muddati (matnda ikki marta); adabiyotlar ro'yxatidagi 3-manba.
- 011 va 012: ostritsa tuxumi o'lchami (50–60 mikrometr); 3-manba.
- 016: bitta urg'ochi gijja qo'yadigan tuxum soni; 3-manba.
- 017: sog'lom organizmni zararlash uchun zarur sporozoit soni (matnda ikki marta).
- Faqat adabiyotlar ro'yxatida belgilangan mavzular: 001, 002, 003, 004, 005, 007, 009, 013, 014, 019, 020, 023, 024, 025.

## Eslatma
Tibbiy mazmun (dozalar, muddatlar, me'yorlar) mutaxassis tomonidan tekshirilishi kerak. Skript faqat matn mosligini tekshiradi.
