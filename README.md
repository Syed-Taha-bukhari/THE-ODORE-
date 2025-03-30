<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chand Raat Mubarak - For My Spouse</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            min-height: 100vh;
            background: linear-gradient(135deg, #0a0e2e, #1a1f4e);
            font-family: 'Arial', sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            color: white;
        }

        .container {
            width: 100%;
            max-width: 800px;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .card {
            position: relative;
            width: 350px;
            min-height: 500px;
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            box-shadow: 0 25px 45px rgba(0, 0, 0, 0.2);
            border: 1px solid rgba(255, 255, 255, 0.1);
            overflow: hidden;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px;
            text-align: center;
            z-index: 10;
            margin: 30px 0;
        }

        .card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(45deg, rgba(106, 90, 205, 0.3), rgba(245, 243, 206, 0.2));
            z-index: -1;
        }

        .moon {
            width: 120px;
            height: 120px;
            background: #f5f3ce;
            border-radius: 50%;
            box-shadow: 0 0 30px 10px rgba(245, 243, 206, 0.6);
            margin-bottom: 30px;
            position: relative;
            animation: glow 3s infinite alternate;
        }

        .moon::before {
            content: '';
            position: absolute;
            width: 30px;
            height: 30px;
            background: #0a0e2e;
            border-radius: 50%;
            top: 30px;
            left: 20px;
        }

        @keyframes glow {
            0% {
                box-shadow: 0 0 30px 10px rgba(245, 243, 206, 0.6);
            }
            100% {
                box-shadow: 0 0 40px 15px rgba(245, 243, 206, 0.8);
            }
        }

        h1 {
            font-size: 2.5rem;
            margin: 0;
            background: linear-gradient(to right, #f5f3ce, #b0a8e0);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            text-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }

        p {
            font-size: 1.1rem;
            margin: 20px 0;
            line-height: 1.6;
        }

        .stars {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
        }

        .star {
            position: absolute;
            background: white;
            border-radius: 50%;
            animation: twinkle var(--duration) infinite ease-in-out;
            opacity: 0;
        }

        @keyframes twinkle {
            0%, 100% {
                opacity: 0;
            }
            50% {
                opacity: var(--opacity);
            }
        }

        .lantern {
            position: fixed;
            width: 40px;
            height: 60px;
            background: rgba(255, 165, 0, 0.7);
            border-radius: 5px;
            box-shadow: 0 0 20px rgba(255, 165, 0, 0.5);
            animation: float 4s infinite ease-in-out;
        }

        .lantern::before {
            content: '';
            position: absolute;
            width: 10px;
            height: 10px;
            background: #ff8c00;
            border-radius: 50%;
            top: -5px;
            left: 15px;
        }

        @keyframes float {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-15px);
            }
        }

        .footer {
            font-size: 0.9rem;
            color: rgba(255, 255, 255, 0.7);
            margin: 20px 0;
        }

        .scroll-content {
            width: 100%;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 30px;
            padding-bottom: 50px;
        }

        .message {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(5px);
            border-radius: 15px;
            padding: 20px;
            width: 80%;
            max-width: 600px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }

        .message h2 {
            color: #f5f3ce;
            margin-top: 0;
            text-align: center;
        }

        .urdu {
            direction: rtl;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            font-size: 1.2rem;
            line-height: 2;
            text-align: right;
        }

        .heart {
            color: #ff6b6b;
            font-size: 1.5rem;
            vertical-align: middle;
        }

        .special-text {
            background: linear-gradient(to right, #f5f3ce, #b0a8e0);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            font-weight: bold;
        }

        .emoji {
            font-size: 1.2rem;
            vertical-align: middle;
        }
    </style>
</head>
<body>
    <div class="stars" id="stars"></div>
    
    <div class="container">
        <div class="scroll-content">
            <div class="card">
                <div class="moon"></div>
                <h1>Assalamualaikum</h1>
                <p>My Spouse (شریک حیات) <span class="emoji">💋✨🌍</span></p>
                <p>Ya Kuch ilfaz Meri traf sy Meri spouse ki Chand Raat ko Thora SA special bnany ka Lia <span class="emoji">👀</span></p>
            </div>

            <div class="message">
                <h2 class="special-text">My Eid Began When I Chose You</h2>
                <p class="urdu">👀 Merri Eid tw jab sy Shuru hai jab sy mny aapka intakab kia aapko apny khwab ma dakha.</p>
                <p class="urdu">ۓ جو ہے بشر منارہے عید آسمان کے چاند کو دیکھ کر <span class="emoji">🌙✨</span></p>
                <p class="urdu">یۓ جو دیکھ لیں میرے چاند کو تو اپنی عیدیں بھول جائیں ۔ <span class="emoji">❣✨</span></p>
                <p class="urdu">اے چاند کیا دکھا ہے تونے کسی کو تجھ سے حسین <span class="emoji">👀🌠</span></p>
                <p class="urdu">آ دیکھ وہ شخص جو میری دسترس میں ہے <span class="emoji">🌝🌸</span></p>
                <p class="urdu">مانتا ہوں ہوگا تو بھی حسین ان لوگوں میں مگر <span class="emoji">😌</span></p>
                <p class="urdu">ہوگی کہا تجھ کو بھی رقابت میری اس شریک حیات سے <span class="emoji">😊🙌🏻</span></p>
                <p class="urdu">جیسے کرتی ہے روشن اس آسمان کو تیری ے چمک <span class="emoji">🌌✨</span></p>
                <p class="urdu">چمکتا ہوں میں ویسے ہی اس شخص کے انگن میں!<span class="emoji">✨🌍🥀</span></p>
            </div>

            <div class="message">
                <h2 class="special-text">My Dua For You <span class="emoji">👀</span></h2>
                <p class="urdu">"ہے دعا کے آپ کو ملے وہ ساری خوشیاں میری دسترس رہ کر جو آپ کا حسن اس دنیا سے اول کر دے <span class="emoji">👀🌸✨</span>اور اللہ پاک میری اس شریک حیات کو جو چاہیں ان کو عطا کریں، مجھے ہمیشہ اپنی شریک حیات کا ساتھ دینے کی ہمت عطا کریں<span class="emoji">😌🙌🏻</span> اور مجھے جلدی سے انکے نکاح میں ڈال دیں،<span class="emoji">😭✨</span> میری جان کو اللہ پاک اس دنیا کی تمام کامیابیاں عطا کریں اور تمام جائز خواہشات کو پورا کریں، میری ساتھ <span class="emoji">👀🌚</span>میری جان کی زندگی میں آنے والے غموں کو ختم کر دیں اور ان کو خوشیوں میں تبدیل کر دیں <span class="emoji">❣🥀</span>اور جو بھی تکلیفیں پریشانیاں ہیں وہ تمام دور کر دیں اور مجھے جلد سے جلد اپنی عیدوں کو اور حسین کرنے کے لیے آپ کو میری نکاح میں ڈال دیں۔ آمین"<span class="emoji">💖✨</span></p>
                <p><span class="emoji">😊</span></p>
            </div>

            <div class="message">
                <h2 class="special-text">My Promises To You</h2>
                <p class="urdu">میں آپ کو بتاؤں گا کہ آپ دنیا کی سب سے حسین ، باوقار اور با صلاحیت لڑکی ہے اور میری محبت کی واحد حقدار<span class="emoji">🙌🏻🥀</span></p>
                <p class="urdu">میں آپ کو کسی کے آگے جھکنے نہیں دوں گا جہاں آپ کی عزت نہیں ہوگی وہاں کبھی آپ کو دیکھنے بھی نہیں دونگا۔۔۔<span class="emoji">✨🥀</span></p>
                <p>Aapky andhery ko mitany ka Lia ma aapki Roshni BN Jao...!</p>
                <p>Mera shor mitany ka Lia Mera sunkoon bn jayn?</p>
                <p class="urdu">اپنے کچھ گزرے ہوئے وقت سے نفرت ہے مجھے۔۔۔<span class="emoji">😐🌍</span></p>
                <p class="urdu">اپنی کچھ خواہشات پر شرمندہ ہوں میں <span class="emoji">🥹🌎</span></p>
            </div>

            <div class="message">
                <h2 class="special-text">A Little Question <span class="emoji">😭</span></h2>
                <p>What Kind of Love do you need? From me! So I can improve myself for you bcz This sweet little gurlll is mine Happiness idk how but Allah makes you Too important for me to live my Life With Joy and happiness if you are feel in love deeply then I won in my Goal that Allah gives me for this sweet Baby <span class="emoji">😭</span></p>
                <p>We all deserve a person who says, "We can fix this, I can't lose you." <span class="emoji">😭 🐼👑🦋💖</span></p>
                <p>"We need at least one friend who understands what we do not say."<span class="emoji">✨🥀</span></p>
                <p>And Efforts are better than promises <span class="emoji">😭</span> give me the path so I make that efforts which make you healer happiest and calmest.</p>
                <p>"I'm a strong person. But once in a while, I need  someone to take my hand and tell me that. Everything is going to be alright.”</p>
            </div>

            <div class="card">
                <div class="moon"></div>
                <h1>My Eternal Promise</h1>
                <p>And as always <span class="emoji">👀</span> in The End of the day Everything will be okay<span class="emoji">✨</span></p>
                <p>Chand Raat Mubarak my love <span class="heart">❤️</span></p>
            </div>

            <div class="footer"> Created By Your Jaan The ODORE  <span class="heart">❤️</span></div>
        </div>
    </div>

    <script>
        // Create stars
        const starsContainer = document.getElementById('stars');
        for (let i = 0; i < 100; i++) {
            const star = document.createElement('div');
            star.classList.add('star');
            star.style.left = `${Math.random() * 100}%`;
            star.style.top = `${Math.random() * 100}%`;
            star.style.width = `${Math.random() * 3 + 1}px`;
            star.style.height = star.style.width;
            star.style.setProperty('--duration', `${Math.random() * 3 + 2}s`);
            star.style.setProperty('--opacity', Math.random() * 0.7 + 0.3);
            star.style.animationDelay = `${Math.random() * 5}s`;
            starsContainer.appendChild(star);
        }

        // Create lanterns
        for (let i = 0; i < 5; i++) {
            const lantern = document.createElement('div');
            lantern.classList.add('lantern');
            lantern.style.left = `${Math.random() * 100}%`;
            lantern.style.top = `${Math.random() * 100}%`;
            lantern.style.animationDelay = `${Math.random() * 4}s`;
            document.body.appendChild(lantern);
        }
    </script>
</body>
</html>
