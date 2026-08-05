# Xtracked website

This repository contains the source code of the Xtracked website.

The website is built with [Zensical](https://zensical.org/) and is published automatically through GitHub Pages.

## Requirements

- Python 3
- pip

## Installation

```bash
pip install zensical
```

## Run locally

```bash
zensical serve
```

The website will be available at:

```
http://localhost:8000
```

## Build

```bash
zensical build
```

The generated site is written to the `site/` directory.

## Deployment

Changes pushed to the default branch are published automatically through GitHub Pages using GitHub Actions.

## License

See the `LICENSE` file for details.