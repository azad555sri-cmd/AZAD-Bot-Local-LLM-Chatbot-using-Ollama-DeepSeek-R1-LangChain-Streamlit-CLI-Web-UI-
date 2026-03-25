AZAD Bot is a lightweight, locally running AI chatbot that leverages the DeepSeek-R1 model through Ollama, integrated with LangChain for prompt management and Streamlit for an interactive web interface.

The project is designed to demonstrate how to build and run a fully local Large Language Model (LLM) application without relying on external APIs. It supports both command-line (CLI) and browser-based (Streamlit) interfaces, making it flexible for development, testing, and user interaction.

With a simple and modular structure, AZAD Bot allows users to input questions and receive step-by-step reasoning-based responses, showcasing the capabilities of modern open-source LLMs in a local environment.


## 🚀 Features

- 🤖 Powered by DeepSeek-R1 (via Ollama)
- 🔗 Built with LangChain
- 🌐 Interactive Streamlit Web UI
- 🖥️ CLI (Command Line Interface) support
- ⚡ Runs locally (no API required)
- 🧠 Step-by-step reasoning responses
- 🧩 Simple and modular code structure

---

## 🛠️ Tech Stack

- Python
- LangChain
- Ollama
- DeepSeek-R1 Model
- Streamlit

---
📦 requirements.txt
 - langchain
 - langchain-core
 - langchain-ollama
 - streamlit

🌐 Local AI Without Internet Dependency
  - Runs fully offline after model download
  - No API keys required
  - Useful for:
    - Privacy-focused applications
    - Low-cost AI development
   
🖥️ Multi-Interface Usage
  - CLI Mode → quick testing and debugging
  - Streamlit UI → user-friendly interaction in browser  

🔐 Privacy-Focused AI
  - No data sent to external servers
  - Everything runs locally via Ollama
