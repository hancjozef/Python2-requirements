# Specifying a Python 2 environment with `runtime.txt`

Testing Python 2 with extra libraries - numpy, matplotlib, pandas, lapack, cvxpy

`python-2.7` in `runtime.txt`:

* A python3 environment is created & installed (this is what the notebook runs from)
* A python2 environment is created and registered
* The contents of `requirements.txt` are installed into the python2 environment

**important:**
Make sure that you save your notebooks with a python 2 kernel activated,
as this defines which kernel Binder will use when a notebook is opened.

**note:**
If you *also* wish to install python 3 dependencies, you may do so
by including a file called `requirements3.txt`. The packages
inside will be installed into the python 3 environment.
