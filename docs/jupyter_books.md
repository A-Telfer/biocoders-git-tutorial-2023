# Working with Jupyter Books
Jupyter books and gitpages allows us to easily document our projects and host them online.

A couple of examples of popular Neuroscience tools using Gitpages and Jupyter Books
- [DeepLabCut](https://deeplabcut.github.io/DeepLabCut/README.html)
- [Nilearn](https://nilearn.github.io/stable/quickstart.html)


## Basic Usage
1. Install jupyter books
```
pip install jupyter-book
```

2. Create jupyter book
```
jupyter-book create docs
```

This will generate a docs folder with template contents. You can start fiddling with it easily, or look up the documentation here! https://jupyterbook.org/en/stable/start/your-first-book.html


3. Build jupyter book
```
jupyter-book build docs
```

## Creating a webpage
```
pip install ghp-import
```

Push changes to github
```
jupyter-book build docs
ghp-import -n -p -f docs/_build/html
```

## Visit your webpage!
You can go into the settings of your repository on github.com, then find the pages tab to get the URL for your project. 

For me it was 
`https://a-telfer.github.io/biocoders-git-tutorial-2023`

e.g. `https:/<username>.github.io/<repository>`
