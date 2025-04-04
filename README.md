# RAGify-Science-Grades-1-10-A-Smart-AI-Powered-Learning-Companion


This project is the first in our **RAG Series**, aimed at creating an AI-powered learning companion for **Classes 1 to 10**, built using **Retrieval-Augmented Generation (RAG)** technology. It simplifies science across grade levels, making it easier to explore, ask, and understand topics. In this basic project, we demonstrate the core concepts of RAG by integrating **LLama 3.2** and utilizing an open-source framework to merge and manage databases effectively. The steps include:

1. Database Creation  We’ve gathered science content for each grade (Class 1 to 10) and merged them into a unified dataset.
2. Data Preprocessing: The content is then chunked into smaller, manageable text pieces for efficient retrieval.
3. Vectorization: We use **CountVectorizer** to convert the text chunks into vector format.
4. Cosine Similarity: After vectorizing the data, cosine similarity is computed to match user queries with the most relevant text chunks.
5. Generation: Finally, we integrate the results with **LLama 3.2** for enhanced response generation based on the user’s question.

This project serves as a basic foundation to understand the RAG workflow, which can be scaled and enhanced in more advanced projects with further integrations of open-source tools and databases.

