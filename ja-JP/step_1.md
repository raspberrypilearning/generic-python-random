Pythonの標準モジュールのひとつに`random`（乱数）モジュールがあります。 これを使うとコードの中で疑似乱数（ぎじらんすう）をつくることができます。

### randint

`randint`関数を使うと、2つの値の間のランダムな整数を生成することができます。 たとえば、次のコード行では0以上10以下のランダムな整数値を生成します。

```python
from random import randint
num = randint(0,10)
```

### uniform

ランダムな浮動小数点数（float（浮動小数）とも呼ばれます）が必要な場合は、`uniform`関数が使えます。 たとえば、次のコード行は0以上10未満のランダムな浮動小数を生成します。

```python
from random import uniform
num = uniform(0,10)
```

### choice

リストからランダムに項目を選びたいときは、`choice`関数が使えます。

```python
from random import choice
deck = ['Ace', 'King', 'Queen', 'Jack']
card = choice(deck)
```
