```python
import pandas as pd

archivo_csv = pd.read_csv('iris-data.csv');


print(archivo_csv)
```

         sepal length  sepal width  petal length  petal width           class
    0             5.1          3.5           1.4          0.2     Iris-setosa
    1             4.9          3.0           1.4          0.2     Iris-setosa
    2             4.7          3.2           1.3          0.2     Iris-setosa
    3             4.6          3.1           1.5          0.2     Iris-setosa
    4             5.0          3.6           1.4          0.2     Iris-setosa
    ..            ...          ...           ...          ...             ...
    145           6.7          3.0           5.2          2.3  Iris-virginica
    146           6.3          2.5           5.0          1.9  Iris-virginica
    147           6.5          3.0           5.2          2.0  Iris-virginica
    148           6.2          3.4           5.4          2.3  Iris-virginica
    149           5.9          3.0           5.1          1.8  Iris-virginica
    
    [150 rows x 5 columns]
    


```python
# Descripción de las columnas El dataset de Iris tiene las siguientes columnas:

# sepal_length: Longitud del sépalo (cm).
# sepal_width: Anchura del sépalo (cm).
# petal_length: Longitud del pétalo (cm).
# petal_width: Anchura del pétalo (cm).
# species: Especie de la flor (setosa, versicolor, virginica).
```


```python
import seaborn as sns

df = sns.load_dataset("iris-data.csv")
df.head()
```


    ---------------------------------------------------------------------------

    ValueError                                Traceback (most recent call last)

    Cell In[19], line 3
          1 import seaborn as sns
    ----> 3 df = sns.load_dataset("iris-data.csv")
          4 df.head()
    

    File ~\anaconda3\Lib\site-packages\seaborn\utils.py:587, in load_dataset(name, cache, data_home, **kws)
        585 if not os.path.exists(cache_path):
        586     if name not in get_dataset_names():
    --> 587         raise ValueError(f"'{name}' is not one of the example datasets.")
        588     urlretrieve(url, cache_path)
        589 full_path = cache_path
    

    ValueError: 'iris-data.csv' is not one of the example datasets.



```python

```
