# Factoring Total
[![PyPI version](https://badge.fury.io/py/FactoringTotal.svg)](https://pypi.org/project/FactoringTotal)


## Descripción
Libreria para convertir numeros a letras para sistemas de facturacion y tambien incorpora una funcion para entregar los dias de mora. 

## Instalación
```
pip install numbers_letters
```

## Uso básico
```python
from numeros_let import NumerosLetras

test = NumerosLetras()

numero = 11111111.0
resultado = test.numero_to_letras(numero)
print(resultado)
```
Obtendremos el siguiente resultado:
```python
ONCE MILLONES CIENTO ONCE MIL CIENTO ONCE con  00/100
```

