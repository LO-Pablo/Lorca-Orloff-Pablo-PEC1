---
title: "Análisis de Datos de Caquexia"
author: "Lorca Orloff, Pablo"
date: "2025-03-30"
description: "Este archivo contiene el análisis de un conjunto de 77 observaciones y 65 variables, que incluye pacientes con caquexia y un grupo control, junto con 63 metabolitos medidos."
---

# Introducción

Este archivo incluye un análisis exploratorio del conjunto de datos de caquexia humana, el cual fue obtenido del repositorio GitHub https://github.com/nutrimetabolomics/metaboData.

Se generó un objeto de la clase `SummarizedExperiment` para almacenar y trabajar el conjunto de datos. Adicionalmente, se generó el respectivo archivo binario 'se_human_cachexia_PEC1_PLO.Rda'.

# Objetivos

Los objetivos de este trabajo son los siguientes:

1.  Analizar de manera exploratoria un conjunto de datos ómicos

2.  Crear, generar y utilizar un objeto de la clase `SummarizedExperiment`

# Métodos

Se realizaron pruebas estadísticas básicas y superficiales, como pruebas de distribución, correlación y PCA para explorar los datos.

# Resultados

Los resultados muestran que la distribución de los metabolitos no es normal, que los pacientes con caquexia tienden a tener, en promedio, los metabolitos en niveles más elevados y en análisis PCA mostró que los 3 primeros componentes explican más del 50% de la variabilidad de los datos.

# Discusión

Los análisis realizados fueron exploratorios de manera superficial y no presentan la potencia para sacar conclusiones generalizadas.

# Conclusiones

El análisis abre las puertas a seguir trabajando con los datos para estudiar las posibles conexiones entre los metabolitos y el síndrome caquexia

# Referencias

Nutrimetabolomics. 2025. «metaboData». [https://github.com/nutrimetabolomics/metaboData](https://github.com/nutrimetabolomics/metaboData)