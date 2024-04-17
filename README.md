Fork with some advantages from 3.0.x like working `from __future__ import annotations` (usable for things like kivy Android apps build)

For example code like that will compile and work fine:

```python
from __future__ import annotations

class B:
    ...

a: int = 5
b: B = B()
c: E = 9  # class E not really exist, but work

print(a, b)
```
