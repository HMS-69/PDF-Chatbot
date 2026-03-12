📚 Chat with Multiple PDFs using LangChain + Groq

A Streamlit-based AI application that allows users to upload multiple PDF documents and chat with them.
The app extracts text from PDFs, converts it into embeddings, stores it in a FAISS vector database, and uses a Groq-powered LLM to answer questions based on the document content.

🚀 Features

📄 Upload multiple PDF documents

🔍 Extract and process text from PDFs

✂️ Split documents into manageable chunks

🧠 Generate embeddings using HuggingFace

⚡ Store embeddings in FAISS vector database

💬 Conversational Q&A with document context

🧾 Chat history maintained using LangChain memory

🌐 Interactive UI built with Streamlit

🛠️ Tech Stack

Python

Streamlit

LangChain

Groq LLM

FAISS Vector Database

HuggingFace Embeddings

PyPDF2

📂 Project Structure
project-folder
│
├── app.py                # Main Streamlit application
├── htmlTemplate.py       # HTML templates for chat UI
├── requirements.txt      # Project dependencies
├── .env                  # Environment variables (API keys)
└── README.md             # Project documentation
⚙️ Installation
1️⃣ Clone the Repository
git clone https://github.com/yourusername/pdf-chatbot.git
cd pdf-chatbot
2️⃣ Create Virtual Environment (Recommended)
python -m venv venv
venv\Scripts\activate

Mac/Linux

source venv/bin/activate
3️⃣ Install Dependencies
pip install -r requirements.txt
4️⃣ Setup Environment Variables

Create a .env file in the project root.

GROQ_API_KEY=your_api_key_here
▶️ Run the Application
streamlit run app.py

The app will open in your browser:

http://localhost:8501
📖 How It Works

User uploads one or more PDF documents

The app extracts text using PyPDF2

Text is split into chunks

Chunks are converted into embeddings using HuggingFace

Embeddings are stored in FAISS vector database

When a user asks a question:

Relevant chunks are retrieved

The Groq LLM generates a response

The conversation history is stored using LangChain Memory

💡 Example Use Cases

📚 Study material assistant

📑 Research paper Q&A

🧾 Document summarization

🏢 Company document search

📖 Book question answering

🔮 Future Improvements

Support for DOCX and TXT files

PDF summarization

Highlight source references

Chat export

Improved UI

🤝 Contributing

Contributions are welcome!

Fork the repository

Create a new branch

Commit your changes

Submit a Pull Request

📜 License

This project is licensed under the MIT License.

👨‍💻 Author

Developed by Himanshu
