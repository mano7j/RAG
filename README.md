📚 Chat with PDF using RAG & Llama 3
Streamlit App Python LangChain Groq

This is a Retrieval-Augmented Generation (RAG) application built with Streamlit and LangChain. It allows users to upload a PDF document and chat with it using the Groq API (Llama 3) for extremely fast inference.

Check out live project here - https://falyfktf3qyiruuzosbtfm.streamlit.app/

🚀 Features
RAG Pipeline: accurately retrieves context from uploaded documents.
Groq API Integration: Uses llama-3.3-70b for high-speed, free/low-cost responses.
Vector Search: Uses FAISS and HuggingFace Embeddings for semantic search.
Memory: Maintains conversation history so you can ask follow-up questions.
Secure: API Keys are managed via Streamlit Secrets (no hardcoding).
🛠️ Tech Stack
Frontend: Streamlit
LLM: Groq (Llama 3.3)
Embeddings: sentence-transformers/all-MiniLm-L6-v2
Vector Store: FAISS
Orchestration: LangChain
📦 Installation & Local Run
Clone the repository

git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)
cd YOUR_REPO_NAME
Install dependencies It is crucial to install the specific versions to avoid conflicts:

pip install -r requirements.txt
Run the App

streamlit run app.py
Screenshots

image
🔑 Configuration
To run this app, you need a Groq API Key.

Get your free key from console.groq.com.
Local Run: The app will ask for the key in the sidebar if not found in environment variables.
Deployment: Set the key in Streamlit "Secrets" settings as GROQ_API_KEY.
📂 Project Structure
├── app.py # Main application logic ├── requirements.txt # Dependencies with specific versions └── README.md # Documentation
