# 🧠 Análisis de Readmisión a la UCI en Pacientes con Hemorragia Intracerebral

Este proyecto utiliza datos del conjunto MIMIC-IV para predecir la readmisión a la UCI en pacientes diagnosticados con hemorragia intracerebral. Se implementa un flujo de análisis en Python, empleando BigQuery como fuente de datos y técnicas de machine learning para modelado.

## 📁 Estructura del repositorio

- `analisis_readmision_uci_hemorragia_intracerebral.ipynb`: Notebook principal con todo el flujo de trabajo.
- `README.md`: Descripción general del proyecto.

## ⚙️ Requisitos

- Cuenta en Google Cloud con acceso al dataset MIMIC-IV en BigQuery.
- Python >= 3.7
- Paquetes: `pandas`, `scikit-learn`, `matplotlib`, `google-cloud-bigquery`

## 🚀 Instrucciones

1. Autenticarte en Google Cloud dentro del entorno donde se ejecute el notebook.
2. Actualizar `project_id` en la celda de configuración.
3. Ejecutar las celdas secuencialmente para obtener, procesar y analizar los datos.

## 📊 Resultado

Se entrena un modelo de Random Forest para estimar la probabilidad de readmisión y se evalúa con métricas como F1-score y AUC. Se visualiza la curva ROC del modelo.

## 🧰 Posibles mejoras

- Implementar interfaz visual con Streamlit o Gradio.
- Incorporar oversampling/undersampling para balanceo.
- Integración en Hugging Face Spaces.

## 🔐 Aviso

Este proyecto utiliza datos de pacientes anonimizados del dataset MIMIC-IV con fines académicos.
