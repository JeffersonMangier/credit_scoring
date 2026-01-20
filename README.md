# 🏦 Credit Risk Scoring: Predicción de Impago con Machine Learning

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)

## 📄 Descripción del Proyecto
Este proyecto desarrolla un modelo de **Machine Learning (Random Forest)** para evaluar el riesgo crediticio de clientes bancarios. Utilizando el dataset *Statlog (German Credit Data)*, el objetivo es predecir la probabilidad de incumplimiento de pago (default) para optimizar la toma de decisiones en la concesión de préstamos.

El modelo no solo predice, sino que explica sus decisiones utilizando **SHAP Values**, permitiendo a los analistas de riesgo entender *por qué* un cliente es clasificado como riesgoso.

## 🎯 Objetivos
* **Predecir** la solvencia crediticia (Bueno/Malo) con alta precisión.
* **Identificar** los factores clave que aumentan el riesgo financiero.
* **Proveer explicabilidad** al modelo para cumplir con normativas de transparencia bancaria.

## 📊 Resultados Clave
El modelo alcanzó un **ROC-AUC Score de 0.74**, superando el umbral base y demostrando una capacidad sólida de discriminación.

### Insights de Negocio (Descubrimientos):
Gracias al análisis con SHAP, se detectaron los siguientes patrones de riesgo:
1.  **Duración del Crédito:** A mayor plazo (meses), mayor es la probabilidad de impago.
2.  **Monto del Crédito:** Solicitudes de montos excesivamente altos están correlacionadas con un alto riesgo.
3.  **Historial de Cuenta:** Curiosamente, clientes sin historial negativo previo en cuentas de cheques mostraron menor riesgo.

## 🛠️ Tecnologías Utilizadas
* **Python**: Lenguaje principal.
* **Pandas & NumPy**: Manipulación y limpieza de datos.
* **Scikit-learn**: Entrenamiento del modelo (Random Forest) y métricas.
* **SHAP**: Interpretabilidad del modelo (XAI).
* **Matplotlib & Seaborn**: Visualización de datos.

## 🚀 Instalación y Uso

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/JeffersonMangier/credit_scoring.git](https://github.com/JeffersonMangier/credit_scoring.git)
