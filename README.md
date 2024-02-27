# FastAPI Blog

A simple, easy-to-use blog application built with FastAPI.

## Features

- Write blog posts in Markdown
- Syntax highlighting for code blocks
- Responsive design
- Dark mode
- RSS feed
- SEO-friendly
- Sitemap
- Docker support

## Releasing a new version

1. Update the version in `pyproject.toml` and `fastapi_blog/__init__.py`

2. Build the distribution locally:

```bash
pip install -U build
python -m build
```

3. Upload the distribution to PyPI:

```bash
pip install -U twine
python -m twine upload dist/*
```

4. Create a new release on GitHub and tag the release:

```bash
git commit -am "Release for vXYZ"
make tag
```
