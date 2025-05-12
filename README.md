# 🧠 Multi-Agent-RAG-System-for-Intelligent-Query-Routing-using-LangChain-LangGraph-and-Astra-DB 

This project leverages **LangChain**, **LangGraph**, **Astra DB**, and **Wikipedia** to create an intelligent system for **routing user queries**. Based on the context of the question, the system dynamically routes queries to either a **Vectorstore Retrieval-Augmented Generation (RAG)** system or a **Wikipedia Search** for the best answer.

---

## 🛠️ Installation

To set up the project, install the required libraries using the following commands:
- **LangChain**, **LangGraph**, **Astra DB**, **Wikipedia**, and other necessary dependencies.

---

## 🔐 Setup Astra DB Connection

Configure the connection to Astra DB using the provided **application token** and **database ID**.

---

## 📄 Load and Embed Documents

The project demonstrates loading documents from URLs, splitting them into chunks, and embedding them into a **Vectorstore** for later retrieval using **HuggingFace Embeddings**.

---

## 🧠 HuggingFace Embeddings + Astra Vector Store

Utilize **HuggingFace Embeddings** and **Astra DB** to store the document embeddings, allowing for efficient document retrieval during query processing.

---

## 🔄 Test Retriever

Test the query retriever by invoking questions to fetch relevant documents from the **Vectorstore** based on the question content.

---

## 🧭 Build Query Router

Create a routing system using **LangChain**, which decides whether a query should be answered by the **Vectorstore RAG system** or **Wikipedia Search** based on the question's context.

---

## 📚 Wikipedia & Arxiv Tools

Incorporate external tools like **Wikipedia API** and **Arxiv API** to handle queries related to general knowledge and research papers, respectively.

---

## ⚙️ Graph State & Functions

The routing process is managed by a **Graph** that uses the current state and decisions made by multiple agents (RAG system or Wikipedia) to guide the query.

---

## 🧩 Build LangGraph App

Develop a **LangGraph** workflow to handle query routing and processing by adding conditional edges and nodes, facilitating decision-making between the different query resolution paths.

---

## 🚀 Run the Graph

Test the system with example queries to demonstrate how the graph processes and routes them to the appropriate sources, either the **Vectorstore RAG system** or **Wikipedia Search**.

---

## ✅ Summary

This project demonstrates:
- Document ingestion and embedding using **LangChain**
- Vector-based retrieval with **AstraDB**
- Dynamic query routing to either **RAG** or **Wikipedia**
- Creating a **LangGraph** to manage decision-making
