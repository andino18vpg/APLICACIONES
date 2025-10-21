# APLICACIones 
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Panel de Aplicaciones</title>
  <style>
    body {
      margin: 0;
      background: #111;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    #myExcelDiv {
      width: 100%;
      height: 100vh;
      border: none;
    }
  </style>
</head>
<body>

  <!-- Contenedor donde se cargará tu Excel -->
  <div id="myExcelDiv"></div>

  <!-- Script de incrustación de Excel Web App -->
  <script type="text/javascript" src="https://onedrive.live.com/embed?resid=5E32C7EE57CA4851!164&authkey=!ALDVBJq_lnIzQAs&em=3&wdDivId=%22myExcelDiv%22&wdHideGridlines=True&wdHideHeaders=True&wdDownloadButton=False&wdAllowInteractivity=True"></script>

</body>
</html>
