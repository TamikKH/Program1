# Program1

Хетагуров Тамерлан Аланович
Группа пиж-б-о-22-1
```
import numpy as np
import matplotlib.pyplot as mpl
fig, ax = mpl.subplots(1,1)
t = np.arange(4, 20, 0.7)
x = np.cos(5*t)+np.cos(4*t)-0.1
y = np.sin(6*t)+np.sin(7*t)+0.45
mpl.plot(x,y)
mpl.show()
```
