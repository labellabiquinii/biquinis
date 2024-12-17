<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LaBella Biquínis</title>
    <style>
        /* Estilo Geral */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            color: #333;
            line-height: 1.6;
        }
        /* Header */
        header {
            background-color: #ff8787;
            color: #fff;
            padding: 1.5rem 0;
            text-align: center;
            font-size: 1.8rem;
        }
        /* Conteúdo Principal */
        .container {
            width: 90%;
            max-width: 600px;
            margin: 2rem auto;
            text-align: center;
        }
        input, button {
            margin-top: 1rem;
            padding: 0.8rem;
            width: 100%;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        button {
            background-color: #ff8787;
            color: #fff;
            border: none;
            cursor: pointer;
            font-size: 1rem;
        }
        button:hover {
            background-color: #e76c6c;
        }
        img {
            max-width: 100%;
            margin: 1rem 0;
        }
        /* Footer */
        footer {
            margin-top: 2rem;
            background-color: #333;
            color: #fff;
            padding: 1rem;
            text-align: center;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <h1>LaBella Biquínis</h1>
    </header>

    <!-- Conteúdo Principal -->
    <div class="container">
        <h2>Bem-vinda à nossa loja!</h2>
        <p>Receba novidades e ofertas especiais diretamente no seu telefone.</p>

        <!-- Formulário -->
        <form action="https://formspree.io/f/SEU_ENDPOINT" method="POST">
            <input type="tel" name="telefone" placeholder="Digite seu telefone" required>
            <button type="submit">Enviar</button>
        </form>

        <!-- Imagem -->
        <img src="https://via.placeholder.com/600x300" alt="Biquínis exclusivos">

        <!-- Redes Sociais -->
        <p>Siga-nos no Instagram:</p>
        <a href="https://instagram.com/labella_biquini" target="_blank">@Labella_biquini</a>
    </div>

    <!-- Rodapé -->
    <footer>
        <p>&copy; 2024 LaBella Biquínis. Todos os direitos reservados.</p>
    </footer>
</body>
</html>