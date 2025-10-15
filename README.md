# José Luis Martínez
# Introducción

Este informe presenta un análisis exploratorio de datos (EDA) del
dataset de noticias relacionadas con el índice Dow Jones Industrial
Average (DJIA). El objetivo es comprender patrones temporales,
distribución de etiquetas y características del contenido textual de las
noticias.

# Número de noticias por día de la semana y semana del año

Se generó un **heatmap** de noticias por semana y día de la semana
usando las columnas `Week` y `DayOfWeek`.

**Análisis:**

-   Los días de semana (lunes a viernes) presentan más noticias que los
    fines de semana, mostrando un patrón de publicación regular.

-   Se identifican semanas con mayor volumen de noticias, posiblemente
    vinculadas a eventos financieros, deportivos o políticos relevantes.

-   El patrón semanal ayuda a detectar ciclos de publicación y días con
    alta cobertura mediática.

# Distribución de etiquetas (Label 0/1)

La columna `Label` indica la polaridad de la noticia: 0 (negativa) y 1
(positiva).

**Análisis:**

-   La mayoría de noticias son negativas (Label=0), reflejando la
    tendencia de los medios a cubrir riesgos o problemas financieros.

-   El desequilibrio en la distribución de etiquetas es importante para
    futuros análisis de sentimiento o modelado predictivo.

# Longitud promedio de titulares por día

Se calculó la longitud total de los titulares por fila y se obtuvo la
media diaria.

**Análisis:**

-   Algunos días presentan titulares más largos, posiblemente debido a
    eventos complejos o reportes extensos.

-   Se observa variabilidad en la longitud promedio a lo largo del
    tiempo, lo que puede indicar cambios en la cobertura mediática.

# Palabras más frecuentes en noticias positivas

Se analizaron los titulares de noticias con Label=1 y se identificaron
las 20 palabras más frecuentes.

**Análisis:**

-   Palabras como *United*, *BBC*, *Ferguson* aparecen con frecuencia,
    indicando concentración en ciertos temas deportivos o mediáticos.

-   Este tipo de análisis permite identificar tópicos predominantes en
    noticias positivas.

# Número de noticias por semana del año

Se contó la cantidad de noticias por semana usando la columna `Week`.

**Análisis:**

-   Hay semanas con un número significativamente mayor de noticias, lo
    que puede coincidir con eventos relevantes del mercado financiero o
    acontecimientos internacionales.

-   Este análisis ayuda a detectar picos de cobertura y planificar
    estudios temporales de tendencias.

# Conclusión

El análisis exploratorio muestra patrones claros en la publicación de
noticias:

-   Mayor actividad informativa durante días laborales.

-   Predominio de noticias negativas sobre positivas.

-   Variaciones en la longitud de titulares según la complejidad de los
    eventos.

-   Concentración temática en noticias positivas.

Estos hallazgos sirven como base para un análisis más profundo de
sentimiento, tendencias temporales y modelado predictivo de noticias
financieras.
