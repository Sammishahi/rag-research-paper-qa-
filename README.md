# rag-research-paper-qa-
Research paper question answering using Retrieval-Augmented Generation (RAG)
# 📄 Research Paper Question Answering using RAG 

## 🔍 Overview
This project implements a **Retrieval-Augmented Generation (RAG)** pipeline  
to answer questions from a **research paper** in a grounded and reliable manner.

The system retrieves relevant sections from the document and uses a language
model to generate concise, context-aware answers.

---

## 📚 Dataset
- **Source:** Open-access research paper  
- **Paper:** *RCCGNet – Scientific Reports (2023)*  
- **Usage:** Used as a document corpus for question answering  
- **Note:** No private or patient-level data is used  

---

## ⚙️ Methodology
- 📄 PDF parsing and text cleaning  
- ✂️ Sentence-based text chunking  
- 🔢 Transformer-based text embeddings  
- 🔍 Semantic retrieval using cosine similarity  
- 🤖 LLM-based answer generation  

---

## 📊 Results
- The system successfully answers **technical questions** related to the
  RCCGNet research paper.
- Generated responses are **grounded in retrieved document context**, reducing
  hallucination compared to standalone LLM responses.
- The RAG pipeline is able to retrieve **relevant sections** for most queries,
  enabling **clear and concise answers**.
- Qualitative evaluation shows that answers accurately summarize concepts such
  as **dataset description, model architecture, and key contributions**.

---

## 🛠 Tools & Technologies
- **Programming Language:** Python  
- **Deep Learning:** PyTorch  
- **NLP Models:** Hugging Face Transformers  
- **Retrieval:** scikit-learn  
- **Environment:** Jupyter Notebook  

---

## 🧪 Project Type
> Research prototype implemented in a Jupyter notebook for educational  
> and experimental purposes.

---

## 📌 Key Takeaway
This project demonstrates how **Retrieval-Augmented Generation (RAG)** can be
used to build **reliable document-based question answering systems** by
combining semantic retrieval with large language models.
