# t-Student-Mixture-Models
Implementation of the paper: 'Robust mixture modelling using the t distribution', D. Peel and G. J. McLachlan.

# Dependencies
* scikit-learn v0.18.1
* numpy v1.11.0
* nose v1.3.7
* scipy v0.19.0
* setuptools v36.0.1

# Install
Using pip (no need to clone this repo):
```
pip install smm --user
```
Manually:
```
git clone https://github.com/luiscarlosgph/t-Student-Mixture-Models.git
cd t-Student-Mixture-Models
python setup.py build
python setup.py install --user
```

# Usage
See example in [src/smm/example.py](src/smm/example.py). 
```
python setup.py build
python build/lib/smm/example.py
```

# Tests
To run the tests execute:
```
python setup.py build
python setup.py test
```

# Coverage
Current coverage: 79%.
To re-run the coverage test (Ubuntu Ubuntu 16.04.2 LTS):
```
python3-coverage run ./setup.py test
python3-coverage html
```
Then open 'htmlcov/index.html' and check the line: 'src/smm/smm'.

# Documentation
See [doc/smm.html](doc/smm.html).
To re-generate the documentation:
```
cd doc
pydoc -w ../src/smm/smm.py
```

# Author
Luis Carlos Garcia-Peraza Herrera (luis.herrera.14@ucl.ac.uk).

# License
BSD 3-Clause License, see LICENSE file for more information.
