# LLM Engineering Tutorial: (RAG, VLM, Multimodal, AI Assistant, KPIs)

A comprehensive, hands-on tutorial series covering the complete journey from LLM basics to production-ready RAG (Retrieval-Augmented Generation) systems. This tutorial emphasizes practical implementation, real-world challenges, and battle-tested solutions.

> **📐 For Math Enthusiasts**: If you love the mathematical foundations behind transformers, check out my companion repository [**Mathematics of Transformers**](https://github.com/esmaeil-rezaei/transformers-math). While it's not required for this tutorial, it provides deep dives into attention mechanisms, positional encodings, and the mathematical theory that makes LLMs work. This tutorial focuses on practical engineering and production systems.


## 📚 Table of Contents

- [Overview](#overview)
- [What You'll Learn](#what-youll-learn)
- [Tutorial Structure](#tutorial-structure)
- [Prerequisites](#prerequisites)
- [Installation](#installation)


## 🎯 Overview

This tutorial takes you from zero to hero in Large Language Model engineering. Starting with basic API calls and progressing through to production-grade RAG systems, you'll gain hands-on experience with:

- **Frontier Models**: OpenAI GPT-4, Anthropic Claude, and others
- **Open Source Models**: Hugging Face transformers, Ollama
- **RAG Systems**: Complete ingestion pipelines, vector databases, evaluation frameworks
- **Real-World Challenges**: PDF processing, data hygiene, multimodal AI

**Target Audience**: Developers, data scientists, and AI engineers who want to build production-ready LLM applications.


## 🚀 What You'll Learn

By completing this tutorial, you will be able to:

✅ **Set up and use** frontier LLM APIs (OpenAI, Anthropic, Google)  
✅ **Build interactive applications** with streaming, tool calling, and multimodal capabilities  
✅ **Work with open-source models** using Hugging Face and Ollama  
✅ **Select the right model** for your use case using benchmarks and practical evaluation  
✅ **Build production RAG systems** from scratch with proper chunking and embedding strategies  
✅ **Handle complex PDFs** with tables, images, multi-column layouts, and encoding issues  
✅ **Implement evaluation frameworks** to measure and improve RAG performance  
✅ **Deploy real-world solutions** with proper error handling, metadata tracking, and data cleaning


## 📖 Tutorial Structure
```
llm-tutorial/
│
├── 01_introduction_and_setup/          # Foundations & API Setup
├── 02_frontier_models_and_tools/       # Building with GPT-4, Claude, etc.
├── 03_open_source_foundations/         # Hugging Face & Model Internals
├── 04_model_selection_and_evaluation/  # Benchmarking & Choosing Models
├── 05_rag_and_vector_embedding/        # Core RAG Implementation
└── 06_rag_challenges_with_pdf/         # Production PDF Processing
```

## 📋 Prerequisites

- **Python 3.9+** (3.10 or 3.11 recommended)
- Basic Python programming knowledge
- Familiarity with Jupyter notebooks
- **API Keys** (at least one):
  - OpenAI API key (recommended for beginners)
  - Anthropic API key (optional)
  - Google AI API key (optional)

**No prior LLM experience required!** This tutorial is designed for learners at all levels.


## 🔧 Installation

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/llm-tutorial.git
cd llm-tutorial
```

### 2. Create Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Set Up Environment Variables

Create a `.env` file in the root directory:
```bash
OPENAI_API_KEY=your_openai_key_here
ANTHROPIC_API_KEY=your_anthropic_key_here
GOOGLE_API_KEY=your_google_key_here
```

**Key Topics**:
- RAG fundamentals and architecture
- Vector embeddings and semantic search
- Document chunking strategies
- Vector databases (Chroma)
- Visualizing embeddings in 2D/3D
- Building retrieval pipelines
- **Evaluation frameworks** (MRR, NDCG, recall, precision)
- LLM-as-a-judge methodology
- Systematic experimentation and optimization