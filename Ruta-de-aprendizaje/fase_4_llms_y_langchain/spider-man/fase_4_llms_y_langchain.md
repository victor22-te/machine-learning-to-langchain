<div align="center">

# Fase 4: Modelos de Lenguaje (LLMs), RAG, LangChain y LangGraph
### Aplicaciones con IA Generativa, Bases de Datos Vectoriales, Flujos Cíclicos y Agentes Autónomos

<br/>

<a href="../../../README.md">
  <img src="https://img.shields.io/badge/-%E2%86%90%20README%20PRINCIPAL-0A0A0F?style=flat-square&logoColor=white&labelColor=1E293B"/>
</a>
<a href="../../00_roadmap_general/spider-man/00_roadmap_general.md">
  <img src="https://img.shields.io/badge/ROADMAP%20GENERAL-0A0A0F?style=flat-square&logoColor=white&labelColor=1E293B"/>
</a>
<a href="../../fase_3_deep_learning_nlp/spider-man/fase_3_deep_learning_nlp.md">
  <img src="https://img.shields.io/badge/%E2%86%90%20ANTERIOR%3A%20FASE%203-0A0A0F?style=flat-square&logoColor=white&labelColor=1E293B"/>
</a>
<a href="../../fase_5_despliegue_mlops/spider-man/fase_5_despliegue_mlops.md">
  <img src="https://img.shields.io/badge/SIGUIENTE%3A%20FASE%205%20%E2%86%92-0A0A0F?style=flat-square&logoColor=white&labelColor=1E293B"/>
</a>

<br/><br/>

<img src="https://img.shields.io/badge/DURACI%C3%93N-10%20a%2012%20SEMANAS-0A0A0F?style=flat-square&labelColor=1E293B"/>
<img src="https://img.shields.io/badge/CARGA%20ESTIMADA-~120%20HORAS-0A0A0F?style=flat-square&labelColor=1E293B"/>
<img src="https://img.shields.io/badge/ESTADO-PENDIENTE-2D3748?style=flat-square"/>

<br/><br/>

<p align="center">
<strong>Objetivo:</strong> Diseñar y construir sistemas avanzados basados en Modelos de Lenguaje Grande (LLMs), implementando pipelines RAG (Retrieval-Augmented Generation) multidocumento sobre bases de datos vectoriales, y orquestando agentes autónomos multi-paso mediante LangChain, LangGraph y observabilidad con LangSmith.
</p>

</div>

---

<img src="https://img.shields.io/badge/-%3E_.%2F01__skills__stack-0A0A0F?style=for-the-badge&logo=windows-terminal&logoColor=38BDF8"/> &nbsp; <i>// skills y herramientas de la fase</i>

<div align="center">

<img src="https://skillicons.dev/icons?i=python,linux,git,github,vscode&theme=dark" />

<br/><br/>

<img src="https://img.shields.io/badge/LangChain-LCEL-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/LangGraph-Multi--Agent-1C3C3C?style=flat-square"/>
<img src="https://img.shields.io/badge/LangSmith-Tracing%20%26%20Eval-1C3C3C?style=flat-square"/>
<img src="https://img.shields.io/badge/Ollama-Local%20LLMs-111111?style=flat-square"/>
<img src="https://img.shields.io/badge/ChromaDB-Vector%20Store-FC521F?style=flat-square"/>
<img src="https://img.shields.io/badge/FAISS-Dense%20Retrieval-0468D7?style=flat-square"/>
<img src="https://img.shields.io/badge/Pydantic-Structured%20Output-E92063?style=flat-square&logo=pydantic&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenAI_API-GPT--4o-412991?style=flat-square&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/Google_Gemini-Multimodal-4285F4?style=flat-square&logo=google&logoColor=white"/>

</div>

---

<img src="https://img.shields.io/badge/-%3E_.%2F02__modules__breakdown-0A0A0F?style=for-the-badge&logo=windows-terminal&logoColor=38BDF8"/> &nbsp; <i>// desglose de módulos y tareas</i>

### Módulo 4.1: Fundamentos de LLMs y Prompt Engineering `[15 horas]`
* [ ] **4.1.1** Mecánica de inferencia y parámetros de generación: Temperature, Top-P, Top-K, Presence Penalty y Frequency Penalty. `[4 hrs]`
* [ ] **4.1.2** Estrategias formales de prompting: Zero-shot, Few-shot contextual, Chain-of-Thought (CoT) y patrón ReAct (Reasoning + Acting). `[6 hrs]`
* [ ] **4.1.3** Ventanas de contexto (Context Window), fragmentación de tokens (Tokenization BPE) y optimización de costos y latencia de inferencia. `[5 hrs]`

### Módulo 4.2: Integración de APIs de LLMs y Modelos Locales `[15 horas]`
* [ ] **4.2.1** Integración de SDKs de frontera: llamadas asíncronas y autenticación con OpenAI, Anthropic Claude y Google Gemini. `[5 hrs]`
* [ ] **4.2.2** Entornos de ejecución local: configuración de **Ollama** y LM Studio para inferencia offline con cuantización (GGUF / Q4_K_M). `[5 hrs]`
* [ ] **4.2.3** Extracción estructurada: Function Calling, JSON Mode e imposición de esquemas de datos con modelos de validación en Pydantic. `[5 hrs]`

### Módulo 4.3: Arquitectura LangChain Core `[30 horas]`
* [ ] **4.3.1** Paradigma LCEL (LangChain Expression Language): composición composable y encadenamiento declarativo mediante sintaxis pipe (`|`). `[8 hrs]`
* [ ] **4.3.2** Capa de abstracción de modelos: `ChatOpenAI`, `ChatAnthropic`, `OllamaLLM` y embeddings vectoriales unificados. `[6 hrs]`
* [ ] **4.3.3** Plantillas dinámicas de prompts: `ChatPromptTemplate`, mensajes de sistema y serialización de historiales. `[5 hrs]`
* [ ] **4.3.4** Parseo de salidas: implementaciones de `StrOutputParser`, `JsonOutputParser` y `PydanticOutputParser` con corrección de fallas. `[5 hrs]`
* [ ] **4.3.5** Gestión de memoria y estado conversacional: `ChatMessageHistory`, persistencia en memoria y resúmenes de contexto en ventanas deslizantes. `[6 hrs]`

### Módulo 4.4: RAG (Retrieval-Augmented Generation) y Bases de Datos Vectoriales `[30 horas]`
* [ ] **4.4.1** Ingestores de documentos (Document Loaders): extracción y parseo de PDF, Markdown, HTML, tablas estructuradas y URLs. `[4 hrs]`
* [ ] **4.4.2** Estrategias de chunking: división recursiva (`RecursiveCharacterTextSplitter`), chunks delimitados por tokens y solapamiento semántico (`chunk_overlap`). `[5 hrs]`
* [ ] **4.4.3** Bases de datos vectoriales: ChromaDB, FAISS, Pinecone y selección de métricas de distancia (Coseno, Producto Punto, Euclidiana L2). `[8 hrs]`
* [ ] **4.4.4** Cadena RAG elemental: composición declarativa Retriever -> Formateador de Documentos -> Prompt de Aumentación -> LLM. `[7 hrs]`
* [ ] **4.4.5** Técnicas RAG de vanguardia: Multi-Query Retriever, Contextual Compression, reranking con Cross-Encoders y Parent Document Retriever. `[6 hrs]`

### Módulo 4.5: Agentes Autónomos con LangGraph y Observabilidad con LangSmith `[30 horas]`
* [ ] **4.5.1** Definición de herramientas (Tools) decoradas con `@tool`, tipado estricto de argumentos y resolución de dependencias. `[6 hrs]`
* [ ] **4.5.2** Arquitectura de grafos de estado con **LangGraph**: nodos de cómputo, aristas condicionales (`conditional_edges`), estado compartido tipado (`StateGraph`) y manejo de ciclos. `[10 hrs]`
* [ ] **4.5.3** Topologías avanzadas de agentes: Human-in-the-loop (pausas para aprobación), supervisión centralizada y flujos Multi-Agente colaborativos. `[8 hrs]`
* [ ] **4.5.4** Monitoreo y evaluación en **LangSmith**: tracing de tokens consumidos, análisis de cuellos de botella de latencia y pruebas de regresión. `[6 hrs]`

---

<img src="https://img.shields.io/badge/-%3E_.%2F03__official__docs-0A0A0F?style=for-the-badge&logo=windows-terminal&logoColor=38BDF8"/> &nbsp; <i>// documentación oficial de referencia</i>

* **LangChain Python Documentation:** Guías conceptuales, componentes de LCEL y catálogo de integraciones.
* **LangGraph Documentation:** Arquitectura de grafos cíclicos, persistencia de checkpoints y coordinación de agentes.
* **LangSmith Docs:** Plataforma para tracing de ejecución, monitoreo de sesiones y datasets de benchmarking.
* **ChromaDB Official Docs:** Creación de colecciones, persistencia local y consultas por similitud semántica.

---

<img src="https://img.shields.io/badge/-%3E_.%2F04__recommended__courses-0A0A0F?style=for-the-badge&logo=windows-terminal&logoColor=38BDF8"/> &nbsp; <i>// cursos y recursos audiovisuales</i>

* **DeepLearning.AI Cursos Especializados:**
  * *LangChain for LLM Application Development* (Harrison Chase)
  * *Building Systems with the ChatGPT API*
  * *Functions, Tools and Agents with LangChain*
* **Canales y Creadores Especializados:**
  * *James Briggs — Vector Databases, Semantic Search & LangChain*
  * *LangChain Official — LangGraph Tutorials & Architecture Deep Dives*

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
<td><strong>Asistente Lector de PDFs (RAG Local)</strong></td>
<td>Script de terminal en Python que procesa archivos PDF con <code>RecursiveCharacterTextSplitter</code>, genera embeddings locales con Ollama y consulta una colección persistente en ChromaDB.</td>
<td><code>script cli</code></td>
</tr>
<tr>
<td><strong>Agente de Búsqueda Web ReAct</strong></td>
<td>Agente conversacional que integra herramientas de búsqueda en vivo (Tavily / DuckDuckGo) y resuelve consultas cronológicas citando fuentes con Function Calling.</td>
<td><code>notebook / script</code></td>
</tr>
<tr>
<td><strong>Proyecto Integrador: Agente Investigador Multi-Paso</strong></td>
<td>Grafo de agentes construido con LangGraph compuesto por un nodo planificador, un buscador web, un retriever de documentos locales y un crítico de coherencia con observabilidad activa en LangSmith.</td>
<td><code>arquitectura langgraph</code></td>
</tr>
</tbody>
</table>

---

<img src="https://img.shields.io/badge/-%3E_.%2F06__references-0A0A0F?style=for-the-badge&logo=windows-terminal&logoColor=38BDF8"/> &nbsp; <i>// referencias consultadas</i>

* Basado en el marco de trabajo del **LangChain Community Roadmap** y las directrices de diseño de aplicaciones cognitivas de **UI Studio AI Engineer Roadmap**.
