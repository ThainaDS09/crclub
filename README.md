# crclub
Uma comunidade para  amantes de Clash Royale
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CR Club - Adquira seu acesso para a Comunidade</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            color: #333;
        }

        header {
            background-color: #333;
            color: white;
            padding: 1em;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        header p {
            margin: 0;
            font-size: 1.2em;
        }

        section {
            max-width: 600px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #333;
        }

        form {
            display: flex;
            flex-direction: column;
        }

        label {
            margin-bottom: 8px;
        }

        input {
            padding: 8px;
            margin-bottom: 16px;
        }

        button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            font-size: 16px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        button:hover {
            background-color: #45a049;
        }

        #confirmacaoPagamento {
            display: none;
        }

        #confirmacaoPagamento p {
            font-size: 1.2em;
        }
    </style>
</head>
<body>

    <header>
        <h1>CR Club</h1>
        <p>Adquira seu acesso para a Comunidade CRClub. A entrada custa R$ 5.</p>
    </header>

    <section>
        <h2>Checkout</h2>
        <p>Preencha suas informações para adquirir o acesso.</p>
        <form id="formularioCheckout" onsubmit="return processarCheckout()">
            <label for="nome">Nome Completo:</label>
            <input type="text" id="nome" name="nome" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="telefone">Telefone:</label>
            <input type="tel" id="telefone" name="telefone" required>

            <label for="cpf">CPF:</label>
            <input type="text" id="cpf" name="cpf" required>

            <button type="submit">Pagar com PIX</button>
        </form>
    </section>

    <section id="confirmacaoPagamento">
        <h2>Pagamento Confirmado!</h2>
        <p>Seu pagamento de R$ 5 foi recebido. Clique no botão abaixo para entrar na comunidade.</p>
        <button onclick="location.href='https://chat.whatsapp.com/BCKloPCSltU4kg9oEa8PhN'">Entrar na Comunidade</button>
    </section>

    <script>
        // Funções JavaScript aqui...
    </script>

</body>
</html>
