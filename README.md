# 📊 Proyecto 6 – Análisis de Clientes ConnectaTel

## 📌 Objetivo del proyecto

El objetivo de este proyecto es analizar el comportamiento de los clientes de ConnectaTel, una empresa de telecomunicaciones con operaciones en Latinoamérica, para identificar patrones de uso, detectar problemas de calidad en los datos, segmentar a los usuarios y generar recomendaciones que apoyen la toma de decisiones del negocio.

## 📂 Datasets utilizados

Se trabajó con los siguientes conjuntos de datos:

- **plans.csv:** Información de los planes disponibles, incluyendo precios, minutos, datos móviles y costos adicionales.
- **users_latam.csv:** Información de los usuarios, como edad, ciudad, fecha de registro y plan contratado.
- **usage.csv:** Registros históricos del uso de los servicios (llamadas y mensajes).

## 🔍 Etapas del análisis

Durante el desarrollo del proyecto se realizaron las siguientes actividades:

1. Carga y exploración inicial de los datos.
2. Identificación de problemas de calidad de datos.
3. Limpieza y transformación de la información:
   - Corrección de valores centinela.
   - Estandarización de fechas.
   - Tratamiento de valores nulos.
4. Creación de métricas agregadas de uso por usuario.
5. Análisis estadístico descriptivo.
6. Visualización de distribuciones y detección de posibles valores atípicos.
7. Segmentación de clientes por edad y nivel de uso.
8. Elaboración de conclusiones y recomendaciones para el negocio.

## 🚀 Cómo ejecutar el proyecto

1. Clona este repositorio o descarga los archivos.
2. Asegúrate de tener instaladas las siguientes librerías:
   - pandas
   - numpy
   - matplotlib
   - seaborn
3. Abre el notebook `.ipynb` en **Jupyter Notebook** o **Google Colab**.
4. Verifica que los archivos `plans.csv`, `users_latam.csv` y `usage.csv` estén disponibles en la ruta esperada.
5. Ejecuta las celdas en orden para reproducir el análisis completo.

## 📈 Resultados principales

- Se identificaron y corrigieron valores centinela e inconsistencias en los datos.
- Se analizaron los patrones de uso de llamadas y mensajes por usuario.
- Se crearon segmentos de clientes según su edad y nivel de uso.
- Se detectaron usuarios con consumos elevados que representan oportunidades para estrategias de fidelización y ofertas especializadas.
- Se generaron recomendaciones para optimizar la oferta de planes y mejorar la segmentación comercial.

## 👩‍💻 Autor

Proyecto desarrollado como parte del Sprint 7 del programa de Análisis de Datos.
