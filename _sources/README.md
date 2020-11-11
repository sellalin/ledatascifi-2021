# LeDataSciFi-2021

The 2021 edition of LeDataSciFi. It will eventually be hosted at [ledatascifi.github.io](https://ledatascifi.github.io).

- Greatly simplified prior website structure - now everything is in one book, and can be ported from year to year.
- Now using `jupyter-book` 0.8.3 instead of 0.6.4, which are in compatible.
- To build the book for local viewing:
    - `cd <>/ledatascifi-2021` (this will move once this repo goes live and replaces the main ledatascifi.github.io repo)
    - (Recommended) Remove the existing `LeDataSciFi-2021/_build/` directory
    - `jupyter-book build ./`
    - A fully-rendered HTML version of the book will be built in the `_build/html/` folder.
- To update website: Simply push or pull the main branch of the repo. A GitHub actions workflow (`.github/workflows/deploy.yml`) automatically builds and pushes the book in the `gh-pages` branch, and GitHub pages will update the website in <5 minutes. 
- Book formatting is controlled by
    - `_config.yml` for most settings
    - `_toc.yml` lays out the book table of contents, ie the left nav bar
    - `_static/*` - any css or js I want to add to modify the base styling goes here

## Credits

This project is created using the excellent open source [Jupyter Book project](https://jupyterbook.org/) and the [executablebooks/cookiecutter-jupyter-book template](https://github.com/executablebooks/cookiecutter-jupyter-book).


