# PythonCExtensions
Forked from https://github.com/mattfowler/PythonCExtensions

I have changed code to make it work with python3


Using a Python C extension and comparing its performance to NumPy and Python

You need to build the C extension before running this. To build and install the extension run:

```python
python3 setup.py install
```

stdtest.py has a main method which will compare Python, NumPy and the C extension for small arrays and plot the performance with matplotlib.

