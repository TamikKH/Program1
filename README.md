# Program1

Хетагуров Тамерлан Аланович
Группа пиж-б-о-22-1
```
import numpy as np
import matplotlib.pyplot as mpl
fig, ax = mpl.subplots(1,1)
t = np.arange(9, 1, 1)
x = np.sin(9*t)+np.sin(1*t)-0.1
y = np.cos(4*t)+np.cos(1*t)+0.45
mpl.plot(x,y)
mpl.show()
```
