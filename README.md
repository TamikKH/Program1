# Program1

Хетагуров Тамерлан Аланович
Группа пиж-б-о-22-1
```
import numpy as np
import matplotlib.pyplot as mpl
fig, ax = mpl.subplots(1,1)
t = np.arange(4, 2, 1)
x = np.cos(2*t)+np.sin(4*t)-0.1
y = np.cos(6*t)+np.sin(2*t)+0.45
mpl.plot(x,y)
mpl.show()
```
