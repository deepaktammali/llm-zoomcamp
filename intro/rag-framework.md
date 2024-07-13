# RAG Framework

RAG stands for `Retrieval Augmented Generation`  
Retrieval - We search for the documents and get relevant documents  
Generation - We feed the original user query and the retrieved documents to the llm  

In this process the retrieval source (The knowledge base) could be anything - it could be a vector store, search index or any database. The generation could be done with the help of an llm. The context would help/aid the llm with in the process of generating the correct response.