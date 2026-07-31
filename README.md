# 🏥 Clinical Knowledge Assistant (Health-RAG)

## 📌 The Real-World Problem
In fast-paced clinical environments, nurses and junior doctors waste critical minutes searching through hundreds of pages of dense clinical guidelines (PDFs) and scattered hospital intranet pages to find specific protocols—such as **[INSERT YOUR CHOSEN DOMAIN HERE, e.g., Sepsis Screening Protocols]**. This delay in retrieving accurate, up-to-date information can lead to delayed care and potential medical errors.

## 💡 The Solution
This project builds a Retrieval-Augmented Generation (RAG) pipeline that acts as a **Clinical Knowledge Assistant**. It ingests unstructured medical guidelines, structures them using a Data Engineering ETL approach, and allows clinical staff to ask plain-English questions to get instant, cited answers from official hospital protocols.

## 🛠️ Tech Stack & Architecture
- **Language:** Python 3.10+
- **AI Framework:** LangChain
- **Data Processing:** PyPDF, BeautifulSoup
- **Vector Database:** ChromaDB / FAISS *(Week 2)*
- **UI Framework:** Gradio *(Week 4)*

## 📂 Project Structure
- `/data`: Raw and processed health documents (Separated into `raw/` and `processed/` for data lineage).
- `/src`: Modular Python ETL pipeline and RAG logic.
- `/notebooks`: Experimental Jupyter notebooks for prototyping.
- `/.env`: Environment variables (API keys - strictly ignored by Git).

## 🚀 How to Run (Week 1 ETL Pipeline)
*(Instructions will be added at the end of Week 1 once the ingestion pipeline is complete)*