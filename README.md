# Phase 0

create a virtual environment in your working directory with

```bash
python -m venv .venv
```

activate the environment on Windows

```bash
.venv\Scripts\Activate
```

install the packages

```bash
python -m pip install -r requirements.txt
```

test the files by running

```bash
pytest -q
```

run the python linter

```bash
ruff check
```
