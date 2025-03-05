# Implementation of Univariate Linear Regression
## AIM:
To implement univariate Linear Regression to fit a straight line using least squares.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Get the independent variable X and dependent variable Y.
2. Calculate the mean of the X -values and the mean of the Y -values.
3. Find the slope m of the line of best fit using the formula. 
<img width="231" alt="image" src="https://user-images.githubusercontent.com/93026020/192078527-b3b5ee3e-992f-46c4-865b-3b7ce4ac54ad.png">
4. Compute the y -intercept of the line by using the formula:
<img width="148" alt="image" src="https://user-images.githubusercontent.com/93026020/192078545-79d70b90-7e9d-4b85-9f8b-9d7548a4c5a4.png">
5. Use the slope m and the y -intercept to form the equation of the line.
6. Obtain the straight line equation Y=mX+b and plot the scatterplot.

## Program:
```
/*
import numpy as np
import matplotlib.pyplot as plt
x = np.array(eval(input()))
y = np.array(eval(input()))
m = (np.sum(x * y) - np.sum(x) * np.sum(y) / len(x)) / (np.sum(x**2) - (np.sum(x)**2) / len(x))
b = np.mean(y) - m * np.mean(x)
x_line = np.linspace(min(x), max(x), 100)
y_line = m * x_line + b
plt.scatter(x, y, color='red', label='Data Points')
plt.plot(x_line, y_line, color='blue', label=f'Line: y = {m:.2f}x + {b:.2f}')
plt.xlabel("X values")
plt.ylabel("Y values")
plt.title("Linear Regression Fit")
plt.legend()
plt.grid()
plt.show()

Developed by: Elamukilan G
RegisterNumber:212223040045
*/
```

## Output:

![download](https://github.com/user-attachments/assets/0ca75ec6-e3d4-4bde-b546-e03dacbf57f6)


## Result:
Thus the univariate Linear Regression was implemented to fit a straight line using least squares using python programming.
