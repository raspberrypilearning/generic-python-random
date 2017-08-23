One of the standard modules in Python is the `random` module. You can use it to create pseudo-random numbers in your code.

### randint

You can generate random integers between two values using the `randint` function. For example, the following line of code will produce a random integer between 0 and 10 (inclusive).

```python
from random import randint
num = randint(0,10)
```

### uniform

If you want a random floating-point number (also called float), you can use the `uniform` function. For example, the following line of code will produce a random float that's equal to or greater than 0, but less than 10.

```python
from random import uniform
num = uniform(0,10)
```

### choice

If you want to choose a random item from a list, you can use the `choice` function.

```python
from random import choice
deck = ['Ace', 'King', 'Queen', 'Jack']
card = choice(deck)
```
