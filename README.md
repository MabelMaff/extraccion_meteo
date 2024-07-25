# Extracción de Datos y Análisis Climático en Python / Data Extraction and Climate Analysis in Python

Este repositorio contiene el código para dos tareas principales: la extracción de datos de senderos de una página web y la obtención de datos climatológicos de la Sierra de Gredos utilizando la API de AEMET.

## Contenido

### Parte 1: Web Scraping con BeautifulSoup

Utilizando la biblioteca BeautifulSoup en Python, se extrae información de la siguiente web:
[Wikipedia: Sendero de Gran Recorrido](https://es.wikipedia.org/wiki/Sendero_de_Gran_Recorrido).

Se extrae la tabla de senderos de España con la siguiente información:
- Identificador
- Denominación
- Itinerario

El código realiza las siguientes acciones:
- Realiza una solicitud a la página web.
- Extrae y procesa la tabla de senderos.
- Guarda la información en un archivo CSV.

### Parte 2: Obtención de Datos Climatológicos con la API de AEMET

Utiliza la API de AEMET para obtener información climatológica de la Sierra de Gredos, específicamente usando el endpoint de "predicciones-específicas" para la predicción de montaña.

El código realiza las siguientes tareas:
- Incluye la temperatura máxima en la Sierra de Gredos.
- Incluye la temperatura mínima en la Sierra de Gredos.
- Incluye la fecha en la que se recopilaron los datos.
- Incluye la sierra de donde vienen los datos.

## Instalación y Uso

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
   ```
2. **Navega al directorio del proyecto**:
   ```bash
   cd tu_repositorio
   ```
3. **Instala las dependencias necesarias**:
   ```bash
   pip install beautifulsoup4 requests pandas
   ```
4. **Ejecuta el script de Jupyter Notebook**:
   ```bash
   jupyter notebook nombre_del_notebook.ipynb
   ```

## Contacto

Si tienes alguna pregunta o necesitas más información, no dudes en contactarme.

- **LinkedIn**: [Mabel Martinez Rodriguez](https://www.linkedin.com/in/mabelmr)

---

# Data Extraction and Climate Analysis in Python

This repository contains code for two main tasks: extracting trail data from a web page and obtaining climate data for the Sierra de Gredos using the AEMET API.

## Contents

### Part 1: Web Scraping with BeautifulSoup

Using the BeautifulSoup library in Python, information is extracted from the following web page:
[Wikipedia: Sendero de Gran Recorrido](https://es.wikipedia.org/wiki/Sendero_de_Gran_Recorrido).

The table of trails in Spain is extracted with the following information:
- Identifier
- Name
- Itinerary

The code performs the following actions:
- Makes a request to the web page.
- Extracts and processes the trails table.
- Saves the information to a CSV file.

### Part 2: Obtaining Climate Data with the AEMET API

Uses the AEMET API to obtain climate information for the Sierra de Gredos, specifically using the "specific-predictions" endpoint for mountain predictions.

The code performs the following tasks:
- Includes the maximum temperature in the Sierra de Gredos.
- Includes the minimum temperature in the Sierra de Gredos.
- Includes the date on which the data was collected.
- Includes the mountain range from which the data comes.

## Installation and Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your_username/your_repository.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd your_repository
   ```
3. **Install the required dependencies**:
   ```bash
   pip install beautifulsoup4 requests pandas
   ```
4. **Run the Jupyter Notebook script**:
   ```bash
   jupyter notebook notebook_name.ipynb
   ```

## Contact

If you have any questions or need more information, feel free to contact me.

- **LinkedIn**: [Mabel Martinez Rodriguez](https://www.linkedin.com/in/mabelmr)
