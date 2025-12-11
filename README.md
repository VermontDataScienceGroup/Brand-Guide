# Vermont Data Science Group - Brand Guide

This repository contains the brand guide for the Vermont Data Science Group, built as a Jupyter Book website.

## About

This brand guide provides comprehensive information about our brand identity, including:
- **Logos**: Official logos and usage guidelines
- **Colors**: Brand color palette with specifications
- **Typography**: Font families and typographic standards
- **Usage Guidelines**: Best practices for brand application

## View the Guide

The brand guide is built as a static website using Jupyter Book. You can view it by:

1. Building the book locally (see instructions below)
2. Opening `_build/html/index.html` in your web browser
3. Or deploying it to GitHub Pages or another hosting service

## Installation

To work with this book locally, you'll need Python 3.7+ and the following dependencies:

```bash
pip install -r requirements.txt
```

## Building the Book

To build the book, run:

```bash
jupyter-book build .
```

The HTML output will be generated in the `_build/html` directory.

## Cleaning Build Files

To clean up build artifacts:

```bash
jupyter-book clean .
```

## Deploying to GitHub Pages

To deploy this book to GitHub Pages:

1. Build the book: `jupyter-book build .`
2. Install `ghp-import`: `pip install ghp-import`
3. Run: `ghp-import -n -p -f _build/html`

This will push the built HTML to the `gh-pages` branch.

## Project Structure

```
Brand-Guide/
├── _config.yml          # Jupyter Book configuration
├── _toc.yml             # Table of contents
├── intro.md             # Landing page
├── logos.md             # Logo guidelines
├── colors.md            # Color palette
├── typography.md        # Typography guidelines
├── usage.md             # Usage guidelines
├── references.bib       # Bibliography file
└── requirements.txt     # Python dependencies
```

## Contributing

To update the brand guide:

1. Edit the relevant `.md` files
2. Rebuild the book: `jupyter-book build .`
3. Review your changes by opening `_build/html/index.html`
4. Commit and push your changes

## Resources

- [Jupyter Book Documentation](https://jupyterbook.org/)
- [MyST Markdown Guide](https://myst-parser.readthedocs.io/)

## License

© 2025 Vermont Data Science Group. All rights reserved.