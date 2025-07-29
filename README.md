# 🤖 Customer Support Chatbot with PydanticAI

This project demonstrates how to build a **type-safe, structured AI chatbot** for customer support using [PydanticAI](https://github.com/pydantic/pydantic-ai). It uses a CSV file containing customer support tickets and responds to user queries by categorizing issues, assigning priority, deciding on escalation, and suggesting appropriate replies — all in a validated JSON format.

---

## 🚀 Features

- ✅ **Type-safe LLM interaction** using Pydantic v2
- 🧠 **LLM agent modeling** using `pydantic_ai.Agent`
- 📄 Reads from a **CSV of tickets** to match user queries
- 🧾 Responds in **structured JSON**
- 🔄 Built-in async chatbot loop
- 🧪 Validates outputs to prevent malformed responses

---

## 🛠️ Tech Stack

- Python 3.10+
- `pydantic-ai==0.1.3`
- `pydantic==2.x`
- `openai` SDK
- `pandas`
- `nest_asyncio`

---

## 📦 Installation

```bash
pip install pydantic-ai==0.1.3 pandas==2.2.3 openai nest_asyncio

📁 Project Structure
bash
Copy
Edit
.
├── chatbot.py         # Main chatbot script
├── tickets.csv        # Customer support tickets
├── requirements.txt   # All dependencies
└── README.md          # This file
