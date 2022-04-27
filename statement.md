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

mx = (p1.x + p2.x + p3.x) / 3
my = (p1.y + p2.y + p3.y) / 3

print(math.hypot(p1.x-mx, p1.y-my))
print(math.hypot(p2.x-mx, p2.y-my))
print(math.hypot(p3.x-mx, p3.y-my))
```



