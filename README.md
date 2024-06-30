# Retrieval-Augmented Generation System for Insurance Policy Chatbot

## Project Overview
This project develops a Retrieval-Augmented Generation (RAG) system using the LlamaIndex or LangChain framework to create a chatbot capable of answering questions about insurance policy documents. The system aims to improve accessibility and understanding of insurance policies by providing accurate and relevant responses to user queries.

## Project Goals
- Develop a chatbot to assist users in understanding insurance policies.
- Combine information retrieval and natural language generation techniques.
- Enhance accessibility and comprehension of complex insurance documents.

## Data Sources
- Insurance policy PDF documents.

## Design Choices
- **Data Preprocessing**: `InsurancePolicyPDFLoader` class for loading, cleaning text, extracting metadata, and splitting documents.
- **Embeddings**: `GoogleGenerativeAIEmbeddings` class for generating dense vector representations.
- **Vector Storage**: `Chroma` class for storing embeddings and enabling efficient similarity search.
- **Query Processing**: `GeminiRAG` class for processing user queries and retrieving relevant documents.
- **Response Generation**: `GoogleGenerativeAI` language model for generating responses.
- **Interactive Interface**: `initialize_conv` function for user interaction.

## Challenges Faced
- Complexity and detail of insurance documents.
- Ensuring accuracy and relevance of generated responses.
- Designing a scalable system.
- Implementing incremental updates for new or modified documents.

## System Design Flowchart
![System Design Flowchart](path_to_flowchart_image)


