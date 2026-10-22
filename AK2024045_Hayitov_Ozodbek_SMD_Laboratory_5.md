# LABORATORIYA 5

1. Oddiy funksiyada lambda obyekt yaratish va funksiya chaqiradigan qo’shimcha xarajatlarni ko’payitiradi. inline kodni chaqirgan joyga joylashtirishi xarajatlarni kamaytiradi. Lambda ishlatilmaydigan funksiyalarda inline foydasi kam.

2. inline lambda ichidagi return tashqi funksiyadan ham chiqishi mumkin. label kerakli joydan chiqishni belgilaydi. break siklni to’xtatadi, continue keyingi takrorlashga o’tadi. Birinchi xatoda return, noto’g’ri raqamlarni o’tkazishda continue ishlatiladi.

3. inline lambda keyinroq ishlatish uchun obyekt sifatida saqlamaydi. noinline uni saqlab, keyin bajarsa bo’ladi. Qayta urinish uchun kerakli bo‘lgan lambdani noinline qilish kerak.

4. crossinline lambda tashqi funksiyadan non-local return orqali chiqishga taqiq qo’yadi, lekin inline qilsa bo’ladi. noinline lambda obyekt sifatida ishlatishga ruhsat beradi. Erta chiqish uchun shartlardan foydalaniladi

5. Generic turdagi dastur ishlaganda aniq saqlanmaydi. reified inline funksiya ichida tur parametridan foydalansa bo’ladi. Bu narsa klassni aniqlash osonlashadi. Nothing ga o’xshash turni oddiy klass sifatida ishlatib bo’lmaydi.

6. Property accessor ni inline qilish mumkin, lekin unda backing field bo’lmasligi kerak. Kompilyator accessor kodini chaqirgan joyga joylaydi. Bu kichik va ko’p ishlatiladigan yordamchilarda foydaliroq bo‘ladi.

7. public inline funksiya boshqa modullarda ham ishlatilgani uchun, uning internal e’lonlarga boglanishi muammo yaratadi. @PublishedApi internal elondan inline funksiya ichida foydalanishga ruhsat beradi. Faqat foydali funksiyalarni inline qilish kerak

8. typealias yangi tur yaratmay mavjud turni nomini o’zgartiradi. Shuning uchun ikkita string aliasining argumentlari almashtirganda, kompilyator xatoni aniqlolmaydi. Kodni o’qishni osonlashtirgani tur xavfsizligini taminlamaydi.

10. Nothing normal yakunlanmaydigan funksiyalarni qiymatsiz ko’rsatadigan turga kiradi. Jiddiy xatolarda dasturni darhol to’xtatish eng maqul lekin tiklanish mumkin bo’lgan xatolarni boshqarish yaxshiroq.
