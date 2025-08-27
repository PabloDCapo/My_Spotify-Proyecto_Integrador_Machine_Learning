# MySpotify: Explorando la Música a través del Machine Learning
## Propuesta
Este proyecto sirve como una guía práctica para la aplicación de modelos de Machine Learning en el análisis de datos musicales. A través de la API de Spotify, creamos un sistema de recomendación que va más allá de los filtros convencionales, enfocándose en las características intrínsecas de las canciones para generar listas de reproducción personalizadas y coherentes.

Este material ha sido meticulosamente diseñado para servir como una guía comprensiva, ofreciendo tanto la fundamentación teórica indispensable del filtrado colaborativo como la implementación práctica detallada del modelo K-Means.

## Objetivos
Analizar y adaptar el sistema de recomendaciones de Spotify utilizando un modelo propio.

Demostrar el potencial de los algoritmos de clustering (K-Means) para agrupar música por similitud.

Generar una guía sencilla e intuitiva sobre la estructura del código y el flujo de trabajo del proyecto.

##¿Cómo usar el código?
Configurar credenciales: Obtener y configurar tus credenciales de la API de Spotify (Client ID y Client Secret).

Instalar dependencias: Asegurarse de tener instaladas todas las librerías necesarias (mencionadas en el archivo requirements.txt).

Ejecutar las celdas en orden: El código está diseñado para ser ejecutado secuencialmente.

## Partes del Código
El proyecto está organizado en las siguientes secciones clave:

Importación de Librerías: Carga de las bibliotecas necesarias.

Definición de Funciones: Módulos para la conexión a Spotify, obtención de datos de las listas de reproducción, y la aplicación del modelo.

Aplicación del Modelo (K-Means): Se ejecuta el algoritmo de clustering sobre los datos de las canciones.

Generación de Nuevas Listas: Creación de listas de reproducción en Spotify, ordenadas por la similitud de los ítems y con la adición de nuevas recomendaciones.
