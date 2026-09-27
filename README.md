<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ZEKRA | ذكرى</title>
    <!-- استيراد خطوط عربية وإنجليزية مناسبة للتصميم -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Amiri:ital,wght@0,400;0,700;1,400&family=Playfair+Display:ital,wght@0,400..900;1,400..900&family=Tajawal:wght@300;400;500;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        :root {
            --primary-color: #513658;
            --accent-color: #8B5F96;
            --bg-color: #faf8f5;
            --text-dark: #2c222e;
            --card-bg: rgba(255, 255, 255, 0.85);
            --shadow: 0 10px 30px rgba(81, 54, 88, 0.08);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Tajawal', sans-serif;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-dark);
            min-height: 100vh;
            overflow-x: hidden;
            background-image: radial-gradient(#e0d7e5 1px, transparent 1px);
            background-size: 24px 24px;
        }

        /* Hero Section - يأخذ الشاشة كاملة في البداية */
        .hero-section {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            position: relative;
            padding: 20px;
        }

        .logo-wrapper {
            margin-bottom: 20px;
            animation: fadeInZoom 1.5s ease-out forwards;
        }

        .brand-title {
            font-family: 'Amiri', serif;
            font-size: 4rem;
            color: var(--primary-color);
            margin-bottom: 5px;
            position: relative;
            display: inline-block;
        }

        .brand-subtitle {
            font-family: 'Playfair Display', serif;
            letter-spacing: 6px;
            font-size: 1.2rem;
            color: var(--accent-color);
            text-transform: uppercase;
        }

        .scroll-hint {
            position: absolute;
            bottom: 40px;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 10px;
            color: var(--accent-color);
            font-size: 0.9rem;
            animation: bounce 2s infinite;
        }

        .scroll-hint i {
            font-size: 1.2rem;
        }

        /* Content Container - يظهر عند التمرير لأسفل */
        .content-container {
            max-width: 480px;
            margin: 0 auto;
            padding: 0 20px 60px 20px;
        }

        /* روابط التواصل الاجتماعي */
        .links-wrapper {
            display: flex;
            flex-direction: column;
            gap: 16px;
            margin-bottom: 40px;
        }

        .link-card {
            background: var(--card-bg);
            backdrop-filter: blur(8px);
            border: 1px solid rgba(139, 95, 150, 0.15);
            padding: 16px 24px;
            border-radius: 16px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            text-decoration: none;
            color: var(--text-dark);
            box-shadow: var(--shadow);
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .link-card:hover {
            transform: translateY(-3px);
            border-color: var(--accent-color);
            box-shadow: 0 15px 35px rgba(81, 54, 88, 0.12);
        }

        .link-info {
            display: flex;
            align-items: center;
            gap: 16px;
        }

        .link-icon {
            width: 42px;
            height: 42px;
            border-radius: 50%;
            background: rgba(139, 95, 150, 0.1);
            color: var(--primary-color);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.2rem;
        }

        .link-title {
            font-weight: 500;
            font-size: 1.1rem;
        }

        .arrow-icon {
            color: var(--accent-color);
            font-size: 0.9rem;
            transition: transform 0.3s;
        }

        .link-card:hover .arrow-icon {
            transform: translateX(-5px);
        }

        /* كروت النصوص والعبارات */
        .text-card {
            background: var(--card-bg);
            border: 1px solid rgba(139, 95, 150, 0.15);
            border-radius: 20px;
            padding: 30px 24px;
            text-align: center;
            box-shadow: var(--shadow);
            margin-bottom: 24px;
        }

        .card-header {
            font-family: 'Amiri', serif;
            font-size: 1.5rem;
            color: var(--primary-color);
            margin-bottom: 12px;
        }

        .card-body {
            font-size: 1rem;
            color: #555;
            line-height: 1.7;
        }

        .footer-note {
            text-align: center;
            margin-top: 40px;
            color: var(--accent-color);
            font-size: 0.9rem;
            font-style: italic;
        }

        /* الأنيميشن */
        @keyframes fadeInZoom {
            0% {
                opacity: 0;
                transform: scale(0.8);
            }
            100% {
                opacity: 1;
                transform: scale(1);
            }
        }

        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% {
                transform: translateY(0);
            }
            40% {
                transform: translateY(-10px);
            }
            60% {
                transform: translateY(-5px);
            }
        }
    </style>
</head>
<body>

    <!-- الجزء الأول: الاسم يملأ نصف الشاشة أولاً -->
    <section class="hero-section">
        <div class="logo-wrapper">
            <h1 class="brand-title">ذِكْرى</h1>
            <div class="brand-subtitle">ZEKRA</div>
        </div>
        <div class="scroll-hint">
            <span>اسحب للأسفل</span>
            <i class="fa-solid fa-chevron-down"></i>
        </div>
    </section>

    <!-- الجزء الثاني: المحتوى الذي يظهر بعد التمرير لأسفل -->
    <div class="content-container">
        
        <!-- روابط وسائل التواصل الاجتماعي -->
        <div class="links-wrapper">
            <a href="https://instagram.com" class="link-card" target="_blank">
                <div class="link-info">
                    <div class="link-icon"><i class="fa-brands fa-instagram"></i></div>
                    <span class="link-title">Instagram</span>
                </div>
                <i class="fa-solid fa-arrow-left arrow-icon"></i>
            </a>

            <a href="https://facebook.com" class="link-card" target="_blank">
                <div class="link-info">
                    <div class="link-icon"><i class="fa-brands fa-facebook-f"></i></div>
                    <span class="link-title">Facebook</span>
                </div>
                <i class="fa-solid fa-arrow-left arrow-icon"></i>
            </a>

            <a href="https://tiktok.com" class="link-card" target="_blank">
                <div class="link-info">
                    <div class="link-icon"><i class="fa-brands fa-tiktok"></i></div>
                    <span class="link-title">TikTok</span>
                </div>
                <i class="fa-solid fa-arrow-left arrow-icon"></i>
            </a>
        </div>

        <!-- الكروت النصية الخاصة بالعلامة التجارية -->
        <div class="text-card">
            <div class="card-header">Handmade with love</div>
            <p class="card-body">
                Every little detail is made with love.<br>
                Created especially for your beautiful memory.
            </p>
        </div>

        <div class="text-card">
            <p class="card-body">
                Follow Zahra & start close to every little detail.
            </p>
        </div>

        <div class="footer-note">
            Made with love. Zikra. ♡
        </div>

    </div>

</body>
</html>
