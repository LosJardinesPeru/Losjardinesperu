<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Jardines - Productora de eventos</title>
  <style>
    body {
      margin: 0;
      font-family: sans-serif;
      background: url('imagen.png') no-repeat center top;
      background-size: cover;
      height: 100vh;
    }
    .formulario {
      position: absolute;
      top: 80px; /* ajusta según tu imagen */
      right: 50px; /* ajusta según tu imagen */
      background-color: rgba(255,255,255,0.6);
      padding: 20px;
      border-radius: 10px;
      width: 300px;
    }
    .formulario input, .formulario textarea {
      width: 100%;
      margin: 5px 0;
      padding: 8px;
      border: none;
      border-radius: 5px;
    }
    .formulario button {
      width: 100%;
      padding: 10px;
      background-color: #497254;
      color: white;
      border: none;
      border-radius: 5px;
    }
  </style>
</head>
<body>
  <form class="formulario" action="https://formsubmit.co/TUCORREO" method="POST">
    <input type="text" name="nombre" placeholder="Nombres" required>
    <input type="email" name="email" placeholder="Correo electrónico" required>
    <input type="tel" name="celular" placeholder="Número de celular">
    <input type="text" name="empresa" placeholder="Nombre de empresa">
    <input type="text" name="ruc" placeholder="Número de RUC">
    <textarea name="requerimiento" placeholder="Requerimiento" rows="3"></textarea>
    <button type="submit">Enviar</button>
  </form>
</body>
</html>
