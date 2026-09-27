<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ذكرى - Zikra</title>
    <style>
        :root {
            --primary-color: #f7dcd5;
            --text-color: #4a4a4a;
            --accent-color: #d4a373;
            --button-bg: #ffffff;
            --font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            --arabic-font: 'Amiri', serif;
        }

        body {
            margin: 0;
            padding: 0;
            font-family: var(--font-family);
            background-color: #fcf9f6;
            color: var(--text-color);
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vh;
            overflow-x: hidden;
            position: relative;
        }

        /* Decorative Background Elements */
        .bg-element {
            position: absolute;
            opacity: 0.1;
            z-index: 0;
        }

        .flower-top-left {
            top: 20px;
            left: 20px;
            width: 80px;
        }

        .bouquet-right {
            top: 100px;
            right: -50px;
            width: 250px;
        }

        .mirror-left {
            bottom: 100px;
            left: -30px;
            width: 150px;
        }

        .thread-bottom-right {
            bottom: 50px;
            right: 20px;
            width: 100px;
        }

        .handheld-top-right {
            top: 20px;
            right: 20px;
            width: 40px;
        }

        /* Main Content Wrapper */
        .container {
            position: relative;
            z-index: 1;
            width: 90%;
            max-width: 500px;
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
            padding-top: 30px;
        }

        /* Logo Animation */
        .logo-container {
            margin-bottom: 20px;
        }

        .logo {
            width: 120px;
            height: auto;
            animation: growLogo 1.5s ease-out forwards;
        }

        @keyframes growLogo {
            0% {
                transform: scale(0.2);
                opacity: 0;
            }
            60% {
                transform: scale(1.1);
            }
            100% {
                transform: scale(1);
                opacity: 1;
            }
        }

        /* Social Buttons */
        .buttons-wrapper {
            width: 100%;
            display: flex;
            flex-direction: column;
            gap: 15px;
            margin-bottom: 40px;
        }

        .btn {
            background-color: var(--button-bg);
            border: 1px solid var(--primary-color);
            border-radius: 50px;
            padding: 15px 25px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            text-decoration: none;
            color: var(--text-color);
            font-weight: 600;
            transition: all 0.3s ease;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
        }

        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
            border-color: var(--accent-color);
        }

        .btn-content {
            display: flex;
            align-items: center;
            gap: 15px;
        }

        .btn-logo {
            width: 24px;
            height: 24px;
        }

        .arrow {
            width: 16px;
            height: 16px;
            opacity: 0.5;
        }

        /* Footer Typography */
        .footer-section {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 15px;
            width: 100%;
            padding-bottom: 20px;
        }

        .handmade-text {
            font-family: var(--arabic-font);
            font-size: 1.2rem;
            color: var(--text-color);
            position: relative;
        }

        .underline-text {
            border-bottom: 1px solid var(--accent-color);
            padding-bottom: 10px;
            width: 80%;
            margin: 0 auto;
        }

        .slogan {
            font-size: 0.9rem;
            line-height: 1.6;
            color: var(--text-color);
            max-width: 80%;
        }

        .follow-text {
            display: flex;
            align-items: center;
            gap: 8px;
            font-weight: 500;
            color: var(--text-color);
        }

        .heart-icon {
            width: 16px;
            height: 16px;
            fill: rgba(212, 163, 115, 0.7);
        }

        .copyright {
            font-size: 0.8rem;
            color: #8a8a8a;
            margin-top: 10px;
        }

    </style>
    <!-- Importing Amiri font for elegant Arabic text -->
    <link href="https://fonts.googleapis.com/css2?family=Amiri:ital@0;1&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
</head>
<body>

    <!-- Background Decorative Elements -->
    <!-- Replace placeholder image URLs with your actual decorative images -->
    <img src="https://img.icons8.com/ios/100/d4a373/flower.png" alt="flower" class="bg-element flower-top-left">
    <img src="https://img.icons8.com/ios/250/d4a373/rose.png" alt="bouquet" class="bg-element bouquet-right">
    <img src="https://img.icons8.com/ios/150/d4a373/mirror.png" alt="mirror" class="bg-element mirror-left">
    <img src="https://img.icons8.com/ios/100/d4a373/sewing-needle.png" alt="thread and needle" class="bg-element thread-bottom-right">
    <img src="https://img.icons8.com/ios/50/d4a373/flower.png" alt="small flower" class="bg-element handheld-top-right">

    <div class="container">
        <!-- Logo Section with Animation -->
        <div class="logo-container">
            <!-- Replace with your actual logo URL -->
            <img src="https://via.placeholder.com/150/f7dcd5/4a4a4a?text=Zikra+Logo" alt="Logo" class="logo">
        </div>

        <!-- Social Media Buttons -->
        <div class="buttons-wrapper">
            <a href="https://www.instagram.com" class="btn" target="_blank">
                <div class="btn-content">
                    <img src="https://img.icons8.com/fluency/48/instagram-new.png" alt="Instagram" class="btn-logo">
                    <span>Instagram</span>
                </div>
                <img src="https://img.icons8.com/ios-filled/50/4a4a4a/long-arrow-right.png" alt="arrow" class="arrow">
            </a>

            <a href="https://www.facebook.com" class="btn" target="_blank">
                <div class="btn-content">
                    <img src="https://img.icons8.com/fluency/48/facebook-new.png" alt="Facebook" class="btn-logo">
                    <span>Facebook</span>
                </div>
                <img src="https://img.icons8.com/ios-filled/50/4a4a4a/long-arrow-right.png" alt="arrow" class="arrow">
            </a>

            <a href="https://www.tiktok.com" class="btn" target="_blank">
                <div class="btn-content">
                    <img src="https://img.icons8.com/fluency/48/tiktok.png" alt="TikTok" class="btn-logo">
                    <span>TikTok</span>
                </div>
                <img src="https://img.icons8.com/ios-filled/50/4a4a4a/long-arrow-right.png" alt="arrow" class="arrow">
            </a>
        </div>

        <!-- Footer Section with Slogans -->
        <div class="footer-section">
            <div class="underline-text">
                <div class="handmade-text">Handmade with love</div>
                <div class="slogan">Every little detail is made with love. Created especially for your beautiful memory.</div>
            </div>

            <div class="follow-text">
                <span>Follow Zahra & start close to every little detail</span>
                <svg class="heart-icon" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
                </svg>
            </div>

            <div class="copyright">
                Made with love. Zikra.
            </div>
        </div>
    </div>

</body>
</html>
 ZEKRA