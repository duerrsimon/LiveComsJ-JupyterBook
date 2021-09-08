# LiveComsJ JupyterBook template

This is a preconfigured template to use JupyterBooks with LiveComsJ style

## How to use

Install required packages

```
$ pip install -r requirements.txt
```


Then modify the `.md` and `.ipynb` files. 

Modify the `_toc.yml` and `_config.yml` to configure which files to build and to setup latex macros,
book title, footer etc. 



### Build the book

```
jb build .
```
