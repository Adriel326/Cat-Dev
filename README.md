# Cat-Dev
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Cat | Dev</title>
    <style>
        body {
            background-color: #121212;
            color: white;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            text-align: center;
            padding-top: 50px;
        }

        .btn {
            display: inline-block;
            padding: 10px 20px;
            margin: 10px;
            font-size: 16px;
            font-weight: bold;
            text-decoration: none;
            border-radius: 8px;
            transition: 0.3s;
            cursor: pointer;
            border: none;
        }

        .btn-buy {
            background-color: #28a745;
            color: white;
        }
        .btn-buy:hover {
            background-color: #218838;
            transform: scale(1.05);
        }

        .btn-discord {
            background-color: #5865F2;
            color: white;
        }
        .btn-discord:hover {
            background-color: #4752C4;
            transform: scale(1.05);
        }

        .btn-contact {
            background-color: #007bff;
            color: white;
        }
        .btn-contact:hover {
            background-color: #0069d9;
            transform: scale(1.05);
        }
    </style>
</head>
<body>
    <h1>Olá, bem-vindo à página inicial!</h1>
    
    <div style="border: 1px solid #333; padding: 20px; border-radius: 15px; display: inline-block;">
        <h2>Contas de Roblox</h2>
        <h3>Conta de 2012</h3>
        <p style="font-size: 24px; color: #ffcc00;">R$ 5,00</p>
        
        <a href="#" class="btn btn-buy">Comprar Agora</a>
        
        <br>
        <a href="https://discord.gg/MgYhcDNghr" target="_blank" class="btn btn-discord">
            Comprar pelo Discord
        </a>
    </div>

    <br><br>

    <a href="mailto:creativegroup158@gmail.com" class="btn btn-contact">
        Enviar E-mail para Contato
    </a>

    <script src="script.js"></script>
</body>
</html>
