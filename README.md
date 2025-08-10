<p align="center">
  <img src="Langchain_using_gemini_API.png" alt="🦜🔗 LangChain using Gemini API" width="800">
</p>

# langchain-rag-tutorial

# LangChain + Google Gemini Learning Journey

This repository documents my **step-by-step learning path** for mastering the [LangChain](https://www.langchain.com/) framework, with **Google Gemini** as the LLM backend.  
It is designed as a reproducible set of **Colab/Jupyter notebooks**, progressing from fundamentals to an **end-to-end RAG Agent Capstone Project**.

---

## 📚 Lessons Overview

| #  | Lesson | Key Concepts | Notebook |
|----|--------|--------------|----------|
| 1  | Intro to LangChain & Gemini Setup | API setup, first LLM call | `Lesson_01.ipynb` |
| 2  | Prompt Templates | Variables, `.format()`, chaining with model | `Lesson_02.ipynb` |
| 3  | LLM Chains | `LLMChain`, combining prompts and models | `Lesson_03.ipynb` |
| 4  | Memory in Chains | `ConversationSummaryMemory` | `Lesson_04.ipynb` |
| 5  | Sequential Chains | `SimpleSequentialChain`, multi-step workflows | `Lesson_05.ipynb` |
| 6  | Agents & Tools | `Tool`, `StructuredTool`, Zero-shot agents | `Lesson_06.ipynb` |
| 7  | Tool vs Structured Tool | Pydantic schemas, typed arguments | `Lesson_07.ipynb` |
| 8  | Document Loading & Splitting | `TextLoader`, `PyPDFLoader`, `WebBaseLoader` | `Lesson_08.ipynb` |
| 9  | Embeddings & FAISS Vector Store | `GoogleGenerativeAIEmbeddings`, `FAISS` search | `Lesson_09.ipynb` |
| 10 | Retrieval-Augmented Generation | Retriever + Prompt + LLM | `Lesson_10.ipynb` |
| 11 | **Capstone: RAG Agent** | Custom knowledge base, tool integration | `Lesson_11.ipynb` |

---

## 🛠️ Tech Stack

- **LLM:** Google Gemini (via `langchain_google_genai`)
- **Framework:** LangChain
- **Vector Store:** FAISS
- **Document Processing:** LangChain Document Loaders, RecursiveCharacterTextSplitter
- **Environment:** Google Colab / Jupyter
- **Languages:** Python 3.11

---

## 🚀 Running the Notebooks
1. Clone the repo
2. Open in Google Colab or Jupyter
3. Add your `GEMINI_API_KEY` as an environment variable
4. Run the notebooks in order — each lesson builds on the previous

---

## ✏️ Author
[Sudeep Kurian](https://www.linkedin.com/in/sudeep-kurian-75721614b) 
---

**Disclaimer:** This project is for educational purposes, showcasing my LangChain learning path and hands-on with Google Gemini.
