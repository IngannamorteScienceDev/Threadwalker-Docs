# 📘 Threadwalker Docs

Official multilingual documentation for **Threadwalker** — a semantic analysis engine that extracts emotion, structure, and meaning from human dialogue.

> 🧭 Explore the inner mechanics, usage cases, architecture, and emotional modeling of Threadwalker in English, Russian, Japanese, and Chinese.

---

## 🌐 Live Documentation

📎 [View the site](https://ingannamortesciencedev.github.io/Threadwalker-Docs/)

---

## 📚 Structure

The documentation supports 4 languages:

```

docs/
├── en/    → English
├── ru/    → Русский
├── ja/    → 日本語
└── zh/    → 中文

````

All content is organized using [MkDocs](https://www.mkdocs.org/) with the [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) theme and multilingual support via `mkdocs-static-i18n`.

---

## 🚀 Quick Start

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
```

2. Run locally:

   ```bash
   mkdocs serve
   ```

3. Open in browser:

   ```
   http://localhost:8000/en/
   http://localhost:8000/ru/
   http://localhost:8000/ja/
   http://localhost:8000/zh/
   ```

---

## 📦 Build & Deploy (GitHub Pages)

```bash
mkdocs gh-deploy
```

This will publish the site to the `gh-pages` branch and make it live at:
`https://<username>.github.io/Threadwalker-Docs/`

---

## ✅ Requirements

* Python 3.10 / 3.11
* MkDocs
* Material for MkDocs
* mkdocs-static-i18n

All dependencies are listed in `requirements.txt`.

---

## 📄 License

This documentation is licensed under the
[Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License](https://creativecommons.org/licenses/by-nc-nd/4.0/).

[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/)

---

## 💡 Future Additions

* Thematic and emotional examples
* Advanced usage with diagrams and visuals
