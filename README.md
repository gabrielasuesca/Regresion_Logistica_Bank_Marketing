# Regresión Logística — Bank Marketing

## Descripción

Proyecto académico desarrollado para la asignatura **Introducción a Machine Learning** de la Universidad de Cundinamarca.

El objetivo es construir un modelo de **Regresión Logística** capaz de estimar la probabilidad de que un cliente acepte contratar un depósito a plazo después de una campaña de marketing telefónico.

## Pregunta de análisis

¿Las características del cliente y su interacción con una campaña de marketing permiten estimar la probabilidad de que acepte un depósito a plazo?

## Dataset

Se utiliza el dataset **Bank Marketing** del UCI Machine Learning Repository.

La variable objetivo es:

- `no` = 0
- `yes` = 1

Entre las variables utilizadas se encuentran:

- Edad
- Trabajo
- Estado civil
- Educación
- Balance
- Crédito de vivienda
- Préstamo personal
- Tipo de contacto
- Número de contactos de la campaña
- Contactos anteriores
- Resultado de campañas previas

## Metodología

El proyecto incluye:

1. Recolección de datos.
2. Exploración y revisión de calidad.
3. Preparación de variables numéricas y categóricas.
4. One-Hot Encoding.
5. Estandarización.
6. División de datos en entrenamiento y prueba.
7. Entrenamiento de un modelo de Regresión Logística.
8. Predicción de probabilidades.
9. Evaluación mediante Accuracy, Precision, Recall, F1, ROC-AUC y PR-AUC.
10. Matriz de confusión.
11. Curvas ROC y Precision-Recall.
12. Ajuste del umbral de decisión.
13. Interpretación mediante coeficientes y Odds Ratios.

## Herramientas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Fuente de datos

Moro, S., Rita, P., & Cortez, P. (2014). *Bank Marketing* [Dataset]. UCI Machine Learning Repository.

https://doi.org/10.24432/C5K306

## Autora

**Gabriela Suesca Castillo**  
Universidad de Cundinamarca  
Asignatura: Introducción a Machine Learning  
Docente: Monica Fonseca
