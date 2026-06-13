# Backend Finance_OS

API construída com FastAPI.

## Requisitos

- Python 3.13+
- Ambiente virtual recomendado

## Instalação

No terminal, dentro de `backend/`:

```bash
python -m venv .venv
# Windows PowerShell
.\.venv\Scripts\Activate.ps1
# macOS / Linux
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install -e .
```

## Executar

```bash
uvicorn main:app --reload --host 0.0.0.0 --port 8000
```

A API estará disponível em `http://127.0.0.1:8000`.

## Rotas principais

- `GET /` - rota de teste
- `GET /docs` - documentação interativa OpenAPI
