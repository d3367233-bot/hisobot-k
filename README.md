
<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Elektr Amaliyoti Mashg'ulotlari Qo'llanmasi</title>
    <style>
        :root {
            --primary-color: #1e3a8a;
            --secondary-color: #3b82f6;
            --bg-color: #f8fafc;
            --card-bg: #ffffff;
            --text-color: #334155;
            --accent-color: #f59e0b;
        }
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            line-height: 1.6;
        }
        header {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: white;
            padding: 30px 20px;
            text-align: center;
            box-shadow: 0 4px 6px -1px rgba(0,0,0,0.1);
        }
        header h1 {
            font-size: 24px;
            margin-bottom: 10px;
        }
        header p {
            font-size: 14px;
            opacity: 0.9;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 0 15px;
            display: grid;
            grid-template-columns: 300px 1fr;
            gap: 20px;
        }
        @media (max-width: 768px) {
            .container {
                grid-template-columns: 1fr;
            }
            .sidebar {
                position: static !important;
                max-height: 300px;
                overflow-y: auto;
            }
        }
        .sidebar {
            background-color: var(--card-bg);
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 1px 3px rgba(0,0,0,0.1);
            position: sticky;
            top: 20px;
            max-height: calc(100vh - 40px);
            overflow-y: auto;
        }
        .sidebar h3 {
            margin-bottom: 15px;
            color: var(--primary-color);
            font-size: 16px;
            border-bottom: 2px solid #e2e8f0;
            padding-bottom: 5px;
        }
        .sidebar ul {
            list-style: none;
        }
        .sidebar ul li {
            margin-bottom: 8px;
        }
        .sidebar ul li a {
            display: block;
            padding: 8px 12px;
            color: var(--text-color);
            text-decoration: none;
            border-radius: 4px;
            font-size: 13px;
            transition: all 0.2s;
            border-left: 3px solid transparent;
        }
        .sidebar ul li a:hover {
            background-color: #eff6ff;
            color: var(--secondary-color);
            border-left-color: var(--secondary-color);
        }
        .content {
            display: flex;
            flex-direction: column;
            gap: 25px;
        }
        .card {
            background-color: var(--card-bg);
            padding: 25px;
            border-radius: 8px;
            box-shadow: 0 1px 3px rgba(0,0,0,0.1);
            border-top: 4px solid var(--primary-color);
            scroll-margin-top: 20px;
        }
        .card h2 {
            font-size: 18px;
            color: var(--primary-color);
            margin-bottom: 10px;
        }
        .badge {
            display: inline-block;
            background-color: #f1f5f9;
            color: #475569;
            padding: 4px 10px;
            border-radius: 20px;
            font-size: 12px;
            font-weight: 600;
            margin-bottom: 15px;
            border: 1px solid #e2e8f0;
        }
        .card-body p {
            margin-bottom: 12px;
            text-align: justify;
            font-size: 14px;
        }
        .card-body ul {
            margin-left: 20px;
            margin-bottom: 15px;
            font-size: 14px;
        }
        .card-body ul li {
            margin-bottom: 5px;
        }
        footer {
            text-align: center;
            padding: 20px;
            margin-top: 40px;
            background-color: #1e293b;
            color: white;
            font-size: 12px;
        }
    </style>
</head>
<body>

<header>
    <h1>Elektr Amaliyoti Mashg'ulotlari Elektron Qo'llanmasi</h1>
    <p>Rasmda keltirilgan 19 ta amaliyot mavzusi bo'yicha to'liq va batafsil tushunchalar platformasi</p>
</header>

<div class="container">
    <div class="sidebar">
        <h3>Mavzular Mundarijasi</h3>
        <ul>
            <li><a href="#mavzu-1">1. Dasturga kirish</a></li>
            <li><a href="#mavzu-2">2. Energetik korxona asosiy va yordamchi sexlari to'g'risida ma'lumot</a></li>
            <li><a href="#mavzu-3">3. Ochiq taqsimlash qurilmadagi elektr jihozlariga texnik xizmat ko'rsatish</a></li>
            <li><a href="#mavzu-4">4. Uchirgich va ajratgichlarni joylashtirish bilan tanishish</a></li>
            <li><a href="#mavzu-5">5. O'lchov transformatorlari va nazorat o'lchov asboblari bilan tanishish</a></li>
            <li><a href="#mavzu-6">6. Elektr jihozlarini hisoblash turlari</a></li>
            <li><a href="#mavzu-7">7. Yopiq taqsimlash qurilmadagi elektr jihozlariga texnik xizmat ko'rsatish</a></li>
            <li><a href="#mavzu-8">8. Yotk dagi elektr jihozlari bilan tanishish</a></li>
            <li><a href="#mavzu-9">9. Yotk ning elektr sxemasi bilan ishlash</a></li>
            <li><a href="#mavzu-10">10. Yotk ning himoya vositalari</a></li>
            <li><a href="#mavzu-11">11. Kuchlanishi 1000 V gacha bo'lgan havo elektr o'tkazish liniyalarini ishlatish va ta'mirlash</a></li>
            <li><a href="#mavzu-12">12. Kuchlanishi 1000 V gacha bo'lgan havo elektr o'tkazish liniyalarini ishlatish va ta'mirlashni o'rganish</a></li>
            <li><a href="#mavzu-13">13. Elektr tarmogpi liniyalarini koprikdan, sinovdan o'tkazish va ta'mirlash muddatlari bilan tanishuv</a></li>
            <li><a href="#mavzu-14">14. Havo elektr o'tkazish liniyasini ishga qabul qilish, liniyani yuklama toki bo'yicha ish rejimiga rioya qilish</a></li>
            <li><a href="#mavzu-15">15. Kuch kabel liniyalarini ishlatish va ta'mirlash</a></li>
            <li><a href="#mavzu-16">16. Kabel liniyalarini ko'rikdan, sinovdan o'tkazish va ta'mirlash muddatlari bilan tanishuv</a></li>
            <li><a href="#mavzu-17">17. Kabel elektr ishlatish liniyasini ishga qabul qilish, kabel liniyasini yuklama toki bo'yicha ish rejimiga rioya qilish</a></li>
            <li><a href="#mavzu-18">18. Kuchlanishi 1000 V gacha bo'lgan tarqatish qurilmalarini ishlatish va ta'mirlash</a></li>
            <li><a href="#mavzu-19">19. Tarqatish qurilmalarining elektr jihozlarini ishlashini o'rganish</a></li>
        </ul>
    </div>

    <div class="content">
        <div class="card" id="mavzu-1">
            <h2>1. Dasturga kirish</h2>
            <span class="badge">Ajratilgan soat: 8 (Ish o'rnida: 6, Mustaqil: 2)</span>
            <div class="card-body">
                
        <p><strong>Dasturning maqsadi va vazifalari:</strong> Mazkur ishlab chiqarish amaliyoti dasturi talabalarga energetika korxonalarining tuzilishi, undagi elektr jihozlarining ishlash prinsiplari, texnik xizmat ko'rsatish va xavfsizlik texnikasi qoidalarini amaliy jihatdan o'rganish imkoniyatini beradi.</p>
        <p>Amaliyot davomida har bir talaba energetika tizimining ajralmas qismi bo'lgan transformator podstansiyalari, taqsimlash qurilmalari, havo va kabel liniyalarida bajariladigan texnik va tashkiliy tadbirlarni bevosita ish o'rnida o'rganadi.</p>
        <p><strong>Xavfsizlik texnikasi va ichki tartib-qoidalar:</strong> Energetika ob'ektlari yuqori xavflilik darajasiga ega bo'lgan korxonalar sirasiga kiradi. Shu sababli, amaliyotning ilk kuni korxonada joriy etilgan ichki tartib-qoidalar, mehnat muhofazasi, yong'in xavfsizligi va elektr xavfsizligi bo'yicha yo'riqnomalar (instruktaj) o'tiladi. Ish joyida shaxsiy himoya vositalaridan (kaska, maxsus kiyim-bosh, parhez poyabzal, dielektrik qo'lqoplar va gilamchalar) foydalanish majburiydir.</p>
        
            </div>
        </div>
        <div class="card" id="mavzu-2">
            <h2>2. Energetik korxona asosiy va yordamchi sexlari to'g'risida ma'lumot</h2>
            <span class="badge">Ajratilgan soat: 8 (Ish o'rnida: 6, Mustaqil: 2)</span>
            <div class="card-body">
                
        <p><strong>Asosiy sexlar:</strong> Energetik korxonalarda (masalan, Issiqlik elektr markazlari - IEM, Gidroelektr stansiyalari - GES yoki yirik podstansiyalar) asosiy sexlarga quyidagilar kiradi:</p>
        <ul>
            <li><strong>Qozonxona sexi:</strong> Yoqilg'i energiyasini bug' energiyasiga aylantirib beradi (IEMlarda).</li>
            <li><strong>Turbina sexi:</strong> Bug' yoki suv energiyasini mexanik energiyaga aylantiradi.</li>
            <li><strong>Generator (Elektr) sexi:</strong> Mexanik energiyani elektr energiyasiga aylantiradi va uni kuchaytiruvchi transformatorlar orqali tarmoqqa uzatadi.</li>
        </ul>
        <p><strong>Yordamchi sexlar:</strong> Korxonaning uzluksiz va barqaror ishlashini ta'minlash uchun xizmat qiladi:</p>
        <ul>
            <li><strong>Kimyo sexi:</strong> Turbina va qozonlar uchun suvni tuzlardan va aralashmalardan tozalaydi (suv tayyorlash qurilmalari).</li>
            <li><strong>Ta'mirlash va mexanika sexi:</strong> Jihozlarni rejali va joriy ta'mirlash ishlarini olib boradi.</li>
            <li><strong>Nazorat-o'lchov asboblari va avtomatika (NO'A va A) sexi:</strong> Texnologik jarayonlarni avtomatik boshqarish va nazorat qilish tizimlariga xizmat ko'rsatadi.</li>
        </ul>
        
            </div>
        </div>
        <div class="card" id="mavzu-3">
            <h2>3. Ochiq taqsimlash qurilmadagi elektr jihozlariga texnik xizmat ko'rsatish</h2>
            <span class="badge">Ajratilgan soat: 8 (Ish o'rnida: 6, Mustaqil: 2)</span>
            <div class="card-body">
                
        <p><strong>Ochiq taqsimlash qurilmalari (OTQ - ORU):</strong> Elektr energiyasini qabul qilish va tarqatish uchun mo'ljallangan, barcha jihozlari ochiq havoda joylashgan qurilmadir. Odatda 35 kV va undan yuqori kuchlanishlarda qo'llaniladi.</p>
        <p><strong>OTQ jihozlari tarkibi:</strong> Kuch transformatorlari, avtotransformatorlar, yuqori kuchlanishli o'chirgichlar, ajratgichlar (razyedinitellar), tok va kuchlanish transformatorlari, razyadniklar yoki o'ta kuchlanishni cheklovchilar (ONX), shina tayanchlari va havo liniyalari portallari.</p>
        <p><strong>Texnik xizmat ko'rsatish qoidalari:</strong> Ochiq havoda joylashganligi sababli, jihozlar atrof-muhit ta'siriga (yomg'ir, qor, chang, harorat o'zgarishi) ko'proq duchor bo'ladi. Texnik xizmat ko'rsatish quyidagilarni o'z ichiga oladi:</p>
        <ul>
            <li>Izolyatorlarning sirtini chang va ifloslanishlardan tozalash, ularda yoriqlar yo'qligini tekshirish.</li>
            <li>Kontakt birikmalarining qizish darajasini teplovizorlar yordamida masofadan nazorat qilish.</li>
            <li>Moy bilan to'ldirilgan jihozlarda (transformatorlar, moyli o'chirgichlar) moy darajasi va uning sifatini (rangi, chidamliligi) tekshirish.</li>
            <li>Yerlashtirish qurilmalarining butunligini va kontaktlarining mustahkamligini ko'rikdan o'tkazish.</li>
        </ul>
        
            </div>
        </div>
        <div class="card" id="mavzu-4">
            <h2>4. Uchirgich va ajratgichlarni joylashtirish bilan tanishish</h2>
            <span class="badge">Ajratilgan soat: 8 (Ish o'rnida: 6, Mustaqil: 2)</span>
            <div class="card-body">
                
        <p><strong>Yuqori kuchlanishli o'chirgichlar (Vikluchatellar):</strong> Tarmoqni normal ish rejimida hamda qisqa tutashuv kabi avariya rejimlarida yuklama ostida o'chirish va yoqish uchun mo'ljallangan eng muhim kommutatsiya qurilmasidir. Ular yoyni so'ndirish muhitiga ko'ra quyidagilarga bo'linadi: moyli, havoli, elegazli (SF6) va vakuumli.</p>
        <p><strong>Ajratgichlar (Razyedinitellar):</strong> Elektr zanjirini ko'rinadigan joyidan uzish (ajratish) uchun xizmat qiladi. Ularning yoy so'ndirish kamerasi bo'lmaganligi sababli, <em>yuklama toklari ostida o'chirish mutlaqo taqiqlanadi</em>. Faqat zanjirda tok bo'lmaganda yoki juda kichik toklar mavjud bo'lganda ishlatiladi.</p>
        <p><strong>Joylashtirish prinsiplari:</strong> Podstansiyalarda o'chirgichlar va ajratgichlar ketma-ket ulanadi. Xavfsiz ta'mirlash ishlarini olib borish uchun o'chirgichning har ikki tomoniga (shina va liniya tomoniga) ajratgichlar o'rnatiladi. Kommutatsiya amallari bajarilganda qat'iy ketma-ketlikka rioya qilinadi: tarmoqni yoqishda avval ajratgichlar, keyin o'chirgich yopiladi; o'chirishda esa avval o'chirgich ochiladi, so'ngra ajratgichlar ajratiladi. Blokirovka tizimlari noto'g'ri amallarning oldini oladi.</p>
        
            </div>
        </div>
        <div class="card" id="mavzu-5">
            <h2>5. O'lchov transformatorlari va nazorat o'lchov asboblari bilan tanishish</h2>
            <span class="badge">Ajratilgan soat: 8 (Ish o'rnida: 6, Mustaqil: 2)</span>
            <div class="card-body">
                
        <p><strong>O'lchov transformatorlari:</strong> Yuqori kuchlanish va katta toklarni standart, xavfsiz qiymatlarga (kuchlanish uchun odatda 100 V, tok uchun esa 1 A yoki 5 A) pasaytirib beruvchi qurilmalardir. Ikki turga bo'linadi:</p>
        <ul>
            <li><strong>Tok transformatori (TT):</strong> Zanjirga ketma-ket ulanadi. Ikkinchi zanjiri hech qachon ochiq qolmasligi kerak, aks holda yuqori kuchlanish hosil bo'lib, hayot uchun xavf tug'diradi va asbobni ishdan chiqaradi.</li>
            <li><strong>Kuchlanish transformatori (KT):</strong> Zanjirga parallel ulanadi va ikkinchi zanjirining qisqa tutashuvidan himoyalangan bo'lishi lozim.</li>
        </ul>
        <p><strong>Nazorat-o'lchov asboblari:</strong> Podstansiyaning ishlash rejimini kuzatish uchun xizmat qiladi. Ularga ampermeyrlar, voltmetrlar, vattmetrlar, chastotamerlar va elektr energiya hisoblagichlari (faol va reaktiv energiya uchun) kiradi. Hozirgi kunda raqamli va mikroprotsessorli ko'p funksiyali o'lchov asboblari keng qo'llanilmoqda.</p>
        
            </div>
        </div>
        <div class="card" id="mavzu-6">
            <h2>6. Elektr jihozlarini hisoblash turlari</h2>
            <span class="badge">Ajratilgan soat: 8 (Ish o'rnida: 6, Mustaqil: 2)</span>
            <div class="card-body">
                
        <p><strong>Elektr energiyasini hisobga olish tizimlari:</strong> Energetika tizimida ishlab chiqarilgan va iste'mol qilingan elektr energiyasini aniq aniqlash iqtisodiy jihatdan juda muhim. Hisobga olish ikki turga bo'linadi:</p>
        <ul>
            <li><strong>Tijoriy hisobga olish:</strong> Iste'molchi va ta'minotchi korxona o'rtasidagi moliyaviy hisob-kitoblar uchun asos bo'ladi. Bu tizim yuqori aniqlik sinfiga ega asboblarni talab qiladi.</li>
            <li><strong>Texnik (ichki) hisobga olish:</strong> Korxona ichida elektr energiyasining texnologik yo'qotishlarini tahlil qilish va energiyani tejash tadbirlarini ishlab chiqish uchun qo'llaniladi.</li>
        </ul>
        <p><strong>ASKUE tizimi:</strong> Hozirgi kunda elektr energiyasini nazorat qilish va hisobga olishning avtomatlashtirilgan tizimi (ASKUE) joriy etilgan. Bu tizim ma'lumotlarni masofadan, inson omilisiz, real vaqt rejimida serverga uzatish imkonini beradi.</p>
        
            </div>
        </div>
        <div class="card" id="mavzu-7">
            <h2>7. Yopiq taqsimlash qurilmadagi elektr jihozlariga texnik xizmat ko'rsatish</h2>
            <span class="badge">Ajratilgan soat: 8 (Ish o'rnida: 6, Mustaqil: 2)</span>
            <div class="card-body">
                
        <p><strong>Yopiq taqsimlash qurilmalari (YTQ - RU):</strong> Barcha elektr jihozlari maxsus binolar ichida joylashgan qurilma bo'lib, odatda 6-10 kV kuchlanishli tarmoqlarda yoki shahar sharoitidagi podstansiyalarda qo'llaniladi. Hozirgi kunda YTQlar ko'pincha KSO (Kamera statsionarnaya odnostoronnego obslujivaniya) yoki KRU (Komplektnoye raspredelitelnoye ustroystvo) shkaflari ko'rinishida yig'iladi.</p>
        <p><strong>Texnik xizmat ko'rsatish xususiyatlari:</strong> Binoning ichki muhiti quruq va toza bo'lishi kerak. Amaliyotda bajariladigan ishlar:</p>
        <ul>
            <li>Xonadagi ventilyatsiya va yoritish tizimlarining sozligini tekshirish.</li>
            <li>KRU shkaflarining tortib olinadigan qismlari (viklyuchatel aravachalari) mexanizmlarini moylash va kontaktlarining mustahkamligini ko'rish.</li>
            <li>Izolyatsiyaning qarshiligini megometr asbobi bilan o'lchash.</li>
            <li>Kabel kirish joylari va teshiklarning germetikligini (zararkunandalar va namlik kirmasligi uchun) tekshirish.</li>
        </ul>
        
            </div>
        </div>
        <div class="card" id="mavzu-8">
            <h2>8. Yotk dagi elektr jihozlari bilan tanishish</h2>
            <span class="badge">Ajratilgan soat: 9 (Ish o'rnida: 6, Mustaqil: 3)</span>
            <div class="card-body">
                
        <p><strong>YOTK (Yopiq o'tkazgichli tarmoqlar / Yopiq taqsimlash korpuslari yoki maxsus bloklar):</strong> Kuchlanishi yuqori bo'lgan tarmoqlarda xavfsizlikni oshirish va tashqi muhit ta'sirini minimal darajaga tushirish uchun mo'ljallangan ixcham blokli qurilmalardir.</p>
        <p><strong>Tarkibiy qismlari:</strong> Elegaz izolyatsiyali taqsimlash qurilmalari (KRUE), ixcham gibrid modullar, germetik kommutatsiya apparatlari, boshqaruv va rele himoyasi shkaflari.</p>
        <p><strong>Afzalliklari:</strong> Katta maydon talab qilmaydi, atrof-muhit xavf-xatarlaridan to'liq himoyalangan, ekspluatatsiya xarajatlari kam va xizmat ko'rsatish xodimlari uchun maksimal darajada xavfsiz.</p>
        
            </div>
        </div>
        <div class="card" id="mavzu-9">
            <h2>9. Yotk ning elektr sxemasi bilan ishlash</h2>
            <span class="badge">Ajratilgan soat: 8 (Ish o'rnida: 6, Mustaqil: 2)</span>
            <div class="card-body">
                
        <p><strong>Elektr sxemalari turlari:</strong> Energetikada ob'ektlar bilan ishlashda sxemalarni to'g'ri o'qish qobiliyati juda muhim. Sxemalar asosan uch turga bo'linadi:</p>
        <ul>
            <li><strong>Birlamchi ulanishlar sxemasi (Bir chiziqli sxema):</strong> Yuqori kuchlanishli oqim o'tadigan asosiy zanjirlarni (liniyalar, transformatorlar, o'chirgichlar) ko'rsatadi.</li>
            <li><strong>Ikkilamchi ulanishlar sxemasi:</strong> Rele himoyasi, avtomatika, o'lchov, signalizatsiya va boshqaruv zanjirlarini qamrab oladi.</li>
            <li><strong>Prinsipial va montaj sxemalari:</strong> Elementlarning o'zaro ulanish simlari va klemma bloklarining joylashishini aniq ko'rsatib beradi.</li>
        </ul>
        <p><strong>Sxema bilan ishlash amaliyoti:</strong> Har qanday tezkor almashtirish (pereklyucheniye) ishlaridan oldin, xodim sxemani o'rganib chiqishi va tezkor blankni (blank pereklyucheniy) to'ldirishi shart. Sxema orqali yuklamaning qaysi liniyadan ketayotganligi va avariya holatida qaysi zanjir uzilishi kerakligi aniqlanadi.</p>
        
            </div>
        </div>
        <div class="card" id="mavzu-10">
            <h2>10. Yotk ning himoya vositalari</h2>
            <span class="badge">Ajratilgan soat: 8 (Ish o'rnida: 6, Mustaqil: 2)</span>
            <div class="card-body">
                
        <p><strong>Elektr xavfsizligi himoya vositalari:</strong> Elektr qurilmalarida ishlayotganda xodimlarni elektr toki urishidan himoya qilish uchun ishlatiladigan vositalar ikki guruhga bo'linadi:</p>
        <ul>
            <li><strong>Asosiy himoya vositalari:</strong> Izolyatsiyasi ishchi kuchlanishga uzoq vaqt bardosh bera oladigan va kuchlanish ostidagi qismlarga to'g'ridan-to'g'ri tegishga ruxsat beradigan vositalar. (Masalan: izolyatsiyalovchi shtangalar, tok o'lchash omburlari, kuchlanish ko'rsatkichlari).</li>
            <li><strong>Qo'shimcha himoya vositalari:</strong> Mustaqil ravishda elektr tokidan himoya qila olmaydi, lekin asosiy vositalarni to'ldiradi. (Masalan: dielektrik qo'lqoplar, botlar, gilamchalar, izolyatsiyalovchi tagliklar).</li>
        </ul>
        <p><strong>Tashkiliy himoya choralari:</strong> Plakatlar va xavfsizlik belgilari (Taqqiqlovchi: "Yoqilmasin! Odamlar ishlamoqda", Ogohlantiruvchi: "To'xtang! Kuchlanish", Ko'rsatuvchi: "Bu yerda ishlang", Yerlashtiruvchi: "Yenlashtirilgan"). Ish joylarini ko'chma yerlashtirgichlar (zazemleniye) yordamida himoya qilish majburiydir.</p>
        
            </div>
        </div>
        <div class="card" id="mavzu-11">
            <h2>11. Kuchlanishi 1000 V gacha bo'lgan havo elektr o'tkazish liniyalarini ishlatish va ta'mirlash</h2>
            <span class="badge">Ajratilgan soat: 8 (Ish o'rnida: 6, Mustaqil: 2)</span>
            <div class="card-body">
                
        <p><strong>Havo liniyalari (HL - VL):</strong> Elektr energiyasini ochiq havoda joylashgan simlar orqali masofaga uzatuvchi qurilmadir. Kuchlanishi 1000 V gacha bo'lgan liniyalar (ko'pincha 0.4 kV) iste'molchilarga bevosita energiya yetkazib beradi.</p>
        <p><strong>Konstruksiyasi:</strong> Tayanchlar (yog'och, temir-beton), simlar (yalang'och alyuminiy - A, AS yoki hozirgi kunda keng qo'llanilayotgan o'zini tutuvchi izolyatsiyalangan simlar - SIP/SIPS), izolyatorlar va chiziqli armaturalar.</p>
        <p><strong>Ekspluatatsiya va ta'mirlash ishlari:</strong></p>
        <ul>
            <li>Liniyalarni davriy ravishda ko'rikdan o'tkazish, tayanchlarning og'ishini va simlarning osilib qolish darajasini (strela povesha) tekshirish.</li>
            <li>Daraxt shoxlarini liniyaga tegib qolmasligi uchun kesish (traza tozalash).</li>
            <li>Shikastlangan izolyatorlarni almashtirish, kontakt birikmalarini tortish va mustahkamlash.</li>
        </ul>
        
            </div>
        </div>
        <div class="card" id="mavzu-12">
            <h2>12. Kuchlanishi 1000 V gacha bo'lgan havo elektr o'tkazish liniyalarini ishlatish va ta'mirlashni o'rganish</h2>
            <span class="badge">Ajratilgan soat: 8 (Ish o'rnida: 6, Mustaqil: 2)</span>
            <div class="card-body">
                
        <p><strong>Ishlarni tashkil etish tartibi:</strong> Kuchlanishi 1000 V gacha bo'lgan havo liniyalarida ishlar asosan kuchlanishni to'liq o'chirgan holda, xavfsizlik choralarini ko'rib bajariladi. Ishlarni bajarish uchun maxsus <strong>Naryad-ruxsatnoma</strong> (Naryad-dopusk) yoki farmoyish rasmiylashtiriladi.</p>
        <p><strong>Amaliy o'rganiladigan jarayonlar:</strong></p>
        <ul>
            <li>Liniyani o'chirish va uning o'chirilganligini kuchlanish ko'rsatkichi (ukazatel) yordamida tekshirish.</li>
            <li>Ish joyiga ko'chma yerlashtirgichlarni (ko'chma zazemleniye) o'rnatish. Bu liniyaga tasodifan kuchlanish berib yuborilganda xodimlarni himoya qiladi.</li>
            <li>Tayanchlarga ko'tarilish qoidalari: xavfsizlik kamari (poyas) va maxsus tirnoqlardan (kogti/lazy) to'g'ri foydalanish texnikasini o'rganish.</li>
        </ul>
        
            </div>
        </div>
        <div class="card" id="mavzu-13">
            <h2>13. Elektr tarmogpi liniyalarini koprikdan, sinovdan o'tkazish va ta'mirlash muddatlari bilan tanishuv</h2>
            <span class="badge">Ajratilgan soat: 8 (Ish o'rnida: 6, Mustaqil: 2)</span>
            <div class="card-body">
                
        <p><strong>Texnik ko'riklar va sinovlar:</strong> Elektr tarmoqlarining ishonchliligini ta'minlash uchun PTE (Texnik ekspluatatsiya qoidalari) asosida rejaviy ishlar amalga oshiriladi. Tarmoqlarni ko'rikdan o'tkazish turlari:</p>
        <ul>
            <li><strong>Kunduzgi ko'riklar:</strong> Liniya elementlarining umumiy holatini, simlar va tayanchlarni ko'zdan kechirish uchun muntazam o'tkaziladi.</li>
            <li><strong>Tungi ko'riklar:</strong> Izolyatorlarda uchqun chiqishi (korona razryadi) va kontaktlarning qizib ketishini qorong'uda aniqlash uchun yilda kamida bir marta o'tkaziladi.</li>
            <li><strong>Avariyali ko'riklar:</strong> Tizimda avtomatik o'chish sodir bo'lganda sababini aniqlash uchun zudlik bilan o'tkaziladi.</li>
        </ul>
        <p><strong>Ta'mirlash muddatlari (Periodichnost):</strong> Havo va kabel liniyalari odatda yiliga kamida bir marta joriy ta'mirdan (tekshirish, kontaktlarni tortish), har 5-6 yilda bir marta esa kapital ta'mirdan (tayanchlarni yoki sim qismlarini to'liq almashtirish) o'tkaziladi.</p>
        
            </div>
        </div>
        <div class="card" id="mavzu-14">
            <h2>14. Havo elektr o'tkazish liniyasini ishga qabul qilish, liniyani yuklama toki bo'yicha ish rejimiga rioya qilish</h2>
            <span class="badge">Ajratilgan soat: 8 (Ish o'rnida: 6, Mustaqil: 2)</span>
            <div class="card-body">
                
        <p><strong>Ishga qabul qilish (Sdat va ekspluatatsiyu):</strong> Yangi qurilgan yoki kapital ta'mirdan chiqqan havo liniyasini ishga tushirishdan oldin maxsus qabul qilish komissiyasi tomonidan ko'rikdan o'tkaziladi. Bunda loyiha hujjatlari, yerlashtirish konturlarining qarshilik bayonnomalari va izolyatsiyaning sinov hisobotlari tekshiriladi.</p>
        <p><strong>Yuklama toki bo'yicha ish rejimi:</strong> Har bir havo liniyasining sim kesimiga (secheniye) qarab ruxsat etilgan maksimal uzoq muddatli tok kuchi (tokovaya nagruzka) mavjud. Agarda liniya o'ta yuklansa (peregruzka), simlar qizib, mexanik mustahkamligini yo'qotadi va osilib, yerga yoki daraxtlarga tegishi, oqibatda qisqa tutashuv kelib chiqishi mumkin.</p>
        <p><strong>Nazorat qilish:</strong> Dispetcherlik punktlarida va podstansiyalarda liniyalarning yuklamasi doimiy ravishda ampermetrlar va avtomatlashtirilgan tizimlar orqali nazorat qilinadi.</p>
        
            </div>
        </div>
        <div class="card" id="mavzu-15">
            <h2>15. Kuch kabel liniyalarini ishlatish va ta'mirlash</h2>
            <span class="badge">Ajratilgan soat: 8 (Ish o'rnida: 6, Mustaqil: 2)</span>
            <div class="card-body">
                
        <p><strong>Kabel liniyalari (KL):</strong> Elektr energiyasini maxsus izolyatsiyalangan kabellar orqali yer ostidan, suv ostidan yoki maxsus kabel inshootlaridan (kanallar, tunnellar) uzatish tizimidir. Shahar sharoitida va yirik sanoat korxonalarida keng qo'llaniladi.</p>
        <p><strong>Kabelning tuzilishi:</strong> Tok o'tkazuvchi tolalar (mis yoki alyuminiy), faza izolyatsiyasi (qog'oz, PVX, tikilgan polietilen - SPE), to'ldirgichlar, himoya qobiqlari (qo'rg'oshin yoki alyuminiy), zirh (bronya - po'lat lentalar) va tashqi himoya qoplami.</p>
        <p><strong>Ishlatish va ta'mirlash:</strong> Yer ostidagi kabellar tashqi mexanik shikastlanishlarga (yer qazish ishlarida) moyil bo'ladi. Ta'mirlash ishlari shikastlangan joyni maxsus laboratoriya mashinalari (kabel qidirgichlar) yordamida aniqlash, yer qazish, kabelni kesish va yangi qism qo'shib, maxsus kabel muftalari (soedinitelnaya mufta) orqali ulanishni tiklashdan iborat.</p>
        
            </div>
        </div>
        <div class="card" id="mavzu-16">
            <h2>16. Kabel liniyalarini ko'rikdan, sinovdan o'tkazish va ta'mirlash muddatlari bilan tanishuv</h2>
            <span class="badge">Ajratilgan soat: 8 (Ish o'rnida: 6, Mustaqil: 2)</span>
            <div class="card-body">
                
        <p><strong>Kabel liniyalarini ko'rikdan o'tkazish:</strong> Yer ostidan o'tgan kabel trasasi bo'ylab rejaviy ko'riklar o'tkaziladi. Maqsad - kabel o'tgan joylarda ruxsatsiz yer qazish ishlari, og'ir texnikalar to'xtashi yoki bino qurilishlari yo'qligini tekshirish. Kabel tunnellarida esa kabellarning qizishi va muftalarning holati tekshiriladi.</p>
        <p><strong>Yuqori kuchlanish bilan sinash:</strong> Kabel liniyalari ekspluatatsiya davomida yilda bir marta yoki ta'mirlashdan so'ng yuqori o'zgarmas kuchlanish (kenotron yordamida) bilan sinovdan o'tkaziladi. Bu kabel izolyatsiyasidagi yashirin nuqsonlarni avariya bo'lishidan oldin aniqlash va portlatish (proboy) orqali yuzaga chiqarish imkonini beradi.</p>
        <p><strong>Muddatlari:</strong> Muhim yuklamali kabellar yiliga kamida 1 marta sinovdan o'tkaziladi. Tekshirish davriyligi korxona bosh muhandisi tomonidan tasdiqlangan grafik asosida belgilanadi.</p>
        
            </div>
        </div>
        <div class="card" id="mavzu-17">
            <h2>17. Kabel elektr ishlatish liniyasini ishga qabul qilish, kabel liniyasini yuklama toki bo'yicha ish rejimiga rioya qilish</h2>
            <span class="badge">Ajratilgan soat: 8 (Ish o'rnida: 6, Mustaqil: 2)</span>
            <div class="card-body">
                
        <p><strong>Ishga qabul qilish hujjatlari:</strong> Kabel liniyasi yotqizilib, ko'milishidan oldin majburiy tartibda "Yashirin ishlar dalolatnomasi" (Akt skritix rabot) tuziladi. Liniya ekspluatatsiyaga qabul qilinayotganda trasaning aniq geodezik xaritasi (gabaritlari va chuqurligi ko'rsatilgan holda), muftalar Coordinates ro'yxati va sinov bayonnomalari topshiriladi.</p>
        <p><strong>Termik chidamlilik va ish rejimi:</strong> Kabellar havo liniyalariga qaraganda yomonroq soviydi, chunki atrofidagi tuproq yoki yopiq kanal issiqlikni sekin o'tkazadi. Shu sababli, kabellarning yuklama toki qat'iy cheklangan.</p>
        <p>Kabellarning haddan tashqari qizib ketishi izolyatsiyaning tez qarishiga va qisqa vaqt ichida teshilishiga (proboy) olib keladi. Yoz oylarida tuproq harorati ko'tarilganda kabellarning ruxsat etilgan yuklama toki pasaytiriladi (koeffitsiyent qo'llaniladi).</p>
        
            </div>
        </div>
        <div class="card" id="mavzu-18">
            <h2>18. Kuchlanishi 1000 V gacha bo'lgan tarqatish qurilmalarini ishlatish va ta'mirlash</h2>
            <span class="badge">Ajratilgan soat: 8 (Ish o'rnida: 6, Mustaqil: 2)</span>
            <div class="card-body">
                
        <p><strong>0.4 kV Tarqatish qurilmalari (TQ - RU-0.4 kV):</strong> Transformator podstansiyalarining (TP) past kuchlanishli qismi bo'lib, iste'molchilarga to'g'ridan-to'g'ri chiquvchi liniyalarni kommutatsiya va muhofaza qilish uchun xizmat qiladi. Odatda ShchO-70 panellari yoki zamonaviy modulli shkaflar ko'rinishida bo'ladi.</p>
        <p><strong>Jihozlar tarkibi:</strong> Kirish va chiquvchi liniyalardagi avtomatik o'chirgichlar (avtomatlar), saqlagichlar (predoxranitellar), rubilniklar, tok transformatorlari va shinalar tizimi.</p>
        <p><strong>Texnik xizmat ko'rsatish:</strong> Amaliyotda eng ko'p bajariladigan ishlar:</p>
        <ul>
            <li>Kontaktlar va shinalarning birikish joylarini ko'rikdan o'tkazish, qizish belgilarini (oksidlanish, rang o'zgarishi) tekshirish.</li>
            <li>Avtomatik o'chirgichlarni changdan tozalash va ularning mexanizmlarini sinab ko'rish.</li>
            <li>Saqlagichlarning eruvchan elementlari (plavkaya vstavka) zavod tomonidan tayyorlangan, kalibrlangan bo'lishini ta'minlash (qo'lbola "juchok"lardan foydalanish qat'iyan taqiqlanadi).</li>
        </ul>
        
            </div>
        </div>
        <div class="card" id="mavzu-19">
            <h2>19. Tarqatish qurilmalarining elektr jihozlarini ishlashini o'rganish</h2>
            <span class="badge">Ajratilgan soat: 8 (Ish o'rnida: 6, Mustaqil: 2)</span>
            <div class="card-body">
                
        <p><strong>Ishlash prinsiplari va rejimlari:</strong> Tarqatish qurilmasining uzluksiz ishlashi iste'molchilarning energiya ta'minoti barqarorligini belgilaydi. Ushbu mavzu doirasida talabalar quyidagilarni o'rganadi:</p>
        <ul>
            <li><strong>Faza yuklamalarining simmetriyasi:</strong> Past kuchlanishli 3 fazali tarmoqlarda yuklamani fazalar bo'ylab teng taqsimlash muhim. Fazalarda nomutanosiblik (perekos faz) bo'lsa, nolinchi simdan katta tok oqib o'tadi va transformatorda yo'qotishlar ortadi.</li>
            <li><strong>Himoya tizimlarining selektivligi:</strong> Qisqa tutashuv sodir bo'lganda faqat shikastlangan liniyaning o'zi o'chishi kerak, butun podstansiya emas. Bunga avtomatik o'chirgichlarning toklari va vaqtlarini to'g'ri sozlash orqali erishiladi.</li>
            <li><strong>Tezkor amallar (Pereklyucheniya):</strong> Liniyalarni zaxiraga o'tkazish yoki ta'mirlashga ajratishda rubilniklar va avtomatlarni o'chirish ketma-ketligini amaliy mashq qilish.</li>
        </ul>
        
            </div>
        </div>
    </div>
</div>

<footer>
    <p>&copy; 2026 Elektr Amaliyoti Mashg'ulotlari Sayti. Barcha huquqlar himoyalangan.</p>
</footer>

</body>
</html>
