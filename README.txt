
Groq LLM Chatbot

This is a simple chatbot powered by a Large Language Model (LLM) using the Groq API. The project includes a FastAPI backend and a web interface for chatting with the model.

Features
- LLM integration using Groq API
- Backend built with FastAPI
- Clean web UI for user input and bot response
- Real-time text generation

Project Structure
groq-chatbot/
│
├── main.py              # FastAPI backend logic

       
├── static/  # Chat interface
    └── index.html              # Optional CSS/JS files
├── .env                 # Contains Groq API Key
├── requirements.txt     # Python dependencies
└── README.txt           # Project documentation

How to Run
1. Install dependencies

   pip install -r requirements.txt

2. Set your Groq API key

   Create a .env file and add your API key:

   GROQ_API_KEY=your_groq_api_key_here

3. Start the server

   uvicorn main:app --reload

4. Open in browser

   http://localhost:8000



Technologies Used
- FastAPI
- HTML + JavaScript
- Groq API
- Python
