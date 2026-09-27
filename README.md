<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ذكرى | ZEKRA</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;500;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary-color: #6b4c68;
            --accent-color: #8b6b88;
            --bg-color: #faf8f9;
            --text-dark: #2c222e;
            --card-bg: #ffffff;
            --shadow: 0 10px 25px rgba(107, 76, 104, 0.08);
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
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px 15px;
        }

        .container {
            width: 100%;
            max-width: 480px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        /* Hero Animation & Logo Section */
        .logo-wrapper {
            margin: 30px 0 20px;
            text-align: center;
            animation: fadeInZoom 1.2s ease-out forwards;
        }

        .logo-img {
            width: 180px;
            height: auto;
            max-width: 100%;
            border-radius: 50%;
            box-shadow: var(--shadow);
        }

        .subtitle {
            font-size: 0.95rem;
            color: var(--accent-color);
            margin-top: 10px;
            margin-bottom: 25px;
        }

        /* Social Buttons */
        .buttons-wrapper {
            width: 100%;
            display: flex;
            flex-direction: column;
            gap: 15px;
            margin-bottom: 30px;
        }

        .btn {
            background-color: var(--card-bg);
            border: 1px solid rgba(107, 76, 104, 0.15);
            border-radius: 50px;
            padding: 14px 22px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            text-decoration: none;
            color: var(--text-dark);
            font-weight: 500;
            font-size: 1rem;
            box-shadow: var(--shadow);
            transition: all 0.3s ease;
        }

        .btn:hover {
            transform: translateY(-2px);
            border-color: var(--primary-color);
            color: var(--primary-color);
        }

        .btn-content {
            display: flex;
            align-items: center;
            gap: 12px;
        }

        .btn-content i {
            font-size: 1.3rem;
            color: var(--primary-color);
        }

        .arrow-icon {
            font-size: 0.9rem;
            color: var(--accent-color);
        }

        /* Information Cards */
        .text-card {
            background: var(--card-bg);
            border: 1px solid rgba(107, 76, 104, 0.1);
            border-radius: 16px;
            padding: 20px;
            text-align: center;
            box-shadow: var(--shadow);
            margin-bottom: 15px;
            width: 100%;
        }

        .card-title {
            font-size: 1.1rem;
            font-weight: 700;
            color: var(--primary-color);
            margin-bottom: 8px;
        }

        .card-body {
            font-size: 0.92rem;
            color: #555;
            line-height: 1.6;
        }

        .footer-note {
            text-align: center;
            margin-top: 20px;
            font-size: 0.85rem;
            color: var(--accent-color);
        }

        @keyframes fadeInZoom {
            0% {
                opacity: 0;
                transform: scale(0.85);
            }
            100% {
                opacity: 1;
                transform: scale(1);
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Logo Section -->
        <div class="logo-wrapper">
            <img src="https://raw.githubusercontent.com/drahmedamragwa-byte/ZEKRA/main/80252.png" alt="ذكرى ZEKRA" class="logo-img">
        </div>

        <p class="subtitle">صُنع بحب.. لكل تفصيلة زفاف ومناسبة خاصة ♡</p>

        <!-- Social Media Links -->
        <div class="buttons-wrapper">
            <a href="https://www.instagram.com/zekra_store.eg?stkn=djhvNnMxNGpocGdv" class="btn" target="_blank">
                <div class="btn-content">
                    <i class="fab fa-instagram"></i>
                    <span>Instagram</span>
                </div>
                <i class="fas fa-chevron-left arrow-icon"></i>
            </a>

            <a href="https://www.facebook.com/share/1DVedBNMVj/" class="btn" target="_blank">
                <div class="btn-content">
                    <i class="fab fa-facebook-f"></i>
                    <span>Facebook</span>
                </div>
                <i class="fas fa-chevron-left arrow-icon"></i>
            </a>

            <a href="#" class="btn" target="_blank">
                <div class="btn-content">
                    <i class="fab fa-tiktok"></i>
                    <span>TikTok</span>
                </div>
                <i class="fas fa-chevron-left arrow-icon"></i>
            </a>
        </div>

        <!-- Details Cards -->
        <div class="text-card">
            <div class="card-title">Handmade with love</div>
            <div class="card-body">
                كل قطعة تُصنع بكل حب وعناية خصيصاً لتُخلد أجمل ذكرياتكم.
            </div>
        </div>

        <div class="footer-note">
            Made with love. Zikra ♡
        </div>
    </div>

</body>
</html>
