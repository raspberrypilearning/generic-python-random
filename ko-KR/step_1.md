파이썬에서 기본적인 모듈 중 하나는 바로 `random` 모듈입니다. 이를 사용하여 Code에서 랜덤한 값을 생성할 수 있습니다.

### randint 함수

`randint` 함수를 사용해 주어진 두 값 사이의 랜덤한 정수를 생성할 수 있습니다. 예를 들어, 다음 코드는 0에서 10사이의 임의의 정수를 생성합니다. (0과 10 포함)

```python
from random import randint
num = randint(0,10)
```

### uniform 함수

랜덤한 부동 소수점 수(실수) 가 필요하다면 `uniform` 함수를 사용할 수 있습니다. 예를 들어, 다음 코드는 0이상 10이하인 랜덤한 부동 소수점 수를 생성합니다.

```python
from random import uniform
num = uniform(0,10)
```

### choice 함수

리스트에서 랜덤한 값을 선택하려면 `choice` 함수를 사용할 수 있습니다.

```python
from random import choice
deck = ['Ace', 'King', 'Queen', 'Jack']
card = choice(deck)
```
