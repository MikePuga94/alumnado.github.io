<!DOCTYPE html>
<html>
<head>
  <meta http-equiv="refresh" content="0;url=(https://github.com/MikePuga94/alumnado.github.io.git)">
</head>
<body>
  <p>Redireccionando...</p>
  <script>
    // Obtén el parámetro "code" de la URL actual
    const urlParams = new URLSearchParams(window.location.search);
    const code = urlParams.get("code");

    // Si se ha obtenido el código de autorización, redirige de vuelta a tu aplicación con el código
    if (code) {
      // Reemplaza TU_URL_DE_REDIRECCION con la URL de redirección a tu aplicación
      window.location.href = `TU_URL_DE_REDIRECCION?code=${code}`;
    }
  </script>
</body>
</html>
