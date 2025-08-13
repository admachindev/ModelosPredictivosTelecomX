📡 TelecomX2 – Predicción de Cancelación de Clientes
📋 Descripción del Proyecto
TelecomX2 es un modelo de análisis predictivo diseñado para identificar patrones y factores clave asociados a la cancelación de clientes (churn) en una compañía de telecomunicaciones.
El objetivo principal es implementar un flujo de trabajo de machine learning que permita anticipar cancelaciones y optimizar estrategias de retención, mejorando así la sostenibilidad del negocio.

🎯 Objetivos
Analizar variables demográficas, contractuales y de uso del servicio para determinar su influencia en la cancelación.

Implementar modelos de clasificación supervisada que permitan predecir la probabilidad de churn con alta precisión.

Evaluar y comparar el rendimiento de diferentes algoritmos, identificando el más eficiente para el contexto empresarial.

Generar métricas y visualizaciones para respaldar la toma de decisiones estratégicas.

📂 Estructura del Proyecto
bash
Copiar
Editar
Telecom_X2.ipynb       # Notebook principal con análisis, modelado y evaluación
TelecomX_Data_Limpio.csv  # Dataset preprocesado y listo para entrenamiento
README.md               # Documento de referencia técnica
🔍 Metodología
Recolección y preparación de datos

Limpieza y tratamiento de valores faltantes.

Codificación One-Hot Encoding para variables categóricas.

Normalización de variables numéricas para modelos basados en distancia.

Balanceo de clases

Implementación de SMOTE (Synthetic Minority Oversampling Technique) para equilibrar la proporción de clases y mejorar la capacidad predictiva del modelo.

Entrenamiento de modelos

Regresión Logística

Random Forest Classifier
Ambos con ajuste de hiperparámetros y manejo de desbalanceo mediante class_weight.

Evaluación de modelos

Métricas utilizadas: Accuracy, Precision, Recall, F1-Score, y AUC-ROC.

Análisis de la matriz de confusión y curvas ROC.

📊 Resultados Destacados
Regresión Logística: Modelo interpretable, buen rendimiento general y adecuado para identificar variables clave de cancelación.

Random Forest: Mayor capacidad de captura de relaciones no lineales y mejor desempeño en AUC-ROC, adecuado para optimización de retención.

(Se adjuntan métricas detalladas y visualizaciones en el notebook principal.)

🛠 Tecnologías Utilizadas
Lenguaje: Python 3.x

Bibliotecas principales:

pandas, numpy → Manipulación y análisis de datos.

scikit-learn → Modelado y evaluación de machine learning.

imblearn → Técnicas de balanceo de clases (SMOTE).

matplotlib, seaborn → Visualización de resultados.

📈 Aplicaciones Potenciales
Detección temprana de clientes con riesgo de cancelación.

Segmentación para campañas de retención personalizadas.

Priorización de recursos para atención proactiva.

👨‍💻 Autor
Adrián Manosalva
