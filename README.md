<!DOCTYPE html>
<html>
<head>
  <title>Tela de Menus</title>
  <style>
    body {
      background-color: #E1F3E1;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: Arial, sans-serif;
    }

    .menu-container {
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      background-color: white;
      padding: 20px;
      border-radius: 5px;
      box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
    }

    .welcome-message {
      font-size: 18px;
      color: #4CAF50;
      margin-bottom: 20px;
    }

    .menu-buttons {
      display: flex;
      flex-direction: column;
    }

    .menu-buttons button {
      background-color: #4CAF50;
      color: white;
      border: none;
      padding: 10px 20px;
      margin-bottom: 10px;
      cursor: pointer;
    }

    .logo-container {
      display: flex;
      align-items: center;
      justify-content: flex-end;
      margin-top: -20px;
      margin-right: -20px;
    }

    .logo-container img {
      width: 80px;
      height: 80px;
      margin-right: 10px;
    }

  </style>
</head>
<body>
  <div class="menu-container">
    <div class="logo-container">
      <img src="https://drive.google.com/uc?id=1lYi-W7s23S9fiqmRv5jO8DzhDuZ8Wuv5" alt="Logo">
      <p>Bem-vindo de volta!</p>
    </div>
    <div class="welcome-message">Selecione uma opção:</div>
    <div class="menu-buttons">
      <button onclick="window.location.href='https://sistemascoachin.github.io/Login-/sublocacoes.html'">Lançar Sublocações</button>
      <button onclick="window.location.href='https://sistemascoachin.github.io/Login-/particulares.html'">Lançar Particulares da Clínica</button>
    </div>
  </div>
</body>
</html>
