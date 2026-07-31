# Xtracked website

This repository contains the source code of the Xtracked website.

The website is built with [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) and is published
automatically through GitHub Pages.

## Requirements

- Python 3
- pip

## Installation

```bash
pip install -r requirements.txt
```

## Run locally

```bash
mkdocs serve
```

The website will be available at:

```
http://localhost:8000
```

## Build

```bash
mkdocs build
```

The generated site is written to the `site/` directory.

## Deployment

Changes pushed to the default branch are published automatically through GitHub Pages using GitHub Actions.

## License

See the `LICENSE` file for details.