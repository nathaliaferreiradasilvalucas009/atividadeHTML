# atividadeHTML
<!DOCTYPE html>
<html lang="pt-PT">
<head>
    <meta charset="UTF-8">
    <title>pagina interativa</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <button id="btnModo">modo black</button>

    <div class="container">

        <h1 id="meuTitulo">iae fessok</h1>

        <p id="meuParagrafo">esse e o meu site aqui ó</p>

        <button id="meuBotao">nao clica em mim pfv</button>

        <p id="mensagem"></p>

    </div>

    <script>
        const botao = document.getElementById('meuBotao');
        const titulo = document.getElementById('meuTitulo');
        const paragrafo = document.getElementById('meuParagrafo');
        const mensagem = document.getElementById('mensagem');

        const btnModo = document.getElementById('btnModo');

        botao.addEventListener('click', function() {
            titulo.textContent = "ai o mudou o titulo";
            paragrafo.textContent = " foi alterado com sucesso essa bosta aqui";
            mensagem.textContent = " ae deu certo o java uhuuuuuuuu";
        });

        btnModo.addEventListener('click', function() {
            document.body.classList.toggle('dark-mode');
        });
    </script>

</body>
</html>
