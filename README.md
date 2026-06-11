# Qwen LangChain Chatbot

A conversational AI chatbot built using the Qwen Large Language Model, Hugging Face Inference API, and LangChain. The chatbot supports multi-turn conversations by maintaining chat history, enabling context-aware and natural interactions.

## Features

* Qwen LLM via Hugging Face Inference API
* LangChain Integration
* Conversation Memory
* Multi-turn Chat Support
* Context-Aware Responses
* Kaggle Notebook Compatible
* Lightweight Implementation (No UI Required)

## Tech Stack

* Python
* LangChain
* Hugging Face Inference API
* Qwen 2.5
* Kaggle Notebook

## Project Structure

```text
qwen-langchain-chatbot/
│
├── notebook/
│   └── qwen_chatbot.ipynb
│
├── images/
│   └── chatbot_demo.png
│
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/Sakhawathossen04/qwen-langchain-chatbot.git
cd qwen-langchain-chatbot
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Hugging Face API Setup

Create a Hugging Face access token and store it securely.

For Kaggle:

1. Open Kaggle Secrets
2. Create a secret named:

```text
HF_TOKEN
```

3. Paste your Hugging Face API token as the value.

## Usage

Run the notebook and execute all cells.

Example:

```python
You: Hello
Bot: Hi! How can I help you today?

You: What is LangChain?
Bot: LangChain is a framework for building applications powered by large language models.
```

## Key Components

### Qwen Model

The chatbot uses:

```text
Qwen/Qwen2.5-7B-Instruct
```

through the Hugging Face Inference API.

### LangChain Memory

Conversation history is stored using LangChain's chat history utilities, allowing the model to retain context across multiple turns.

## Future Improvements

* Streamlit Web Interface
* Gradio Deployment
* Persistent Database Memory
* RAG Integration
* Vector Database Support
* Tool Calling Agents

## License

This project is released under the MIT License.

## Author

Developed as a learning project to explore conversational AI systems using Qwen, Hugging Face, and LangChain.

---

### requirements.txt

langchain
langchain-core
langchain-huggingface
huggingface_hub

---

### .gitignore

.env
*.env
**pycache**/
.ipynb_checkpoints/
.vscode/
.DS_Store

---

### Git Commands

```bash
git init

git add .

git commit -m "Initial commit: Qwen LangChain Chatbot"

git branch -M main

git remote add origin https://github.com/your-username/qwen-langchain-chatbot.git

git push -u origin main
```
