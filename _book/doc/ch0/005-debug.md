### DEBUG

###### 标准库pbd

```
python -m pdb test_pdb.py
```

![pdb命令](../images/005-01.jpg)

```python
#/usr/bin/python
from __future__ import print_function
import pdb
def sum_nums(n):
    s=0
    for i in range(n):
        pdb.set_trace()
        s += i
        print(s)
if __name__ == '__main__':
    sum_nums(5)
```

###### ipbd

```
pip install ipbd
```
