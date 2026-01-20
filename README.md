simple AI-powered web application using LangChain, FastAPI, LangServe, Streamlit, OpenAI, and Ollama (LLaMA2).

FEATURES:

Generate essays using OpenAI’s GPT model
Generate poems using local LLaMA2 (Ollama)
Simple and interactive Streamlit UI
FastAPI backend with auto-generated routes using LangServe
Supports both cloud-based and local LLMs

TECH STACK:

Python
FastAPI
LangChain
LangServe
Streamlit
OpenAI API
Ollama (LLaMA2)

ENVIRONMENT SETUP:
Create a .env file in the project root:

OPENAI_API_KEY=your_openai_api_key_here

INSTALL DEPENDENCIES:
pip install -r requirements.txt

Make sure Ollama is installed and LLaMA2 is pulled:

ollama pull llama2

WORKFLOW:
User Input (Streamlit UI)
        ↓
HTTP POST Request
        ↓
FastAPI + LangServe
        ↓
LangChain Prompt + LLM
        ↓
AI Generated Response
        ↓
Displayed to User
