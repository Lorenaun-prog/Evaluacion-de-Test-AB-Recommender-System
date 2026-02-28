# Evaluación de Test A/B — Sistema de Recomendaciones

Nota: El nombre de la empresa ha sido modificado por motivos de confidencialidad.

¿Qué hice?

Validación técnica del experimento A/B.

Análisis del embudo de conversión (product_page → cart → purchase).

Verificación de asignación correcta de usuarios.

Prueba z para evaluar diferencias significativas entre grupos.

Identificación de posibles sesgos y anomalías.

Tecnologías: Python, pandas, numpy, matplotlib, seaborn, scipy, statsmodels


# Evaluación de Test A/B — Recommender System

Nota de confidencialidad:
Por motivos de seguridad y protección de datos, el nombre de la empresa y ciertos detalles contextuales han sido adaptados. El análisis refleja la metodología utilizada y los resultados obtenidos, preservando la confidencialidad de la información original.

## 📌 Contexto

Análisis de un experimento A/B lanzado por una tienda online internacional para evaluar el impacto de un sistema de recomendaciones mejorado en el embudo de conversión.

## 🔎 Objetivos

Verificar si el test fue correctamente configurado y ejecutado.

Analizar la conversión en el embudo:
product_page → product_card → purchase

Validar si el grupo B logra al menos un 10% de mejora en cada etapa.

Detectar posibles sesgos o problemas en la asignación de usuarios.

Evaluar la significancia estadística mediante prueba z para proporciones.

## 📂 Datasets

ab_project_marketing_events_us.csv → calendario de campañas de marketing.

final_ab_new_users_upd_us.csv → nuevos usuarios registrados.

final_ab_events_upd_us.csv → eventos realizados por los usuarios.

final_ab_participants_upd_us.csv → asignación a grupos A y B.

## 📊 Análisis realizado

Limpieza y validación de tipos de datos.

Revisión de duplicados y usuarios en ambos grupos.

Distribución de eventos por usuario y por día.

Cálculo de tasas de conversión por etapa.

Prueba z para diferencia de proporciones entre grupos.

Evaluación de posibles interferencias externas (campañas activas).

## 🛠️ Tecnologías

Python · pandas · numpy · matplotlib · seaborn · scipy · statsmodels · Jupyter Notebook
