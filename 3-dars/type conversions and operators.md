# JavaScript: Type Conversion (Turga Aylantirish)

    JavaScript’da qiymatlar bir turdan boshqasiga avtomatik yoki qo‘l bilan o‘zgartirilishi mumkin. Bu jarayon type conversion deb ataladi.

# 1. Avtomatik Type Conversion (Type Coercion)

    JavaScript ba’zida o‘zi avtomatik tarzda qiymat turini o‘zgartiradi, ayniqsa arifmetik amallar yoki matn bilan ishlaganda.
    Number() — qiymatni raqamga aylantiradi.

    String() — qiymatni matnga aylantiradi.

    Boolean() — qiymatni mantiqiy (true/false) turga aylantiradi.

# 3. Esda Tutish Zarur Bo‘lgan Holatlar

Matnga qo‘shish (+) ko‘pincha stringga aylantiradi.

Arifmetik amallar (-, \*, /) qiymatni raqamga aylantiradi.

JavaScript: Operatorlar (Amallar)
JavaScript’da operatorlar — bu qiymatlar ustida amallar bajaruvchi belgilar yoki so‘zlar.

🔹 1. Aritmetik Operatorlar (Matematik amallar)

- — qo‘shish

* — ayirish

- — ko‘paytirish

/ — bo‘lish

% — qoldiqli bo‘lish

\*\* — darajaga ko‘tarish

++ — birga oshirish (inkrement)

-- — birga kamaytirish (dekrement)

🔹 2. Taqqoslash Operatorlari (Comparison)
== — teng

!= — teng emas

=== — aynan teng (turini ham tekshiradi)

!== — aynan teng emas

> — katta

< — kichik

> = — katta yoki teng

<= — kichik yoki teng

🔹 3. Mantiqiy Operatorlar (Logical)
&& — va (ikkalasi ham true bo‘lsa)

|| — yoki (bittasi true bo‘lsa)

! — inkor (teskari qiymat)

🔹 4. qisqartma Operatorlari (Assignment)
= — o‘zlashtirish

+= — qo‘shib o‘zlashtirish

-= — ayirib o‘zlashtirish

\*= — ko‘paytirib o‘zlashtirish

/= — bo‘lib o‘zlashtirish

%= — qoldiqli bo‘lib o‘zlashtirish

     JavaScript: Logical Operations (Mantiqiy Amallar)

Mantiqiy operatorlar shartlarni tekshirishda ishlatiladi va true yoki false natijalarini qaytaradi.

🔹 1. && — VA (AND)
Faqat ikkala shart ham to‘g‘ri (true) bo‘lsa, natija true bo‘ladi. Aks holda false.

🔹 2. || — YOKI (OR)
Agar kamida bittasi true bo‘lsa, natija true bo‘ladi. Ikkalasi false bo‘lsa — false.

🔹 3. ! — INKOR (NOT)
Qiymatni teskarisiga aylantiradi: true → false, false → true.

🔹 4. True va Falsy Qiymatlar
JavaScript’da ba’zi qiymatlar true deb, boshqalari false deb baholanadi:

Falsy qiymatlar (har doim false bo‘ladi):

false

0

"" (bo‘sh string)

null

undefined

NaN -- Not a Number

Tru qiymatlar — qolgan barcha qiymatlar true hisoblanadi.

🔹 5. Qisqacha
&& — agar birinchi qiymat false bo‘lsa, keyingisini tekshirmaydi.

|| — agar birinchi qiymat true bo‘lsa, keyingisini tekshirmaydi.
