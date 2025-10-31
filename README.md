# Q-s-Free-AI-Chatbot-Mistral-
# 🤖 Q's Free AI Chatbot (Mistral)

A **free, local AI chatbot** powered by the open-source [Mistral model](https://mistral.ai/) through [Ollama](https://ollama.ai/), and built with [Streamlit](https://streamlit.io/).

This chatbot runs **entirely on your computer** — no API keys, no cloud costs, just Python and your local model.

---

## 🧩 Features
- 🗨️ Interactive web-based chat UI (built with Streamlit)
- ⚡ Fast local inference using Ollama + Mistral
- 🔒 100% offline — your data never leaves your device
- 💾 Saves chat history during session
- 🧰 Built fully in Python using `subprocess` and Streamlit components

---

🚀 How to Run It Yourself

### 1️⃣ Install Requirements
Make sure you have Python 3.10+ installed. Then open a terminal and install the dependencies:

pip install streamlit
2️⃣ Install and Set up Ollama
Download Ollama for your platform:
👉 https://ollama.ai/download

Then open a terminal (PowerShell on Windows) and pull the Mistral model:
Copy code
ollama pull mistral
3️⃣ Clone This Repository
bash
Copy code
git clone https://github.com/QB2134/Q-s-Free-AI-Chatbot-Mistral.git
cd Q-s-Free-AI-Chatbot
4️⃣ Run the App
bash
Copy code
streamlit run app.py
Your chatbot will open automatically at http://localhost:8501

🧩 File Overview
File	Description
app.py	Main Streamlit chatbot script
requirements.txt	Python dependencies (optional)
README.md	This documentation file

🧠 How It Works
This app uses Python’s subprocess module to send your input text directly to Ollama’s local model (Mistral). The response is captured and displayed dynamically in a Streamlit chat interface.
Copy code
User Input ➜ Python (subprocess) ➜ Ollama ➜ Mistral Model ➜ Response ➜ Streamlit UI
🖼️ Screenshot

🧑‍💻 About the Author
Qudus
A student and developer exploring computational mathematics, finance, and artificial intelligence.
💼 Connect with me on https://www.linkedin.com/in/qudus-bawa-allah-a226a5242/
