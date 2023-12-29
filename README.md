### Implementation of Multivariate Linear Regression

## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
Import pandas as pd.

### Step2
Read the csv file.

### Step3
Get the value of X and y variables.

### Step4

Create the linear regression model and fit.
### Step5
Predict the CO2 emission of a car where the weight is 3300kg, and the volume is 1300cm3.

### step6
Print the predicted output.

## Program:
```python
#Developed by: Abdul kalaam k m
#Reg no:23005114
import pandas as pd
from sklearn import linear_model
df=pd.read_csv("cars (1).csv")
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("Coefficient:",regr.coef_)
print("Intercept:",regr.intercept_)
print("Amount:",regr.predict([[3300,1300]]))
```
## Output:
### Insert your output
![image](https://github.com/23006860/Multivariate-Linear-Regression/assets/139841752/25cce7e4-721e-487e-b847-a41540965e3f)
## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
