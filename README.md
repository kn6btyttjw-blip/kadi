# kadi
محافظة شقراء<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>محافظة شقراء - عراقة التاريخ وأصالة نجد</title>
    <style>
        /* إعدادات الخطوط والألوان العامة */
        @import url('https://fonts.googleapis.com/css2?family=Cairo:wght=300;400;600;700&display=swap');
        
        :root {
            --primary-color: #8B0000; /* عنابي دافئ مستوحى من الفلفل والتراث */
            --secondary-color: #D2A679; /* لون طيني نجدي فاتح */
            --text-dark: #333333;
            --bg-light: #FDFBF7; /* خلفية كريمية مريحة للعين */
            --white: #ffffff;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Cairo', sans-serif;
        }

        body {
            background-color: var(--bg-light);
            color: var(--text-dark);
            line-height: 1.8;
            padding-bottom: 40px;
        }

        /* الهيدر (رأس الصفحة) */
        header {
            background: linear-gradient(rgba(139, 0, 0, 0.85), rgba(139, 0, 0, 0.95)), url('https://images.unsplash.com/photo-1578894381163-e72c17f2d45f?q=80&w=1000') no-repeat center center/cover;
            color: var(--white);
            text-align: center;
            padding: 60px 20px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }

        header h1 {
            font-size: 2.5rem;
            font-weight: 700;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.2rem;
            font-weight: 300;
            opacity: 0.9;
        }

        /* الحاوية الرئيسية */
        .container {
            max-width: 900px;
            margin: 40px auto;
            padding: 0 20px;
        }

        /* كرت المقدمة */
        .intro-card {
            background-color: var(--white);
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            border-right: 6px solid var(--primary-color);
            margin-bottom: 30px;
            font-size: 1.1rem;
        }

        /* الأقسام (Sections) */
        .section {
            background-color: var(--white);
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            margin-bottom: 25px;
            transition: transform 0.3s ease;
        }

        .section:hover {
            transform: translateY(-2px);
        }

        .section-title {
            color: var(--primary-color);
            font-size: 1.4rem;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            gap: 10px;
            border-bottom: 2px solid #f0f0f0;
            padding-bottom: 10px;
        }

        /* القوائم والتنسيقات الداخلية */
        ul {
            list-style: none;
        }

        li {
            margin-bottom: 15px;
            position: relative;
            padding-right: 25px;
        }

        li::before {
            content: "•";
            color: var(--secondary-color);
            font-weight: bold;
            font-size: 1.5rem;
            position: absolute;
            right: 0;
            top: -4px;
        }

        strong {
            color: var(--primary-color);
            font-weight: 600;
        }

        /* لمسة خاصة بقسم الفلفل */
        .pepper-highlight {
            border: 2px dashed #ffcccc;
            background-color: #fff9f9;
        }

        /* تنسيق جدول المربع الرئيسي المشترك للأسماء */
        .table-credits-card {
            background-color: #f4ebe1 !important;
            border: 2px solid #D2A679 !important;
            border-radius: 12px !important;
            width: 100% !important;
            max-width: 550px !important;
            margin: 40px auto !important;
            padding: 25px !important;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05) !important;
        }

        /* تنسيق مستطيلات الأسماء البيضاء الاحترافية لتبدو كأزرار */
        .table-credits-card td.name-box {
            background-color: #ffffff !important;
            padding: 12px 15px !important;
            border-radius: 6px !important;
            font-weight: 600 !important;
            color: #333333 !important;
            font-size: 1rem !important;
            text-align: center !important;
            border-bottom: 3px solid #8B0000 !important;
            box-shadow: 0 2px 4px rgba(0,0,0,0.03) !important;
            width: 45% !important;
        }

        /* الفوتر (أسفل الصفحة) */
        footer {
            text-align: center;
            margin-top: 50px;
            padding-top: 20px;
            border-top: 1px solid #e0e0e0;
            color: #777;
            font-size: 0.9rem;
        }

        /* التوافق مع الشاشات الصغيرة */
        @media (max-width: 600px) {
            header h1 { font-size: 2rem; }
            .section { padding: 20px; }
        }
    </style>
</head>
<body>

    <header>
        <h1>محافظة شقراء</h1>
        <p>عراقة التاريخ وأصالة نجد</p>
    </header>

    <div class="container">

        <div class="intro-card">
            محافظة شقراء هي واحدة من أهم المحافظات التاريخية والتعليمية في منطقة الرياض بالمملكة العربية السعودية. تُعد العاصمة الإدارية لإقليم <strong>الوشم</strong>، وتتميز بموقعها الاستراتيجي وتاريخها العريق الذي جعل منها مركزاً تجارياً وثقافياً بارزاً في قلب نجد.
        </div>

        <div class="section">
            <h2 class="section-title">📍 الموقع والجغرافيا</h2>
            <ul>
                <li><strong>الموقع:</strong> تقع شمال غرب مدينة الرياض, وتبعد عنها حوالي <strong>190 كم</strong>.</li>
                <li><strong>الحدود:</strong> يحدها من الشمال محافظة الغاط، ومن الجنوب محافظة مرات، ومن الشرق محافظة المجمعة ومحافظة ثادق، ومن الغرب محافظة الدوادمي.</li>
                <li><strong>التضاريس:</strong> تحيط بها كثبان رملية ذهبية تُعرف بـ <strong>"نفود قنيع"</strong>، وتخترقها أودية شهيرة مثل وادي الريمة ووادي الغدير.</li>
            </ul>
        </div>

        <div class="section pepper-highlight">
            <h2 class="section-title">🌶️ بماذا تشتهر؟ (فلفل شقراء الشهير)</h2>
            <p style="margin-bottom: 15px; color: #555;">إلى جانب تاريخها، ارتبط اسم المحافظة بمنتج زراعي مميز منحه شهرة واسعة في كل بيت سعودي:</p>
            <ul>
                <li><strong>فلفل شقراء (الشقرواي):</strong> تُعد شقراء العاصمة غير الرسمية لإنتاج الفلفل الحار في المملكة. يتميز فلفل شقراء بنكهته الفريدة وحرارته المميزة جودته العالية، حتى أصبح مطلباً أساسياً في المطبخ النجدي والسعودي عموماً.</li>
                <li><strong>مهرجان الفلفل:</strong> نظراً لهذه الشهرة، تُقيم المحافظة <strong>"مهرجان فلفل شقراء"</strong> السنوي، وهو حدث اقتصادي وسياحي جاذب، يستقطب الزوار والمستثمرين من مختلف المناطق لدعم المزارعين المحليين واستعراض المنتجات المشتقة من الفلفل.</li>
            </ul>
        </div>

        <div class="section">
            <h2 class="section-title">📜 الأهمية التاريخية والأثرية</h2>
            <p style="margin-bottom: 15px; color: #555;">تميزت شقراء تاريخياً بأنها مركز تجاري رئيسي يربط شرق الجزيرة العربية بغربها، ومن أبرز معالمها التراثية:</p>
            <ul>
                <li><strong>البلدة القديمة (شقراء التاريخية):</strong> نموذج حي للعمارة النجدية التقليدية بأزقتها وبيوتها الطينية.</li>
                <li><strong>بيت السبيعي:</strong> قصر أثري تاريخي مميز، كان مقراً لبيت المال ومحطاً لرحال الملك عبد العزيز -طيب الله ثراه-.</li>
                <li><strong>سوق المجلس:</strong> السوق التجاري القديم الذي يعكس حركة البيع والشراء في نجد قديماً.</li>
            </ul>
        </div>

        <div class="section">
            <h2 class="section-title">🎓 التعليم والتنمية</h2>
            <p style="margin-bottom: 15px; color: #555;">تُعرف شقراء بأنها <strong>منارة تعليمية</strong>؛ فقد كانت رائدة في التعليم والكتاتيب قديماً، واليوم يمتد هذا الإرث عبر:</p>
            <ul>
                <li><strong>جامعة شقراء:</strong> الصرح التعليمي الأكبر الذي يخدم المحافظة والمراكز المجاورة لها من خلال كليات متنوعة تدعم تطلعات الجيل الجديد تماشياً مع رؤية السعودية 2030.</li>
            </ul>
        </div>

        <div class="table-credits-card">
            <h3 style="color: #8B0000; font-size: 1.3rem; font-weight: 700; text-align: center; margin-bottom: 20px; border-bottom: 1px dashed #D2A679; padding-bottom: 10px;">✨ إعداد وعمل الطالبات ✨</h3>
            
            <table style="width: 100%; border-collapse: separate; border-spacing: 15px; margin: 0 auto;">
                <tr>
                    <td style="background: none; border: none; box-shadow: none;"></td>
                    <td class="name-box" style="width: 50%;">كادي العتيبي</td>
                    <td style="background: none; border: none; box-shadow: none;"></td>
                </tr>
                
                <tr>
                    <td class="name-box">ندى المهوس</td>
                    <td style="background: none; border: none; box-shadow: none;"></td>
                    <td class="name-box">العنود الغانم</td>
                </tr>
                
                <tr>
                    <td class="name-box">انتصار الشعيل</td>
                    <td style="background: none; border: none; box-shadow: none;"></td>
                    <td class="name-box">جوري الشلعان</td>
                </tr>
                
                <tr>
                    <td class="name-box">لين السهلي</td>
                    <td style="background: none; border: none; box-shadow: none;"></td>
                    <td class="name-box">شهد الحسن</td>
                </tr>

                <tr>
                    <td class="name-box">موضي القحطاني</td>
                    <td style="background: none; border: none; box-shadow: none;"></td>
                    <td class="name-box">ريما بن دحيم</td>
                </tr>
            </table>
        </div>

        <footer>
            <p>موقع تعريفي بمحافظة شقراء - 2026 - طالبات الثانوية 101</p>
        </footer>

    </div>

</body>
</html>

.
