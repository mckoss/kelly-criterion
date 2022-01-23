# Kelly Criterion

This repository is designed to explain the Kelly Criterion and how
it can inform investment strategies.

## Installation

The primary file here is a [Jupyter Notebook](./index.ipynb) - which you can just
visit here if you want to view it statically.

If you want to run the Python code in the notebook, follow these steps.

*I'll assume you have Python3 installed on your system already.*

```
$ python -m venv .env        # Create a local Virtual Environment
$ source .env/bin/activate   # Activate it

# Confirm python 3 and pip are both coming from the environment:

$ which python && python --version
$ which pip

$ pip install -r requirements.txt

# Confirm Jupyter notebook installed

$ which jupyter && jupyter --version

# Run the notebook opening a browser window:

$ jupyter notebook index.ipynb
```

As an alternative to running the Notebook in a browser, you can open it in
VS-Code.  Install all the same code above, but then open VS-Code in this
folder and open index.ipynb.  In the upper right, select ".env" as your
Python environment.

VS-Code will launch the kernel for you.

