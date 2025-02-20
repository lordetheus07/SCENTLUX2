<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja de Perfumes</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            text-align: center;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px;
            font-size: 24px;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }
        .produto {
            background-color: white;
            margin: 15px;
            padding: 15px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            text-align: center;
            width: 250px;
        }
        .produto img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .botao {
            background-color: #28a745;
            color: white;
            border: none;
            padding: 10px;
            margin-top: 10px;
            cursor: pointer;
            border-radius: 5px;
        }
        .botao:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>
    <header>Loja de Perfumes</header>
    <div class="container">
        <div class="produto">
            <img src="https://via.placeholder.com/200" alt="Perfume 1">
            <h3>Perfume Elegance</h3>
            <p>R$ 199,90</p>
            <button class="botao">Comprar</button>
        </div>
        <div class="produto">
            <img src="https://via.placeholder.com/200" alt="Perfume 2">
            <h3>Perfume Sensation</h3>
            <p>R$ 179,90</p>
            <button class="botao">Comprar</button>
        </div>
    </div>
</body>
</html>
