# Lambdata-DSPT6
A collection of data science utility functions.

## Installation

```py
pip install -i https://test.pypi.org/simple/ lambdata-dspt6
```

## Usage

```py
from my_lambdata.ds_utilities import enlarge

x = 11
print(enlarge(x))
```

```py
from my_lambdata.ds_utilities import train_validation_test_split

X_train, X_val, X_test, y_train, y_val, y_test = train_validation_test_split(X, y)
```
