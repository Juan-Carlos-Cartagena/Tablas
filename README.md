<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tabla   
 de Ventas</title>
    <style>
        table {
            border-collapse: collapse;
            width: 100%;
        }

        th, td {
            border: 1px solid black;
            padding: 8px;
            text-align: center;
        }

        tr:nth-child(5)   
 {
            background-color: lightblue;
        }
    </style>
</head>
<body>

<table>
    <thead>
        <tr>
            <th>Producto</th>
            <th>Cantidad</th>
            <th>Precio Unitario</th>
            <th>Fecha</th>
            <th>Total</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Naranja</td>
            <td>10</td>
            <td>$10.00</td>
            <td>2023-11-20</td>
            <td>$100.00</td>
        </tr>
        <tr>
            <td>Limon</td>
            <td>5</td>
            <td>$20.00</td>
            <td>2023-11-21</td>
            <td>$100.00</td>
        </tr>
        <tr>
            <td>Melon</td>
            <td>15</td>
            <td>$5.00</td>
            <td>2023-11-22</td>
            <td>$75.00</td>
        </tr>
        <tr>
            <td>Manzana</td>
            <td>8</td>
            <td>$12.50</td>
            <td>2023-11-23</td>
            <td>$100.00</td>
        </tr>
        <tr>
            <td>Pera</td>
            <td>20</td>
            <td>$3.00</td>
            <td>2023-11-24</td>
            <td>$60.00</td>
        </tr>
    </tbody>
</table>

</body>
</html>
