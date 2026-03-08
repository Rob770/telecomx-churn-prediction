# 📊 Predicción de Cancelación de Clientes (Churn)

## 📌 Descripción del Proyecto

Este proyecto analiza los factores que influyen en la cancelación de clientes en una empresa de telecomunicaciones y desarrolla modelos de Machine Learning para predecir qué clientes tienen mayor probabilidad de abandonar el servicio.

El análisis incluye limpieza de datos, exploración de variables, visualización, entrenamiento de modelos y evaluación del rendimiento.

---

## 🎯 Objetivos

* Identificar los factores que influyen en la cancelación de clientes.
* Construir modelos predictivos de churn.
* Comparar el rendimiento de diferentes algoritmos de Machine Learning.
* Proponer estrategias de retención basadas en los resultados obtenidos.

---

## 📂 Dataset

El dataset contiene información sobre clientes de telecomunicaciones, incluyendo:

* Tipo de contrato
* Servicios contratados
* Cargos mensuales
* Tiempo de permanencia del cliente
* Método de pago

La variable objetivo es **Churn**, que indica si el cliente canceló el servicio.

---

## ⚙️ Modelos Utilizados

Se entrenaron dos modelos de Machine Learning:

### Regresión Logística

Modelo lineal utilizado para estimar la probabilidad de cancelación.

### Random Forest

Modelo basado en árboles de decisión que permite identificar la importancia de las variables.

---

## 📊 Resultados

| Modelo              | Accuracy |
| ------------------- | -------- |
| Regresión Logística | 0.80     |
| Random Forest       | 0.78     |

La Regresión Logística mostró un mejor desempeño general en la predicción de cancelación.

---

## 🔎 Factores más importantes en el churn

Los factores más influyentes en la cancelación fueron:

* Tiempo de permanencia del cliente
* Tipo de contrato
* Cargos mensuales
* Tipo de servicio de internet
* Método de pago

---

## 💡 Estrategias de Retención

* Incentivar contratos de largo plazo
* Implementar programas de fidelización para clientes nuevos
* Optimizar precios en planes con cargos elevados
* Promover servicios adicionales como soporte técnico

---

## 🛠 Tecnologías Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 👨‍💻 Autor

Proyecto desarrollado como parte de un ejercicio de análisis de datos y machine learning.
