<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ORKUT</title>
</head>
<body>
        <header id="logo"><img id="img1" src="./img/orkut-logo.png"></header>
    <div class="container">
            <br>
            <h1>Acesse o <span style="color:#eb238b; ">orkut</span> com sua conta <span style="color: rgb(41, 41, 238);">G</span><span style="color: rgb(246, 17, 231)">o</span><span style="color: rgb(255, 196, 0)">o</span><span style="color: rgb(88, 7, 227)">g</span><span style="color: gray">l</span><span style="color: rgb(246, 17, 231)">e</span>!</h1>
            <br>
            <div class="mb-3 mt-3">
              <input class="form-control" id="emailtelefone" placeholder="E-mail ou número de celular" name="email">
            </div>
            <br>
            <br>
            <div class="mb-3">
              <input type="password" class="form-control" id="senha" placeholder="Senha" name="pswd">
            </div>
            <br>
            <div class="form-check mb-3">
              <label class="form-check-label">
                <input class="form-check-input" type="checkbox" name="remember" id="checkbox"> Lembrar sempre do meu acesso
              </label>
            </div>
            <br>
            <button type="submit" class="entrar" onclick="window.location.href='usuario.html'">Entrar</button>
            <h1 id="esqueci">Esqueci senha ou e-mail </h1>
    </div>
    <div>
      <h1 id="naotemconta">Não tem conta? <span style="color: rgb(246, 17, 231)">Criar agora</span></h1>
    </div>
</body>
<style>
    body {
        background-color: rgba(200, 162, 200);
    }
    #logo {
      display: flex;
      justify-content: center;
    }
    #img1 {
      width: 20%;
    }
    .container {
      max-width: 700px;
      height: 400px;
      border-radius: 3%;
      background-color: white;
      margin: 3% auto;
    }
    .entrar {
      background-color: #eb238b;
      color: black;
      margin-left: 13%;
      width: 500px;
      height: 40px;
      border: solid white;
      border-radius: 10px;
    }
    h1 {
      text-align: center;
      font-size: 150%;
    }
    #emailtelefone {
      margin-left: 13%;
      width: 500px;
      height: 40px;
      border-radius: 10px;
      border: solid silver;
    }
    #senha {
      margin-left: 13%;
      width: 500px;
      height: 40px;
      border-radius: 10px;
      border: solid silver;
    }
    #checkbox {
      margin-left: 13%;
    }
    #esqueci {
      font-size: 85%;
      margin-left: 45%;
      color: black;
      font-family: Arial;
    }
    #naotemconta {
      font-size: 130%;
    }
</style>
</html>

