# Byte Objects vs String Objects

Python-da bayt ob'ektlari:

 Python-da bayt ob'ekti baytlarning o'zgarmas ketma-ketligidir.  U 8 bitli baytlar ketma-ketligini ifodalaydi.  Bayt ob'ektlari ikkilik ma'lumotlarni, masalan, tasvirlar, audio fayllar va siqilgan ma'lumotlarni saqlash uchun ishlatiladi.  Bayt ob'ektlari satr literalidan oldin b prefiksi yordamida yaratiladi.  Masalan, b"salom" bayt ob'ekti bo'lib, "salom" qatorining ASCII tasvirini o'z ichiga oladi.

 Bayt ob'ektlari quyidagi xususiyatlarga ega:

 1. O'zgarmas: Bayt ob'ektlari o'zgarmasdir, ya'ni ularni yaratilgandan keyin o'zgartirib bo'lmaydi.

 2. Indexable: bayt ob'ektlari xuddi satrlar kabi indekslanishi va kesilishi mumkin.

 3. Kodlanishi mumkin: Bayt ob'ektlari UTF-8 yoki ASCII kabi boshqa kodlashlarga kodlanishi mumkin.

 4. Decodable: Bayt ob'ektlari UTF-8 yoki ASCII kabi boshqa kodlashlardan dekodlanishi mumkin.

 Python-da string ob'ektlari:

 Python-da string ob'ekti Unicode belgilarning o'zgarmas ketma-ketligidir.  Satr ob'ekti belgilar ketma-ketligini bitta tirnoq ('...') yoki qo'sh tirnoq ("...") ichiga olish orqali yaratiladi.  Masalan, "hello" - "h", "e", "l", "l" va "o" belgilarni o'z ichiga olgan qator ob'ekti.

 String ob'ektlari quyidagi xususiyatlarga ega:

 1. O'zgarmas: String ob'ektlari o'zgarmasdir, ya'ni ularni yaratilgandan keyin o'zgartirib bo'lmaydi.

 2. Indexable: String ob'ektlari xuddi bayt ob'ektlari kabi indekslanishi va kesilishi mumkin.

 3. Kodlanadigan: String ob'ektlari UTF-8 yoki ASCII kabi boshqa kodlashlarga kodlanishi mumkin.

 4. Decodable: String ob'ektlari UTF-8 yoki ASCII kabi boshqa kodlashlardan dekodlanishi mumkin.

 Bayt ob'yektlari satr ob'ektlari o'rtasidagi asosiy farq shundaki, bayt ob'ektlari ikkilik ma'lumotlarni, string ob'ektlari esa matnli ma'lumotlarni ifodalaydi.  Bayt ob'ektlari tasvirlar va audio fayllar kabi ikkilik ma'lumotlarni saqlash uchun ishlatiladi, string ob'ektlar esa matn ma'lumotlarini, masalan, belgilar qatorlarini saqlash uchun ishlatiladi. 