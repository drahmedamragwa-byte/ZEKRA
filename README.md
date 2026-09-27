<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ذِكْرى | ZEKRA</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Amiri:ital@0;1&family=Tajawal:wght@300;400;500;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary-color: #5b3d56;
            --secondary-color: #7b5874;
            --accent-color: #a47ea0;
            --light-bg: #f9f6f3;
            --text-dark: #2c2530;
            --card-bg: rgba(255, 255, 255, 0.9);
            --shadow: 0 4px 15px rgba(123, 88, 116, 0.08);
            --border-color: rgba(164, 126, 160, 0.2);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Tajawal', sans-serif;
        }

        body {
            background-color: var(--light-bg);
            color: var(--text-dark);
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 40px 15px;
            overflow-x: hidden;
            background-image: radial-gradient(var(--accent-color) 0.5px, transparent 0.5px);
            background-size: 30px 30px;
            opacity: 0.95;
        }

        .container {
            width: 100%;
            max-width: 480px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        /* Logo Section */
        .logo-wrapper {
            margin-bottom: 20px;
            animation: fadeInZoom 1.2s ease-out forwards;
            text-align: center;
            position: relative;
        }

        .logo-img {
            width: 250px;
            height: auto;
            max-width: 100%;
            transition: transform 0.3s ease;
        }

        /* Handmade Section */
        .handmade-section {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 15px;
            color: var(--primary-color);
            margin: 20px 0 30px;
            font-size: 1.1rem;
            font-weight: 500;
        }

        .diamond {
            width: 8px;
            height: 8px;
            background-color: var(--primary-color);
            transform: rotate(45deg);
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
            background-color: var(--card-bg);
            border: 1px solid var(--border-color);
            border-radius: 50px;
            padding: 16px 24px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            text-decoration: none;
            color: var(--text-dark);
            font-weight: 500;
            font-size: 1rem;
            backdrop-filter: blur(10px);
            box-shadow: var(--shadow);
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .btn:hover {
            transform: translateY(-3px);
            border-color: var(--primary-color);
            box-shadow: 0 10px 20px rgba(123, 88, 116, 0.15);
            color: var(--primary-color);
        }

        .btn-content {
            display: flex;
            align-items: center;
            gap: 15px;
        }

        .btn-content i {
            font-size: 1.4rem;
            color: var(--primary-color);
            width: 25px;
            text-align: center;
        }

        .arrow-icon {
            font-size: 0.9rem;
            color: var(--accent-color);
        }

        /* Info Cards */
        .text-card {
            background: var(--card-bg);
            border: 1px solid var(--border-color);
            border-radius: 20px;
            padding: 25px;
            text-align: center;
            box-shadow: var(--shadow);
            margin-bottom: 20px;
            width: 100%;
            backdrop-filter: blur(10px);
        }

        .card-body {
            font-size: 0.95rem;
            color: #433842;
            line-height: 1.8;
            font-weight: 400;
        }

        .heart-icon {
            color: var(--accent-color);
            font-size: 1rem;
            margin-top: 15px;
            display: block;
        }

        /* Footer */
        .footer {
            text-align: center;
            margin-top: auto;
            padding-bottom: 20px;
            font-size: 0.85rem;
            color: var(--secondary-color);
            letter-spacing: 2px;
            text-transform: uppercase;
        }

        @keyframes fadeInZoom {
            0% {
                opacity: 0;
                transform: scale(0.9);
            }
            100% {
                opacity: 1;
                transform: scale(1);
            }
        }

        /* Responsive adjustments */
        @media (max-width: 480px) {
            body {
                padding: 30px 15px;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Logo Section -->
        <div class="logo-wrapper">
            <img src="https://raw.githubusercontent.com/drahmedamragwa-byte/ZEKRA/main/80252.png" alt="ذِكْرى ZEKRA" class="logo-img">
        </div>

        <!-- Handmade Section -->
        <div class="handmade-section">
            <div class="diamond"></div>
            <span>Handmade with love</span>
            <div class="diamond"></div>
        </div>

        <!-- Social Media Links -->
        <div class="buttons-wrapper">
            <a href="https://www.instagram.com/zekra_store.eg?stkn=djhvNnMxNGpocGdv" class="btn" target="_blank">
                <div class="btn-content">
                    <i class="fa-brands fa-instagram"></i>
                    <span>Instagram</span>
                </div>
                <i class="fa-solid fa-chevron-left arrow-icon"></i>
            </a>

            <a href="https://www.facebook.com/share/1DVedBNMVj/" class="btn" target="_blank">
                <div class="btn-content">
                    <i class="fa-brands fa-facebook-f"></i>
                    <span>Facebook</span>
                </div>
                <i class="fa-solid fa-chevron-left arrow-icon"></i>
            </a>

            <a href="#" class="btn" target="_blank">
                <div class="btn-content">
                    <i class="fa-brands fa-tiktok"></i>
                    <span>TikTok</span>
                </div>
                <i class="fa-solid fa-chevron-left arrow-icon"></i>
            </a>
        </div>

        <!-- Details Card 1 -->
        <div class="text-card">
            <p class="card-body">
                Every little detail is made with love,<br>
                created especially for your beautiful moments.
            </p>
        </div>

        <!-- Details Card 2 -->
        <div class="text-card">
            <p class="card-body">
                Follow ZEKRA and stay close to every little detail.
                <i class="fa-regular fa-heart heart-icon"></i>
            </p>
        </div>

        <!-- Footer -->
        <div class="footer">
            ♡ MADE WITH LOVE • ZEKRA ♡
        </div>
    </div>

</body>
</html>
