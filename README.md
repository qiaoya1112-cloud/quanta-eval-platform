# Quanta 双盲评测平台 (Demo)

Single-file Flask demo for embodied intelligence model evaluation.

## Local run

```bash
pip install -r requirements.txt
python3 quanta_eval_platform.py
# open http://localhost:5001
```

## Deploy (Render)

- Build command: `pip install -r requirements.txt`
- Start command: `gunicorn quanta_eval_platform:app --bind 0.0.0.0:$PORT --timeout 120`
