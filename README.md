
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Walentynki</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Pacifico&display=swap&family=Roboto:wght@400;700&display=swap');
    
        body {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            background-color: #fae3e3; /* Beżowo-różowe tło */
            background-image: url('walentynkowe-tlo.png'); /* Motyw serduszek */
            background-size: cover;
            background-position: center;
            text-align: center;
            font-family: 'Pacifico', cursive;
            padding-top: 20px;
        }
        .valentine-text {
            font-size: 80px;
            color: #b30000;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
            margin-bottom: 10px;
        }
        .separator {
            width: 60%;
            border-top: 2px solid black;
            margin: 20px auto;
        }
        .text-group {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            line-height: 1.2;
            margin-bottom: 50px;
        }
        .text-group p {
            margin: 5px 0;
            font-size: 24px;
            font-weight: bold;
        }
        img {
            max-width: 80%;
            height: auto;
            border-radius: 10px;
            border: 5px solid #b30000;
            margin-bottom: 20px;
        }
        a {
            display: inline-block;
            margin-top: 20px;
            font-size: 24px;
            text-decoration: none;
            color: #b30000;
            font-weight: bold;
            background: #fff0f0;
            padding: 12px 25px;
            border-radius: 20px;
            box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
            transition: all 0.3s ease-in-out;
        }
        a:hover {
            background: #ff6f61;
            color: white;
        }
        .phone-number {
            margin-top: 20px;
            font-size: 24px;
            font-weight: bold;
            color: #b30000;
            text-decoration: none;
            background: #fff0f0;
            padding: 12px 25px;
            border-radius: 20px;
            box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
            transition: all 0.3s ease-in-out;
        }
        .phone-number:hover {
            background: #ff6f61;
            color: white;
        }
        .static-text {
            font-size: 24px;
            color: black;
            font-family: 'Roboto', sans-serif;
            font-weight: bold;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
            margin-top: 15px;
        }
    </style>
</head>
<body>
    <div class="valentine-text">Walentynki</div>
    <p style="margin: 0; font-size: 24px; font-weight: bold;">Kwiaty więdną, czekoladki znikają.</p>
    <div class="separator"></div>
    <div class="text-group">
        <p>BIŻUTERIA</p>
        <p>Prezent na dziś, skarb na zawsze.</p>
    </div>
    <img src="https://github.com/user-attachments/assets/1f40c95c-7f81-4e32-b641-828dd979f8d6" alt="Zdjęcie sklepu">
    <p style="font-size: 24px; font-weight: bold;">Z hasłem <span style="color: #b30000;">Thoni-Alutec</span> 10% zniżki!</p>
    <a href="https://www.google.com/maps/place//data=!4m2!3m1!1s0x473d2da806df8d8d:0xb6c8bb17d8b92786?sa=X&ved=1t:8290&ictx=111" target="_blank">Zobacz lokalizację sklepu</a>
    <a href="tel:+48509512989" class="phone-number">📞 Telefon lub Whatsapp: +48 509 512 989 </a>
    <div class="static-text">Oferta ważna do 15.02.2025</div>
    <div class="static-text">Zapraszamy!</div>
</body>
</html>
