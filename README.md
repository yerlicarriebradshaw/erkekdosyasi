# erkekdosyasi
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Erkek Dosyası</title>
    <style>
        body {
            background-color: #fff5f9;
            color: #7d3c98;
            font-family: 'Poppins', sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
            background-image: url('https://www.transparenttextures.com/patterns/white-floral.png');
        }
        header {
            background-color: #ffccd9;
            color: white;
            padding: 20px;
            font-size: 24px;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 2px;
            border-bottom-left-radius: 40px;
            border-bottom-right-radius: 40px;
            box-shadow: 0 3px 8px rgba(255, 204, 217, 0.3);
        }
        .container {
            padding: 30px;
        }
        .section {
            margin: 10px auto;
            padding: 15px;
            background: #ffebf0;
            border-radius: 40px;
            max-width: 600px;
            height: 90px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            box-shadow: 0 3px 10px rgba(255, 204, 217, 0.3);
            border: 2px solid #f8b6c8;
            position: relative;
            opacity: 0;
            transform: translateY(30px);
            animation: fadeInUp 0.8s ease-in-out forwards;
        }
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        .button {
            background-color: #f8b6c8;
            color: white;
            padding: 4px 10px;
            text-decoration: none;
            border-radius: 15px;
            display: inline-block;
            margin-top: 4px;
            font-weight: bold;
            font-size: 10px;
            transition: all 0.3s ease;
            border: 2px solid #f8b6c8;
        }
        .button:hover {
            background-color: #fff;
            color: #f8b6c8;
            border: 2px solid #f8b6c8;
            box-shadow: 0 0 6px rgba(255, 204, 217, 0.4);
        }
        h2 {
            font-size: 18px;
            color: #a04574;
            font-family: 'Playfair Display', serif;
        }
        p {
            font-size: 12px;
            line-height: 1.2;
            font-family: 'Poppins', sans-serif;
            color: #8d4a7b;
        }
    </style>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;700&family=Playfair+Display:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
    <header>ERKEK DOSYASI 📂</header>
    <div class="container">
        <div class="section">
            <h2>🗂️ Erkek Kütüphanesi</h2>
            <p>Erkek tiplerini ve davranışlarını analiz eden arşiv.</p>
            <a href="#" class="button">Keşfet</a>
        </div>
        <div class="section">
            <h2>💌 Sizden Gelenler</h2>
            <p>Sizin hikayeleriniz.</p>
            <a href="#" class="button">Göz At</a>
        </div>
        <div class="section">
            <h2>💑 İlişki Uyumu</h2>
            <p>Partnerinle gerçekten uyumlu musun?</p>
            <a href="#" class="button">Uyumu Test Et</a>
        </div>
        <div class="section">
            <h2>📝 Testler</h2>
            <p>Kendi aşk haritanı çıkarmaya hazır mısın? <br> ⚠️ Toksik olan taraf sen olabilir misin?</p>
            <a href="#" class="button">Teste Başla</a>
        </div>
    </div>
</body>
</html>
