We have implemented a RAG Pipeline for PDF Question-answering using Meta Llama , Langchain and FAISS Vector Database.

* We have accessed LLM (Meta Llama3-8b) functionality through Groq
* Used PyPDFDirectoryLoader for loading the source document
* RecursiveCharacterTextSplitter for splitting the documents into chunks
* GoogleGenerativeAIEmbeddings for creating the embeddings
* FAISS Vector DB to store the embeddings
* Langchain's create_retrieval_chain to retreive relevant matching documents from the Vector DB as per user prompt

  ![image](https://github.com/user-attachments/assets/edeb7c80-a42a-4a17-a1cd-5427fa1cdd8f)
