# Overview
### Primary Author: Nicholas J. Yee, MD
This repo contains the source code for the [Jupyter Book]([url](https://jupyterbook.org/en/stable/intro.html)https://jupyterbook.org/en/stable/intro.html) for my graduate studies.


If this is your first time running this project, 
install the conda environment for this project, which will
install all the necessary packages locally and enclosed:
```bash
conda env create -f docs.yml
```


Build the html and pdf using the command:

```bash
conda activate docs 
```
```bash
jb build .
````

Host the html file using the command:

```bash 
python3 -m http.server -d _build/html 
```

Update the package list using the command:

```bash
conda env export --name docs > docs.yml
```

