<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Título de la página</title>
    <!-- Agregar enlace a la hoja de estilos de Bootstrap -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    
</head>
<body>
    <div class="container mt-5">
        <table class="table table-bordered table-striped">
            <thead class="thead-dark">
                <tr>
                    <th scope="col">Numero</th>
                    <th scope="col">Fecha</th>
                    <th scope="col">Nevera</th>
                    <th scope="col">Producto</th>
                    <th scope="col">Cantidad</th>
                    <th scope="col">Pesos</th>
                </tr>
            </thead>
            <tbody>
                <tr class="fila-resaltada">
                    <td>1</td>
                    <td>2023-09-27 6:16:38</td>
                    <td>bebida</td>
                    <td>cerveza</td>
                    <td>10</td>
                    <td>30000</td>
                </tr>
                <!-- Agregar más filas si es necesario -->
            </tbody>
        </table>
        <!-- Agregar el hipervínculo -->
        <a href="https://docs.google.com/spreadsheets/d/1Mz10aB8jaR5z4HtA6InIBALCUz7c7HtJU9jYgZ5yolM/edit?usp=sharing" target="_blank">Haz click aquí para ver tabla de datos</a>
    </div>
    <!-- Agregar el iframe -->
    <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTcEzIXW7rn25aeuK5V-CZgMBgzNNPvM5jLWxahDlW2g-0_IGiBmVt4GtSvRc5dfSrsbyfxmPdvsETw/pubhtml?widget=true&amp;headers=false"></iframe>
    <!-- Agregar el script de Bootstrap al final del body -->
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
