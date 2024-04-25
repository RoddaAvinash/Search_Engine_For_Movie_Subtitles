## Project Title: Enhancing Search Engine Relevance for Video Subtitles
## Overview
In the digital content landscape, effective search engines are essential for connecting users with relevant information. This project focuses on enhancing search relevance for video subtitles, to improve the accessibility of video content. By leveraging natural language processing (NLP) and machine learning (ML) techniques, we aim to develop an advanced search engine algorithm that delivers accurate and meaningful search results.

## Objective
The main objective of this project is to develop an algorithm that efficiently retrieves subtitles based on user queries, with a specific emphasis on subtitle content. By comparing user queries against video subtitle documents, we aim to improve the relevance and accuracy of search results.

## Key Features
Data Ingestion and Preprocessing: Reading and decoding subtitle data, applying appropriate cleaning steps, and preprocessing the data for further analysis.
Vectorization Techniques: Experimenting with Bag-of-Words (BOW), TF-IDF, and BERT-based SentenceTransformers for generating text vectors of subtitle documents.
Document Chunking: Addressing the challenge of embedding large documents by dividing them into smaller, manageable chunks to mitigate information loss.
Cosine Similarity Calculation: Computing cosine similarity between document embeddings and user query embeddings to determine relevance.
ChromaDB Database: Storing embeddings in a ChromaDB database for efficient retrieval.
## How to Use
Data Ingestion: Clone the repository and navigate to the data directory. Follow the instructions in the README.txt file to understand the structure of the provided subtitle database.
Preprocessing and Vectorization: Use the provided scripts to preprocess subtitle data and experiment with different vectorization techniques.
Document Chunking: Implement the document chunking algorithm to divide large subtitle documents into smaller chunks.
Cosine Similarity Calculation: Calculate cosine similarity between document embeddings and user query embeddings to retrieve relevant documents.
ChromaDB Integration: Store embeddings in a ChromaDB database for efficient retrieval.
## Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these guidelines:

## Fork the repository
Create a new branch
Make your changes
Submit a pull request
## License
This project is licensed under the MIT License. See the LICENSE.md file for more details.

## Acknowledgements
Special thanks to Innomatics Research Labs for their support and guidance throughout this project.
Gratitude to Kanav Bansal, Chief Data Scientist at Innomatics Research Labs, for his valuable insights and mentorship.

