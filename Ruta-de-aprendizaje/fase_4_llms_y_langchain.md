# 🟪 Fase 4: Modelos de Lenguaje (LLMs), RAG, LangChain y LangGraph

> **Duración estimada:** 10 a 12 semanas (~120 horas lectivas y prácticas)  
> **Objetivo:** Dominar el desarrollo de aplicaciones modernas impulsadas por IA Generativa, arquitectura RAG (Retrieval-Augmented Generation), bases de datos vectoriales y agentes autónomos con LangChain y LangGraph.

---

## ⏱️ Distribución de Tareas e Horas Estimadas

### 🔹 Módulo 4.1: Fundamentos de LLMs y Prompt Engineering *(15 horas)*
- [ ] **4.1.1** Parámetros de LLMs (Temperature, Top-P, Top-K, Presence/Frequency Penalty) `[4 hrs]`
- [ ] **4.1.2** Técnicas de Prompting: Zero-shot, Few-shot, Chain-of-Thought (CoT), ReAct `[6 hrs]`
- [ ] **4.1.3** Context Window, Gestión de Tokens y Costos de API `[5 hrs]`

### 🔹 Módulo 4.2: Integración de APIs de LLMs y Modelos Locales *(15 horas)*
- [ ] **4.2.1** Uso de SDKs oficiales (OpenAI API, Anthropic Claude API, Google Gemini API) `[5 hrs]`
- [ ] **4.2.2** Ejecución de LLMs Locales con **Ollama** y LM Studio `[5 hrs]`
- [ ] **4.2.3** Formatos de Salida Estructurados (JSON Mode, Pydantic Function Calling) `[5 hrs]`

### 🔹 Módulo 4.3: Arquitectura LangChain Core *(30 horas)*
- [ ] **4.3.1** Componentes LangChain: LCEL (LangChain Expression Language) y Sintaxis Pipe `[8 hrs]`
- [ ] **4.3.2** Modelos: ChatModels vs. LLMs y Embeddings (`OpenAIEmbeddings`, `HuggingFaceEmbeddings`) `[6 hrs]`
- [ ] **4.3.3** Prompts: `ChatPromptTemplate`, `FewShotPromptTemplate` `[5 hrs]`
- [ ] **4.3.4** Output Parsers (`StrOutputParser`, `JsonOutputParser`, `PydanticOutputParser`) `[5 hrs]`
- [ ] **4.3.5** Memoria y Conversación (`ChatMessageHistory`, Memory Stores) `[6 hrs]`

### 🔹 Módulo 4.4: RAG (Retrieval-Augmented Generation) y Bases de Datos Vectoriales *(30 horas)*
- [ ] **4.4.1** Document Loaders (PDF, Markdown, HTML, Notion, Web) `[4 hrs]`
- [ ] **4.4.2** Text Splitters: `RecursiveCharacterTextSplitter`, Token-based Splitting `[5 hrs]`
- [ ] **4.4.3** Bases de Datos Vectoriales: ChromaDB, FAISS, Pinecone y Métricas de Similitud `[8 hrs]`
- [ ] **4.4.4** Construcción de RAG Chain Tradicional (Retriever -> Prompt -> LLM -> Output) `[7 hrs]`
- [ ] **4.4.5** RAG Avanzado: Multi-Query Retriever, Contextual Compression, Parent Document Retriever `[6 hrs]`

### 🔹 Módulo 4.5: Agentes Autónomos con LangGraph y Observabilidad con LangSmith *(30 horas)*
- [ ] **4.5.1** Definición de Tools y Function Calling en Agentes `[6 hrs]`
- [ ] **4.5.2** Introducción a **LangGraph**: Nodos, Aristas (Edges), Estado (`TypedDict` / Pydantic) y Ciclos `[10 hrs]`
- [ ] **4.5.3** Patrones de Agentes: Human-in-the-loop, Agentes Multi-Agente, Plan-and-Execute `[8 hrs]`
- [ ] **4.5.4** Monitoreo, Tracing y Depuración de Cadenas con **LangSmith** `[6 hrs]`

---

## 📖 Documentación Oficial Recomendada

- **LangChain Python Documentation**: Documentación oficial de LCEL, componentes, retrievers y chains.
- **LangGraph Documentation**: Guía para la creación de flujos cíclicos, estados y agentes autónomos.
- **LangSmith Documentation**: Plataforma de evaluación, tracing y monitoreo de llamadas a LLMs.
- **ChromaDB Documentation**: Base de datos vectorial de código abierto.

---

## 🎥 Videos y Cursos Recomendados

- **Cursos Gratuitos Recomendados:**
  - *DeepLearning.AI — LangChain for LLM Application Development (Harrison Chase)*
  - *DeepLearning.AI — Building Systems with the ChatGPT API*
  - *DeepLearning.AI — LangChain: Functions, Tools and Agents*
- **Tutoriales y Canales de Referencia:**
  - *James Briggs (AI / Vector DBs & LangChain en YouTube)*
  - *LangChain Official YouTube Channel (LangGraph Tutorials)*

---

## 🛠️ Ejercicios y Proyectos Prácticos

1. **Ejercicio 1: Asistente Lector de PDFs (RAG Local con Ollama y ChromaDB):**  
   Crea una script en Python que reciba un archivo PDF, divida el texto con `RecursiveCharacterTextSplitter`, genere embeddings locales con Ollama y permita hacer preguntas sobre el documento.
2. **Ejercicio 2: Agente de Búsqueda Web con LangChain Tools:**  
   Implementa un agente ReAct que use la API de Tavily o DuckDuckGo para buscar noticias en tiempo real y responder preguntas complejas.
3. **Proyecto Integrador de Fase 4:**  
   **Agente Investigador Multi-Paso con LangGraph y LangSmith:**  
   Construye un grafo de agentes que coordine un planificador de investigación, un buscador web, un sintetizador RAG sobre documentos locales y un crítico que valide la coherencia de la respuesta antes de entregarla al usuario.

---

## 🔗 Referencias a Fuentes Consultadas
- Diseñado directamente con base en las recomendaciones del **LangChain Forum Learning Roadmap** y la guía de **UI Studio AI Engineer Roadmap**.
