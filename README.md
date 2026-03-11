# CHALLENGETelcom2
# Telecom X – Predicción de Cancelación de Clientes

Este proyecto desarrolla un modelo de Machine Learning para predecir la cancelación de clientes (Churn) en la empresa Telecom X.

El objetivo es identificar los factores que influyen en la cancelación del servicio y ayudar a la empresa a anticipar el riesgo de pérdida de clientes.

---

# Objetivos del proyecto

- Preparar los datos para el modelado
- Analizar la correlación entre variables
- Entrenar modelos de clasificación
- Evaluar el desempeño de los modelos
- Identificar las variables más importantes
- Generar recomendaciones estratégicas para reducir el churn

---

# Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Google Colab

---

# Modelos implementados

Se entrenaron dos modelos de clasificación:

**Regresión Logística**

Modelo lineal que requiere normalización de variables y permite interpretar la importancia de los coeficientes.

**Random Forest**

Modelo basado en árboles que permite analizar la importancia de variables sin necesidad de normalización.

---

# Resultados

El modelo con mejor desempeño fue **Regresión Logística**.

Métricas obtenidas:

Accuracy: 0.80  
Precision: 0.66  
Recall: 0.54  
F1-score: 0.59  

La tasa de cancelación observada en el dataset es aproximadamente **26.58%**.

---

# Variables más influyentes en la cancelación

Los principales factores asociados al churn son:

- Tipo de servicio de internet (Fiber optic)
- Método de pago (Electronic check)
- Cargos mensuales elevados
- Facturación digital (Paperless billing)
- Tiempo como cliente (Tenure)
- Tipo de contrato

---

# Conclusión

El modelo desarrollado permite identificar clientes con mayor probabilidad de cancelar el servicio. Este tipo de solución puede ayudar a Telecom X a implementar estrategias de retención y mejorar la fidelización de clientes.

---

# Autor

Proyecto desarrollado como parte del desafío **Telecom X – Machine Learning Challenge**.
