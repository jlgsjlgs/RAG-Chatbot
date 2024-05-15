# RAG Chatbot

This web application comprises of the following components:

- **ReactJS** Frontend that allows users to interact with the chatbot
- Embedding script (**LangChain Python**) that performs the necessary pre-processing to enhance the knowledge base
- LLM API middleware (**LangChain Python & Flask**) that facilitates communication between the frontend and the LLM API
- Microservice (**ExpressJS**) that facilitates writing and updating of chat histories to database
- **MongoDB** instance for storing chat histories
- **Azure CosmosDB** for storing embeddings & performing vector search

![Architecture Overview][https://github.com/jlgsjlgs/RAG-Chatbot/blob/de6636bf76a380dcbaf6dcf5ba5f27e26a8c5e60/architecture.png]
