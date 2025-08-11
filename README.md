# challenge3-data-science-LATAM
# 📊 Telecom X – Parte 2: Predicción de Cancelación (Churn)

## 🎯 Misión
Desarrollar modelos predictivos capaces de prever qué clientes tienen mayor probabilidad de cancelar sus servicios.  
El objetivo es que la empresa pueda **anticiparse al problema del churn**, identificando clientes en riesgo y diseñando estrategias de retención basadas en datos.

---

## 🧠 Objetivos del Desafío
1. **Preparar los datos para el modelado**
   - Tratamiento de datos faltantes.
   - Codificación de variables categóricas (One-Hot Encoding).
   - Normalización y estandarización de variables numéricas.

2. **Realizar análisis exploratorio**
   - Análisis de correlación.
   - Selección de variables más relevantes.
   - Visualización de patrones de churn.

3. **Entrenar modelos de clasificación**
   - Al menos dos algoritmos distintos (ej. Árbol de decisión, Random Forest, XGBoost, Regresión logística).
   - Ajuste de hiperparámetros.

4. **Evaluar el rendimiento**
   - Matriz de confusión.
   - Accuracy, Precision, Recall, F1-Score.
   - ROC-AUC y curvas de precisión-recall.

5. **Interpretar resultados**
   - Importancia de las variables.
   - Factores clave que explican la cancelación.

6. **Conclusión estratégica**
   - Identificación de variables críticas para el churn.
   - Propuestas de retención basadas en los hallazgos.

---

## 📂 Estructura del Proyecto

|-README.md
|-TelecomX_LATAM_Parte_2.ipynb
|-TelecomX_diccionario.md
|-datos_tratados.csv

## ⚙️ Tecnologías y Librerías
- **Python 3.9+**
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost / LightGBM
- Jupyter Notebook

---

## 🚀 Ejecución del Proyecto

1. **Clonar el repositorio**
```bash
git clone https://github.com/usuario/telecom-x-churn.git
cd telecom-x-churn

2. **Instalar dependencias**
```bash
pip install -r requirements.txt

3. **Ejecutar analisis y modelos**
```bash
jupyter notebook notebooks/01_preprocesamiento.ipynb
jupyter notebook notebooks/02_modelado.ipynb

---

📈 Resultados esperados
Dataset procesado y listo para modelado.

Comparativa de rendimiento entre modelos.

Visualización de importancia de variables.

Informe con conclusiones estratégicas.

---

📝 Conclusión estratégica
Tras el modelado, se espera identificar los factores más influyentes en la cancelación, como:

Tipo de contrato (mensual vs. anual).

Cargos mensuales.

Tipo de servicio de internet.

Tenure (tiempo como cliente).

Servicios adicionales (seguridad en línea).

Estos hallazgos permitirán diseñar campañas focalizadas para retener a clientes en riesgo y reducir la tasa de churn.

---

👨‍💻 Autor
Proyecto desarrollado por Carlos Sánchez como parte del reto Telecom X – Predicción de Churn.
