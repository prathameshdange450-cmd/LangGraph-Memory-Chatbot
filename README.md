
# LangGraph Memory Chatbot

An advanced AI-powered conversational chatbot built using LangGraph, Streamlit, LangChain, Google Gemini API, and SQLite database integration. This project demonstrates a ChatGPT-like conversational system with persistent memory, real-time streaming responses, multi-thread chat management, and stateful workflow orchestration.

The chatbot is designed using LangGraph’s graph-based workflow architecture, enabling efficient conversation handling and scalable AI interaction management. The application maintains long-term conversation history using SQLite checkpointing, allowing users to revisit and continue previous chats seamlessly.

The frontend is developed using Streamlit, providing an interactive and user-friendly chat interface similar to modern AI assistants. The system supports multiple chat sessions where users can create new conversations, switch between stored threads, and retrieve historical messages dynamically.

The backend workflow is powered by LangGraph and LangChain, where conversation states are managed using a state graph architecture. Messages are processed through workflow nodes, and responses are generated using Google Gemini 2.5 Flash LLM. The system streams responses word-by-word in real time, improving user interaction and creating a smooth conversational experience similar to ChatGPT.

Key Features:

* Real-time streaming AI responses
* Persistent memory using SQLite database
* Multi-thread conversation support
* Conversation history retrieval
* ChatGPT-like UI using Streamlit
* LangGraph stateful workflow management
* Gemini 2.5 Flash LLM integration
* Session-based conversation tracking
* Dynamic thread generation using UUID
* Scalable and modular architecture

Workflow:

1. User sends a message through the Streamlit interface
2. LangGraph processes the conversation state
3. Messages are stored using SQLite checkpointing
4. Gemini LLM generates contextual responses
5. Responses are streamed live to the frontend
6. Conversations are saved and retrievable across sessions

Tech Stack:

* Python
* Streamlit
* LangGraph
* LangChain
* Google Gemini API
* SQLite
* Generative AI
* Agentic AI

This project demonstrates practical implementation of conversational AI systems, memory-enabled agents, real-time LLM streaming, and graph-based workflow orchestration for intelligent chatbot applications.
