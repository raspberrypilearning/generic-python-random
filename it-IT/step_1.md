Uno dei moduli standard in Python è il modulo `random `. Puoi usarlo per creare numeri pseudo-casuali nel tuo codice.

### randint

È possibile generare interi casuali compresi tra due valori utilizzando la funzione `randint`. Ad esempio, la seguente riga di codice produrrà un numero intero casuale compreso tra 0 e 10 (incluso).

```python
from random import randint
num = randint(0,10)
```

### uniform

Se desideri un numero casuale decimale (chiamato anche float), è possibile utilizzare la funzione `uniform`. Ad esempio, la seguente riga di codice produrrà un numero decimale casuale uguale o superiore a 0, ma inferiore a 10.

```python
from random import uniform
num = uniform(0,10)
```

### choice

Se vuoi scegliere un elemento casuale da una lista, puoi usare la funzione `choice`.

```python
from random import choice
banco = ['Asso', 'Re', 'Regina', 'Jack']
carta = choice(banco)
```
