# Welcome!

This Python template lets you get started quickly with a simple one-page playground.

```python runnable
print('Hello World!')
```

```python runnable
from dataclasses import dataclass
import math

@dataclass
class Point:
    x: int
    y: int


p1 = Point(0, 0)
p2 = Point(100, 0)
p3 = Point(0, 100)

print(math.hypot(p1.x-p2.x, p1.y-p2.y))
```



