Ένα από τα τυπικά modules στην Python είναι το module `random` (τυχαίο). Μπορείς να τo χρησιμοποιήσεις για να δημιουργήσεις ψευδο-τυχαίους αριθμούς στον κώδικά σου.

### randint

Μπορείς να δημιουργήσεις τυχαίους ακέραιους αριθμούς μεταξύ δύο τιμών χρησιμοποιώντας την συνάρτηση `randint`. Για παράδειγμα, η ακόλουθη γραμμή κώδικα θα παράγει έναν τυχαίο ακέραιο μεταξύ 0 και 10 (συμπεριλαμβανομένου του 10).

```python
from random import randint
num = randint(0,10)
```

### uniform

Εάν θέλεις έναν τυχαίο αριθμό κινητής υποδιαστολής (που ονομάζεται επίσης float), μπορείς να χρησιμοποιήσεις την συνάρτηση `uniform`. Για παράδειγμα, η ακόλουθη γραμμή κώδικα θα παράγει ένα τυχαίο float ίσο ή μεγαλύτερο από 0, αλλά μικρότερο από 10.

```python
from random import uniform
num = uniform(0,10)
```

### choice

Εάν θέλεις να επιλέξεις ένα τυχαίο στοιχείο από μια λίστα, μπορείς να χρησιμοποιήσεις την συνάρτηση `choice`.

```python
from random import choice
deck = ['Ace', 'King', 'Queen', 'Jack']
card = choice(deck)
```
