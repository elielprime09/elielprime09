<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulário</title>
</head>
<body>
    <h1>Preencha seus dados</h1>
    <p>Por favor, preencha os campos abaixo para que possamos entrar em contato com você.</p>
    
    <form action="seu_servidor.php" method="post">
        <label for="nome">Nome:</label><br>
        <input type="text" id="nome" name="nome" placeholder="Digite seu nome completo" required><br><br>
        
        <label for="email">E-mail:</label><br>
        <input type="email" id="email" name="email" placeholder="Digite seu e-mail" required><br><br>
        
        <label for="telefone">Telefone:</label><br>
        <input type="tel" id="telefone" name="telefone" placeholder="Digite seu número de telefone" required><br><br>
        
        <input type="submit" value="Enviar">
    </form>
</body>
</html>
