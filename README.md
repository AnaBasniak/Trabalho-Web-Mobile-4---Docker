cat << 'EOF' > README.md
# Trabalho Web Mobile 4 - Docker e CI/CD

Projeto desenvolvido para a disciplina de Web Mobile. Aplicação FastAPI integrada ao PostgreSQL, configurada com Docker e pipeline de testes no GitHub Actions.

## Tecnologias

- Python 3.11
- FastAPI / Uvicorn
- PostgreSQL 15
- Docker & Docker Compose
- Pytest
- GitHub Actions

## Estrutura do Projeto

```text
.
├── app/
│   ├── __init__.py
│   ├── main.py
│   └── test_main.py
├── .github/
│   └── workflows/
│       └── main.yml
├── Dockerfile
├── docker-compose.yml
└── requirements.txt