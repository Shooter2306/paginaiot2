
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      background-color: #f0f0f0;
    }

  button-container {
      display: flex;
      flex-direction: column;
      align-items: center;
    }

  button {
      padding: 10px 20px;
      margin-bottom: 10px;
      font-size: 16px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: background-color 0.3s;
    }

  button:active {
      background-color: #cccccc;
    }

  button-10 {
      background-color: #66bb6a;
      color: white;
    }

  button-25 {
      background-color: #29b6f6;
      color: white;
    }

  button-50 {
      background-color: #ffa726;
      color: white;
    }

  button-on {
      background-color: #d32f2f;
      color: white;
    }

  button-off {
      background-color: #bdbdbd;
      color: white;
    }
  </style>

  <div class="button-container">
    <button class="button button-10" onclick="window.location.href='#10-percent'">10%</button>
    <button class="button button-25" onclick="window.location.href='#25-percent'">25%</button>
    <button class="button button-50" onclick="window.location.href='#50-percent'">50%</button>
    <button class="button button-on" onclick="window.location.href='#encender'">Encender</button>
    
    <
<button class="button button-off" onclick="window.location.href='#apagar'">Apagar</button>
  </div>

  <!-- Content sections for redirection -->
  <div id="10-percent" style="height: 100vh; background-color: #66bb6a;"></div>
  <div id="25-percent" style="height: 100vh; background-color: #29b6f6;"></div>
  <div id="50-percent" style="height: 100vh; background-color: #ffa726;"></div>
  <div id="encender" style="height: 100vh; background-color: #d32f2f;"></div>
  <div id="apagar" style="height: 100vh; background-color: #bdbdbd;"></div>
</body>
</html>
