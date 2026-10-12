# 🟩 Fase 2: Machine Learning Tradicional y Scikit-Learn

> **Duración estimada:** 10 a 12 semanas (~120 horas lectivas y prácticas)  
> **Objetivo:** Dominar los algoritmos de aprendizaje supervisado y no supervisado, entender el flujo completo de modelado de datos y saber evaluar y optimizar un modelo.

---

## ⏱️ Distribución de Tareas e Horas Estimadas

### 🔹 Módulo 2.1: Preprocesamiento e Ingeniería de Características *(25 horas)*
- [ ] **2.1.1** Imputación de datos faltantes (`SimpleImputer`, `KNNImputer`) `[5 hrs]`
- [ ] **2.1.2** Codificación de variables categóricas (One-Hot, Ordinal, Target Encoding) `[6 hrs]`
- [ ] **2.1.3** Escalado de características (`StandardScaler`, `MinMaxScaler`, `RobustScaler`) `[5 hrs]`
- [ ] **2.1.4** Manejo de clases desbalanceadas (SMOTE, Undersampling, Class Weights) `[5 hrs]`
- [ ] **2.1.5** Pipelines de Scikit-Learn (`Pipeline` y `ColumnTransformer`) `[4 hrs]`

### 🔹 Módulo 2.2: Aprendizaje Supervisado *(35 horas)*
- [ ] **2.2.1** Regresión Lineal y Regresión Logística (Cost Function, Gradiente) `[8 hrs]`
- [ ] **2.2.2** Regularización: Lasso (L1), Ridge (L2) y ElasticNet `[5 hrs]`
- [ ] **2.2.3** Árboles de Decisión (CART, Entropía, Gini, Pruning) `[6 hrs]`
- [ ] **2.2.4** Métodos Ensamble (Bagging): Random Forest `[6 hrs]`
- [ ] **2.2.5** Métodos Ensamble (Boosting): XGBoost, LightGBM, CatBoost `[10 hrs]`

### 🔹 Módulo 2.3: Aprendizaje No Supervisado *(25 horas)*
- [ ] **2.3.1** Clustering: K-Means, K-Medoids y Método del Codo / Silhouette Score `[8 hrs]`
- [ ] **2.3.2** Clustering Jerárquico y DBSCAN (Detección de ruido) `[7 hrs]`
- [ ] **2.3.3** Reducción de Dimensionalidad: Análisis de Componentes Principales (PCA) `[10 hrs]`

### 🔹 Módulo 2.4: Evaluación, Métricas y Optimización *(20 horas)*
- [ ] **2.4.1** Matriz de Confusión, Accuracy, Precision, Recall, F1-Score y Curva ROC-AUC `[6 hrs]`
- [ ] **2.4.2** Métricas de Regresión: MSE, RMSE, MAE, R² Ajustado `[4 hrs]`
- [ ] **2.4.3** Validación Cruzada (K-Fold, Stratified K-Fold, TimeSeriesSplit) `[5 hrs]`
- [ ] **2.4.4** Búsqueda de Hiperparámetros (`GridSearchCV`, `RandomizedSearchCV`, `Optuna`) `[5 hrs]`

---

## 📖 Documentación Oficial Recomendada

- **Scikit-Learn User Guide**: Guías completas de algoritmos supervisados, no supervisados y pipelines.
- **XGBoost & LightGBM Documentation**: Guías avanzadas para modelos de gradiente boosting.
- **Optuna Documentation**: Framework moderno para optimización de hiperparámetros.

---

## 🎥 Videos y Cursos Recomendados

- **Cursos Principales:**
  - *Machine Learning Specialization por Andrew Ng (Coursera / DeepLearning.AI)*
  - *StatQuest con Josh Starmer — Machine Learning Series (YouTube)*
- **Libro de Texto Referente:**
  - *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow (Aurélien Géron)* — Capítulos 1 al 9.

---

## 🛠️ Ejercicios y Proyectos Prácticos

1. **Ejercicio 1: Predicción de Precios de Viviendas (Regresión):**  
   Implementa un pipeline en Scikit-Learn con preprocesamiento completo, imputación, escalado y compara Regresión Ridge vs. XGBoost.
2. **Ejercicio 2: Clasificación de Churn de Clientes (Clasificación Desbalanceada):**  
   Utiliza un dataset de telecomunicaciones con clases desbalanceadas. Aplica SMOTE, ajusta un Random Forest y evalúa con F1-Score y ROC-AUC.
3. **Proyecto Integrador de Fase 2:**  
   **Sistema de Segmentación de Clientes y Predicción de Compras:**  
   Aplica PCA + K-Means para agrupar usuarios por comportamiento y entrena un modelo XGBoost optimizado con Optuna para predecir si realizarán una compra.

---

## 🔗 Referencias a Fuentes Consultadas
- Estructurado según las fases de aprendizaje supervisado y no supervisado de **Coursera ML Roadmap** y **roadmap.sh Machine Learning**.
