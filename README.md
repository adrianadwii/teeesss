<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Confession</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f5f5dc;
            font-family: Arial, sans-serif;
        }
        .container {
            text-align: center;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        button {
            margin-top: 10px;
            padding: 10px 20px;
            border: none;
            background-color: #ff69b4;
            color: white;
            font-size: 16px;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #ff1493;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Hey, ini buat kamu! 🌸</h1>
        <p>Tekan tombol di bawah untuk melihat pesan spesial.</p>
        <button onclick="showMessage()">Klik Aku</button>
        <p id="message" style="display: none; margin-top: 15px; font-size: 18px; color: #333;"></p>
    </div>
    
    <script>
        function showMessage() {
            document.getElementById("message").innerText = "Aku suka kamu! 🌷💖";
            document.getElementById("message").style.display = "block";
        }
    </script>
</body>
</html>
