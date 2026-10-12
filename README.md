# style-guide-project

Учебный проект по методологии Docs as Code: руководство по стилю корпоративной и технической документации на MkDocs.

## Локальный запуск

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

Для Windows PowerShell:

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
pip install -r requirements.txt
mkdocs serve
```

После запуска откройте адрес, который выведет MkDocs, обычно `http://127.0.0.1:8000/`.

## Проверка сборки

```bash
mkdocs build --strict
```

## Структура

- `docs/` — исходные Markdown-файлы руководства;
- `mkdocs.yml` — конфигурация сайта и навигации;
- `.github/workflows/` — CI/CD;
- `.markdownlint-cli2.yaml` — правила линтинга Markdown;
- `CONTRIBUTING.md` — правила внесения изменений.
