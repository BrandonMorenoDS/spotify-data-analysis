#  Análisis de Canciones Populares en Spotify

Este proyecto es un **análisis exploratorio de datos (EDA)** sobre canciones populares de Spotify.  
El dataset fue obtenido de [Kaggle - Spotify Music Dataset](https://www.kaggle.com/datasets/solomonamen/spotify-music-dataset).  

El objetivo es practicar limpieza, transformación de datos y visualización en Python, utilizando `pandas` y `matplotlib`.

---

## Dataset
El dataset contiene canciones recopiladas de la API de Spotify, incluyendo:  
- **Características descriptivas:** artista, álbum, fecha de lanzamiento.  
- **Características de audio:** energía, valencia, bailabilidad, tempo, entre otras.  
- **Popularidad:** métrica provista por Spotify.  

---

## Pasos de Limpieza
1.  Eliminación de valores nulos en columnas clave.  
2.  Conversión de `duration_ms` a minutos.  
3. Conversión de `track_album_release_date` a formato fecha y creación de la columna `year`.  
4.  Normalización de artistas (separación de colaboraciones en filas individuales).  

---

##  Visualizaciones
- **Top 10 artistas con más canciones** (incluyendo colaboraciones).  
- **Distribución de la duración de canciones** (histograma).  
- **Relación entre energía y bailabilidad** (scatter plot).  
- **Popularidad promedio de canciones por año** (línea temporal).  

---

## Conclusiones
- El dataset abarca canciones desde **1954** hasta la actualidad, con mayor densidad en décadas recientes.  
- La mayoría de canciones duran entre **3 y 4 minutos**, lo estándar en la industria musical.  
- Los artistas más recurrentes incluyen tanto solistas como colaboradores frecuentes.  
- Las canciones populares se concentran en rangos **medios-altos de energía y bailabilidad**, sugiriendo que ambas características influyen en su éxito.  
- La **popularidad promedio** se mantiene relativamente estable desde los 80, con picos específicos por grandes éxitos.  

---

## Tecnologías utilizadas
- Python  
- Pandas  
- Matplotlib  

---

Autor: Brandon Moreno  
Proyecto subido como parte de mi práctica inicial en Ciencia de Datos.
