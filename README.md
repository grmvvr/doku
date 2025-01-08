# doku
Documentation using readthedocs [(RTD)](https://docs.readthedocs.io/en/stable/index.html) and GitHub.
- Get a free personal page using github and RTD just because you want to.


## TLDR
```bash
git clone https://github.com/grmvvr/doku.git
cd doku && python -m pip install -U docs/requirements-docs.txt
sphinx-build -M html docs/source docs/build
```

## How to use:
- clone repo
    ```bash
    git clone https://github.com/grmvvr/doku.git
    ```

- install requirements in python env
    ```bash
    # activate python env
    cd doku
    python -m pip install -U docs/requirements-docs.txt
    ```
- modify markdown file in [docs/source/markdown/p1.md](docs/source/markdown/p1.md)


- build html using sphinx
    ```bash
    sphinx-build -M html docs/source docs/build
    ```

- link GitHub proect to RTD by following steps [ in RTD docs pages here](https://docs.readthedocs.io/en/stable/intro/add-project.html#automatically-add-your-project).