# Cinta-dalam-ridha
Teruntuk kamu seseorang yang allah ridhoin dan ridho kedua orang tua


<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cinta dalam Ridha-Nya</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Amiri&display=swap');

        body {
            font-family: 'Amiri', serif;
            background: url('https://i.ibb.co/6ZtSxGB/islamic-bg.jpg') no-repeat center center fixed;
            background-size: cover;
            text-align: center;
            color: white;
            margin: 0;
            padding: 0;
        }

        .overlay {
            background: rgba(0, 0, 0, 0.6);
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }

        .container {
            position: relative;
            margin-top: 10%;
            z-index: 2;
        }

        h1 {
            font-size: 2.5rem;
            text-shadow: 2px 2px 10px rgba(255, 215, 0, 0.8);
            animation: fadeIn 3s ease-in-out;
        }

        p {
            font-size: 1.3rem;
            max-width: 600px;
            margin: auto;
            text-shadow: 1px 1px 5px rgba(255, 255, 255, 0.5);
            animation: fadeIn 5s ease-in-out;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        .heart {
            font-size: 4rem;
            color: gold;
            animation: glow 1.5s infinite alternate;
        }

        @keyframes glow {
            0% { text-shadow: 0 0 10px gold; }
            100% { text-shadow: 0 0 20px yellow; }
        }

        .button {
            margin-top: 20px;
            padding: 10px 20px;
            font-size: 1.2rem;
            border: none;
            color: white;
            background: #d4af37;
            cursor: pointer;
            border-radius: 5px;
            transition: background 0.3s ease-in-out;
            box-shadow: 2px 2px 10px rgba(255, 215, 0, 0.8);
        }

        .button:hover {
            background: #ffd700;
        }
    </style>
</head>
<body>

    <div class="overlay"></div>

    <div class="container">
        <h1>Untukmu yang Tak Peka, tapi Kucintai karena Allah ❤️</h1>
        <p>
            Aku tak meminta banyak...  
            Cukup Allah menakdirkanmu dalam hidupku.  
            Jika engkau jodohku, semoga Allah mempertemukan kita dalam kebaikan.  
            Jika tidak, semoga Allah menggantinya dengan yang lebih baik.  
            Tapi ketahuilah...  
            <strong>Dalam doa, namamu selalu kusebut.</strong>
        </p>
        
        <div class="heart">🌙✨</div>

        <button class="button" onclick="showLove()">Balas Aku?</button>
    </div>

    <script>
        function showLove() {
            alert('Semoga Allah meridhoi perasaan ini. Jika engkau jodohku, semoga Allah mempermudah jalan kita. 💖');
        }
    </script>
