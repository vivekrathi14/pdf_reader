## Project Description
This project aims to create an interactive PDF reader that allows users to upload custom PDF files and interact with a chatbot capable of answering questions based on the content of the PDF. The chatbot utilizes the power of GPT-3.5/GPT-4 to provide meaningful responses by leveraging the context extracted from the PDF apply RAG (Retrieval Data Augmentation)

## Key Skills Learned:
1. Deep Learning: Using GPT models (GPT-3.5/GPT-4) for language generation and question-answering.
2. Natural Language Processing (NLP): Creating embeddings for text data and processing PDF content.
3. LangChain: Framework to seamlessly integrate NLP models and document processing into the application.
4. Prompt Engineering: Crafting effective prompts for GPT-3.5/GPT-4 to answer questions based on the extracted PDF content.
5. Streamlit: Building interactive web applications for user interaction.
6. Chroma: Used to create vector embeddings for the PDF content to facilitate search and retrieval.
7. Python Programming: Core language used for backend logic, API integration, and web development.

## Technologies:
1. LangChain: For creating embeddings and integrating with LLMs like GPT-3.5/GPT-4.
2. GPT-3.5/GPT-4: OpenAI language models for question-answering and text generation.
3. Chroma: Document retrieval system for creating embeddings and indexing PDF content.
4. Streamlit: Framework for building and deploying the frontend application.
5. HuggingFace Embeddings: Used for processing text embeddings of the PDF content.

## How to use?
1. Clone the repo
2. Create python env using requirements.txt
3. Create .env file with OPENAI_API_KEY & HUGGINGFACEHUB_API_TOKEN
4. Run the app using
```
streamlit run app.py
```



