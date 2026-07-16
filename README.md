# Mental-Help-Assistant
RAG-based project to help people on mental health questions based on the Manual of Mental Disorders

The objective of this project is to gain practical experience in building a Retrieval-Augmented Generation (RAG) pipeline. You will integrate state-of-the-art Large Language Models (LLMs) from Hugging Face with Milvus, an open-source vector database, to create an intelligent question-answering system capable of retrieving relevant information and generating accurate, contextual answers.

Subject: Mental Health Assistant

Idea: Based on the scientific books, this chat-bot will provide guidance to the users with mental health questions. The problem with the psychology right now is that it is at it’s pick of popularity, and high demand, there is a lack of specialists, especially for people with lower income. Difficulty is to find relevant recourses to rely on and trust upon, therefore our assistant will use reliable resources to help people with their issues. Goal of the assistant is to navigate users with the questions they may have about their mental health. 

Example of use: user has a question about a particular disorder/ disease, and the chat-bot gives a brief explanation on this disease.

The project involves the following technical steps:

1. Data Preparation
- Select or create a dataset of your choice, relevant to the project's domain (e.g., academic articles, FAQs, documentation).
- Preprocess and structure the data for embedding generation.
  
2. Embedding Generation
- Use embedding models from Hugging Face (e.g., Sentence Transformers) to convert textual data into semantic vectors.

3. Vector Database Setup with Milvus
- Deploy Milvus locally.
- Store embeddings generated from the dataset into Milvus for efficient retrieval.

4. Integration with Hugging Face LLM
- Choose an appropriate LLM from Hugging Face's library.
- Implement a prompt engineering strategy to effectively combine retrieved contexts with user queries.

5. System Implementation
- Build the end-to-end pipeline: query → retrieval from Milvus → prompt construction → answer generation by Hugging Face LLM.

6. Evaluation and Optimization
- Assess retrieval accuracy, response quality, and latency.
- Optimize parameters and components based on evaluation results.
- Experiment with several embedding models and LLMs.
- Experiment with various prompt templates.
