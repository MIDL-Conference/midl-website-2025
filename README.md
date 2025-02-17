[![Netlify Status](https://api.netlify.com/api/v1/badges/b8c8d8c7-d65e-4073-b4a7-22c26ea71e33/deploy-status)](https://app.netlify.com/sites/midl-2025/deploys)

# MIDL 2025 (Salt Lake City) website

This repository contains the source code of the 2025.midl.io website.

* Pages are files in `pages/` and can either be MarkDown (`.md`) or HTML (`.html`) files
* Global settings, such as the navigation bar, are in `website.yaml`

The website is automatically rebuilt after every commit to the master branch.

## Building the website locally

We use [poetry](https://python-poetry.org/) to manage dependencies. Check runtime.txt to see which Python version is required.

Install the dependencies by running:

```
poetry install
```

Then run the website builder:

```
poetry run python -m mwb . output/ --no-minify --serve --verbose
```

This builds the website and writes the generated output into the directory `output/`, then starts a webserver on
`http://localhost:8000` until you stop it with Ctrl+C.

Alternatively, you can also install the dependencies with pip:

```
pip install -r requirements.txt
python -m mwb . output/ --no-minify --serve --verbose
```

To clone with all dependencies, such as the midl-website-theme repository use this command to clone the repository:
```
git clone --recurse-submodules <GITHUB-REPO>
```
