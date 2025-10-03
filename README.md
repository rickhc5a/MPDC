# TB1 - Comprensión de Datos: Predicción de Churn en Telecomunicaciones

**Autor:** Gianpiero Rick Huaricapcha  
**Tema:** Predicción de abandono de clientes (Customer Churn) en una empresa de telecomunicaciones  
**Dataset:** Telco Customer Churn (IBM)  
**Fuente:** [Kaggle – Denis Expósito (2024)](https://www.kaggle.com/datasets/denisexpsito/telco-customer-churn-ibm)

---

## 🎯 Problema a resolver
El objetivo es identificar qué clientes tienen mayor probabilidad de cancelar su servicio (churn) en una empresa de telecomunicaciones, a partir de datos demográficos, de contrato y de uso de servicios.  
Esto permitirá diseñar estrategias de retención y fidelización de clientes.

---

## 📈 Objetivos del proyecto
- **Objetivo principal:**  
  Desarrollar un modelo de clasificación supervisada que prediga si un cliente dejará la empresa (Churn: Sí / No).
- **Objetivos específicos:**
  - Limpiar y preprocesar el dataset (valores faltantes, codificación, estandarización).
  - Realizar un análisis exploratorio de datos (EDA) para entender relaciones y patrones.
  - Entrenar y comparar modelos de Machine Learning (Regresión Logística, Random Forest, XGBoost).
  - Evaluar los modelos usando métricas como Accuracy, Recall, F1-score y AUC-ROC.
  - Interpretar los factores que influyen en el churn para apoyar decisiones de negocio.

---

## 📚 Dataset
| Característica | Descripción |
|----------------|--------------|
| **Nombre** | Telco Customer Churn |
| **Filas** | 7,043 |
| **Columnas** | 23 |
| **Variable objetivo** | `Churn` (Yes/No) |
| **Principales variables** | `tenure`, `MonthlyCharges`, `TotalCharges`, `Contract`, `PaymentMethod`, `InternetService`, `gender`, `SeniorCitizen`, `Partner`, `Dependents` |
| **Tipo de problema** | Clasificación binaria supervisada |

---

## 📂 Estructura del repositorio
