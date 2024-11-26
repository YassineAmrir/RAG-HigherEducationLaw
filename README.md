# Retrieval-Augmented Generation (RAG) for "La loi n° 01-00 portant organisation de l'enseignement supérieur"

This project integrates **Retrieval-Augmented Generation (RAG)** to facilitate the query and generation of contextual responses from the document **"La loi n° 01-00 portant organisation de l'enseignement supérieur"**. By combining a retrieval system with a generative model, this tool aims to enhance the ability to extract and generate relevant information from legal texts.

## Table of Contents

- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Key Features](#key-features)
- [Technologies Used](#technologies-used)
- [License](#license)

## Project Overview

This project applies the **Retrieval-Augmented Generation (RAG)** model, which is designed to efficiently query large legal documents and generate insightful and relevant responses based on the retrieved sections. The project focuses on **"La loi n° 01-00 portant organisation de l'enseignement supérieur"**, a key legal text related to higher education in France.

By leveraging retrieval models to fetch relevant document sections and a generative model to process these sections into human-readable responses, the project allows users to query the law for specific sections, explanations, and more.

## Objectives

- Develop a system that can retrieve relevant sections from a large legal document based on user queries.
- Use **generative models** to create contextually accurate responses based on the retrieved content.
- Create an efficient and scalable retrieval system using **FAISS** (Facebook AI Similarity Search) for fast document indexing.
- Enable users to interact with the law text through natural language queries.

## Key Features

- **Document Querying**: Automatically fetch relevant sections of the law document based on user input.
- **Text Generation**: Generate answers, summaries, or explanations based on the context of the retrieved document.
- **FAISS Integration**: Use **FAISS** to index and search through large amounts of legal text, enabling quick and accurate retrieval of relevant document sections.
- **Contextual Understanding**: Utilize **transformer-based models** to ensure the generation of accurate, context-aware responses.

## Technologies Used

- **Natural Language Processing (NLP)**: For text analysis and generation.
- **Retrieval-Augmented Generation (RAG)**: To combine information retrieval with natural language generation.
- **FAISS**: For fast similarity search and document indexing.
- **Python**: Programming language for implementing the solution.
- **Hugging Face Transformers**: Pre-trained models for natural language understanding and generation.
- **dotenv**: For secure environment variable management (e.g., API keys).
- **pandas**: For data manipulation and processing.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
