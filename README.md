  <!DOCTYPE html><html lang='en'><head><meta charset='UTF-8'>
  <meta name='viewport' content='windth=device-width, initial-scale=1.0'>
  <title>Primer Programa : Control de un LED</title></head>
  /////////////////////
client.println("<body style='font-family:Century gothic; width:800;'><center>");
client.println("<div style='box-shadow:0px 0px 20px 8px rgba(0,0,0,0.22); padding :20px; width: 300px; display:inline-block; margin:30px; '>");
client.println("<h1>LED 1</h1>");
client.println("<h2>IoT : Control de encendido de un LED - WEB</h2>");
client.println("<button style='background-color:red; color:white; border-radius:10px; border-color:rgb(25,255,4);'");
client.println("type='button' onClick=location.href='/LED=OFF'><h2>Apagar LED</h2>");
client.println("</button><button style='background-color:blue; color:white; border-radius:10px; border-color:rgb(25,255,4);' ");
client.println("type='button' onClick=location.href='/LED=ON'><h2>Encender LED</h2>");
client.println("</button></div></center></body></html>");
//fin de la pagina
//se finaliza indicando que la petición fue finalizada
delay(10);
Serial.println("la petición fue finzalizada");
Serial.println(" ");
