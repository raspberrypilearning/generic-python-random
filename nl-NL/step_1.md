Een van de standaardmodules in Python is de `random` module. Je kunt het gebruiken om pseudo-willekeurige getallen in je code te maken.

### randint

Je kunt willekeurige gehele getallen tussen twee waarden genereren met de functie `randint`. De volgende coderegel produceert bijvoorbeeld een willekeurig geheel getal tussen 0 en 10 (inclusief).

```python
from random import randint
getal = randint(0,10)
```

### uniform

Als je een willekeurig getal met drijvende komma (ook float genoemd) wilt, kun je de functie `uniform` gebruiken. De volgende coderegel zal bijvoorbeeld een willekeurige float produceren die gelijk is aan of groter is dan 0, maar minder dan 10.

```python
from random import uniform
getal = uniform(0,10)
```

### keuze

Als je een willekeurig item uit een lijst wilt kiezen, kun je de functie `choice` gebruiken.

```python
from random import choice
kaarten = ['Aas', 'Heer', 'Vrouw', 'Boer']
kaart = choice(kaarten)
```
