# VehicleGPT – AI Powered Vehicle Recommendation Chatbot

## Overview

VehicleGPT is an AI-powered vehicle recommendation chatbot developed using Generative AI and Retrieval-Augmented Generation (RAG) concepts. The system allows users to ask questions in natural language and receive intelligent vehicle recommendations from a real-world vehicle dataset.

The project combines semantic search, vector embeddings, FAISS indexing, and Large Language Models (LLMs) to create a smart chatbot capable of understanding user requirements and retrieving the most relevant vehicle information.

This project demonstrates the practical implementation of:
- Generative AI
- Natural Language Processing (NLP)
- Semantic Search
- Vector Databases
- Retrieval-Augmented Generation (RAG)

---

# Problem Statement

Traditional vehicle search systems rely on filters and keyword matching, which often fail to understand user intent effectively.

This project solves the problem by building an AI chatbot that:
- Understands natural language queries
- Retrieves semantically relevant vehicles
- Generates human-like responses
- Provides intelligent vehicle recommendations

---

# Objectives

- Build an AI-based vehicle recommendation chatbot
- Implement semantic similarity search using embeddings
- Store embeddings efficiently using FAISS
- Generate intelligent responses using transformer models
- Enable natural language interaction with vehicle data

---

# Features

- AI-powered chatbot interface
- Natural language querying
- Vehicle recommendation system
- Semantic search using embeddings
- Fast vector similarity search using FAISS
- Context-aware response generation
- Real-world vehicle dataset support
- Interactive conversational system

---

# Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data preprocessing |
| NumPy | Numerical computations |
| Sentence Transformers | Text embeddings |
| FAISS | Vector similarity search |
| Hugging Face Transformers | Text generation |
| Google Colab | Development environment |
| NLP | Natural language processing |

---

# Dataset Information

The project uses a vehicle dataset containing:
- Manufacturer
- Model
- Year
- Price
- Fuel type
- Transmission
- Condition
- Odometer reading
- Vehicle type
- Drive type
- Paint color
- State information

The dataset is converted into textual documents for semantic retrieval.

---

# Project Architecture

```text
User Query
    ↓
Text Embedding Generation
    ↓
FAISS Vector Search
    ↓
Relevant Vehicle Retrieval
    ↓
Context Generation
    ↓
LLM Response Generation
    ↓
Final Chatbot Response
```

---

# Working Process

## Step 1: Data Loading
The vehicle dataset is loaded using Pandas.

## Step 2: Data Preprocessing
Missing values are removed and important columns are selected.

## Step 3: Text Conversion
Each vehicle record is converted into descriptive text.

## Step 4: Embedding Generation
Sentence Transformer model generates vector embeddings.

## Step 5: FAISS Indexing
Embeddings are stored in FAISS for efficient retrieval.

## Step 6: Query Processing
User queries are converted into embeddings.

## Step 7: Semantic Retrieval
Most relevant vehicle records are retrieved using similarity search.

## Step 8: Response Generation
Transformer model generates intelligent chatbot responses.

---

# Installation

## Clone Repository

```bash
git clone https://github.com/your-username/VehicleGPT.git
```

## Navigate to Project Folder

```bash
cd VehicleGPT
```

## Install Dependencies

```bash
pip install sentence-transformers
pip install faiss-cpu
pip install transformers
pip install pandas
pip install numpy
```

---

# Running the Project

## Open Google Colab

Upload:
- Python notebook
- vehicles.csv dataset

Run all cells sequentially.

---

# Sample Queries

```text
Suggest fuel efficient cars under $15000
```

```text
Show automatic transmission SUVs
```

```text
Recommend low mileage Honda cars
```

```text
Find family vehicles with good condition
```

---

# Sample Output

```text
Based on your requirements, here are some suitable vehicles:
1. Honda Civic 2018
2. Toyota Corolla 2019
3. Hyundai Elantra 2017
```

---

# Advantages

- Intelligent semantic search
- Faster retrieval using FAISS
- Better than keyword-based systems
- Human-like conversational interaction
- Scalable for large datasets
- Easy integration with web applications

---

# Future Enhancements

- Web application deployment
- Voice-enabled chatbot
- Advanced filtering
- Multi-language support
- Real-time vehicle APIs
- Personalized recommendations
- Fine-tuned LLM integration

---

# Applications

- Vehicle recommendation systems
- Automobile e-commerce platforms
- AI customer support systems
- Smart dealership assistants
- Automotive analytics platforms

---

# Learning Outcomes

This project helps understand:
- Generative AI concepts
- Vector databases
- Semantic search
- NLP pipelines
- Transformer models
- RAG architecture
- Embedding generation
- Information retrieval systems

---

# Conclusion

VehicleGPT demonstrates how Generative AI and semantic search can improve traditional vehicle recommendation systems. By combining embeddings, FAISS, and transformer models, the chatbot delivers intelligent and context-aware vehicle suggestions through natural language interaction.

---

# Author

Developed as a Generative AI and NLP project using Python, FAISS, Sentence Transformers, and Hugging Face Transformers.

---

# License

This project is developed for educational and learning purposes.
