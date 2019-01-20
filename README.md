# distpy
How to distribute a python package

# How to use it
## install package from source code
```bash
$ python setup.py install
```

# build a wheel
```bash
$ pip install wheel  # Make sure Wheel is installed
$ python setup.py sdist bdist_wheel
```