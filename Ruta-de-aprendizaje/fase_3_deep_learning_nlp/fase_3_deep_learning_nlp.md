<div align="center">

# Fase 3: Deep Learning, PyTorch y NLP
### Redes Neuronales Profundas, Autograd, Embeddings, Mecanismo de Atención y Transformers

<br/>

<a href="../../README.md">
  <img src="https://img.shields.io/badge/-%E2%86%90%20README%20PRINCIPAL-0A0A0F?style=flat-square&logoColor=white&labelColor=1E293B"/>
</a>
<a href="../00_roadmap_general/00_roadmap_general.md">
  <img src="https://img.shields.io/badge/ROADMAP%20GENERAL-0A0A0F?style=flat-square&logoColor=white&labelColor=1E293B"/>
</a>
<a href="../fase_2_machine_learning/fase_2_machine_learning.md">
  <img src="https://img.shields.io/badge/%E2%86%90%20ANTERIOR%3A%20FASE%202-0A0A0F?style=flat-square&logoColor=white&labelColor=1E293B"/>
</a>
<a href="../fase_4_llms_y_langchain/fase_4_llms_y_langchain.md">
  <img src="https://img.shields.io/badge/SIGUIENTE%3A%20FASE%204%20%E2%86%92-0A0A0F?style=flat-square&logoColor=white&labelColor=1E293B"/>
</a>

<br/><br/>

<img src="https://img.shields.io/badge/DURACI%C3%93N-12%20a%2014%20SEMANAS-0A0A0F?style=flat-square&labelColor=1E293B"/>
<img src="https://img.shields.io/badge/CARGA%20ESTIMADA-~140%20HORAS-0A0A0F?style=flat-square&labelColor=1E293B"/>
<img src="https://img.shields.io/badge/ESTADO-PENDIENTE-2D3748?style=flat-square"/>

<br/><br/>

<p align="center">
<strong>Objetivo:</strong> Comprender la fundamentación teórica de redes neuronales artificiales, dominar PyTorch como framework central para desarrollo en GPU, y profundizar en la arquitectura Transformer y el ecosistema Hugging Face como base de los modelos de lenguaje modernos.
</p>

</div>

---

<img src="https://img.shields.io/badge/-%3E_.%2F01__skills__stack-0A0A0F?style=for-the-badge&logo=windows-terminal&logoColor=38BDF8"/> &nbsp; <i>// skills y herramientas de la fase</i>

<div align="center">

<img src="https://skillicons.dev/icons?i=python,pytorch,linux,git,github,vscode&theme=dark" />

<br/><br/>

<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/CUDA-GPU%20Acceleration-76B900?style=flat-square&logo=nvidia&logoColor=white"/>
<img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/Transformers-Models%20%26%20Pipelines-FFD21E?style=flat-square"/>
<img src="https://img.shields.io/badge/Datasets-Tokenization-1E293B?style=flat-square"/>
<img src="https://img.shields.io/badge/NLP-Natural%20Language-2D3748?style=flat-square"/>
<img src="https://img.shields.io/badge/Attention_Mechanisms-Transformers-4A90E2?style=flat-square"/>
<img src="https://img.shields.io/badge/Torchvision-Vision%20%26%20Tensors-EE4C2C?style=flat-square"/>

</div>

---

<img src="https://img.shields.io/badge/-%3E_.%2F02__modules__breakdown-0A0A0F?style=for-the-badge&logo=windows-terminal&logoColor=38BDF8"/> &nbsp; <i>// desglose de módulos y tareas</i>

### Módulo 3.1: Redes Neuronales Artificiales (ANN / MLP) `[30 horas]`
* [ ] **3.1.1** El Perceptrón simple y multicapa: funciones de activación no lineales (ReLU, LeakyReLU, Sigmoid, Tanh, Softmax). `[6 hrs]`
* [ ] **3.1.2** Propagación hacia adelante (Forward Propagation) y funciones de pérdida: BCE (Binary Cross-Entropy), Cross-Entropy multinomial y MSE. `[6 hrs]`
* [ ] **3.1.3** Retropropagación (Backpropagation): cálculo explícito del gradiente mediante regla de la cadena multivariable. `[10 hrs]`
* [ ] **3.1.4** Algoritmos de optimización: Descenso de gradiente estocástico (SGD), Momentum, RMSprop, Adam y AdamW con weight decay. `[8 hrs]`

### Módulo 3.2: Framework de Deep Learning con PyTorch `[35 horas]`
* [ ] **3.2.1** Tensores en PyTorch: manipulación dimensional, operaciones matemáticas, tipos de datos y transferencia a aceleradores (`.to('cuda')`). `[6 hrs]`
* [ ] **3.2.2** Motor Autograd: diferenciación automática, grafos computacionales dinámicos y llamada a `loss.backward()`. `[6 hrs]`
* [ ] **3.2.3** Modularización de arquitecturas: subclases de `torch.nn.Module`, constructores, capas densas y flujos de datos. `[8 hrs]`
* [ ] **3.2.4** Ingesta de datos eficiente: diseño de clases personalizadas `Dataset` y `DataLoader` con batching y shuffling. `[7 hrs]`
* [ ] **3.2.5** Ciclo de entrenamiento canónico (Training Loop): `optimizer.zero_grad()`, forward pass, cálculo de pérdida, backward pass y `optimizer.step()`. `[5 hrs]`
* [ ] **3.2.6** Regularización profunda: técnicas de Dropout, Batch Normalization, Layer Normalization y Early Stopping. `[3 hrs]`

### Módulo 3.3: Procesamiento de Lenguaje Natural (NLP) y Embeddings `[25 horas]`
* [ ] **3.3.1** Preprocesamiento textual clásico: segmentación, normalización, stopword removal, lematización y representación ponderada TF-IDF. `[6 hrs]`
* [ ] **3.3.2** Representaciones vectoriales continuas (Word Embeddings): formulación de Word2Vec (Skip-gram, CBOW), GloVe y FastText. `[7 hrs]`
* [ ] **3.3.3** Arquitecturas recurrentes: Redes Neuronales Recurrentes (RNN), celdas LSTM y GRU, analizando la mitigación del desvanecimiento del gradiente. `[12 hrs]`

### Módulo 3.4: La Arquitectura Transformer y Mecanismo de Atención `[30 horas]`
* [ ] **3.4.1** Mecanismo de Atención: formulación matemática de Self-Attention y Scaled Dot-Product Attention: $\text{Softmax}\left(\frac{QK^T}{\sqrt{d_k}}\right)V$. `[10 hrs]`
* [ ] **3.4.2** Multi-Head Attention, proyecciones lineales ortogonales y codificación posicional (Sinusoidal y Rotary Position Embedding). `[8 hrs]`
* [ ] **3.4.3** Topologías Encoder-Decoder: comparación de modelos Encoder-only (BERT), Decoder-only (GPT) y Encoder-Decoder (T5). `[12 hrs]`

### Módulo 3.5: Ecosistema Hugging Face `[20 horas]`
* [ ] **3.5.1** Biblioteca `transformers`: arquitectura de `AutoTokenizer`, tokenizadores subpalabra (BPE, WordPiece) y carga de modelos `AutoModelForSequenceClassification`. `[8 hrs]`
* [ ] **3.5.2** Gestión de datos con `datasets` y estandarización de métricas con `evaluate`. `[5 hrs]`
* [ ] **3.5.3** Fine-tuning supervisado: uso de la API `Trainer` y entrenamiento sobre modelos compactos preentrenados (DistilBERT / RoBERTa). `[7 hrs]`

---

<img src="https://img.shields.io/badge/-%3E_.%2F03__official__docs-0A0A0F?style=for-the-badge&logo=windows-terminal&logoColor=38BDF8"/> &nbsp; <i>// documentación oficial de referencia</i>

* **PyTorch Documentation:** Tensores, Autograd, capas `nn`, optimizadores y guías CUDA.
* **Hugging Face Transformers Docs:** Guías de tokenización, model hub, Trainer API y pipelines de inferencia.
* **Paper Fundacional:** *"Attention Is All You Need"* (Vaswani et al., 2017).

---

<img src="https://img.shields.io/badge/-%3E_.%2F04__recommended__courses-0A0A0F?style=for-the-badge&logo=windows-terminal&logoColor=38BDF8"/> &nbsp; <i>// cursos y recursos de estudio</i>

* **PyTorch y Redes Neuronales:**
  * *Andrej Karpathy — Neural Networks: Zero to Hero* (YouTube Series)
  * *Daniel Bourke — PyTorch for Deep Learning Bootcamp* (YouTube / GitHub)
* **Visualización de Transformers:**
  * *Jay Alammar — The Illustrated Transformer* (Publicación técnica)
  * *3Blue1Brown — Visualizing Transformers & Attention* (YouTube)

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
<td><strong>Clasificador MLP en PyTorch</strong></td>
<td>Implementación desde cero de una red neuronal multicapa sobre el dataset MNIST utilizando subclases de <code>nn.Module</code> y <code>DataLoader</code> con métricas de pérdida por época.</td>
<td><code>notebook</code></td>
</tr>
<tr>
<td><strong>Implementación del Scaled Dot-Product Attention</strong></td>
<td>Módulo en PyTorch puro que calcula las matrices Q, K, V, aplica escalado por $\sqrt{d_k}$, genera el heatmap de atención y procesa secuencias de texto.</td>
<td><code>script</code></td>
</tr>
<tr>
<td><strong>Proyecto Integrador: Fine-Tuning de Clasificador NLP</strong></td>
<td>Ajuste fino de <code>distilbert-base-uncased</code> sobre un corpus de análisis de sentimientos con Hugging Face <code>Trainer</code>, reportando F1-Score y matriz de confusión.</td>
<td><code>pipeline pytorch</code></td>
</tr>
</tbody>
</table>

---

<img src="https://img.shields.io/badge/-%3E_.%2F06__references-0A0A0F?style=for-the-badge&logo=windows-terminal&logoColor=38BDF8"/> &nbsp; <i>// referencias consultadas</i>

* Basado en las recomendaciones curriculares de PyTorch y arquitecturas Transformer de **AI Weekly 2026 Roadmap** y **Suchibrata Blog**.
