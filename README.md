# Pesentacion 
Introducción y objetivos del proyecto
Este proyecto tiene como objetivo analizar un conjunto de datos de transacciones de ventas para obtener insights relevantes sobre el comportamiento de los clientes, las tendencias de compra, y el desempeño de los productos. Buscamos entender patrones en la cantidad de productos vendidos, diferencias entre grupos demográficos, y detectar oportunidades para mejorar las estrategias comerciales.

Descripción del conjunto de datos
El dataset contiene 1000 registros de transacciones de ventas con 9 columnas:

Proyecto core de analisis de grafico
| Columna          | Descripción                                       | Tipo de dato |
| ---------------- | ------------------------------------------------- | ------------ |
| Transaction ID   | Identificador único de cada transacción           | int64        |
| Date             | Fecha de la transacción                           | object       |
| Customer ID      | Identificador único del cliente                   | object       |
| Gender           | Género del cliente                                | object       |
| Age              | Edad del cliente                                  | int64        |
| Product Category | Categoría del producto vendido                    | object       |
| Quantity         | Cantidad de unidades vendidas                     | int64        |
| Price per Unit   | Precio por unidad del producto                    | int64        |
| Total Amount     | Monto total de la transacción (Cantidad x Precio) | int64        |

