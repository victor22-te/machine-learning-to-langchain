<div align="center">

# Fase 5: Despliegue de Aplicaciones de IA, APIs y MLOps
### Microservicios Asíncronos, Containerización, UIs con Streamlit y Evaluación de LLMs

<br/>

<a href="../../../README.md">
  <img src="https://img.shields.io/badge/-%E2%86%90%20README%20PRINCIPAL-0A0A0F?style=flat-square&logoColor=white&labelColor=1E293B"/>
</a>
<a href="../../00_roadmap_general/spider-man/00_roadmap_general.md">
  <img src="https://img.shields.io/badge/ROADMAP%20GENERAL-0A0A0F?style=flat-square&logoColor=white&labelColor=1E293B"/>
</a>
<a href="../../fase_4_llms_y_langchain/spider-man/fase_4_llms_y_langchain.md">
  <img src="https://img.shields.io/badge/%E2%86%90%20ANTERIOR%3A%20FASE%204-0A0A0F?style=flat-square&logoColor=white&labelColor=1E293B"/>
</a>

<br/><br/>

<img src="https://img.shields.io/badge/DURACI%C3%93N-8%20a%2010%20SEMANAS-0A0A0F?style=flat-square&labelColor=1E293B"/>
<img src="https://img.shields.io/badge/CARGA%20ESTIMADA-~90%20HORAS-0A0A0F?style=flat-square&labelColor=1E293B"/>
<img src="https://img.shields.io/badge/ESTADO-PENDIENTE-2D3748?style=flat-square"/>

<br/><br/>

<p align="center">
<strong>Objetivo:</strong> Transformar scripts experimentales y cadenas de inferencia en servicios web de producción seguros, resilientes y escalables; empaquetando aplicaciones en contenedores Docker y aplicando métricas de calidad y confiabilidad de sistemas generativos con Ragas.
</p>

</div>

---

<img src="https://img.shields.io/badge/-%3E_.%2F01__skills__stack-0A0A0F?style=for-the-badge&logo=windows-terminal&logoColor=38BDF8"/> &nbsp; <i>// skills y herramientas de la fase</i>

<div align="center">

<img src="https://skillicons.dev/icons?i=python,fastapi,docker,linux,git,github,vscode&theme=dark" />

<br/><br/>

<img src="https://img.shields.io/badge/FastAPI-High%20Performance-009688?style=flat-square&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/Pydantic_v2-Validation-E92063?style=flat-square&logo=pydantic&logoColor=white"/>
<img src="https://img.shields.io/badge/Uvicorn-ASGI%20Server-499848?style=flat-square"/>
<img src="https://img.shields.io/badge/Streamlit-Interactive%20UI-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>
<img src="https://img.shields.io/badge/Gradio-Demo%20Interfaces-FF8800?style=flat-square"/>
<img src="https://img.shields.io/badge/Docker-Containers-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker_Compose-Orchestration-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Ragas-LLM%20Evaluation-2D3748?style=flat-square"/>
<img src="https://img.shields.io/badge/SSE-Server--Sent%20Events-1E293B?style=flat-square"/>

</div>

---

<img src="https://img.shields.io/badge/-%3E_.%2F02__modules__breakdown-0A0A0F?style=for-the-badge&logo=windows-terminal&logoColor=38BDF8"/> &nbsp; <i>// desglose de módulos y tareas</i>

### Módulo 5.1: Creación de APIs de Alto Rendimiento con FastAPI `[20 horas]`
* [ ] **5.1.1** Fundamentos de FastAPI: diseño RESTful, arquitectura ASGI con Uvicorn y programación concurrente con `async` / `await`. `[5 hrs]`
* [ ] **5.1.2** Definición de contratos y validación de payloads de entrada y esquemas de respuesta mediante Pydantic v2. `[5 hrs]`
* [ ] **5.1.3** Streaming de respuestas de modelos de lenguaje en tiempo real utilizando Server-Sent Events (`EventSourceResponse` / SSE). `[5 hrs]`
* [ ] **5.1.4** Seguridad en microservicios: autenticación por API Keys, configuración de CORS y rate limiting para mitigación de sobrecargas. `[5 hrs]`

### Módulo 5.2: Interfaces de Usuario Rápidas (Streamlit & Gradio) `[15 horas]`
* [ ] **5.2.1** Desarrollo de interfaces conversacionales reactivas en Streamlit con `st.chat_message`, `st.chat_input` y persistencia en `session_state`. `[7 hrs]`
* [ ] **5.2.2** Creación rápida de interfaces para demostración de modelos mediante Gradio (`gr.Interface`, `gr.ChatInterface`). `[4 hrs]`
* [ ] **5.2.3** Desacoplamiento arquitectónico: consumo de los endpoints de FastAPI desde la interfaz web vía HTTP asíncrono. `[4 hrs]`

### Módulo 5.3: Containerización con Docker `[20 horas]`
* [ ] **5.3.1** Conceptos clave de virtualización ligera: imágenes base, capas inmutables, contenedores y Docker Hub. `[4 hrs]`
* [ ] **5.3.2** Creación de un `Dockerfile` optimizado: compilación multi-etapa (multi-stage builds), minimización de imagen y ejecución sin privilegios de root. `[8 hrs]`
* [ ] **5.3.3** Orquestación multi-servicio con `docker-compose.yml`: definición de redes compartidas y volúmenes persistentes (Backend FastAPI + Base de datos vectorial + Frontend). `[8 hrs]`

### Módulo 5.4: Despliegue en la Nube `[20 horas]`
* [ ] **5.4.1** Despliegue continuo de demos en Hugging Face Spaces integrando repositorios Git. `[5 hrs]`
* [ ] **5.4.2** Alojamiento de servicios backend en plataformas PaaS como Render, Railway o Fly.io con variables de entorno protegidas. `[7 hrs]`
* [ ] **5.4.3** Nociones de infraestructura cloud: despliegue de contenedores serverless en Google Cloud Run o AWS ECS. `[8 hrs]`

### Módulo 5.5: Evaluación, Monitoreo y Guardrails de LLMs `[15 horas]`
* [ ] **5.5.1** Evaluación cuantitativa de sistemas RAG con **Ragas**: fidelidad (Faithfulness), relevancia de la respuesta (Answer Relevance) y recuperación de contexto (Context Recall). `[5 hrs]`
* [ ] **5.5.2** Implementación de guardrails de seguridad: validación de contenido, moderación de sesgos y prevención de prompt injection. `[5 hrs]`
* [ ] **5.5.3** Instrumentación y telemetría: medición de latencia por token (Time to First Token - TTFT) y registro de consumo de cuotas. `[5 hrs]`

---

<img src="https://img.shields.io/badge/-%3E_.%2F03__official__docs-0A0A0F?style=for-the-badge&logo=windows-terminal&logoColor=38BDF8"/> &nbsp; <i>// documentación oficial de referencia</i>

* **FastAPI Official Tutorial:** Rutas, dependencias, middleware, gestión asíncrona y Pydantic.
* **Streamlit Documentation:** Componentes de chat, estado de sesión y caching de datos.
* **Docker Documentation:** Sintaxis de Dockerfile, gestión de imágenes y configuración de redes en compose.
* **Ragas Documentation:** Métricas de evaluación automatizada para componentes de arquitecturas RAG.

---

<img src="https://img.shields.io/badge/-%3E_.%2F04__recommended__courses-0A0A0F?style=for-the-badge&logo=windows-terminal&logoColor=38BDF8"/> &nbsp; <i>// cursos y recursos de estudio</i>

* **FastAPI y Desarrollo Web Asíncrono:**
  * *Sebastián Ramírez — FastAPI Official Tutorials and Deep Dives*
  * *FreeCodeCamp — FastAPI Course for Machine Learning APIs*
* **Docker y DevOps para Machine Learning:**
  * *Tech With Tim — Docker Course for Developers*
  * *NetworkChuck — Docker Containers from Scratch*

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
<td><strong>Microservicio RAG con FastAPI y Streaming</strong></td>
<td>Servidor web asíncrono que expone un endpoint <code>/chat</code> transmitiendo la respuesta de un modelo en tokens mediante Server-Sent Events (SSE).</td>
<td><code>api fastapi</code></td>
</tr>
<tr>
<td><strong>Arquitectura de 3 Contenedores en Docker</strong></td>
<td>Archivo <code>docker-compose.yml</code> que levanta el backend de inferencia, la base de datos vectorial ChromaDB y una UI en Streamlit con red interna aislada.</td>
<td><code>docker-compose</code></td>
</tr>
<tr>
<td><strong>Proyecto Final de Carrera: AI SaaS en Producción</strong></td>
<td>Plataforma completa de análisis de documentos: subida de archivos, indexación vectorial, interfaz conversacional, observabilidad en LangSmith y reporte cuantitativo de fidelidad generado con Ragas.</td>
<td><code>producto end-to-end</code></td>
</tr>
</tbody>
</table>

---

<img src="https://img.shields.io/badge/-%3E_.%2F06__references-0A0A0F?style=for-the-badge&logo=windows-terminal&logoColor=38BDF8"/> &nbsp; <i>// referencias consultadas</i>

* Basado en los requisitos de arquitectura e ingeniería de software de **UI Studio AI Engineer Roadmap** y las mejores prácticas de **roadmap.sh Machine Learning**.
