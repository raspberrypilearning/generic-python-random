Un des modules standards en Python est le module `random`. Tu peux l'utiliser pour créer des nombres pseudo-aléatoires dans ton code.

### randint

Tu peux générer des entiers aléatoires entre deux valeurs en utilisant la fonction `randint` . Par exemple, la ligne de code suivante produira un entier aléatoire compris entre 0 et 10 (inclus).

```python
from random import randint
num = randint(0,10)
```

### uniform

Si tu veux un nombre aléatoire à virgule flottante (également appelé float), tu peux utiliser la fonction `uniform`. Par exemple, la ligne de code suivante produira un float aléatoire égal ou supérieur à 0, mais inférieur à 10.

```python
from random import uniform
num = uniform(0,10)
```

### choice

Si tu veux choisir un élément aléatoire dans une liste, tu peux utiliser la fonction `choice`.

```python
from random import choice
jeu = ['As', 'Roi', 'Reine', 'Valet']
carte = choice(jeu)
```
