# College Admission Agent (RAG-Based)

This is a simple AI-powered assistant built with Flask that answers college admission-related queries using Retrieval-Augmented Generation (RAG) logic.

## Features
- Answers FAQs about admission, fees, deadlines, eligibility.
- Easy to extend with IBM Watson Discovery for dynamic document retrieval.
- Simple web interface.

## Run Locally
```bash
pip install -r requirements.txt
python app.py
```

Then open `http://127.0.0.1:5000` in your browser.

## Folder Structure
- `app.py`: Main Flask app
- `retriever/`: Data fetching logic
- `generator/`: RAG response generator
- `data/admission_faqs.txt`: Sample static knowledge base