<div align="center">

# Fase 2: Machine Learning Tradicional y Scikit-Learn
### Modelos Supervisados, No Supervisados, Pipelines y Optimización de Hiperparámetros

<br/>

<a href="../../../README.md">
  <img src="https://img.shields.io/badge/-%E2%86%90%20README%20PRINCIPAL-0A0A0F?style=flat-square&logoColor=white&labelColor=1E293B"/>
</a>
<a href="../../00_roadmap_general/Ania/00_roadmap_general.md">
  <img src="https://img.shields.io/badge/ROADMAP%20GENERAL-0A0A0F?style=flat-square&logoColor=white&labelColor=1E293B"/>
</a>
<a href="../../fase_1_fundamentos/Ania/fase_1_fundamentos.md">
  <img src="https://img.shields.io/badge/%E2%86%90%20ANTERIOR%3A%20FASE%201-0A0A0F?style=flat-square&logoColor=white&labelColor=1E293B"/>
</a>
<a href="../../fase_3_deep_learning_nlp/Ania/fase_3_deep_learning_nlp.md">
  <img src="https://img.shields.io/badge/SIGUIENTE%3A%20FASE%203%20%E2%86%92-0A0A0F?style=flat-square&logoColor=white&labelColor=1E293B"/>
</a>

<br/><br/>

<img src="https://img.shields.io/badge/DURACI%C3%93N-10%20a%2012%20SEMANAS-0A0A0F?style=flat-square&labelColor=1E293B"/>
<img src="https://img.shields.io/badge/CARGA%20ESTIMADA-~120%20HORAS-0A0A0F?style=flat-square&labelColor=1E293B"/>
<img src="https://img.shields.io/badge/ESTADO-PENDIENTE-2D3748?style=flat-square"/>

<br/><br/>

<p align="center">
<strong>Objetivo:</strong> Dominar los algoritmos fundamentales de aprendizaje supervisado y no supervisado, el diseño de pipelines robustos de preprocesamiento, la selección de métricas de evaluación rigurosas y la optimización bayesiana de hiperparámetros.
</p>

</div>

---

<img src="https://img.shields.io/badge/-%3E_.%2F01__skills__stack-0A0A0F?style=for-the-badge&logo=windows-terminal&logoColor=38BDF8"/> &nbsp; <i>// skills y herramientas de la fase</i>

<div align="center">

<img src="https://skillicons.dev/icons?i=python,scikitlearn,linux,git,github,vscode&theme=dark" />

<br/><br/>

<img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white"/>
<img src="https://img.shields.io/badge/XGBoost-111111?style=flat-square"/>
<img src="https://img.shields.io/badge/LightGBM-2E7D32?style=flat-square"/>
<img src="https://img.shields.io/badge/CatBoost-FFCC00?style=flat-square&logoColor=black"/>
<img src="https://img.shields.io/badge/Optuna-Hyperopt-4A90E2?style=flat-square"/>
<img src="https://img.shields.io/badge/Imbalanced--Learn-SMOTE-E65100?style=flat-square"/>
<img src="https://img.shields.io/badge/Pandas-Feature%20Eng-150458?style=flat-square&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-Vectorized%20Ops-013243?style=flat-square&logo=numpy&logoColor=white"/>

</div>

---

<img src="https://img.shields.io/badge/-%3E_.%2F02__modules__breakdown-0A0A0F?style=for-the-badge&logo=windows-terminal&logoColor=38BDF8"/> &nbsp; <i>// desglose de módulos y tareas</i>

### Módulo 2.1: Preprocesamiento e Ingeniería de Características `[25 horas]`
* [ ] **2.1.1** Imputación de datos faltantes: estrategias univariables (`SimpleImputer`) e imputación multivariable basada en vecinos (`KNNImputer`). `[5 hrs]`
* [ ] **2.1.2** Codificación de variables cualitativas: One-Hot Encoding, Ordinal Encoding y Target Encoding evitando data leakage. `[6 hrs]`
* [ ] **2.1.3** Escalado y normalización: análisis comparativo entre `StandardScaler`, `MinMaxScaler` y `RobustScaler` ante outliers. `[5 hrs]`
* [ ] **2.1.4** Tratamiento de clases desbalanceadas: sobremuestreo sintético (SMOTE), submuestreo y pesos de clase balanceados (`class_weight`). `[5 hrs]`
* [ ] **2.1.5** Construcción de flujos productivos con Scikit-Learn: encapsulamiento con `Pipeline` y `ColumnTransformer`. `[4 hrs]`

### Módulo 2.2: Aprendizaje Supervisado `[35 horas]`
* [ ] **2.2.1** Modelos lineales: Regresión Lineal y Regresión Logística, funciones de costo y análisis de residuales. `[8 hrs]`
* [ ] **2.2.2** Técnicas de regularización: penalización L1 (Lasso), penalización L2 (Ridge) y combinación convexa (ElasticNet). `[5 hrs]`
* [ ] **2.2.3** Árboles de decisión (CART): criterios de partición (entropía, impureza de Gini), sobreajuste y poda (pruning). `[6 hrs]`
* [ ] **2.2.4** Ensambles por Bagging: Random Forest, importancia de variables y reducción de varianza. `[6 hrs]`
* [ ] **2.2.5** Ensambles por Boosting: formulación teórica de Gradient Boosting, implementación con XGBoost, LightGBM y CatBoost. `[10 hrs]`

### Módulo 2.3: Aprendizaje No Supervisado `[25 horas]`
* [ ] **2.3.1** Algoritmos de particionamiento: K-Means, K-Medoids, método del codo y cálculo de coeficientes de Silhouette. `[8 hrs]`
* [ ] **2.3.2** Algoritmos basados en densidad y jerarquía: Agglomerative Clustering (dendrogramas) y DBSCAN para detección de ruido. `[7 hrs]`
* [ ] **2.3.3** Reducción de dimensionalidad: Análisis de Componentes Principales (PCA), varianza explicada acumulada y visualización latente. `[10 hrs]`

### Módulo 2.4: Evaluación, Métricas y Optimización `[20 horas]`
* [ ] **2.4.1** Evaluación en clasificación: matriz de confusión, métricas de precisión, recall, F1-score ponderado y análisis ROC-AUC. `[6 hrs]`
* [ ] **2.4.2** Evaluación en regresión: error cuadrático medio (MSE, RMSE), error absoluto medio (MAE) y coeficiente de determinación ajustado ($R^2$). `[4 hrs]`
* [ ] **2.4.3** Estrategias de validación cruzada: K-Fold, Stratified K-Fold y TimeSeriesSplit para series temporales. `[5 hrs]`
* [ ] **2.4.4** Búsqueda sistemática de hiperparámetros: Grid Search, Random Search y optimización bayesiana con Optuna. `[5 hrs]`

---

<img src="https://img.shields.io/badge/-%3E_.%2F03__official__docs-0A0A0F?style=for-the-badge&logo=windows-terminal&logoColor=38BDF8"/> &nbsp; <i>// documentación oficial de referencia</i>

* **Scikit-Learn User Guide:** Manual integral de algoritmos supervisados, no supervisados, preprocesamiento y validación.
* **XGBoost Documentation:** Parámetros de árboles de decisión con regularización y aceleración por GPU.
* **LightGBM Documentation:** Guía de optimización basada en histogramas para datasets masivos.
* **Optuna Documentation:** Framework moderno para optimización de hiperparámetros y poda de pruebas.

---

<img src="https://img.shields.io/badge/-%3E_.%2F04__recommended__courses-0A0A0F?style=for-the-badge&logo=windows-terminal&logoColor=38BDF8"/> &nbsp; <i>// cursos y recursos bibliográficos</i>

* **Cursos Fundamentales:**
  * *Machine Learning Specialization* por Andrew Ng (Coursera / DeepLearning.AI)
  * *StatQuest con Josh Starmer — Machine Learning Series* (YouTube)
* **Texto de Referencia:**
  * *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow* (Aurélien Géron) — Capítulos 1 al 9.

---

<img src="https://img.shields.io/badge/-%3E_.%2F05__practical__projects-0A0A0F?style=for-the-badge&logo=windows-terminal&logoColor=38BDF8"/> &nbsp; <i>// proyectos prácticos aplicados</i>

<table>
<thead>
<tr>
<th width="35%">Proyecto / Ejercicio</th>
<th width="50%">Descripción Técnica</th>
<th width="15%">Entregable</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>Predicción de Precios de Viviendas</strong></td>
<td>Pipeline en Scikit-Learn con imputación, codificación de variables nominales/ordinales, escalado robusto y comparación de Ridge vs. XGBoost.</td>
<td><code>notebook</code></td>
</tr>
<tr>
<td><strong>Clasificación de Churn Desbalanceado</strong></td>
<td>Modelo de retención de clientes en telecomunicaciones. Preprocesamiento con SMOTE, ensamble con Random Forest y optimización según métrica PR-AUC.</td>
<td><code>script</code></td>
</tr>
<tr>
<td><strong>Proyecto Integrador: Segmentación y Propensión</strong></td>
<td>Sistema completo de clustering de clientes con PCA + K-Means acoplado a un clasificador XGBoost con optimización bayesiana en Optuna para predecir compras.</td>
<td><code>pipeline python</code></td>
</tr>
</tbody>
</table>

---

<img src="https://img.shields.io/badge/-%3E_.%2F06__references-0A0A0F?style=for-the-badge&logo=windows-terminal&logoColor=38BDF8"/> &nbsp; <i>// referencias consultadas</i>

* Alineado con las fases de algoritmos tradicionales y evaluación predictiva de **Coursera ML Roadmap** y **roadmap.sh Machine Learning**.
