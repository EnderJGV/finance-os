# Finance_OS

Projeto Finance_OS com frontend, backend e app.

## Estrutura

- `frontend/` - aplicação React + Vite
- `backend/` - API FastAPI
- `app/` - outros arquivos do projeto (não documentados aqui)

## Requisitos

- Node.js + npm
- Python 3.13+

## Backend

1. Abra o terminal em `backend/`
2. Crie e ative um ambiente virtual:
   - Windows PowerShell: `python -m venv .venv` e `.\.venv\Scripts\Activate.ps1`
   - Windows CMD: `python -m venv .venv` e `\.venv\Scripts\activate.bat`
   - macOS / Linux: `python -m venv .venv` e `source .venv/bin/activate`
3. Instale as dependências:
   ```bash
   python -m pip install --upgrade pip
   python -m pip install -e .
   ```
4. Inicie o servidor:
   ```bash
   uvicorn main:app --reload --host 0.0.0.0 --port 8000
   ```

A API ficará disponível em `http://127.0.0.1:8000`.

## Frontend

1. Abra o terminal em `frontend/`
2. Instale as dependências:
   ```bash
   npm install
   ```
3. Inicie o frontend:
   ```bash
   npm run dev
   ```

O frontend ficará disponível no endereço mostrado no terminal (normalmente `http://127.0.0.1:5173`).

## Observações

- Se quiser abrir apenas o backend ou o frontend, use os comandos acima dentro das respectivas pastas.
- Para ver a documentação da API FastAPI, acesse `http://127.0.0.1:8000/docs` após iniciar o backend.
