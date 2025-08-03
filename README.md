# Civic Service Chatbot (NDMC-Themed)

A personal AI chatbot project built during my internship, themed around NDMC services. It helps simulate how a local government assistant might respond to citizen queries about sanitation, complaints, and general services. No official NDMC data was used—mock datasets were created for demonstration.

## Features
- Natural language interface for mock civic queries
- LangChain agent powered by Ollama (LLM)
- Simple and interactive Streamlit UI
- Uses synthetic data for realistic interactions

## Tech Stack
- Python
- Ollama (LLM)
- LangChain
- Streamlit
- spaCy
- Pandas

## How to Run Locally

1. Clone the repository:
```bash
git clone https://github.com/your-username/civic-chatbot.git
cd civic-chatbot
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Start Ollama:
```bash
ollama run llama3
```

4. Launch the chatbot:
```bash
streamlit run app.py
```
