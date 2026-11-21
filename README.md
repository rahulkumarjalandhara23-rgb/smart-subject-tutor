
# 🎓 Smart Subject Tutor (v1.0 — Open-Source RAG)

An open-source, zero-API-key Retrieval-Augmented Generation (RAG) tutor built in GitHub Codespaces that adapts explanations across four pedagogical styles.

## 📖 Project Overview

Smart Subject Tutor is an AI-powered educational application designed to help B.Tech students understand complex subjects using their own study notes.

The application uses Retrieval-Augmented Generation (RAG) to retrieve relevant information from subject notes and generate explanations using an open-source Large Language Model.

## 🚀 Key Features

- 100% Open-Source AI Stack
- Zero Paid API Keys Required
- Retrieval-Augmented Generation (RAG)
- Subject-Specific Knowledge Base
- Four Adaptive Teaching Styles
- Semantic Search with Vector Embeddings
- Cosine Similarity-Based Retrieval
- Interactive Streamlit Web Interface

## 🎨 Adaptive Learning Styles

### 1. ELI10 (Real-World Analogy)
Explains complex engineering concepts using simple everyday examples and analogies.

### 2. Exam Topper (10-Mark Structured Notes)
Provides structured definitions, numbered key points, and exam-focused summaries.

### 3. Socratic Professor (Intuition + Quiz)
Explains concepts step by step and ends with a conceptual question.

### 4. Practical Engineer (System & Code Focus)
Focuses on implementation, pseudocode, system performance, and engineering trade-offs.

## 🏗️ v1.0 Architecture

- **Subject Knowledge Base:** `data/subject_notes.md`
- **Embedding Model:** `sentence-transformers/all-MiniLM-L6-v2`
- **Embedding Dimensions:** 384
- **Vector Database:** ChromaDB
- **Similarity Metric:** Cosine Similarity
- **Open-Source LLM:** `Qwen/Qwen2.5-0.5B-Instruct`
- **Frontend:** Streamlit
- **Programming Language:** Python
- **Execution Environment:** GitHub Codespaces

## 📂 Project Structure

smart-subject-tutor/
    README.md
    requirements.txt
    rag_engine.py
    app.py
    .gitignore
    data/
        subject_notes.md

## 🚀 How to Run in GitHub Codespaces

### Step 1: Create a Virtual Environment

```bash
python3 -m venv .venv
```

### Step 2: Activate Virtual Environment

```bash
source .venv/bin/activate
```

### Step 3: Install CPU-Optimized PyTorch

```bash
pip install torch --index-url https://download.pytorch.org/whl/cpu
```

### Step 4: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 5: Run Streamlit Application

```bash
streamlit run app.py
```

Open the application using the forwarded port 8501 in GitHub Codespaces.

## 🧪 Example Question

What is a Deadlock and what are the four conditions required for it?

Select different teaching styles to compare the AI-generated explanations.

## 📚 Current Subject

Operating Systems (B.Tech CSE Core)

Topics covered:

1. Process vs Thread
2. Deadlock and Four Coffman Conditions
3. Virtual Memory, Paging, and Page Faults
4. CPU Scheduling Algorithms

## 🔮 Future Improvements

- Multiple Subject Support
- PDF Notes Upload
- Chat History
- Interactive Quizzes
- Improved Retrieval Accuracy

## 📜 Version

v1.0 — Open-Source RAG Smart Subject Tutor
