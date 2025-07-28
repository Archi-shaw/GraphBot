## 🤖 LangGraph Architecture

This repository contains implementations and experiments with building AI-powered chatbots using LangGraph — a powerful framework for building stateful, multi-agent applications powered by language models.

## 🚀 Project Overview

The goal of this project is to create a modular, scalable chatbot architecture leveraging:
- 🧠 **LangGraph** for state management and agent flow
- 🛠️ **Pydantic** for data validation and structuring
- 🧰 Supporting tools and utilities to expand chatbot functionality




## LangGraph Chatbots

Modular and scalable AI chatbot architectures built using **LangGraph** and **Pydantic**.  
This project demonstrates how to build multi-agent chatbots, define structured flows, and prototype intelligent workflows using LangGraph.

---

## 🚀 Features

- ✅ Multi-agent chatbot workflows using **LangGraph**
- 🧠 State validation with **Pydantic**
- 🔄 Switchable architectures (e.g., Supervisor, Swarm)
- ⚙️ Custom tools and utilities
- 🧪 Easy to test via LangGraph Dev Studio

---

## 📁 Project Structure

```

langgraph-chatbots/
├── demo\_supervisor/   # Supervisor architecture demo
│   ├── graph.py
│   └── state.py
├── demo\_swarm/        # Swarm-based agent demo
│   ├── graph.py
│   └── state.py
├── tools/             # Custom tools/utilities
│   └── custom\_tools.py
├── requirements.txt
├── .env               # Your LLM credentials
└── README.md

````

---

## ⚙️ Getting Started

### 1. Clone & Install

```bash
git clone https://github.com/Archi-shaw/langgraph-chatbots.git
cd langgraph-chatbots
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
````

### 2. Setup `.env`

Create a `.env` file with your OpenAI credentials:

```
OPENAI_API_KEY=your-api-key-here
```

### 3. Run a Demo

```bash
cd demo_supervisor
langgraph dev
```

---

## 📌 Use Cases

* Prototyping AI chatbot workflows
* Simulating multi-agent systems
* Exploring LangGraph capabilities

---

## 🧩 Technologies

* [LangGraph](https://github.com/langchain-ai/langgraph)
* [Pydantic](https://docs.pydantic.dev/)
* [Python 3.11+](https://www.python.org)

---

## 🤝 Contribute

Have ideas for new architectures or improvements? PRs are welcome!
