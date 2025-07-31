#  Sprint 6: Proyecto del Módulo 1 - Análisis de Videojuegos
##  Descripción General

Este proyecto marca el cierre del primer módulo del curso. El objetivo es aplicar todas las habilidades adquiridas hasta ahora en un estudio de caso del mundo real: analizar datos de ventas de videojuegos para identificar patrones de éxito y apoyar decisiones estratégicas de marketing.

Trabajas para la tienda online **Ice**, que vende videojuegos a nivel mundial. Utilizarás datos históricos hasta 2016 para planificar una campaña para 2017.

---

##  Contenido del Proyecto
- Análisis exploratorio de datos
- Limpieza y transformación de datos
- Visualización de tendencias
- Pruebas de hipótesis
- Segmentación por regiones
- Conclusiones estratégicas

---

##  Descripción del Dataset
El archivo de datos se encuentra en: `/datasets/games.csv`

Columnas disponibles:

- `name`: Nombre del videojuego
- `platform`: Plataforma (e.g., Xbox, PlayStation)
- `year_of_release`: Año de lanzamiento
- `genre`: Género
- `na_sales`, `eu_sales`, `jp_sales`, `other_sales`: Ventas por región (en millones USD)
- `critic_score`: Puntuación de críticos (0-100)
- `user_score`: Puntuación de usuarios (0-10)
- `rating`: Clasificación ESRB

---

##  Paso 1: Preparación de los Datos
- Renombrar columnas a minúsculas
- Conversión de tipos de datos
- Manejo de valores ausentes (incluyendo "TBD")
- Cálculo de ventas globales por juego

---

##  Paso 2: Análisis Exploratorio

- Juegos lanzados por año
- Ventas por plataforma y evolución temporal
- Identificación de plataformas líderes y emergentes
- Análisis de reseñas vs. ventas
- Distribución de géneros y su rentabilidad

---

##  Paso 3: Perfil de Usuario por Región
Para cada región (NA, EU, JP):

- Top 5 plataformas
- Top 5 géneros
- Impacto de la clasificación ESRB en ventas
---

##  Paso 4: Pruebas de Hipótesis

Hipótesis evaluadas:

1. Las calificaciones promedio de usuarios para **Xbox One** y **PC** son iguales.
2. Las calificaciones promedio de usuarios para los géneros **Acción** y **Deportes** son diferentes.

- Definición de hipótesis nula y alternativa
- Selección del valor alfa
- Justificación del método estadístico utilizado
- Interpretación de resultados

---

##  Paso 5: Conclusiones

- Resumen de hallazgos clave
- Recomendaciones para campañas de marketing
- Reflexión sobre el proceso analítico

---

##  Evaluación del Proyecto

El proyecto será evaluado en base a:

- Calidad de la limpieza y análisis de datos
- Claridad en visualizaciones y explicaciones
- Razonamiento estadístico en pruebas de hipótesis
- Organización del notebook y comentarios
- Conclusiones bien fundamentadas

---

##  Herramientas Utilizadas

- Python (pandas, matplotlib, seaborn, scipy)
- Jupyter Notebook

---

