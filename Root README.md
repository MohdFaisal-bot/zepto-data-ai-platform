# Zepto Data & AI Platform

An end-to-end data and machine learning platform built for the Zepto analytics guild, integrating:
1. **Data Pipeline (`/data_pipeline`)**: Automated web scraping, currency enrichment, normalized SQLite persistence, and dual SQL/pandas verification.
2. **Analytics Pipeline (`/analytics`)**: Rigorous exploratory data analysis, multivariate storytelling, stratified predictive modeling pipelines, class imbalance mitigations, hyperparameter tuning, and regression diagnostics.
3. **GenAI Support Assistant (`/support_assistant`)**: LangGraph RAG workflow with ChromaDB vector search, local embeddings (`all-MiniLM-L6-v2`), deterministic mock routing, and containerized FastAPI delivery.

---

## 1. Setup and Environment

A consolidated `requirements.txt` is provided at the repository root.

```bash
git clone <YOUR_REPO_URL>
cd zepto-data-ai-platform
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
