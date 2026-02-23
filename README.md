# 📊 Telecom X - Análisis de Evasión de Clientes

## 📝 Descripción del Proyecto
Este proyecto fue desarrollado para Telecom X, una empresa que enfrenta una alta tasa de cancelaciones, con el objetivo de comprender los factores que llevan a la pérdida de clientes. A través de un análisis de datos exhaustivo utilizando Python, el objetivo fue extraer información valiosa que permita al equipo de Data Science avanzar en modelos predictivos y desarrollar estrategias de retención.

## 🛠️ Tecnologías y Herramientas Utilizadas
* **Lenguaje:** Python
* **Librerías:** Pandas, NumPy, Matplotlib, Seaborn
* **Conceptos:** Consumo de APIs, ETL (Extracción, Transformación y Carga), EDA (Análisis Exploratorio de Datos)

## 🚀 Fases del Proyecto

1. **Extracción de Datos:** Se importaron los datos en formato JSON directamente desde la API de Telecom X.
2. **Transformación y Limpieza (ETL):** * Conversión de los datos a un DataFrame de Pandas.
   * Tratamiento de valores nulos, duplicados y errores de formato.
   * Creación de la columna calculada `Cuentas_Diarias` a partir de la facturación mensual.
   * Estandarización de variables categóricas a valores binarios (1 y 0) para facilitar el procesamiento matemático.
3. **Análisis Exploratorio de Datos (EDA):** * Análisis descriptivo de las variables.
   * Visualización de la distribución de la evasión (`Churn`) frente a variables categóricas (como tipo de contrato) y numéricas (como total gastado).
   * Análisis de correlación entre las distintas variables del dataset.
4. **Conclusiones y Recomendaciones:** Generación de un informe final con hallazgos estratégicos para reducir la tasa de abandono.

## 💡 Principales Insights
* Los clientes con contratos de mes a mes presentan la mayor tasa de evasión.
* Existe una fuerte sensibilidad al precio; los cargos mensuales altos sin servicios de retención adicionales incrementan el riesgo de abandono.
* Los primeros meses de suscripción son el periodo más crítico para la fidelización.

## 📂 Cómo ejecutar este proyecto
1. Clona este repositorio: `git clone https://github.com/JoseSalgado2003/Challenge-Telecom-X.git`
2. Abre el archivo `TelecomX_LATAM.ipynb` en Jupyter Notebook o Google Colab.
3. Ejecuta las celdas secuencialmente para reproducir el análisis.

---
*Desarrollado por José Salgado - https://www.linkedin.com/in/jos%C3%A9-salgado/*
