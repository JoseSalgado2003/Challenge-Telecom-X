# 📊 Telecom X - Análisis de Evasión de Clientes

## 📝 Descripción del Proyecto
[cite_start]Este proyecto fue desarrollado para Telecom X, una empresa que enfrenta una alta tasa de cancelaciones, con el objetivo de comprender los factores que llevan a la pérdida de clientes[cite: 1, 2]. [cite_start]A través de un análisis de datos exhaustivo utilizando Python, el objetivo fue extraer información valiosa que permita al equipo de Data Science avanzar en modelos predictivos y desarrollar estrategias de retención[cite: 3, 4].

## 🛠️ Tecnologías y Herramientas Utilizadas
* [cite_start]**Lenguaje:** Python [cite: 3]
* [cite_start]**Librerías:** Pandas, NumPy, Matplotlib, Seaborn [cite: 3]
* [cite_start]**Conceptos:** Consumo de APIs, ETL (Extracción, Transformación y Carga), EDA (Análisis Exploratorio de Datos) [cite: 6, 7]

## 🚀 Fases del Proyecto

1. [cite_start]**Extracción de Datos:** Se importaron los datos en formato JSON directamente desde la API de Telecom X[cite: 9, 11].
2. [cite_start]**Transformación y Limpieza (ETL):** * Conversión de los datos a un DataFrame de Pandas[cite: 12].
   * [cite_start]Tratamiento de valores nulos, duplicados y errores de formato[cite: 23].
   * [cite_start]Creación de la columna calculada `Cuentas_Diarias` a partir de la facturación mensual[cite: 27, 28].
   * [cite_start]Estandarización de variables categóricas a valores binarios (1 y 0) para facilitar el procesamiento matemático[cite: 30, 31].
3. [cite_start]**Análisis Exploratorio de Datos (EDA):** * Análisis descriptivo de las variables[cite: 34].
   * [cite_start]Visualización de la distribución de la evasión (`Churn`) frente a variables categóricas (como tipo de contrato) y numéricas (como total gastado) [cite: 35-40].
   * [cite_start]Análisis de correlación entre las distintas variables del dataset[cite: 48, 51].
4. [cite_start]**Conclusiones y Recomendaciones:** Generación de un informe final con hallazgos estratégicos para reducir la tasa de abandono[cite: 45, 46].

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
