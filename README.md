# RAG-Text-Generator
This Repository Contains the Implementation of my 2nd Final Project for the Course Fundamentals of Natural Language Processing taken during the Spring 2024 Semester at the School of Computer Engineering at Iran University of Science and Technology.

## Project Description
- This project is designed with the aim of improving answering questions related to organizational reports by RAG. The use of this technology makes it possible to provide accurate and current answers to users' questions based on the content in organizational reports.

## Data Extraction:
- The libraries `pandas` and `docx2txt` are used to extract questions from `Word` and `Excel` files.

## Embedding and Search Models:
- The model `LaBSE (Language-agnostic BERT Sentence Embedding)` is used to create embeddings.
- The `VectorStoreIndex` is used to store and search embeddings.

## Natural Language Processing Model:
- The model `Meta-Llama-3-8B-Instruct` from `HuggingFace` is used to generate answers to questions.
- These models, using the extracted data from the files, create embeddings and generate answers to the questions.

## Results and Evaluations:
- The system's response to 40 questions are stored in the file `ModelGenerations.xlsx`.

## Document and Files
- The Document of the Project can found [here](https://github.com/iMahdiGhazavi/RAG-Text-Generator/blob/main/Document.pdf) *This ducument is in Persian.*
- The code implementations are available at the file [NLP_Final_Project_2.ipynb](https://github.com/iMahdiGhazavi/RAG-Text-Generator/blob/main/NLP_Final_Project_2.ipynb)
- The Project Proposal can be found [here](https://github.com/iMahdiGhazavi/RAG-Text-Generator/blob/main/RAG%20Project.pdf) *This ducument is in Persian.*
