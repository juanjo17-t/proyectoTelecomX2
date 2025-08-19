Uso del Proyecto

Abrir desafio3.ipynb en Google Colab.

Cargar los datos desde la API o desde el archivo JSON proporcionado.

Ejecutar las celdas en orden, siguiendo la secuencia:

Limpieza y transformación de datos.

Análisis exploratorio de datos (EDA).

Creación y entrenamiento de modelos de machine learning.

Evaluación de modelos y análisis de la importancia de variables.

Conclusiones y recomendaciones estratégicas.

Análisis Realizado

Limpieza y Tratamiento de Datos:

Se eliminaron columnas irrelevantes (como identificadores únicos).

Se transformaron variables categóricas en numéricas mediante One-Hot Encoding.

Se calcularon variables derivadas, como Cuentas_Diarias.

Análisis Exploratorio de Datos:

Se identificaron patrones en la evasión de clientes según género, tipo de contrato, método de pago y gasto mensual.

Se visualizaron distribuciones numéricas y categóricas con gráficos de barras, boxplots y scatterplots.

Creación de Modelos:

Regresión Logística (normalizada)

Random Forest (sin normalización)

Evaluación de Modelos:

Métricas utilizadas: Accuracy, Precision, Recall, F1-score y matriz de confusión.

Comparación de desempeño y análisis de posibles overfitting o underfitting.

Importancia de Variables:

Se identificaron las variables más relevantes para la predicción de cancelación, ayudando a orientar decisiones estratégicas.

Conclusiones y Recomendaciones

Las variables más influyentes en la cancelación de clientes incluyen: tiempo de contrato, tipo de contrato, método de pago, gasto mensual/total y servicios adicionales.

Se recomienda implementar estrategias de retención personalizadas para clientes con mayor riesgo de cancelación, mejorar servicios adicionales y monitorear clientes con alto gasto.

Los modelos permiten predecir clientes en riesgo y tomar acciones preventivas para reducir la tasa de Churn.
