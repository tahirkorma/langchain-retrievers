# LangChain Retrievers  

This repository demonstrates different **retrieval methods** available in [LangChain](https://www.langchain.com/). Retrievers play a crucial role in **retrieval-augmented generation (RAG)** pipelines by fetching the most relevant context for Large Language Models (LLMs).  

The code covers the following retrievers:  

- **Wikipedia Retriever**  
- **Vector Store Retriever**  
- **Maximal Marginal Relevance (MMR) Retriever**  
- **MultiQuery Retriever**  
- **Contextual Compression Retriever**  

---

## 🚀 Use Cases  

Retrievers are useful in scenarios where an LLM needs access to external knowledge, such as:  

- **Question Answering** from knowledge bases.  
- **Chatbots** with contextual memory.  
- **Summarization** of large document sets.  
- **Semantic Search** over structured/unstructured data.  
- **RAG Pipelines** for grounding LLMs with external sources.  

---

## 📚 Retrievers Covered in this Repository  

### 1. **Wikipedia Retriever**  
- Retrieves relevant passages directly from **Wikipedia**.  
- Useful for factual Q&A and general-purpose information retrieval.  
- Great starting point for lightweight experiments.  

### 2. **Vector Store Retriever**  
- Uses a **vector database** (like FAISS, Chroma, Pinecone, etc.) to store embeddings.  
- Retrieves documents based on **semantic similarity** rather than keyword search.  
- Essential for building scalable semantic search systems.  

### 3. **Maximal Marginal Relevance (MMR) Retriever**  
- Balances **relevance** and **diversity** of retrieved results.  
- Reduces redundancy by ensuring documents aren’t too similar.  
- Ideal for summarization tasks or when variety of perspectives matters.  

### 4. **MultiQuery Retriever**  
- Generates multiple rephrasings of a user query.  
- Retrieves results for each variation and combines them.  
- Improves recall and ensures more comprehensive results.  

### 5. **Contextual Compression Retriever**  
- Compresses retrieved documents to keep only the **most relevant context**.  
- Uses an LLM or embeddings model to filter out irrelevant parts.  
- Useful when working with token-limited models or large documents.
