# JavaScript nima?

        masalan: HTML odam ning skeleti bolsa
                 CSS unga style beradi
                 JavaScript esa uni harakatga keltiradi

# Node JS ornatish

                agar biz JS dagi malumotlarni yurgizmoqchi bolsak node console da chiqarmoqchi bolsak Node JS ni ornatish kerak boladi

# JS ni 3 xil usulda compile qilsa boladi

                in HTML -- browser -- f12
                in node console -- vs code terminal
                online js compilers

# Variables -- ozgaruvchilar

                O‘zgaruvchi nima?
                 O‘zgaruvchi – bu ma’lumotni saqlash uchun ajratilgan joy (xotira) bo‘lib, unga nom beriladi.

                Har xil ma’lumotlarni (string, number, boolean va h.k.) vaqtincha saqlash uchun ishlatiladi.
                ozgaruvchi yaratish bizga ishimizni ancha osonlashtirib beradi
                bitta katta matn ni har doim yozib otiravermaymizda ozgaruvchiga osha value ni biriktirib qoyamiz
                va hohlagan joyimiz da ishlata olamiz osha matnni.

# O‘zgaruvchilarni e’lon qilish:

        JavaScript’da ozgaruvchini uch xil kalit so‘z bilan e’lon qilinadi:
        var – ozgaradigan qiymat(ES5gacha)
        let – o‘zgaradigan qiymat (ES6 dan boshlab)
        const – o‘zgarmas qiymat (ES6 dan boshlab)
        let bilan o‘zgaruvchi e’lon qilish:
        let ism = "Ali";
        let yosh = 17;

        ism = "Vali"; // qiymatini o‘zgartirish mumkin
        const bilan o‘zgarmas o‘zgaruvchi:
        javascript
        const PI = 3.14;
        PI = 3.15; // Qiymatini o‘zgartirib bo‘lmaydi

# Nomlash qoidalari:

        Harf yoki _ bilan boshlanishi kerak.

        Son bilan boshlanmasligi kerak.

        JavaScript kalit so‘zlaridan foydalansa bo‘lmaydi  (let, var, if, for, h.k.)     reserved keywords --- band qilingan keywordlar

        camelCase usuli tavsiya etiladi

# Datatypes

Datatypelar 2 turga bolinadi
1.primitive
2.non-primitive

# (Primitive data types):

Number (sonlar)

        Butun sonlar: 1, 100, -45

        O'nlik sonlar: 3.14, -0.5

String (matnlar)

        matnlar ketma-ketligi: "Hello", 'Salom'

Boolean (mantiqiy)

        Faqat 2 qiymat oladi: true yoki falsenode

Undefined -- hech narsa yoq hatto box ham
Null --- box bolsa box bor ichida hech narsa yoq

        MAX-SAFE-INTEGER ---- js dagi eng katta sonni aniqlash uchun
         MIN-SAFE-INTEGER ---- js dagi eng kichik sonni aniqlash uchun

BigInt

        Juda katta sonlar bilan ishlash uchun: 12345678901234567890n

#(Non-primitive):
Object: Object, Array, Function
Object (obyektlar)--- bitta object ga tegishli narsa yozladi
let person = { name: "Ali", age: 25 };
Array (massivlar) --- hohlagan turdagi datatype ni yozsak boladi

        let fruits = ["olma", "banan", "nok"];

    Function (funktsiyalar)

        function salom() {
                console.log("Salom!");
        }
        salom();
