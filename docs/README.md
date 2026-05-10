# Análisis del Mercado de Airbnb en España

## Descripción del proyecto

Este repositorio contiene el código desarrollado para el Trabajo de Fin de Grado titulado:

**“Análisis del mercado de Airbnb en España”**

El objetivo del proyecto es analizar el comportamiento del mercado de alojamientos turísticos de Airbnb en distintas poblaciones españolas mediante técnicas de Big Data y procesos ETL.

Para ello, se trabajó con más de:

* 99.000 alojamientos
* 42 millones de registros de disponibilidad
* 5 millones de reseñas

correspondientes a distintas poblaciones españolas como Madrid, Barcelona, Valencia, Sevilla, Málaga, Girona, Euskadi, Mallorca y Menorca.

# Objetivos del proyecto

* Integrar múltiples datasets de Airbnb en una única estructura de datos.
* Limpiar y transformar grandes volúmenes de información.
* Analizar patrones relacionados con:

  * precios
  * ocupación
  * demanda
  * satisfacción de usuarios
  * Comparar el comportamiento del mercado entre diferentes poblaciones españolas.

---

# Herramientas utilizadas

* SQL
* DuckDB
* Google Colab

# Proceso ETL

El proyecto sigue un proceso ETL (Extract, Transform, Load):

## 1. Extract

Obtención de datasets públicos de Airbnb correspondientes a 9 poblaciones españolas.

Datasets utilizados:

* Listings
* Calendar
* Reviews

## 2. Transform

Durante esta fase se realizaron:

* Unificación de datasets
* Limpieza de valores nulos
* Conversión de formatos
* Validación de datos
* Creación de tablas consolidadas
* Transformación de variables

## 3. Load

Carga de los datos procesados para su posterior análisis mediante consultas SQL.

# Principales análisis realizados

* Precio medio por población
* Distribución de tipos de alojamiento
* Relación entre precio y capacidad
* Tasas de ocupación
* Análisis de disponibilidad
* Comparativa entre poblaciones
* Estudio de satisfacción del cliente
* Relación entre precio y demanda

# Fuente de datos

Los datasets utilizados en este proyecto proceden de la plataforma pública **Inside Airbnb**, una iniciativa independiente que recopila y publica información relacionada con el mercado de alojamientos turísticos de Airbnb en distintas ciudades del mundo.

Los datos utilizados incluyen información sobre:

* alojamientos (listings)
* disponibilidad y calendario (calendar)
* reseñas de usuarios (reviews)

Fuente oficial de los datos:
[Inside Airbnb](https://insideairbnb.com/get-the-data/)

Los datos han sido utilizados exclusivamente con fines académicos y educativos.

# Autoras

* Adriana González de Mesa Bravo
* Patricia Sotillos Pérez

Trabajo de Fin de Grado
Grado en Datos y Analítica de Negocio
ESIC University
Curso 2025/2026


# Licencia

Este proyecto ha sido desarrollado con fines académicos y educativos.
