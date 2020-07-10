Um dos módulos padrão do Python é o módulo `random`. Você pode usá-lo para criar números pseudo-aleatórios no seu código.

### randint

Você pode gerar números inteiros aleatórios entre dois valores usando a função `randint`. Por exemplo, a seguinte linha de código produzirá um número inteiro aleatório entre 0 e 10 (inclusive).

```python
from random import randint
num = randint(0,10)
```

### uniform

Se você quiser um número aleatório de ponto flutuante, você pode usar a função `uniform`. Por exemplo, a seguinte linha de código irá produzir um número de ponto flutuante aleatório igual ou maior que 0, mas menor que 10.

```python
from random import uniform
num = uniform(0,10)
```

### choice

Se você quiser escolher um item aleatório de uma lista, você pode usar a função `choice`.

```python
from random import choice
baralho = ['Ás', 'Rei', 'Rainha', 'Valete']
carta = choice(baralho)
```
