# 🟥 Fase 5: Despliegue de Aplicaciones de IA, APIs y MLOps Básico

> **Duración estimada:** 8 a 10 semanas (~90 horas lectivas y prácticas)  
> **Objetivo:** Convertir tus prototipos y scripts de IA en servicios web de producción seguros, escalables, containerizados y con monitoreo activo.

---

## ⏱️ Distribución de Tareas e Horas Estimadas

### 🔹 Módulo 5.1: Creación de APIs de Alto Rendimiento con FastAPI *(20 horas)*
- [ ] **5.1.1** Fundamentos de FastAPI, Routing y Asincronía (`async` / `await`) `[5 hrs]`
- [ ] **5.1.2** Validación de Esquemas de Entrada/Salida con Pydantic `[5 hrs]`
- [ ] **5.1.3** Streaming de Respuestas de LLM en tiempo real (`EventSourceResponse` / SSE) `[5 hrs]`
- [ ] **5.1.4** Autenticación API Keys, CORS y Limitación de Peticiones (Rate Limiting) `[5 hrs]`

### 🔹 Módulo 5.2: Interfaces de Usuario Rápidas (Streamlit & Gradio) *(15 horas)*
- [ ] **5.2.1** Desarrollo de Chatbots Interactivos con Streamlit (`st.chat_message`, `st.chat_input`) `[7 hrs]`
- [ ] **5.2.2** Creación de Demos Interactivas de Modelos con Gradio `[4 hrs]`
- [ ] **5.2.3** Conexión de la Interfaz Web con la API backend de FastAPI `[4 hrs]`

### 🔹 Módulo 5.3: Containerización con Docker *(20 horas)*
- [ ] **5.3.1** Conceptos de Imágenes, Contenedores y Docker Hub `[4 hrs]`
- [ ] **5.3.2** Creación de `Dockerfile` optimizado para aplicaciones Python/LangChain `[8 hrs]`
- [ ] **5.3.3** Orquestación local con `docker-compose` (API + Vector DB Chroma + Frontend Streamlit) `[8 hrs]`

### 🔹 Módulo 5.4: Despliegue en la Nube *(20 horas)*
- [ ] **5.4.1** Despliegue de Demos en Hugging Face Spaces (Gradio/Streamlit) `[5 hrs]`
- [ ] **5.4.2** Despliegue de APIs en Render / Railway / Fly.io `[7 hrs]`
- [ ] **5.4.3** Nivel Básico de Cloud Providers (AWS ECS / GCP Cloud Run para contenedores) `[8 hrs]`

### 🔹 Módulo 5.5: Evaluación, Monitoreo y Guardrails de LLMs *(15 horas)*
- [ ] **5.5.1** Evaluación de RAG con Ragas Framework (Faithfulness, Answer Relevance, Context Recall) `[5 hrs]`
- [ ] **5.5.2** Implementación de Guardrails (Moderación de contenido, Inyección de Prompts) `[5 hrs]`
- [ ] **5.5.3** Monitoreo de Latencia y Token Usage en Producción `[5 hrs]`

---

## 📖 Documentación Oficial Recomendada

- **FastAPI Documentation**: Guía oficial de microservicios asíncronos y Pydantic.
- **Streamlit Documentation**: Creación de apps de datos interactivas en minutos.
- **Docker Documentation**: Guías de Dockerfile, multicontenedores e imágenes.
- **Hugging Face Spaces Guide**: Despliegue gratuito de aplicaciones de IA.

---

## 🎥 Videos y Cursos Recomendados

- **FastAPI & Python Web Services:**
  - *Sebastián Ramírez (Creador de FastAPI) — FastAPI Tutorials*
  - *FreeCodeCamp — FastAPI Course for Beginners (YouTube)*
- **Docker para Desarrolladores de IA:**
  - *Tech With Tim — Docker Course for Beginners (YouTube)*
  - *NetworkChuck — You need to learn Docker NOW!*

---

## 🛠️ Ejercicios y Proyectos Prácticos

1. **Ejercicio 1: Microservicio RAG con FastAPI y Streaming:**  
   Crea un endpoint `/api/v1/chat` en FastAPI que reciba un prompt, invoque una cadena LangChain y devuelva la respuesta token por token en formato streaming.
2. **Ejercicio 2: Arquitectura de 3 Contenedores con Docker-Compose:**  
   Escribe un archivo `docker-compose.yml` que levante un contenedor con la API de FastAPI, un contenedor con ChromaDB y un contenedor con la UI de Streamlit.
3. **Proyecto Final de Carrera (End-to-End Product):**  
   **Plataforma SaaS de Análisis Inteligente de Documentos:**  
   Aplicación web completa containerizada con Docker y desplegada en la nube, donde los usuarios suben documentos, un agente de LangGraph responde consultas complejas mediante un backend FastAPI y los resultados se monitorean en tiempo real con LangSmith.

---

## 🔗 Referencias a Fuentes Consultadas
- Basado en los requisitos de MLOps y Despliegue descritos en **UI Studio AI Engineer Roadmap** y **roadmap.sh Machine Learning**.
