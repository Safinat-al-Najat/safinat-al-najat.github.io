---
title: Home
---
---
## Home

---

<div class="home-bismillah">بِسْمِ اللّٰهِ الرَّحْمٰنِ الرَّحِيْمِ</div>

Assalamu Alaikum Wa Rahmatullahi Wa Barakatuh  🌙

<div class="quran-verse" dir="rtl">
 وَٱعْتَصِمُوا۟ بِحَبْلِ ٱللَّهِ جَمِيعًۭا وَلَا تَفَرَّقُوا۟
</div>

"Hold firmly to the rope of Allah all together and do not become divided." — [Surah Al-Imran 3:103](https://quran.com/3/103)

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Islamic Navigation</title>
    <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;600;700&family=Outfit:wght@300;400;500&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Outfit', sans-serif;
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
            padding: 2rem;
        }

        .container {
            max-width: 900px;
            width: 100%;
        }

        .button-grid {
            display: grid;
            gap: 1.5rem;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
        }

        .nav-button {
            position: relative;
            background: white;
            border: none;
            border-radius: 16px;
            padding: 2rem;
            cursor: pointer;
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
            box-shadow: 
                0 4px 6px rgba(0, 0, 0, 0.05),
                0 1px 3px rgba(0, 0, 0, 0.08);
            overflow: hidden;
            text-align: left;
            width: 100%;
        }

        .nav-button::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 4px;
            background: linear-gradient(90deg, #2c5f2d, #4a9d4f);
            transform: scaleX(0);
            transform-origin: left;
            transition: transform 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .nav-button:hover::before {
            transform: scaleX(1);
        }

        .nav-button:hover {
            transform: translateY(-4px);
            box-shadow: 
                0 12px 24px rgba(0, 0, 0, 0.12),
                0 4px 8px rgba(0, 0, 0, 0.08);
        }

        .nav-button:active {
            transform: translateY(-2px);
        }

        .icon-wrapper {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            display: inline-block;
            transition: transform 0.3s ease;
        }

        .nav-button:hover .icon-wrapper {
            transform: scale(1.1) rotate(5deg);
        }

        .button-title {
            font-family: 'Cormorant Garamond', serif;
            font-size: 1.5rem;
            font-weight: 700;
            color: #1a1a1a;
            margin-bottom: 0.5rem;
            letter-spacing: 0.3px;
        }

        .button-subtitle {
            font-family: 'Outfit', sans-serif;
            font-size: 0.95rem;
            font-weight: 300;
            color: #666;
            line-height: 1.5;
            opacity: 0.9;
        }

        .nav-button::after {
            content: '→';
            position: absolute;
            bottom: 1.5rem;
            right: 2rem;
            font-size: 1.5rem;
            color: #4a9d4f;
            opacity: 0;
            transform: translateX(-10px);
            transition: all 0.3s ease;
        }

        .nav-button:hover::after {
            opacity: 1;
            transform: translateX(0);
        }

        @media (max-width: 768px) {
            .button-grid {
                grid-template-columns: 1fr;
            }
            
            .nav-button {
                padding: 1.5rem;
            }
        }

        /* Specific button variations */
        .nav-button:nth-child(1):hover {
            background: linear-gradient(135deg, #ffffff 0%, #f8f9fa 100%);
        }

        .nav-button:nth-child(2):hover {
            background: linear-gradient(135deg, #ffffff 0%, #f1f8f4 100%);
        }

        .nav-button:nth-child(3):hover {
            background: linear-gradient(135deg, #ffffff 0%, #f4f6f8 100%);
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="button-grid">
            <button class="nav-button" onclick="handleClick('virtues')">
                <div class="icon-wrapper">📁</div>
                <div class="button-title">Virtues and Merits</div>
                <div class="button-subtitle">Virtues of ahlulbayt and companions</div>
            </button>

            <button class="nav-button" onclick="handleClick('events')">
                <div class="icon-wrapper">📁</div>
                <div class="button-title">ISLAMIC EVENTS</div>
                <div class="button-subtitle">Major Islamic Events</div>
            </button>

            <button class="nav-button" onclick="handleClick('rulings')">
                <div class="icon-wrapper">⚖️</div>
                <div class="button-title">Rulings</div>
                <div class="button-subtitle">Fiqh, obligations & Islamic law</div>
            </button>
        </div>
    </div>

    <script>
        function handleClick(section) {
            console.log(`Navigating to: ${section}`);
            // Add your navigation logic here
            alert(`You clicked: ${section}`);
        }
    </script>
</body>
</html>


---
### For any queries:
📧 [safinatalnajat151214@gmail.com](mailto:safinatalnajat151214@gmail.com)