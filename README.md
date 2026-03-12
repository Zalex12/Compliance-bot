# Compliance Bot Clean Release

This is a sanitized upload package for GitHub.

Included:
- `src/`
- `requirements.txt`
- `config.json` (example only)
- `.env.example`
- `.gitignore`

Excluded:
- real API keys and webhooks
- internal knowledge base documents
- company website task URLs
- runtime outputs, screenshots, HAR files, and reports

## Quick start

1. Copy `.env.example` to `.env`
2. Fill in your own API keys and webhook
3. Replace the example sites in `config.json`
4. Put your private compliance docs into `knowledge_base/` locally
5. Run:

```powershell
python -m venv venv
venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
python -m src.main
```
