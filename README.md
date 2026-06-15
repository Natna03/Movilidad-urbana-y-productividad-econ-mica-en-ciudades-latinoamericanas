# Movilidad urbana y productividad económica en ciudades latinoamericanas

Este proyecto analiza la relación entre movilidad urbana, congestión vial y productividad económica en ciudades latinoamericanas durante 2024.

El análisis integra datos de tráfico y economía para comparar ciudades, identificar patrones de congestión y construir una primera lectura sobre posibles prioridades de inversión en transporte urbano.

---

## Herramientas y tipos de proyecto

![Python](https://img.shields.io/badge/PYTHON-2F80C0?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/PANDAS-2F80C0?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NUMPY-2F80C0?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/MATPLOTLIB-2F80C0?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/SEABORN-2F80C0?style=for-the-badge)
![Power BI](https://img.shields.io/badge/POWER%20BI-2F80C0?style=for-the-badge\&logo=powerbi\&logoColor=white)

![Limpieza de datos](https://img.shields.io/badge/LIMPIEZA%20DE%20DATOS-255F99?style=for-the-badge)
![Análisis exploratorio](https://img.shields.io/badge/ANÁLISIS%20EXPLORATORIO-255F99?style=for-the-badge)
![Movilidad urbana](https://img.shields.io/badge/MOVILIDAD%20URBANA-255F99?style=for-the-badge)
![Indicadores urbanos](https://img.shields.io/badge/INDICADORES%20URBANOS-255F99?style=for-the-badge)
![Priorización](https://img.shields.io/badge/PRIORIZACIÓN%20DE%20INVERSIÓN-255F99?style=for-the-badge)

---

## Objetivo

Evaluar cómo se relacionan los indicadores de movilidad urbana con variables económicas en ciudades latinoamericanas, usando datos de tráfico y economía para identificar patrones, comparar territorios y apoyar decisiones de planificación urbana.

---

## Preguntas clave

1. ¿Qué ciudades presentan mayores niveles de retraso por congestión?
2. ¿Qué ciudades tienen mayor índice de congestión urbana?
3. ¿Existe una relación fuerte entre congestión vial y PIB per cápita?
4. ¿Qué ciudades podrían ser prioritarias para inversión en transporte?
5. ¿Qué indicadores permiten monitorear mejor las condiciones urbanas?

---

## Metodología

- Carga y exploración de datos: revisión inicial de los archivos tomtom_traffic.csv y oecd_city_economy.csv.
- Limpieza y preparación: estandarización de columnas, fechas, valores numéricos y nombres de países.
- Filtro temporal: selección de datos correspondientes al año 2024.
- Unión de datasets: integración de datos de tráfico y economía mediante una unión INNER.
- Análisis visual: uso de boxplots, histogramas, gráficos de barras y dispersión para observar patrones y valores atípicos.
- Análisis de relación: cálculo de correlación de Spearman entre retraso por congestión y PIB per cápita.
- Índice de prioridad: construcción de un indicador para ordenar ciudades según congestión, retraso vial y desempleo.

---

## Principales hallazgos

- El análisis incluye 15 ciudades latinoamericanas de 7 países: Brasil, Colombia, Argentina, Perú, México, Chile y Uruguay.
Ciudad de México presentó el mayor retraso promedio por congestión dentro del grupo analizado.
Bogotá registró el mayor índice promedio de congestión urbana.
- São Paulo, Bogotá y Lima también aparecen como ciudades con altos niveles de retraso vial.
- La correlación de Spearman entre retraso por congestión y PIB per cápita fue de 0.13, lo que indica una relación positiva muy débil.
- Montevideo presentó el mayor PIB per cápita dentro del grupo analizado.
- Según el índice de prioridad construido, Bogotá aparece como la ciudad con mayor prioridad para inversión en transporte, seguida por Ciudad de México, São Paulo y Lima.

---

## Conclusiones y recomendaciones

## Conclusiones
- Los datos de movilidad y economía permiten monitorear condiciones urbanas y comparar ciudades latinoamericanas con diferentes niveles de congestión, productividad y presión territorial.
- La congestión vial es un indicador relevante para analizar movilidad urbana, pero con los datos disponibles no se puede afirmar que exista una relación causal directa entre congestión y productividad económica.
- El índice de prioridad ayuda a identificar ciudades que podrían requerir mayor atención en transporte, especialmente Bogotá, Ciudad de México, São Paulo y Lima.

## Recomendaciones
- Usar el índice de prioridad como una herramienta inicial de monitoreo, no como una conclusión definitiva.
- Profundizar el análisis de Bogotá, debido a que aparece como la ciudad con mayor prioridad según el índice construido.
- Incorporar variables adicionales en futuros análisis, como inversión en transporte público, infraestructura vial, tiempos de viaje y acceso a centros de empleo.
- Utilizar visualizaciones y reportes para comunicar los resultados a equipos técnicos, instituciones públicas u organizaciones interesadas en movilidad urbana y bienestar social.

---

📌 **Notebook:** [`Movilidad_urbana_y_productividad_económica_en_ciudades_latinoamericanas.ipynb`](./Movilidad_urbana_y_productividad_económica_en_ciudades_latinoamericanas.ipynb)
