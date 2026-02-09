## Smart Study Assistant

Upload your PDFs and ask questions. The app answers only from your notes and shows sources.

### Setup
1. Create a `.env` file with:
	- `GEMINI_API_KEY=your_key_here`
2. Install dependencies from `pyproject.toml`.

### Run (local)
Start Streamlit and open the provided URL:
- `streamlit run app.py`

### Notes
- Vector store is local Chroma in `data/chroma`.
- Uploaded files are stored in `data/uploads`.
- If Gemini embeddings fail, keep "Use local embeddings" enabled (default).
