# Kino Mod Documentation

This repository contains a statically generated website for documentation on how to setup the [Kino modification for CarX](https://github.com/trbflxr/kino).

This has been an effort by [locomoco28](https://github.com/locomoco28) to improve the user experience for the less tech-affine users who struggle working with `.md` documentation placed in a Github repository.

## Requirements

This project uses [mkdocs](https://github.com/mkdocs/mkdocs/) as site generator, and [mkdocs-material](https://github.com/squidfunk/mkdocs-material) as theme for mkdocs.

You need Python 3 installed for mkdocs.

## Installing

```bash
# install dependencies
pip install -r requirements.txt

# run local development server with hot reloading
mkdocs serve

# build and deploy website to github pages
mkdocs gh-deploy
```
