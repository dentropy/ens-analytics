
## Requirements

* pip packages
``` bash 
pip install ipython-sql
pip install sqlalchemy
pip install pandas
```

## Clear outputs of jupyter notebook

``` bash
jupyter nbconvert --ClearOutputPreprocessor.enabled=True --inplace  ./ens-analytics-dev.ipynb
```