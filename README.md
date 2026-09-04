3. Documentación Redactá un breve documento (puede ser un archivo .docx o un README.md) donde expliques:
- Qué transformaciones realizaste y en qué orden.

Las transformaciones efectuadas sobre la tabla fueron:
  - Modificar los nombres de los encabezados de las columnas, por nombres entendibles para cualquier lector
  - Corroborar y modificar los tipos de datos de las columnas, según correspondiesen.
  - Duplicar la tabla en otras 2 tablas.
  - Modificar el nombre de cada tabla por ventas, clientes, productos respectivamente
  - Normalizar cada tabla, eliminando aquellas columnas que no fueran necesarias para dicha tabla.
  - Ordenar cada tabla en base a su columna de ID
  - Eliminar repetidos en base al ID
  - Eliminar filas que sean completamente 'null'
  - Reemplazar los valores 'null' por un el símbolo '-' en aquellas columnas que son compatibles con textos
  - Reemplazar los valores 'null' por 0 en aquellas columnas que son compatibles con valores numéricos
  - Aplicar cambios

- Por qué elegiste cada tipo de dato.

  Los tipos de datos elegidos fueron
    - Texto: Presenta una gran versatilidad para registrar datos, desde ID con codificación hasta nombres
    - Numero Decimal fijo: Fue seleccionado para la representación de montos numéricos financieros, dado que solo permiten 2 decimales
    - Porcentaje: Se lo utiliza para representar valores porcentuales sin haberse convertido a decimal, de esta forma es mucho más fácil representarlos en los gráficos
    - Número entero: Se lo eligió para representar valores que sean enteros sin decimales, ya sea para un cuantificador o contador
    - Fecha: Se eligió fecha para representar las fechas de las actividades evitando incorporar datos adicionales innecesarios, como ser la hora

- Cómo resolviste los valores nulos y duplicados encontrados.

  Para resolver los:
    - Valores nulos: Utilizado la herramienta de "reemplazar valores" busque todos los campos que tuvieran el valor null, y los reemplace por '-' en aquellas columnas que son compatibles con textos. Aquellas columnas que son compatibles con valores numéricos, los reemplacé por 0
    - Valores duplicados: Utilizando la función de "Quitar filas" seleccione eliminar duplicados, utilizando de referencia las columnas ID de cada tabla

- Qué criterio usaste para separar los datos del cliente de los de la transacción.

  Los criterios que utilicé para separar los datos del cliente de las transacciones, fueron:
    - No debían ser información relacionada a productos
    - No debía ser información referida a la venta
  Esos mismos criterios fueron elegidos para separar las tablas y crear de esa forma 3 tablas diferentes.
