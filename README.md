# ml-lab-1: Practice GitHub

1. Clone this repository to your local computer
2. Open Jupyter notebook `ml-lab-1.ipynb`
3. Change author name to your name
4. Save locally, then use git add and commit changes
5. Copy the code below and run in a code cell in Jupyter notebook
6. Save locally, then use git add and commit changes
7. Run the second cell to display all conda environments 
8. Save locally, then use git add and commit changes
9. git push changes to your GitHub


```Python
import sys
print("Python version:", sys.version)

import pandas as pd
print("pandas version:", pd.__version__)

import matplotlib
print("matplotlib version:", matplotlib.__version__)

import numpy as np
print("NumPy version:", np.__version__)

import scipy as sp
print("SciPy version:", sp.__version__)

import IPython
print("IPython version:", IPython.__version__)

import sklearn
print("scikit-learn version:", sklearn.__version__)

import yellowbrick
print("yellowbrick version:", yellowbrick.__version__)
```

For me, the package versions are:
```
Python version: 3.8.15 (default, Nov 24 2022, 14:38:14) [MSC v.1916 64 bit (AMD64)]
pandas version: 1.5.2
matplotlib version: 3.6.2
NumPy version: 1.24.0
SciPy version: 1.9.3
IPython version: 7.31.1
scikit-learn version: 1.1.3
yellowbrick version: 1.3
```

For me, the list of conda environments include:
```
# conda environments:
#
                         C:\Users\ladaw\anaconda3
base                  *  C:\Users\ladaw\anaconda3\envs\ensf-ml
```
Note the `*` indicating that `ensf-ml` is the currently active environment
