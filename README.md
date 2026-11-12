# Yondoş — Maxfiylik siyosati

**Kuçga kirgan sana:** 12-noyabr, 2026

Yondoş — kitob öqişni kuzatiş va odatga aylantiriş uçun mobil ilova. Ilovani Xusanboy Tursunov işlab çiqqan va qöllab-quvvatlaydi (keyingi örinlarda — "biz").

Bu hujjat ilova qanday ma'lumot yiğişi, undan nima uçun foydalanişi, kim körişi va siz uni qanday boşqarişingiz mumkinligini tuşuntiradi. Ilovadan foydalanib, siz şu siyosatga rozilik bildirasiz.

---

## 1. Qanday ma'lumot yiğamiz

### Google akkauntingizdan
Ilovaga Google orqali kirasiz. Bunda Google bizga quyidagilarni beradi:
- ismingiz;
- elektron poçta manzilingiz;
- profil rasmingiz.

Google parolingizni biz körmaymiz va saqlamaymiz.

### Siz öziningiz kiritadigan ma'lumotlar
- **Kitoblar:** nomi, muallifi, betlar soni, qaysi betdan boşlaganingiz, holati (rejada / öqilmoqda / tugatilgan) va sanalari.
- **Muqova rasmlari:** kitobga qöşgan rasmlaringiz.
- **Iqtiboslar:** kitoblardan saqlagan parçalaringiz.
- **Profil:** ism va profil rasmini özgartirsangiz — yangisi.
- **Maqsadlar va eslatmalar:** kunlik bet maqsadi, yillik kitob maqsadi, eslatma vaqti, bildirişnomalar yoqilgan-yoqilmagani.
- **Maxfiylik sozlamasi:** profilingiz reytingda anonim körinişi.

### Ilovadan foydalaniş jarayonida
- **Mutolaa faolligi:** har kuni öqilgan betlar soni, XP (ball), streak (ketma-ket kunlar), muzlatişlar, oylik va yillik reyting.
- **Bildirişnoma tokeni:** telefoningizga eslatma yuboriş uçun Firebase beradigan identifikator.

### Telefoningizda qoladigan ma'lumotlar
Ba'zi sozlamalar (masalan, qaysi bayram ekrani körsatilgani) va yuklangan rasmlar keşi faqat telefoningizda saqlanadi va bizga yuborilmaydi.

### Yiğmaydigan ma'lumotlarimiz
- joylaşuv (geolokatsiya);
- kontaktlar, SMS, qöngiroqlar;
- reklama identifikatori — ilovada reklama yöq;
- analitika yoki kuzatuv SDK'lari orqali yiğiladigan ma'lumot.

---

## 2. Ma'lumotdan nima uçun foydalanamiz

- akkauntingizni yaratiş va ilovaga kiritiş;
- kitoblaringiz, iqtiboslaringiz va mutolaa tarixini saqlaş, barça qurilmalaringizda körsatiş;
- XP, streak, muzlatiş va reytingni hisoblaş;
- siz tanlagan vaqtda va kun davomida mutolaa eslatmalarini yuboriş;
- statistika, maqsadlar va bayram ekranlarini körsatiş;
- ilova işini yaxşilaş va xatolarni tuzatiş.

Ma'lumotlaringizni sotmaymiz va reklama uçun işlatmaymiz.

---

## 3. Boşqalar nimani köradi

Yondoşda umumiy reyting bor. Ilovaga kirgan boşqa foydalanuvchilar quyidagilarni körişi mumkin:
- ismingiz va profil rasmingiz;
- XP, streak, reytingdagi örningiz va natijalaringiz;
- kitoblar javoningiz, iqtiboslaringiz va mutolaa faolligingiz.

**Anonim rejim:** profil sozlamalarida "maxfiy" rejimni yoqsangiz, boşqalar reytingda ismingiz va rasmingiz örniga "Anonim" va umumiy belgini köradi.

Elektron poçta manzilingiz ilovada boşqa foydalanuvchilarga körsatilmaydi.

**Ulaşiş:** natija kartasini Telegram yoki boşqa ilovaga yuborsangiz, rasm siz tanlagan ilovaga ötadi. Undan keyin u şu ilovaning maxfiylik qoidalariga böysunadi.

---

## 4. Telefon ruxsatlari

Ruxsatlar faqat kerakli payt söraladi. Ularni istalgan vaqt telefon sozlamalaridan öçirişingiz mumkin.

| Ruxsat | Nima uçun |
|---|---|
| Kamera va rasmlar | Kitob muqovasi yoki profil rasmini tanlaş |
| Rasmlarga saqlaş | Natija kartasini galereyaga saqlaş (faqat "Saqlaş" bosilganda) |
| Bildirişnomalar | Mutolaa eslatmalari |

---

## 5. Uçinçi tomon xizmatlari

Ilova Google xizmatlari ustida işlaydi:
- **Firebase Authentication** — Google orqali kiriş;
- **Cloud Firestore** — kitoblar, faollik va profil ma'lumotlari;
- **Firebase Storage** — muqova va profil rasmlari;
- **Cloud Functions** — XP, streak va reyting hisobi, eslatmalar;
- **Firebase Cloud Messaging** — bildirişnomalar;
- **Firebase Remote Config** — ilova sozlamalari (masalan, bosh sahifadagi iqtibos).

Bu xizmatlar texnik ma'lumotlarni (masalan, qurilma turi va ilova versiyasi) qayta işlaşi mumkin. Batafsil: [Google maxfiylik siyosati](https://policies.google.com/privacy) va [Firebase maxfiyligi](https://firebase.google.com/support/privacy).

---

## 6. Ma'lumot qayerda va qança saqlanadi

Ma'lumotlar Google Cloud (Firebase) serverlarida saqlanadi va ular Özbekistondan taşqarida joylaşgan bölişi mumkin. Ilova va serverlar orasidagi aloqa şifrlangan (HTTPS).

Ma'lumotlaringiz akkauntingiz faol ekan saqlanadi. Akkaunt öçirilganda ular 30 kun içida butunlay öçiriladi.

---

## 7. Sizning huquqlaringiz

- **Köriş va tahrirlaş:** kitoblar, iqtiboslar, maqsadlar va profil ilovaning özida tahrirlanadi.
- **Öçiriş:** kitob va iqtiboslarni ilovada istalgan vaqt öçirişingiz mumkin.
- **Akkauntni butunlay öçiriş:** quyidagi aloqa manzillaridan biriga sörov yuboring. Akkauntingiz va unga boğliq barça ma'lumotlar (kitoblar, rasmlar, iqtiboslar, faollik, reyting) 30 kun içida öçiriladi.
- **Bildirişnomalarni öçiriş:** ilova sozlamalaridan yoki telefon sozlamalaridan.

---

## 8. Bolalar

Ilova 13 yoşdan kiçik bolalarga möljallanmagan. 13 yoşdan kiçik bolaning ma'lumoti bizga tuşganini bilsangiz, biz bilan boğlaning — uni öçirib taşlaymiz.

---

## 9. Siyosatdagi özgarişlar

Bu siyosat yangilanişi mumkin. Muhim özgarişlar bölsa, ilova orqali xabar beramiz. Yuqoridagi "Kuçga kirgan sana" oxirgi tahrir sanasini bildiradi.

---

## 10. Aloqa

Savollar yoki ma'lumotni öçiriş sörovi bölsa:
- **Telegram:** [@xusanboy_tursunov](https://t.me/xusanboy_tursunov)
- **Elektron poçta:** [tursunovkhusanboy@gmail.com]
