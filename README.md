
# 📚 LangChain Vector Store with ChromaDB

A practical project demonstrating how to use **LangChain** with **Chroma** vector database for building scalable document retrieval systems. This hands-on project focuses on storing and retrieving vectorized document chunks, enabling effective semantic search in GenAI-powered applications.

---

## 🚀 Objective

To integrate a vector database (ChromaDB) into a LangChain-based pipeline for processing and querying documents using embeddings and efficient chunk management.

---

## 🛠️ Tech Stack

- 🧠 LangChain
- 🧪 ChromaDB (Vector Store)
- 🔗 LangChain Community Modules
- 📄 PyMuPDF (PDF loading)
- 🧵 LangChain TextSplitters
- 🔐 OpenAI API (for embeddings)
- 🐍 Python 3.11+

---

## 📂 Project Structure



---

## 🔧 How it Works

1. **PDF Loading**  
   - Uses `PyMuPDFLoader` to ingest content from a PDF file.

2. **Text Splitting**  
   - Applies `RecursiveCharacterTextSplitter` to chunk large documents into manageable text segments.

3. **Embeddings**  
   - Embeds each chunk using OpenAI's embedding model via LangChain.

4. **Chroma Vector Store**  
   - Stores embeddings in **Chroma**, a local in-memory vector database.

5. **Querying**  
   - Performs semantic search over stored chunks to retrieve relevant document sections.

---

## 💡 Skills Gained

- Vector Store configuration (Chroma)
- Document chunking with TextSplitters
- Embedding generation with OpenAI
- LangChain integration for data pipelines
- Semantic search implementation
- Python environment setup and dependency management

---

## 📦 Installation

```bash
git clone https://github.com/GovindaTak/langchain-vectorstore-chroma-demo.git
cd langchain-vectorstore-chroma-demo
````

Set your OpenAI API Key securely:

```python
import os
os.environ["OPENAI_API_KEY"] = "your-api-key"
```

---

## 🧪 Run the Demo

Use file to walk through:

* Loading the GenAI PDF
* Chunking and embedding
* Storing in and querying Chroma

---

## 📜 License

This project is open-source under the MIT License.

---

## 🙌 Special Thanks

This project was built as part of my ongoing learning journey in LangChain and Retrieval-Augmented Generation. Thanks to the LangChain community for extensive documentation and the open-source ecosystem for enabling experimentation.

---

## ✍️ Author

**Govinda Tak**
🧠 Exploring GenAI, RAG Systems & Vector DBs
📧 [govindatak19@gmail.com](mailto:govindatak19@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/govindatak)
