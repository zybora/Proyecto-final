```python
import pandas as pd

archivo_csv = pd.read_csv('iris-data.csv');
df = pd.read_csv('iris-data.csv')

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
import pandas as pd

# desde url
url = "https://raw.githubusercontent.com/plotly/datasets/master/iris-data.csv"
df = pd.read_csv(url)

# Primeras filas 
print("Primeras filas del dataset:")
print(df.head())

# Estad ́ısticas de cada columna num ́erica (utilice df.describe()). 
print("\nEstadísticas descriptivas de cada columna numérica:")
print(df.describe())

#Qu ́e columnas tiene el dataset y que representan.: representan partes de una flor
#La existencia (o no) de valores nulos. No ha valores nulos 



```

    Primeras filas del dataset:
       sepal length  sepal width  petal length  petal width        class
    0           5.1          3.5           1.4          0.2  Iris-setosa
    1           4.9          3.0           1.4          0.2  Iris-setosa
    2           4.7          3.2           1.3          0.2  Iris-setosa
    3           4.6          3.1           1.5          0.2  Iris-setosa
    4           5.0          3.6           1.4          0.2  Iris-setosa
    
    Estadísticas descriptivas de cada columna numérica:
           sepal length  sepal width  petal length  petal width
    count    150.000000   150.000000    150.000000   150.000000
    mean       5.843333     3.054000      3.758667     1.198667
    std        0.828066     0.433594      1.764420     0.763161
    min        4.300000     2.000000      1.000000     0.100000
    25%        5.100000     2.800000      1.600000     0.300000
    50%        5.800000     3.000000      4.350000     1.300000
    75%        6.400000     3.300000      5.100000     1.800000
    max        7.900000     4.400000      6.900000     2.500000
    


```python

```


```python

```
