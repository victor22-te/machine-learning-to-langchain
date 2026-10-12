# 🟧 Fase 3: Deep Learning, PyTorch y Procesamiento de Lenguaje Natural (NLP)

> **Duración estimada:** 12 a 14 semanas (~140 horas lectivas y prácticas)  
> **Objetivo:** Comprender la teoría de redes neuronales profundas, dominar PyTorch como framework principal, y aprender la arquitectura Transformer que sustenta los LLMs actuales.

---

## ⏱️ Distribución de Tareas e Horas Estimadas

### 🔹 Módulo 3.1: Redes Neuronales Artificiales (ANN / MLP) *(30 horas)*
- [ ] **3.1.1** El Perceptrón y Funciones de Activación (ReLU, Sigmoid, Tanh, Softmax) `[6 hrs]`
- [ ] **3.1.2** Forward Propagation, Loss Functions (BCE, Cross-Entropy, MSE) `[6 hrs]`
- [ ] **3.1.3** Backpropagation y Regla de la Cadena paso a paso `[10 hrs]`
- [ ] **3.1.4** Algoritmos de Optimización (SGD, Momentum, RMSprop, Adam, AdamW) `[8 hrs]`

### 🔹 Módulo 3.2: Framework de Deep Learning con PyTorch *(35 horas)*
- [ ] **3.2.1** Tensores en PyTorch, GPU CUDA Acceleration (`.to('cuda')`) `[6 hrs]`
- [ ] **3.2.2** Autograd (Diferenciación automática con `loss.backward()`) `[6 hrs]`
- [ ] **3.2.3** Estructura de un Modelo: `nn.Module`, `Dataset` y `DataLoader` `[10 hrs]`
- [ ] **3.2.4** Training Loop Estándar (Zero Grad, Forward, Loss, Backward, Step) `[8 hrs]`
- [ ] **3.2.5** Técnicas de Regularización: Dropout, Batch Normalization, Early Stopping `[5 hrs]`

### 🔹 Módulo 3.3: Procesamiento de Lenguaje Natural (NLP) y Embeddings *(25 horas)*
- [ ] **3.3.1** Preprocesamiento de texto tradicional (Tokenización, Stopwords, Lemmatización, TF-IDF) `[6 hrs]`
- [ ] **3.3.2** Word Embeddings (Word2Vec, GloVe, FastText) `[7 hrs]`
- [ ] **3.3.3** Redes Recurrentes (RNN, LSTM, GRU) y el problema de vanishing gradient `[12 hrs]`

### 🔹 Módulo 3.4: La Arquitectura Transformer y Mecanismo de Atención *(30 horas)*
- [ ] **3.4.1** Mecanismo de Atención (Self-Attention, Scaled Dot-Product Attention) `[10 hrs]`
- [ ] **3.4.2** Multi-Head Attention y Positional Encoding `[8 hrs]`
- [ ] **3.4.3** Encoder-Decoder Architecture (Modelos tipo BERT vs. Modelos tipo GPT) `[12 hrs]`

### 🔹 Módulo 3.5: Ecosistema Hugging Face *(20 horas)*
- [ ] **3.5.1** Biblioteca `transformers`: Tokenizers (`AutoTokenizer`) y Modelos (`AutoModel`) `[8 hrs]`
- [ ] **3.5.2** Carga de Datasets con `datasets` y Evaluación con `evaluate` `[5 hrs]`
- [ ] **3.5.3** Fine-tuning básico de un modelo Preentrenado (DistilBERT/RoBERTa) `[7 hrs]`

---

## 📖 Documentación Oficial Recomendada

- **PyTorch Documentation**: Documentación de tensores, Autograd y `nn.Module`.
- **Hugging Face Transformers Documentation**: Guías para modelos preentrenados, tokenizadores y fine-tuning.
- **Paper Original: "Attention Is All You Need" (Vaswani et al.)**: Lectura clave para entender el mecanismo de atención.

---

## 🎥 Videos y Cursos Recomendados

- **PyTorch & Deep Learning desde Cero:**
  - *Andrej Karpathy — "Neural Networks: Zero to Hero" (YouTube Playlist Imprescindible)*
  - *Daniel Bourke — PyTorch for Deep Learning in 100 Hours (YouTube)*
- **Explicación Visual de Transformers:**
  - *Jay Alammar — "The Illustrated Transformer" (Blog Post / Visual Guide)*
  - *3Blue1Brown — How Transformers Work & Neural Networks (YouTube)*

---

## 🛠️ Ejercicios y Proyectos Prácticos

1. **Ejercicio 1: Red Neuronal MLP desde Cero en PyTorch:**  
   Escribe un clasificador para el dataset MNIST usando PyTorch con custom `Dataset` y `DataLoader`.
2. **Ejercicio 2: Visualizador del Mecanismo de Atención:**  
   Implementa en PyTorch la ecuación de $Softmax(\frac{QK^T}{\sqrt{d_k}})V$ y grafica la matriz de atención para una oración.
3. **Proyecto Integrador de Fase 3:**  
   **Clasificador de Sentimientos Fine-Tuned con Hugging Face:**  
   Toma el modelo `distilbert-base-uncased`, realiza fine-tuning sobre un dataset de reseñas de películas (IMDB) y evalúa el F1-Score en test.

---

## 🔗 Referencias a Fuentes Consultadas
- Siguiendo la ruta de PyTorch y Transformers destacada en **AI Weekly 2026 Guide** y **Suchibrata Blog**.
