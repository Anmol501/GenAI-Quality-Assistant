# GenAI Quality Assistant 

A smart, GenAI-powered assistant designed to help **MSMEs** (Micro, Small and Medium Enterprises) understand and apply **quality tools and concepts** like FMEA, FTA, PDCA, and more.

It uses **Retrieval-Augmented Generation (RAG)** to answer queries using expert content from books like *Juran’s Quality Handbook*, and generates:
- Detailed answers to quality-related queries
- Flowcharts for process understanding
- Self-assessment questionnaires with scoring
- PDF reports with recommendations

---

## Tech Stack

| Component | Tool |
|----------|------|
| LLM | `mistral-7b-instruct` via OpenRouter |
| RAG | LangChain + FAISS + sentence-transformers |
| Docs | Text files and book chapters |
| Embeddings | `all-MiniLM-L6-v2` |
| Flowcharts | `graphviz` |
| Report Generation | `reportlab` |
| Platform | Google Colab |

---

## Features

- **RAG-powered chatbot** that answers questions based on uploaded quality books
- **Flowchart generation** from natural language
- **Self-assessment module** to evaluate MSME practices
- **PDF report generation** with recommendations

---

## How to Run

1. Open the `genaI_assistant.py`
2. Upload your documents (e.g., quality handbooks)
3. Ask your queries in natural language
4. Use the assessment block to interactively rate your practices
5. Download the final PDF report

---


