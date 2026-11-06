# Reservas de Laboratórios

Aplicação Full Stack didática para gerenciar reservas de laboratórios, feita com FastAPI, SQLite e HTML/CSS/JavaScript.

## Como rodar

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install fastapi uvicorn pytest pytest-cov httpx
python -m uvicorn backend.app.main:app --reload
```

- Interface: http://127.0.0.1:8000/
- Documentação da API: http://127.0.0.1:8000/docs

## Como testar

```powershell
python -m pytest -v
```
