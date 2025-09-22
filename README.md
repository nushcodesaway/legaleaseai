# LegalEase AI

Generative AI app to simplify legal documents, highlight risks, and provide Q&A.

## Quickstart

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
cp .env.example .env

# Run backend
uvicorn backend.main:app --reload --port 8000

# Run frontend
streamlit run frontend/app.py
```

Then open http://localhost:8501



KINDLY REFER THE "ENTIRE PROJECT.pdf" for the codes, as many weren't uploaded due to size issues.
