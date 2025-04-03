# Delivery app orders analysis

DA-3
Objetivo:
Encontrar hábitos de compra de los clientes de Instacart con base en los datos de las ordenes realizadas en la app
Manipulación de datos (Data Wrangling)
Preprocesamiento de datos: Limpiar los datos y preparar un informe que brinde información sobre los hábitos de compra de los clientes de Instacart
Realizar gráficos que comuniquen los resultados. Con un título, ejes etiquetados y una leyenda

Se desarrollan las siguientes habilidades:
- Leer y visualizar datos
- Trabajar con datos ausentes y duplicados
- Filtrado de datos
- Tipos de datos
- Transformación de datos
- Visualización de datos

## Conjunto de Datos

Hay cinco tablas en el conjunto de datos, y tendrás que usarlas todas para hacer el preprocesamiento de datos y el análisis exploratorio de datos. A continuación se muestra un diccionario de datos que enumera las columnas de cada tabla y describe los datos que contienen.

instacart_orders.csv: cada fila corresponde a un pedido en la aplicación Instacart.
- 'order_id': número de ID que identifica de manera única cada pedido.
- 'user_id': número de ID que identifica de manera única la cuenta de cada cliente.
- 'order_number': el número de veces que este cliente ha hecho un pedido.
- 'order_dow': día de la semana en que se hizo un pedido (0 si es domingo).
- 'order_hour_of_day': hora del día en que se hizo el pedido.
- 'days_since_prior_order': número de días transcurridos desde que este cliente hizo su pedido anterior.

products.csv: cada fila corresponde a un producto único que pueden comprar los clientes.
- 'product_id': número ID que identifica de manera única cada producto.
- 'product_name': nombre del producto.
- 'aisle_id': número ID que identifica de manera única cada categoría de pasillo de víveres.
- 'department_id': número ID que identifica de manera única cada departamento de víveres.

order_products.csv: cada fila corresponde a un artículo pedido en un pedido.
- 'order_id': número de ID que identifica de manera única cada pedido.
- 'product_id': número ID que identifica de manera única cada producto.
- 'add_to_cart_order': el orden secuencial en el que se añadió cada artículo en el carrito.
- 'reordered': 0 si el cliente nunca ha pedido este producto antes, 1 si lo ha pedido.

aisles.csv
- 'aisle_id': número ID que identifica de manera única cada categoría de pasillo de víveres.
- 'aisle': nombre del pasillo.

departments.csv
- 'department_id': número ID que identifica de manera única cada departamento de víveres.
- 'department': nombre del departamento.

