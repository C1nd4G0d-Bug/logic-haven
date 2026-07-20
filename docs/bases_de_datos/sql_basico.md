## Antes de empezar...

Cada vez que una aplicación recuerda tu usuario, guarda una foto o almacena una compra, detrás existe una base de datos organizando toda esa información.

SQL es el lenguaje que nos permite comunicarnos con esas bases de datos para consultar, guardar, modificar o eliminar datos.

---

## ¿Qué encontrarás en esta guía?

En esta guía aprenderás:

- Qué es SQL.
- Los tipos de datos más comunes.
- Cómo crear tablas.
- Restricciones y claves.
- Consultas usando SELECT.
- Filtros con WHERE.
- Inserción de datos.
- Actualización de registros.
- Eliminación de registros.
- Funciones básicas.
- Relaciones entre tablas mediante JOIN.

No necesitas conocimientos previos para seguir los ejemplos.

---

## Empecemos 🗄️

Vamos a descubrir cómo funcionan las bases de datos y cómo podemos comunicarnos con ellas usando SQL.

# ¿Qué es SQL?

Cada vez que una aplicación recuerda tu usuario, guarda una compra o almacena una fotografía, existe una base de datos trabajando detrás de escena.

Las bases de datos permiten organizar grandes cantidades de información para que pueda consultarse rápidamente cuando sea necesario.

Para comunicarnos con ellas utilizamos SQL.

# Crear estructuras

Antes de guardar información es necesario preparar el espacio donde se almacenará.

Por eso una de las primeras tareas en SQL consiste en crear tablas y definir cómo estarán organizados los datos.

Es parecido a preparar un archivador antes de empezar a guardar documentos.

# Tipos de datos

No toda la información ocupa el mismo formato.

Algunas columnas almacenan números, otras guardan texto, fechas o valores de verdadero y falso.

Definir correctamente estos tipos ayuda a mantener la información ordenada y evita errores.

# Tablas

Las tablas son el elemento principal de una base de datos.

Funcionan de manera muy similar a una hoja de cálculo, donde cada fila representa un registro y cada columna almacena un dato específico.

La diferencia es que una base de datos puede manejar cantidades enormes de información de manera mucho más eficiente.

# Restricciones

Las restricciones actúan como reglas que ayudan a proteger la información.

Gracias a ellas podemos evitar datos duplicados, impedir campos vacíos o garantizar que cada registro tenga una identificación única.

Estas reglas ayudan a mantener la calidad de los datos almacenados.

# Consultas

Guardar información es importante, pero poder encontrarla rápidamente es aún más importante.

Las consultas permiten buscar exactamente lo que necesitamos dentro de una base de datos.

Podemos solicitar registros específicos, aplicar filtros o recuperar únicamente la información que nos interesa.

# Filtros

A medida que la cantidad de registros aumenta, encontrar información se vuelve más difícil.

Los filtros ayudan a reducir los resultados y mostrar únicamente aquellos que cumplen determinadas condiciones.

De esta manera las búsquedas son más precisas y fáciles de interpretar.

# Agregar información

Las bases de datos están en constante crecimiento.

Cada nuevo usuario, producto o venta representa información que debe almacenarse correctamente.

SQL proporciona herramientas para registrar nuevos datos de forma organizada.

# Modificar información

A veces los datos cambian o contienen errores.

Cuando eso ocurre es posible actualizar la información existente sin necesidad de eliminar el registro completo.

Esto permite mantener la base de datos siempre actualizada.

# Eliminar información

También existen situaciones donde ciertos registros dejan de ser necesarios.

En esos casos pueden eliminarse para mantener la base de datos limpia y organizada.

Sin embargo, siempre es recomendable verificar cuidadosamente antes de borrar información importante.

# Funciones

SQL incluye funciones que permiten realizar cálculos automáticamente.

Gracias a ellas podemos contar registros, calcular promedios, obtener totales o identificar valores máximos y mínimos sin necesidad de hacerlo manualmente.

# Relaciones entre tablas

En una base de datos grande, la información suele dividirse en varias tablas.

Estas tablas pueden conectarse entre sí para compartir información relacionada.

Gracias a estas relaciones es posible construir sistemas organizados, eficientes y mucho más fáciles de mantener.