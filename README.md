# 
body {
    background-color: #1D4221;
    color: white;
    font-family: "Bai Jamjuree", sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 700px;
    margin: 0;
}

button {
    background-color: #64A712;
    color: white;
    font-family: "Bai Jamjuree", sans-serif;
}






<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Em busca da cidade perdida</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Edu+VIC+WA+NT+Beginner:wght@400..700&display=swap" rel="stylesheet">
</head>
<body>
    <main>
        <div class="passo" id="passo-0">
            <p>Um dia desses, dentro de um livro da biblioteca da escola, eu descobri uma carta antiga sobre uma cidade perdida, escondida por riquezas e belezas naturais. Nessa carta, a autora deixa algumas pistas para encontrar essa cidade e eu decidi segui-las!</p>
            <button class="btn-proximo" data-proximo="1">Rio de Janeiro</button>
            <button class="btn-proximo" data-proximo="2">Pernambuco</button>
        </div>
        <div class="passo" id="passo-1">
            <p>Você começa sua jornada no Rio de Janeiro, subindo o Pico da Tijuca ao amanhecer para encontrar a primeira pista.</p>
            <button class="btn-proximo" data-proximo="3">Procurar a pista no topo do pico</button>
            <button class="btn-proximo" data-proximo="4">Desistir e voltar para casa</button>
        </div>
    </main>



</body>
</html>
