Olá,me chamo João lucas 😊
💻Sou estudante de Análise e desenvolvimento de sistemas,
apaixonado por tecnologia e jogos,atualmente estou praticando 
Front-end(HTML,CSS,JAVASCRIPT).
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu primeiro formulário</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="form-container">
    <h1>Preencha o formulário abaixo:</h1>
    <p>Preencha os campos abaixo com suas informaçoes.<br>Garantimos que seus dados serão mantidos em segurança.<br>e utilizados apenas para entrar em contato com voçê.</p>
    <form>
        <label type="nome">Seu nome:</label>
        <input type="nome" id="nome"placeholder=Nome>
        <br><br>

        <label for="email">Seu e-mail:</label>
        <input type="email" id="email"placeholder=E-mail>
        <br><br>

        <label for="tefelofe">Seu telefone:</label>
        <input type="tefelofe" id="telefone"placeholder=Telefone>
        <br><br>

        <label for="mensagem">Mensagem:</label>
        <textarea id="mensagens"
        name="mensagem" rows="5" cols="40"
        placeholder="Digite sua mensagem aqui..."></textarea>
        <br><br>
    </form>
    <button>Enviar</button>

    .form-container{
    display:flex;
    justify-content: center;
    align-items:center;
    height: 100vh;
    border-radius: 2px;
} 

body{
    color: black;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    margin: 0;
    background-color: blueviolet
}
form{
    display:block;
    justify-content: center;
    align-items: center;
    margin-right: auto;
    margin-left: auto;
    height: 200px;
    position: absolute;
    top: 70%;
    transform: translatey(-70%);
    
    

}
h1{
      position:absolute;
      top: 20px;

}
p{
    position:absolute;
    top: 70px;

}
button{
    position:absolute;
    top: 600px;
}


    </div>
</body>
</html>
