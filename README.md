# 🤖 GURU Chatbot

A conversational AI chatbot powered by a local **Ollama** model (`GURU`), with a clean web interface built using **Gradio**

---

## 📋 Features

- 💬 **Conversational memory** — maintains chat history across turns
- 🎨 **Modern UI theme** — clean, modern Gradio interface
- ⚡ **Local inference** — runs fully offline via Ollama (no API keys needed)
- 🖊️ **Multi-line prompt input** — easy to type longer prompts


## 📁 Project Structure

```
guru-chatbot/
│
├── app.py              # Main application file
├── requirements.txt    # Python dependencies
├── .gitignore          # Files to exclude from Git
└── README.md           # Project documentation
```

---

## ⚙️ Configuration

In `app.py`, you can change:

| Setting | Default | Description |
|---|---|---|
| `url` | `http://localhost:11434/api/generate` | Ollama API endpoint |
| `model` | `"GURU"` | The Ollama model to use |

---

## 📦 Dependencies

- [langchain](https://www.langchain.com/) — Framework for building LLM-powered applications
- [gradio](https://gradio.app/) — Web UI framework
- [requests](https://docs.python-requests.org/) — HTTP client for Ollama API

