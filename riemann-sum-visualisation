import numpy as np
import matplotlib.pyplot as plt

def f(x):
  return x**2
x1 = int(input("enter the start of the interval:"))
x2 = int (input("enter the end of the interval:"))
n = int(input("enter no. of squares:"))
h = (x2-x1) /n
x = np.linspace(x1,x2-h,n)
y = f(x)
area = np.sum(y)*h
plt.plot(x,y,color = "red")
plt.bar( x,y,width=h,align="edge",alpha= 0.3, color= "green", edgecolor = "black")
plt.xlim(x1-0.5, x2+0.5)

plt.title(f"The calculated Area is: {area:.2f}")
plt.show()
