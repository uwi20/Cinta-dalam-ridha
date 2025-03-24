# Cinta-dalam-ridha
Teruntuk kamu seseorang yang allah ridhoin dan ridho kedua orang tua


<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cinta dalam Ridha-Nya</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Scheherazade&display=swap');

        body {
            font-family: 'Scheherazade', serif;
            background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.7)), 
                        url('https://i.ibb.co/W5F9ZwN/islamic-mosque-bg.jpg') no-repeat center center fixed;
            background-size: cover;
            text-align: center;
            color: white;
            margin: 0;
            padding: 0;
            position: relative;
        }

        .container {
            margin-top: 10%;
            z-index: 2;
            position: relative;
        }

        h1 {
            font-size: 2.8rem;
            text-shadow: 2px 2px 15px rgba(255, 223, 0, 0.9);
            animation: fadeIn 3s ease-in-out;
        }

        p {
            font-size: 1.5rem;
            max-width: 650px;
            margin: auto;
            text-shadow: 1px 1px 8px rgba(255, 255, 255, 0.8);
            animation: fadeIn 5s ease-in-out;
        }

        .heart {
            font-size: 4rem;
            color: gold;
            animation: glow 1.5s infinite alternate;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes glow {
            0% { text-shadow: 0 0 10px gold; }
            100% { text-shadow: 0 0 20px yellow; }
        }

        .button {
            margin-top: 20px;
            padding: 12px 25px;
            font-size: 1.4rem;
            border: none;
            color: white;
            background: linear-gradient(45deg, #d4af37, #ffdd57);
            cursor: pointer;
            border-radius: 8px;
            transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
            box-shadow: 0px 4px 10px rgba(255, 223, 0, 0.8);
        }

        .button:hover {
            transform: scale(1.1);
            box-shadow: 0px 6px 15px rgba(255, 223, 0, 1);
        }

        .stars {
            position: absolute;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
            z-index: 1;
            pointer-events: none;
            background: url('https://i.ibb.co/3YpB3LZ/stars.png') repeat;
            animation: twinkling 8s infinite linear;
        }

        @keyframes twinkling {
            from { background-position: 0 0; }
            to { background-position: -1000px 1000px; }
        }
    </style>
</head>
<body>

    <div class="stars"></div>

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
