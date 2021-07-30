# Introducción a NumPy
![NumPy Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/3/31/NumPy_logo_2020.svg/1280px-NumPy_logo_2020.svg.png)
## ¿Qué es NumPy?
***NumPy*** es el paquete fundamental para la computación numérica con Python.

### Objetos en NumPy

Los objetos con los que trabajamos son arreglos multidimensionales, se pueden pensar como vectores, matrices y tensores.

**Tensor**: Tensor can be represented as a multi-dimensional array.
```
[1, 2, 3, 4] -> [1.0 2.0 3.0 4.0]

[[1, 2, 3], [4, 5, 6], [7, 8, 9]] -> [[1.0 2.0 3.0],
                                      [4.0 5.0 6.0],
                                      [7.0 8.0 9.0]]
```

### Forma de importar NumPy:

```python
import numpy as np
```

**Array** : Contenedor de tamaño fijo de elementos del mismo tipo y tamaño. El número de *dimensiones* y *elementos* se define por su forma.

**Forma (Shape)** : Es una *tupla* de números enteros no negativos que especifican los tamaños de cada *dimensión*.

En NumPy las dimensiones se denominan **ejes (axes)**.

Esto significa que si tenemos un arreglo 2D (una matriz) que se ve así:

```python
[[0, 0, 0],
 [1, 1, 1]]
```

Entonces tenemos 2 ejes. El primer eje tiene una longitud de 2, y el segundo eje tiene una longitud de 3. (**shape=(2,3)**)