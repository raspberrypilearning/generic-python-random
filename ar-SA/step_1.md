إحدى الوحدات القياسية في Python هي وحدة ` عشوائي `. يمكنك استخدامه لإنشاء أرقام عشوائية مزيفة في التعليمات البرمجية الخاصة بك.

### randint

يمكنك إنشاء أعداد صحيحة عشوائية بين قيمتين باستخدام دالة `randint`. على سبيل المثال، السطر التالي من التعليمات البرمجية سينتج عدداً صحيحاً عشوائياً بين 0 و 10 (ضمنياً).

```python
from random import randint
num = randint(0,10)
```

### uniform

إذا كنت ترغب في رقم عشوائي (عشري) ، يمكنك استخدام دالة `uniform`. على سبيل المثال، السطر التالي من التعليمات البرمجية سينتج ارقام عشرية عشوائية أكبر او تساوي 0 ، ولكن أقل من 10.

```python
from random import uniform
num = uniform(0,10)
```

### choice

إذا كنت ترغب في اختيار عنصر عشوائي من قائمة ، يمكنك استخدام دالة `choice`.

```python
from random import choice
deck = ['الآيس', 'ملك', 'ملكة', 'جاك']
card = choice(deck)
```
