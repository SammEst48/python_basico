# Dejame escuchar la musica 🎹

## Descripción
Este proyecto analiza datos de transmisión de música en línea para comparar las preferencias musicales de dos ciudades: Springfield y Shelbyville.

## Objetivos
El enfoque principal es probar la siguiente hipótesis: La actividad de los usuarios y las usuarias difiere según el día de la semana y la ciudad donde se encuentre.

## Dataset
- `'userID'`: identifica de forma exclusiva a cada usuario o usuaria;
- `'Track'`: título de la canción;
- `'artist'`: nombre del artista;
- `'genre'`: género musical;
- `'City'`: ciudad del usuario o la usuaria;
- `'time'`: hora del día en la que se reprodujo la pista (HH:MM:SS);
- `'Day'`: día de la semana.

## Herramientas utilizadas
- **Python**: pandas
- **Jupyter Notebooks**: para análisis interactivo y visualización.

## Pasos de análisis
 1. **Descripción de los datos**: se examinan los datos y se identifican posibles problemas
 2. **Preprocesamiento de datos**: se corrigen los encabezados de las columnas, se llenan los valores faltantes y se eliminan los duplicados
 3. **Prueba de hipótesis**: se agrupa a los usuarios por ciudad y se compara el número de canciones reproducidas por cada grupo en diferentes días de la semana.

## Conclusiones
El análisis de los datos procesados, utilizando agrupaciones por ciudad y día de la semana, reveló lo siguiente:
- Diferencias por ciudad: Existe una diferencia significativa en la cantidad de canciones reproducidas entre Springfield y Shelbyville, con Springfield registrando un volumen de reproducciones mucho mayor.
- Diferencias por día de la semana: Las reproducciones son más frecuentes en días cercanos al fin de semana, especialmente los viernes y lunes. Hay una disminución notable en las reproducciones durante la mitad de la semana.

La conclusión del proyecto afirma que, en base al análisis de datos, se puede confirmar la hipótesis. Sin embargo, se reconoce que hay otros factores que podrían influir en los resultados, como el medio de reproducción y el acceso a la música en cada ciudad.

