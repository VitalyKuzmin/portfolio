![alt text](img/7.jpg)

### hAi (AI assistant for computer control) | [Project Website](https://hi-ai.app/)

The **hAi** project is aimed at creating an advanced AI assistant for the desktop.

**Key Idea:**
To create an assistant that has a cognitive memory model (sensory, short-term, long-term), tracks user activity on the computer (using ActivityWatch), and provides flexible options for interaction and extension.

**Architecture and Stack:**
The system is built on the principle of a **distributed local application**. The core, based on **Python/FastAPI** with **LangChain**, manages the logic, while specialized services like **LiveKit** (voice communication) and **ActivityWatch** (monitoring) operate as independent components. This ensures stability and loose coupling. Additionally, a RAG approach allows for extensive personalized memory.

- **Backend:** Python, FastAPI, LangChain, SQLAlchemy.
- **Frontend:** Electron, React, TypeScript.
- **AI:** Integration with various LLMs (OpenAI, Gemini, Ollama), Computer Vision (Moondream), and STT/TTS solutions (Whisper, Piper).
- **DB**: SQLite, LanceDB.
- **Protocols:** REST, SSE, and a custom **MCP (Model Context Protocol)** for connecting external tools.

**My Role:**
I serve as the **Lead** and **Backend Developer**. I designed the architecture, manage a team of 6 people (2xBackend, 2xFrontend, Analyst, Designer), and establish development processes (JIRA, GitOps).
