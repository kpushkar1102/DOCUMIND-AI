# Docu Mind AI
    python -m venv .venv && source .venv/bin/activate
    pip install -r requirements.txt
    python scripts/seed.py            # demo files, ingest, SSL fit, reindex
    python -m app.app                 # http://localhost:5000  (eval dashboard: /eval)
    EMBED_BACKEND=hash pytest -q      # offline tests, no model download
