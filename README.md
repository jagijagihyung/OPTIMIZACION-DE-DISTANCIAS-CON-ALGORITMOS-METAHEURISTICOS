<h1 align="center">OPTIMIZACIÓN DE DISTANCIAS CON ALGORITMOS METAHEURÍSTICOS</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Estado-Activo-2E8B57" />
  <img src="https://img.shields.io/badge/Python-3.10-1E90FF" />
  <img src="https://img.shields.io/badge/Dataset-Rutas%20Reales-696969" />
</p>

---

## Descripción general

Este repositorio contiene el código, los notebooks y los datos utilizados en el estudio de optimización de rutas empleando algoritmos metaheurísticos.  
El proyecto forma parte de una investigación cuyo objetivo es comparar el desempeño, estabilidad y calidad de solución de distintos algoritmos aplicados a rutas reales de taxis en la ciudad de Puno.

El análisis incluye métricas como distancia total optimizada, distancia promedio, tiempo de ejecución y variabilidad entre múltiples ejecuciones.

---

## Estructura del repositorio

| Carpeta / Archivo | Descripción |
|-------------------|-------------|
| **/notebooks** | Implementación, pruebas y análisis en notebooks. |
| **/data** | Archivos CSV con rutas reales, coordenadas y distancias. |
| **/scripts** | Funciones auxiliares para procesamiento y cálculo de métricas. |

---

## Algoritmos implementados

El estudio considera tres algoritmos metaheurísticos ampliamente utilizados en problemas de optimización:

- **Algoritmo de Colonia de Hormigas (ACO)**  
- **Búsqueda Tabú (TS)**  
- **Algoritmo Genético (GA)**  

Cada algoritmo fue evaluado bajo diferentes perfiles de parámetros y ejecutado múltiples veces para garantizar estabilidad estadística.

---

## Metodología  
1. Construcción del dataset a partir de coordenadas reales de viajes urbanos.  
2. Limpieza y depuración del conjunto de datos, eliminando registros con errores, valores atípicos o coordenadas inválidas.  
3. Implementación de los tres algoritmos metaheurísticos.   
4. Evaluación mediante métricas de distancia, tiempo de ejecución, consistencia y variabilidad.  


---

## Autoras  
- **Milagros Medalit Contreras Chuquitarqui**  
- **Yosseline Keila Ticona Velasquez**
