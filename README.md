# Documentation Template

Use this folder as a starter for a new bilingual MkDocs documentation repository.

## What to edit

- `mkdocs.yml`
- `docs/index.md` for Chinese content
- `docs/en/index.md` for English content
- `docs/` for Chinese pages
- `docs/en/` for English pages with matching paths
- `docs/assets/图片材料/` for shared site images

## Local development

```bash
pip install -r requirements.txt
mkdocs serve
```

## Internationalization

- Chinese is the default language.
- English pages live under `docs/en/`.
- English pages should mirror the relative path of their Chinese counterpart.
- Untranslated pages fall back to the Chinese source page.


