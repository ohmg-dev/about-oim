# About OldInsuranceMaps.net

A static site for information and documentation about OldInsuranceMaps.net. See [ohmg-dev/OldInsuranceMaps](https://github.com/ohmg-dev/OldInsuranceMaps) for the georeferencing application code base, or [ohmg-dev/ohmg-website](https://github.com/ohmg-dev/ohmg-website) for the OHMG information site at [ohmg.dev](https://ohmg.dev).

# Local install

These docs are generated with [mkdocs-material](https://squidfunk.github.io/mkdocs-material). 

The pypi packages used are `mkdocs-material`, `mkdocs-glightbox`, though the full set of dependencies is rewritten to `requirements.txt` into order to pin all the versions. 

To install the documentation locally use the following steps:

```
git clone https://github.com/ohmg-dev/about-oim && cd about-oim
python3 -m venv env
source ./env/bin/activate
pip install -r requirements.txt
```

To view them, use

```
mkdocs serve
```

and visit `http://localhost:8000` in a browser.
