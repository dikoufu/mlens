![Python 3.5](https://img.shields.io/badge/python-3.5-blue.svg)
![License](https://img.shields.io/badge/license-MIT-red.svg)

# ML Ensemble - A library for ensemble learning

**ML Ensemble is a Python library for building ensembles through Scikit-learn's API to allow for full parallelization and integration with sklearn's cross-validation, pipelining and diagnostics tools.**


## Notes

The package is under construction and as such may not function properly. If you are interested in trying it out or to contribute, the package builds without issues. 

## How to install

#### PyPI

** global PyPI database (coming) **
With bash, execute  

```bash
pip install mlens  
```

** manual download **

The package can be installed by downloading the repo and using pip install:



```bash
git clone https://flennerhag/mlens.git; cd mlens;
pip install .
```

#### Bleeding edge

To ensure latest version is installed, fork the GitHub repository and install mlxtens using the symlink options.

```bash
pip install -e .
```

To update the package, simply pull the latest changes from the github repo

<br>
<br>

## License

MIT License

Copyright (c) 2017 Sebastian Flennerhag

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.