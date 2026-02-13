# CV Digital — Anthony Cruz

[![Deploy CV to GitHub Pages](https://github.com/ancrz/cv-digital/actions/workflows/deploy.yml/badge.svg)](https://github.com/ancrz/cv-digital/actions/workflows/deploy.yml)

> Schema-Driven CV: datos en JSON, presentacion en HTML.

## [https://ancrz.github.io/cv-digital/](https://ancrz.github.io/cv-digital/)

## Como funciona

```
data/cv.json   →  Source of truth (editar datos aqui)
index.html     →  Renderizador (no tocar para actualizar datos)
GitHub Actions →  CI/CD automatico (validate + deploy on push)
```

## Actualizar CV

1. Editar `data/cv.json` con los datos nuevos
2. Push a `main`
3. El pipeline valida el JSON y despliega automaticamente

## Stack

HTML5 · Tailwind CSS (CDN) · Vanilla JS · GitHub Actions · GitHub Pages
