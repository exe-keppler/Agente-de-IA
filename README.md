# 🧠 Agentes de IA - Tarea Semana 4

Este repositorio contiene la implementación de una tarea académica cuyo objetivo es crear un flujo de agentes inspirado en [LangGraph](https://github.com/langchain-ai/langgraph), diseñado para ejecutar tareas de análisis y generación de comunicación sobre una base de datos estructurada de obligaciones fiscales.

---

## 🎯 Instrucciones de la tarea

> Crea una representación gráfica de flujo de agentes replicando LangGraph para ejecutar tareas que un usuario pida hacia una base de datos estructurada con precisión, memoria procedural, memoria semántica y memoria episódica.

---

## 🧱 Componentes del sistema

### ✅ Lenguajes y librerías utilizadas

- Python 3.13+
- [LangGraph](https://github.com/langchain-ai/langgraph)
- LangChain + OpenAI (para generación LLM)
- SQLite (en memoria)
- JSON estructurado como fuente de datos
- IPython (para visualización del grafo)

---

## 🧠 Memorias implementadas

| Tipo de memoria      | Implementación concreta                                                                 |
|----------------------|------------------------------------------------------------------------------------------|
| **Procedural**       | Flujo de nodos secuenciales definidos en `StateGraph` de LangGraph                      |
| **Semántica**        | Diccionario `SEMANTIC_MEMORY` con significados para los distintos tipos de obligación   |
| **Episódica**        | Tabla `execution_log` que guarda la fecha de ejecución, número de obligaciones encontradas y timestamp |

---

## 📦 Archivo JSON requerido

Debes colocar el archivo `obligations.json` en esta ruta (ajústala si cambias la ubicación):

