
# Proyecto Python: análisis de ventas de un e-commerce

 ### Resumen (Overview)
 Un e-commerce busca mejorar su servicio y brindar un mejor servicio a sus clientes. Mi objetivo utilizar Python para obtener información para mejorar el servicio del e-commerce.

 ### Sobre los Datos
 Los datos originales con la información de cada columna se encuentra [aquí](https://www.kaggle.com/datasets/abbas829/e-commerce-sales-analytics-dataset?resource=download).

El conjunto de datos consta de 5.000 registros con las siguientes columnas:

Order_id: Un identificador único para cada pedido.
Order_date: La fecha en que se realizó el pedido.
Customer_id: Un identificador único para el cliente que realizó el pedido.
Product_category: La categoría del producto vendido (por ejemplo, Belleza, Ropa, Electrónica).
Region: La región geográfica donde se realizó el pedido (por ejemplo, Sur, Este, Oeste).
Quantity: El número de artículos comprados en el pedido.
Unit_price: El precio de una sola unidad del producto.
Discount: El descuento aplicado al pedido (expresado como un número decimal).
Payment_method: El método utilizado para el pago (por ejemplo, monedero electrónico, tarjeta, contra reembolso).
Delivery_days: El número de días que tarda en entregarse el pedido.
Customer_rating: La calificación otorgada por el cliente al pedido (en una escala del 1 al 5).
Revenue: Los ingresos totales generados por el pedido (calculados como quantity * unit_price * (1 - discount)).
Total_sales: Son los ingresos totales del pedido que consite en la multiplicacion de quantity con unit_price. Sin aplicar el descuento.

 ### Tareas (Task)

1. ¿Cuál es el la región con mayor ingreso?

2. ¿Cuál es el método de pago más usado al realizar las compras?

3. ¿Cuál es el promedio de ingreso de los clientes por categoría de producto?

4. Si segmentamos la experiencia del cliente según los rangos estándar (Alto, Neutral, Bajo). ¿Cómo se distribuye la calificación de los pedidos?

5. ¿Cuál es el promedio de entrega de cada región?




 ### Análisis

 1. ¿Cuál es el la región con mayor ingreso?


!['barra1'](../Proyecto_de_Python/picture/grafica1.jpeg)


En la gráfica se muestra que West es la región con mayor ingreso entre todos.





2. ¿Cuál es el método de pago más usado al realizar las compras?


!['2'](../Proyecto_de_Python/picture/grafica2.jpeg)

En la gráfica se muestra que Card es el método de pago más usado al contar con un 45.4%.

3. ¿Cuál es la categoría de producto que tiene el promedio de ingreso más alto?

!['3'](../Proyecto_de_Python/picture/grafica3.jpeg) 


La categoría que tiene el ingreso promedio más alto es la categoría Beauty.

4. Si segmentamos la experiencia del cliente según los rangos estándar (Alto, Neutral, Bajo). ¿Cuál es la calificación más votada en general? 

!['4'](../Proyecto_de_Python/picture/grafica4.jpeg) 


Cada pedido fue calificado por cada cliente por lo cual se realizó una gráfica para saber el estado de calificación de los pedidos. Según la gráfica la calificación más alta está en el apartado de Bajo.

5. ¿El promedio de días de entrega por cada región es menor a 8 días?

!['5'](../Proyecto_de_Python/picture/grafica5.jpeg) 

Según la gráfica el promedio de días de entrega por cada región es menor a 8 días, porque cada región tiene un promedio de casi 6 días. 