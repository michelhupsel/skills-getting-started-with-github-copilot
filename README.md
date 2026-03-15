# Getting Started with GitHub Copilot

<img src="https://octodex.github.com/images/Professortocat_v2.png" align="right" height="200px" />

Hey michelhupsel!

Mona here. I'm done preparing your exercise. Hope you enjoy! 💚

Remember, it's self-paced so feel free to take a break! ☕️

[![](https://img.shields.io/badge/Go%20to%20Exercise-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)](https://github.com/michelhupsel/skills-getting-started-with-github-copilot/issues/1)

---
## 🚀 Como rodar localmente

### 1) Instalar dependências

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
```

### 2) Iniciar servidor

```bash
cd src
uvicorn app:app --reload --host 0.0.0.0 --port 8000
```

Abra [http://localhost:8000](http://localhost:8000).

### 3) Rodar testes (FastAPI backend)

```bash
source .venv/bin/activate
.venv/bin/python -m pytest -q tests/test_app.py
```

### 4) Observações

- O frontend está em `src/static/`.
- O back-end está em `src/app.py`.
- O arquivo de testes está em `tests/test_app.py`.

---
&copy; 2025 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

