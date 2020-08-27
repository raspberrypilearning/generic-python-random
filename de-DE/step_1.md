Eines der Standardmodule in Python ist das `random` (Zufalls) -Modul. Du kannst es verwenden, um pseudo-zufällige Zahlen in deinem Code zu erstellen.

### randint

Du kannst zufällige Ganzzahlen zwischen zwei Werten generieren, indem du die `randint` Funktion verwendest. Zum Beispiel erzeugt die folgende Codezeile eine zufällige Ganzzahl zwischen 0 und 10 (inklusive).

```python
from random import randint
num = randint(0,10)
```

### uniform

Wenn du eine zufällige Fließkommazahl (auch float genannt) haben willst, kannst du die `uniform` Funktion verwenden. Zum Beispiel erzeugt die folgende Codezeile eine zufällige Fließkommazahl, der gleich oder größer als 0 ist, aber kleiner als 10.

```python
from random import uniform
num = uniform(0,10)
```

### choice

Wenn du ein zufälliges Element aus einer Liste auswählen möchtest, kannst du die `choice` Funktion verwenden.

```python
from random import choice
deck = ['Ass', 'Koenig', 'Dame', 'Bube']
karte = choice(deck)
```
