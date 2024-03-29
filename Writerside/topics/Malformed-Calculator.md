# Malformed Calculator

```Python

import re

while True:
    x = input()
    if x == "Stop": break
    if re.match(r'\d+[+\-*/]\d+', x): print(int(eval(x)))

```

![image_4.png](image_4.png)