Este proyecto analiza un dataset de cáncer de mama (disponible en sklearn.datasets). El objetivo fue clasificar tumores como benignos o malignos mediante diferentes algoritmos de Machine Learning y analizar los factores más importantes asociados con la predicción.
1) Objetivos
Realizar la limpieza y preprocesamiento del dataset.
Explorar relaciones entre variables mediante matrices de correlación.
Entrenar varios algoritmos de clasificación supervisada.
Evaluar y comparar su desempeño.
Interpretar los resultados con SHAP values para identificar las características más influyentes.
2)Metodología
EDA y limpieza de datos
Revisión de valores faltantes y normalización de variables.
Análisis descriptivo de características relacionadas al diagnóstico.
Matriz de correlación para estudiar dependencias entre variables.
División de datos: Separación en conjuntos de entrenamiento y prueba.
Modelado: Se entrenaron y evaluaron distintos modelos de clasificación:
-LogisticRegression
-RandomForestClassifier
-XGBoostClassifier
-SVM
-MLPClassifier (red neuronal)
-KNN

3)Evaluación y métricas
Accuracy, precision, recall y f1-score.
Matriz de confusión para análisis detallado de errores.

4)Interpretabilidad
Se aplicó SHAP (SHapley Additive exPlanations) para explicar el impacto de cada variable en la predicción.

5)Resultados:
Los modelos basados en Random Forest y XGBoost ofrecieron el mejor desempeño general.
La red neuronal (MLP) también mostró buenos resultados, aunque con mayor complejidad de entrenamiento.
SVM y KNN se comportaron bien en la clasificación, pero con menor interpretabilidad.
Con SHAP se evidenció que ciertas características del tumor son determinantes en la predicción del diagnóstico.
