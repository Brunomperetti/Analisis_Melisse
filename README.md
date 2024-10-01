# Proyecto de Scraping y Análisis de Sentimiento

## Descripción del Proyecto

Este proyecto tiene como objetivo realizar un análisis de sentimiento sobre reseñas de un restaurante competidor que vende el mismo producto que nosotros. Para ello, se llevó a cabo un proceso de scraping para extraer las reseñas desde una página web, seguido por un análisis de los datos extraídos, y finalmente, la construcción y despliegue de un modelo de Machine Learning para la clasificación de los sentimientos. El modelo fue desplegado usando **Streamlit**.

## Tecnologías Utilizadas

- **Python**: Lenguaje principal utilizado para la ejecución del scraping, procesamiento de datos y creación del modelo de Machine Learning.
- **Selenium**: Librería utilizada para la automatización del scraping. Se encargó de interactuar con la página web y extraer la información.
- **Cloud Bucket**: Los datos extraídos fueron almacenados en un bucket en la nube, lo que permitió una gestión segura y escalable de los datos.
- **Streamlit**: Plataforma empleada para desplegar el modelo de Machine Learning en una interfaz web sencilla y accesible.

## Proceso

### 1. **Scraping con Selenium**
Se utilizó **Selenium**, una herramienta que permite la automatización de navegadores web, para extraer información de reseñas de un sitio web de un restaurante. Las reseñas estaban distribuidas en 139 páginas, resultando en un total de **3660 reseñas**.

### 2. **Subida de Datos a un Cloud Bucket**
Una vez extraídas las reseñas, los datos fueron procesados y almacenados en un bucket en la nube para una mayor accesibilidad y almacenamiento seguro. El proceso de subida fue realizado programáticamente desde Python.

### 3. **Análisis de Sentimiento**
Con los datos de las reseñas, se procedió a un análisis de sentimiento para determinar si las opiniones de los usuarios eran positivas, negativas o neutras. Esto nos permitió obtener una visión más clara sobre cómo los clientes perciben productos similares a los nuestros.

### 4. **Modelo de Machine Learning**
Para realizar el análisis de sentimiento, se construyó un modelo de **Machine Learning**. Este modelo fue entrenado con las reseñas previamente extraídas y procesadas, y se utilizó para clasificar nuevas opiniones en diferentes categorías de sentimiento.

# ¿Quieres ver el resultado?

Si deseas explorar el análisis de sentimiento en acción y probar el modelo, puedes hacerlo accediendo a la aplicación en el siguiente enlace:  
[Ver el análisis en Streamlit](https://brunomperetti-analisis-melisse-app-ha9pyo.streamlit.app/)



