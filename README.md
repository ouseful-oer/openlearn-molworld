# oer-md-publish
Template repo for autobuilding nbsphinx sites

This template repository can be used as a basis for creating documentation sites that are auto-built using CircleCI.

CircleCI uses Spninx / nbSphinx to produce the a website in `gh-pages` from text and Jupyter notebook documents.

Jupytext is installed so that text files (`.py`, `.md`, etc) can be executed as notebooks via Jupytext.

Code execution is disabled by default in the `nbsphinx` configuration file (`conf.py`).
