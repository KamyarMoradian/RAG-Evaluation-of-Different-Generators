# RAG - Evaluation of Different Generators

## Overview

This repository contains the final project for the "Introduction to Natural Language Processing" course at the IUST Computer Engineering Department. The project explores the concept of Retrieval-Augmented Generation (RAG), a method that enhances the capabilities of large language models by integrating retrieval-based techniques to generate more accurate and contextually relevant responses.

## Project Context

- **Course**: Introduction to Natural Language Processing (NLP)
- **Institution**: IUST Computer Engineering Department
- **Instructor**: Dr. Marzieh Davoodabadi Farahani
- **Teaching Assistant**: Erfan Moosavi Monazzah

## What is RAG?

RAG stands for Retrieval-Augmented Generation, a technique that addresses some of the limitations of Large Language Models (LLMs) such as ChatGPT. While LLMs are trained on extensive datasets, they can still produce incorrect or outdated information. RAG improves this by retrieving relevant documents or data from a large corpus based on the user's query and then generating a response using both the retrieved information and the generative model.

## Models Used

### Generator Models

The following models were used as the generator part of the RAG system:

- **Meta-Llama-3-8B-Instruct** (`NousResearch/Meta-Llama-3-8B-Instruct`): A large-scale language model optimized for generating instructive and helpful content.
- **Qwen-2-7B-Instruct** (`Qwen/Qwen2-7B-Instruct`): A powerful generative model designed for high-quality instruction-based responses.
- **Mistral-7B-Instruct-v0.3** (`mistralai/Mistral-7B-Instruct-v0.3`): Another strong generative model focused on producing accurate and concise instructive responses.

### Evaluation Model

The outputs of the models were evaluated using:

- **GTE-Large-EN-v1.5** (`Alibaba-NLP/gte-large-en-v1.5`): This model was employed to assess the quality and relevance of the generated responses, ensuring the outputs meet the required standards.

## Dataset Used

The project utilized the following dataset:

- **AI Medical Chatbot Dataset** (`ruslanmv/ai-medical-chatbot`): A specialized dataset containing medical-related conversational data, ideal for testing the RAG model's ability to handle domain-specific queries and generate accurate, contextually relevant responses.

## Project Structure

The project is implemented in a Jupyter notebook and covers the following:

1. **Introduction to RAG**: A conceptual overview of RAG, its importance, and how it compares to traditional LLMs.
2. **Setup and Installation**: Instructions for setting up the environment, including the installation of necessary Python libraries.
3. **Implementation**: Code examples demonstrating how to implement a basic RAG model using libraries like `transformers`, `sentence-transformers`, and `datasets`.
4. **Experiments and Results**: Testing the model with various queries and analyzing the results.
