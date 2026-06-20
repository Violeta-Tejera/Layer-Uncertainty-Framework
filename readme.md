# AI Explainability through uncertainty quantification across layers

This repository contains an adaptation for this seminar of  [this paper](https://link.springer.com/chapter/10.1007/978-3-032-04558-4_30)'s by Font et. al. Their authors propose a framework for uncertainty quantification based on nearest neighbors across layers as a post-hoc method to yield explainations in regards to Neural Nets' produced decisions.

## Using this repository

After cloning, create a Python (It's preferable to use version 3.12) virtual environment and activate it.

```
python3 -m venv venv/
source venv/bin/activate
```

Install the framework's required library versions:

```
pip3 install -r requirements.txt
```

Now, you're ready to go.

### Relevant files

From all the files provided, the most important ones to focus on for this seminar are the Fexigo library $\texttt{fexigo.py}$ and the $\texttt{fexigo\_mnist\_demo.ipynb}$ notebook.

The former implements all the necessary code for the explaination protocol described whereas the later serves as a demo notebook for this seminar.