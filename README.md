# ai-chatbot-memory
A stateful AI chatbot with long-term memory built using LangGraph and SQLite.

# 🧠 LangGraph Long-Term Memory AI Chatbot

An AI chatbot built with LangGraph that uses SQLite for persistent long-term memory, conversation summarization, and stateful workflow execution.

---

## 🚀 Project Overview

This project demonstrates how to build an AI chatbot capable of remembering previous conversations across sessions using LangGraph's checkpointing system.

Instead of sending the entire conversation history to the language model, the chatbot periodically summarizes previous interactions and stores them in a SQLite database. This approach reduces token usage while allowing the chatbot to maintain long-term conversational context.

The project showcases state management, memory persistence, graph-based workflows, and conversation summarization using LangGraph.

---

## ✨ Features

- Long-term conversational memory
- Persistent memory using SQLite
- Conversation summarization
- Stateful AI workflows
- LangGraph graph execution
- Memory checkpointing
- GPT-4o integration
- Context-aware responses

---

## 🛠 Technologies Used

- Python
- LangGraph
- LangChain
- OpenAI GPT-4o
- SQLite
- Jupyter Notebook

---

## 📂 Repository Contents

- `Langgraph_long_term_ai_chatbot.ipynb` – Complete implementation of the chatbot with persistent memory.

---

## ⚙️ Workflow

1. Create a custom graph state using `MessagesState`.
2. Accept user input through the conversation workflow.
3. Generate AI responses with GPT-4o.
4. Summarize the conversation to preserve important context.
5. Store conversation state using `SqliteSaver`.
6. Retrieve previous conversations from SQLite.
7. Continue conversations with long-term memory across sessions.

---

## 🎯 Skills Demonstrated

- AI Agent Development
- LangGraph
- Stateful Workflow Design
- Long-Term Memory
- SQLite Persistence
- Checkpointing
- Conversation Summarization
- Prompt Engineering
- LLM Integration

---

## 📈 Key Concepts

- LangGraph `StateGraph`
- `MessagesState`
- `SqliteSaver`
- Checkpointing
- Conversation Summarization
- Persistent AI Memory
- Graph-Based AI Workflows

---

## 🔮 Future Improvements

- Support multiple users
- Semantic memory with vector databases
- Hybrid memory (SQLite + Pinecone/ChromaDB)
- Tool calling
- Web interface using Streamlit or Gradio
- User authentication

---

## 👤 Author

**Happiness Chibuzor**

AI Engineer | NLP | Transformers | LangChain | LangGraph | Voice AI
