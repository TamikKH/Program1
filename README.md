# Program1

Хетагуров Тамерлан Аланович
Группа пиж-б-о-22-1

import numpy as np
import matplotlib.pyplot as mpl
fig, ax = mpl.subplots(1,1)
t = np.arange(0, 300, 0.5)
x = np.cos(0*t)+np.sin(1*t)
y = np.cos(100*t)+np.sin(0*t)
mpl.plot(x,y)
mpl.show()
