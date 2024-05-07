# docs

Documentation for OldInsuranceMaps.net, and, at least for now, the underlying Online Historical Map Georeferencer in general.

# Local install

These docs are generated with [mkdocs-material](https://squidfunk.github.io/mkdocs-material). 

The pypi packages used are `mkdocs-material`, `mkdocs-glightbox`, though the full set of dependencies is rewritten to `requirements.txt` into order to pin all the versions. 

To install the documentation locally use the following steps:

```
python3 -m venv env
source ./env/bin/activate
pip install -r requirements.txt
```

To view them, use

```
mkdocs serve
```

and visit `http://localhost:8000` in a browser.
