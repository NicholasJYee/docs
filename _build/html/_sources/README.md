# Overview
### Primary Author: Nicholas J. Yee
This repo contains the source code for the [Jupyter Book]([url](https://jupyterbook.org/en/stable/intro.html)https://jupyterbook.org/en/stable/intro.html) for my graduate studies.

Build the html and pdf using the command:

```bash
conda activate docs 
```


```bash
jb build .
````
Update the 'requirements.txt' using the command:

```bash
conda list --export > requirements.txt 
```

Host the html file using the command:

```bash 
python3 -m http.server -d docs/_build/html 
```



