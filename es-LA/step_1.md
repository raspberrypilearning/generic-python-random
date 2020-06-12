Uno de los módulos estándar en Python es el módulo `random`. Puedes usarlo para crear números pseudo-aleatorios en tu código.

### randint

Puedes generar enteros aleatorios entre dos valores usando la función `randint`. Por ejemplo, la siguiente línea de código producirá un entero aleatorio entre 0 y 10 (inclusivo).

```python
from random import randint
num = randint(0,10)
```

### uniform

Si quieres un número de punto flotante aleatorio (también llamado float), puedes usar la función `uniform`. Por ejemplo, la siguiente línea de código producirá un flotante aleatorio igual o mayor que 0, pero menor que 10.

```python
from random import uniform
num = uniform(0,10)
```

### choice

Si quieres elegir un elemento aleatorio de una lista, puedes usar la función `choice`.

```python
from random import choice
baraja = ['As', 'Rey', 'Reina', 'Jota']
carta = choice(baraja)
```
