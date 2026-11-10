Ali-Electronics-
Ac error code 
<!DOCTYPE html>
<html lang="ur" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ali Electronics PCB Repair - Master Error Codes</title>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Nastaliq+Urdu:wght@400;700&family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #0284c7;
            --primary-dark: #0369a1;
            --secondary: #0f172a;
            --accent: #22c55e;
            --bg: #f8fafc;
            --card-bg: #ffffff;
            --text: #1e293b;
            --text-light: #64748b;
        }
        * { box-sizing: border-box; margin: 0; padding: 0; font-family: 'Poppins', 'Noto Nastaliq Urdu', sans-serif; }
        body { background-color: var(--bg); color: var(--text); line-height: 1.6; padding-bottom: 40px; }
        header { background: linear-gradient(135deg, var(--secondary), #1e293b); color: white; padding: 25px 20px; text-align: center; box-shadow: 0 4px 12px rgba(0,0,0,0.15); }
        .profile-container { display: flex; align-items: center; justify-content: center; gap: 20px; margin-bottom: 15px; flex-wrap: wrap; }
        .profile-pic { width: 95px; height: 95px; border-radius: 50%; object-fit: cover; border: 3px solid var(--accent); box-shadow: 0 4px 10px rgba(0,0,0,0.3); }
        .profile-info h1 { font-size: 22px; color: #f1f5f9; font-weight: 700; }
        .profile-info p { font-size: 13px; color: #94a3b8; }
        .contact-badge { background: rgba(34, 197, 94, 0.15); color: #4ade80; padding: 6px 15px; border-radius: 20px; font-size: 13px; display: inline-block; margin-top: 5px; font-weight: 600; }
        
        .container { max-width: 1000px; margin: 20px auto; padding: 0 15px; }
        .tabs { display: flex; justify-content: center; gap: 10px; margin-bottom: 20px; flex-wrap: wrap; }
        .tab-btn { background: #e2e8f0; border: none; padding: 10px 18px; border-radius: 30px; font-weight: 600; cursor: pointer; transition: all 0.3s; font-size: 14px; }
        .tab-btn.active { background: var(--primary); color: white; box-shadow: 0 4px 12px rgba(2, 132, 199, 0.3); }
        
        .search-box { width: 100%; padding: 14px 20px; font-size: 16px; border: 2px solid #cbd5e1; border-radius: 12px; margin-bottom: 25px; outline: none; transition: border-color 0.3s; background: white; }
        .search-box:focus { border-color: var(--primary); }

        .category-section { display: none; }
        .category-section.active { display: block; }

        .brand-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(280px, 1fr)); gap: 15px; }
        .card { background: var(--card-bg); border-radius: 12px; padding: 18px; box-shadow: 0 2px 8px rgba(0,0,0,0.06); border: 1px solid #e2e8f0; transition: transform 0.2s; }
        .card:hover { transform: translateY(-3px); box-shadow: 0 6px 16px rgba(0,0,0,0.1); }
        .card h3 { color: var(--primary-dark); font-size: 18px; margin-bottom: 8px; border-bottom: 2px solid #f1f5f9; padding-bottom: 5px; }
        .error-item { background: #f8fafc; padding: 10px; border-radius: 8px; margin-top: 8px; border-right: 4px solid var(--primary); }
        .error-code { font-weight: bold; color: #dc2626; font-size: 16px; }
        .error-desc { font-size: 13px; color: var(--text-light); margin-top: 3px; }
        .error-solution { font-size: 13px; color: #16a34a; margin-top: 4px; font-weight: 600; }

        .footer-actions { text-align: center; margin-top: 30px; display: flex; justify-content: center; gap: 15px; flex-wrap: wrap; }
        .btn-action { background: #25d366; color: white; padding: 10px 20px; border-radius: 8px; text-decoration: none; font-weight: 600; display: inline-flex; align-items: center; gap: 8px; }
    </style>
</head>
<body>

    <header>
        <div class="container">
            <div class="profile-container">
                <!-- آپ کی اصل تصویر یہاں بالکل سیٹ کر دی گئی ہے -->
                <img src="1000163368.jpg" alt="Ali Akbar" class="profile-pic">
                <div class="profile-info">
                    <h1>علی اکبر - علی الیکٹرانکس پی سی بی ریپئر</h1>
                    <p>انورٹر اور نان انورٹر AC، واشنگ مشین اور ریفریجریٹر ماسٹر ٹیکنیشن</p>
                    <div class="contact-badge">📞 0537294004 (جدہ، سعودی عرب)</div>
                </div>
            </div>
        </div>
    </header>

    <div class="container">
        <!-- کیٹیگری ٹیبز -->
        <div class="tabs">
            <button class="tab-btn active" onclick="switchTab('ac')">❄️ ایئر کنڈیشنر (AC)</button>
            <button class="tab-btn" onclick="switchTab('washer')">🧼 واشنگ مشین</button>
            <button class="tab-btn" onclick="switchTab('fridge')">🌡️ ریفریجریٹر (فريج)</button>
        </div>

        <!-- لائیو سرچ -->
        <input type="text" id="searchInput" class="search-box" placeholder="کوئی بھی ایرر کوڈ، برانڈ یا مسئلہ سرچ کریں (مثلاً: E6, UE, F1, P1)..." onkeyup="searchCodes()">

        <!-- 1. AC SECTION -->
        <div id="ac-section" class="category-section active">
            <div class="brand-grid">
                <div class="card">
                    <h3>Gree Inverter & Non-Inverter AC</h3>
                    <div class="error-item"><div class="error-code">E1</div><div class="error-desc">کمپریسر ہائی پریشر پروٹیکشن</div><div class="error-solution">حل: گیس پریشر اور کنڈینسر کوائل صاف کریں۔</div></div>
                    <div class="error-item"><div class="error-code">E4</div><div class="error-desc">ڈسچارج ٹمپریچر ہائی</div><div class="error-solution">حل: گیس کم یا چوکنگ چیک کریں۔</div></div>
                    <div class="error-item"><div class="error-code">E5</div><div class="error-desc">اوور کرنٹ پروٹیکشن</div><div class="error-solution">حل: وولٹیج اور کمپریسر وائنڈنگ چیک کریں۔</div></div>
                    <div class="error-item"><div class="error-code">E6</div><div class="error-desc">انورٹر کمیونیکیشن فیلڈ (مدر بورڈ اور ڈسپلے کا رابطہ منقطع)</div><div class="error-solution">حل: سگنل وائر، وولٹیج اور آؤٹ ڈور پی سی بی چیک کریں۔</div></div>
                    <div class="error-item"><div class="error-code">F1</div><div class="error-desc">انڈور روم ٹمپریچر سینسر شارٹ یا اوپن</div><div class="error-solution">حل: سینسر تبدیل کریں۔</div></div>
                    <div class="error-item"><div class="error-code">H6</div><div class="error-desc">انڈور بلوئر موٹر فیڈ بیک مسئلہ (فین جام)</div><div class="error-solution">حل: فین موٹر بیرنگ اور وائرنگ چیک کریں۔</div></div>
                    <div class="error-item"><div class="error-code">P8</div><div class="error-desc">انورٹر ماڈیول (IPM) پروٹیکشن</div><div class="error-solution">حل: آئی پی ایم ہیٹ سنک اور پیسٹ چیک کریں۔</div></div>
                </div>

                <div class="card">
                    <h3>Mitsubishi Inverter AC</h3>
                    <div class="error-item"><div class="error-code">E1 / E2</div><div class="error-desc">مدر بورڈ اور ریسیور کمیونیکیشن فالٹ</div><div class="error-solution">حل: ڈسپلے کیبل کنیکٹر چیک کریں۔</div></div>
                    <div class="error-item"><div class="error-code">E6 / E9</div><div class="error-desc">انڈور / آؤٹ ڈور ٹرانسمیشن ایرر</div><div class="error-solution">حل: کمیونیکیشن وائر (S1, S2, S3) چیک کریں۔</div></div>
                    <div class="error-item"><div class="error-code">P1 - P5</div><div class="error-desc">تھرمل سینسر یا ہیٹ سنک فالٹ</div><div class="error-solution">حل: کوائل سینسر اور کمپریسر تھার্মিস্টর چیک کریں۔</div></div>
                    <div class="error-item"><div class="error-code">UF / UP</div><div class="error-desc">کمپریسر اوور لوڈ یا کمپریسر فیز مسنگ</div><div class="error-solution">حل: کمپریسر کی تینوں تاریں اور آئی پی ایم چیک کریں۔</div></div>
                </div>

                <div class="card">
                    <h3>Carrier & Changhong Ruba AC</h3>
                    <div class="error-item"><div class="error-code">E1 / E2</div><div class="error-desc">سنسر فالٹ یا کراس زرو ایرر</div><div class="error-solution">حل: روم اور کوائل سینسر چیک کریں۔</div></div>
                    <div class="error-item"><div class="error-code">E3 / E4</div><div class="error-desc">فین موٹر فیڈ بیک یا بلوئر جام</div><div class="error-solution">حل: فین موٹر کا کیپیسیٹر اور وائرنگ دیکھیں۔</div></div>
                    <div class="error-item"><div class="error-code">P0 / P1</div><div class="error-desc">آئی پی ایم پروٹیکشن یا ان پٹ وولٹیج لو</div><div class="error-solution">حل: مین سپلائی وولٹیج 220V چیک کریں۔</div></div>
                </div>

                <div class="card">
                    <h3>Haier & Orient Inverter AC</h3>
                    <div class="error-item"><div class="error-code">E4</div><div class="error-desc">کم پریشر پروٹیکشن یا گیس کم ہونا</div><div class="error-solution">حل: گیس لیکج دور کر کے چارج کریں۔</div></div>
                    <div class="error-item"><div class="error-code">F3</div><div class="error-desc">کوائل ٹمپریچر سینسر خراب</div><div class="error-solution">حل: نیا سینسر لگائیں۔</div></div>
                    <div class="error-item"><div class="error-code">E7 / F7</div><div class="error-desc">کمیونیکیشن ایرر یا انڈور ڈسپلے فالٹ</div><div class="error-solution">حل: انڈور آؤٹ ڈور وائرنگ کنکشن ٹائٹ کریں۔</div></div>
                </div>
            </div>
        </div>

        <!-- 2. WASHER SECTION -->
        <div id="washer-section" class="category-section">
            <div class="brand-grid">
                <div class="card">
                    <h3>LG / Samsung Automatic Washer</h3>
                    <div class="error-item"><div class="error-code">UE / Ub</div><div class="error-desc">بیلنس آؤٹ ایرر (کپڑے ایک طرف اکٹھے ہو جانا)</div><div class="error-solution">حل: کپڑے برابر کریں اور سسپنشن راڈز چیک کریں۔</div></div>
                    <div class="error-item"><div class="error-code">OE</div><div class="error-desc">پانی خارج نہ ہونا (Drain Error)</div><div class="error-solution">حل: ڈرین پمپ، فلٹر اور پائپ صاف کریں۔</div></div>
                    <div class="error-item"><div class="error-code">IE</div><div class="error-desc">پانی نہ بھرنا (Water Inlet Error)</div><div class="error-solution">حل: نلکا کھولیں اور واٹر انلیت والو واش کریں۔</div></div>
                    <div class="error-item"><div class="error-code">dE</div><div class="error-desc">ڈور لاک ایرر (ढक्कन खुला होना)</div><div class="error-solution">حل: ڈور سوئچ یا لاک کا کنیکٹر چیک کریں۔</div></div>
                </div>
                <div class="card">
                    <h3>Haier / Dawlance Washer</h3>
                    <div class="error-item"><div class="error-code">E1</div><div class="error-desc">ڈور لاک یا ڈھکن کھلا رہنا</div><div class="error-solution">حل: ڈور سوئچ چیک کریں۔</div></div>
                    <div class="error-item"><div class="error-code">E2</div><div class="error-desc">واٹر لیول پریشر سوئچ فالٹ</div><div class="error-solution">حل: پریشر پائپ اور سینسر چیک کریں۔</div></div>
                    <div class="error-item"><div class="error-code">E3</div><div class="error-desc">اسپن (Spin) کے دوران پانی نہ نکلنا</div><div class="error-solution">حل: ڈرین پمپ اور پائپ کی صفائی کریں۔</div></div>
                </div>
            </div>
        </div>

        <!-- 3. FRIDGE SECTION -->
        <div id="fridge-section" class="category-section">
            <div class="brand-grid">
                <div class="card">
                    <h3>Inverter Refrigerator (فریج)</h3>
                    <div class="error-item"><div class="error-code">E1 / F1</div><div class="error-desc">فریج کیبنٹ ٹمپریچر سینسر خراب</div><div class="error-solution">حل: فریج کا سنسر (Sensor) تبدیل کریں۔</div></div>
                    <div class="error-item"><div class="error-code">E4 / F3</div><div class="error-desc">ڈی فروسٹ سسٹم فالٹ (برف جمنا)</div><div class="error-solution">حل: ڈی فروسٹ ہیٹر، بائی میٹل اور تھرمل فیوز چیک کریں۔</div></div>
                    <div class="error-item"><div class="error-code">84E / 85E</div><div class="error-desc">انورٹر کمپریسر کمیونیکیشن یا ڈرائیو فالٹ</div><div class="error-solution">حل: مین پی سی بی بورڈ اور کمپریسر انورٹر کارڈ چیک کریں۔</div></div>
                </div>
            </div>
        </div>

        <div class="footer-actions">
            <a href="https://wa.me/966537294004" class="btn-action" target="_blank">💬 واٹس ایپ پر رابطہ کریں</a>
            <a href="tel:0537294004" class="btn-action" style="background:#0284c7;">📞 براہ راست کال کریں</a>
        </div>
    </div>

    <script>
        function switchTab(category) {
            document.querySelectorAll('.category-section').forEach(sec => sec.classList.remove('active'));
            document.querySelectorAll('.tab-btn').forEach(btn => btn.classList.remove('active'));
            
            if(category === 'ac') {
                document.getElementById('ac-section').classList.add('active');
                event.currentTarget.classList.add('active');
            } else if(category === 'washer') {
                document.getElementById('washer-section').classList.add('active');
                event.currentTarget.classList.add('active');
            } else if(category === 'fridge') {
                document.getElementById('fridge-section').classList.add('active');
                event.currentTarget.classList.add('active');
            }
        }

        function searchCodes() {
            let input = document.getElementById('searchInput').value.toLowerCase();
            let cards = document.querySelectorAll('.error-item');
            cards.forEach(card => {
                let text = card.innerText.toLowerCase();
                if(text.includes(input)) {
                    card.style.display = "block";
                } else {
                    card.style.display = "none";
                }
            });
        }
    </script>
</body>
</html>
