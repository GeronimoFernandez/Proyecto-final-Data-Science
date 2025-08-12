# SUPER MARKET SALES PREDICTIONS
# Geronimo Fernandez

# Objetivo:
# El objetivo de este proyecto es analizar los datos de ventas de un supermercado con el fin de descubrir insights interesantes que puedan ser útiles para mejorar la estrategia de ventas y toma de decisiones a traves de visualizaciones.

# El conjunto de datos utilizado proviene de un archivo CSV titulado supermarket_sales.csv originario de kaggle, que contiene información sobre las transacciones realizadas por los clientes en diferentes sucursales del supermercado. Las variables disponibles incluyen información sobre el cliente, el producto, la cantidad comprada, el precio, el método de pago, entre otros aspectos que podrían ofrecer una perspectiva integral sobre las ventas.

# Contexto Comercial:
# El dataset proporciona datos transaccionales de un supermercado con información clave como métodos de pago, líneas de productos, y la distribución de ventas por género y ubicación geográfica. Este análisis puede ayudar a optimizar inventarios, mejorar la experiencia del cliente, y aumentar las ganancias.

# Contexto analitico:
# Utilizaremos técnicas de análisis exploratorio de datos (EDA) para generar insights clave. El enfoque será identificar tendencias de ventas, evaluar la relación entre variables y explorar los métodos de pago y productos preferidos.Despues utilizaremos un modelo de machine learning llamado 'DecisionTreeClassifier' para buscar patrones que permitan anticipar si el cliente pagara en efectivo, con tarjeta de credito o mediante un e-wallet.

# Tipo de Aprendizaje: El modelo de árbol de decisión que hemos utilizado se enmarca dentro del aprendizaje supervisado.El modelo se entrena utilizando un conjunto de datos donde cada entrada está asociada a una etiqueta o resultado conocido. En mi caso, las observaciones corresponden a transacciones de clientes en un supermercado, y las etiquetas son los métodos de pago utilizados (efectivo, tarjeta de crédito, e-wallet).El objetivo a predecir es el método de pago que un cliente utilizará en una transacción en un supermercado.

# Listado de variables y breve explicacion:

# Invoice ID: Identificador único de la factura.
# Branch: Sucursal donde se realizó la venta.
# City: Ciudad en la que se encuentra la sucursal.
# Customer type: Tipo de cliente (miembro o no miembro).
# Gender: Género del cliente.
# Product line: Línea de productos comprados.
# Unit price: Precio por unidad del producto.
# Quantity: Cantidad de productos comprados.
# Tax 5%: Impuesto aplicado sobre la venta.
# Total: Total de la venta, incluyendo impuestos.
# Date: Fecha en que se realizó la transacción.
# Time: Hora en la que se realizó la transacción.
# Payment: Método de pago utilizado.
# Cogs: Costos de los productos vendidos.
# Gross margin percentage: Porcentaje de margen bruto de la venta.
# Gross income: Ingreso bruto generado por la venta.
# Rating: Valoración del cliente sobre la compra.

# Preguntas de hipotesis:

# Preferencia de pago: ¿Existe una relación entre el método de pago y la cantidad total de la compra? Por ejemplo, ¿las compras con tarjeta de crédito    tienden a tener montos más altos que las realizadas en efectivo?

# Ventas según el día de la semana: ¿Se observa un incremento en las ventas en ciertos días de la semana? Por ejemplo, ¿hay más ventas durante los fines de semana?
