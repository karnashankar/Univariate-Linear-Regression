# Implementation of Univariate Linear Regression
## Aim:
To implement univariate Linear Regression to fit a straight line using least squares.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the independent variable X and dependent variable Y.
2.	Calculate the mean of the X -values and the mean of the Y -values.
3.	Find the slope m of the line of best fit using the formula.
 ![eqn1](./eq1.jpg)
4.	Compute the y -intercept of the line by using the formula:
![eqn2](./eq2.jpg)  
5.	Use the slope m and the y -intercept to form the equation of the line.
6.	Obtain the straight line equation Y=mX+b and plot the scatterplot.
## Program
```
Developed by:karna s
Register Number:22008977
```
```
import numpy as n
import matplotlib.pylot as plt
X = np.array(eval(input()))
y = np.array(eval(input()))
Xmean = np.mean(x)
ymean = np.mean(y)
num, den = 0, 0
for i in range(len(X)):
    mum += (X[i]-Xmean)*(y[i]-Ymean)
    den += (X[i]-Xmean)**2
m = num/den
c = ymean-m*Xmean
print(m, c)
Y_pred = m*X+C
plt.scatter(x, y)
plt.plot(X, Y_pred colum"")
plt.show()




```
## Output
<img width="469" alt="image" src="https://user-images.githubusercontent.com/121109150/214907806-56d276cf-1055-4342-bbaa-ca0da89f9256.png">




## Result
Thus the univariate Linear Regression was implemented to fit a straight line using least squares.
