<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>Saludo</title>
    <link href="style.css" rel="stylesheet" type="text/css" />
  </head>
  <body>
    <div>
      <input type="text" placeholder="Nombre" id="nombre"></input>
      <input type="text" placeholder="Apellido Paterno" id="paterno"></input>
      <input type="text" placeholder="Apellido Materno" id="materno"></input>
      <button onclick="saludar()">saludar</button>

    </div>

    <div id="el_saludo">
    </div>
    <script src="script.js"></script>
  </body>
</html>
