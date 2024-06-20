# Prediction-using-supervised-ml-LinearRegression-
!pip install matplotlib
import numpy as np
import matplotlib.pyplot as plt
from sklearn.linear_model import LinearRegression
ages = np.array([20, 25, 30, 35, 40, 45, 50, 55, 60, 65, 70]).reshape(-1,1)
weights = np.array([70, 72, 75, 80, 85, 88, 92, 95, 97, 100,110]).reshape(-1,1)
ages
model = LinearRegression()
!pip install scikit-learn
model.fit(ages,weights)
m = model.coef_
c = model.intercept_
print(m,c)
predicted_weights = model.predict(ages)
predicted_weights
weights
model.score(ages,weights)
model.score(ages,predicted_weights)
plt.scatter(ages,weights,color='cyan')
plt.plot(ages,predicted_weights,color='purple')
plt.xlabel('age(yrs)')
plt.ylabel('weights(kg)')
plt.title('linear regression of weights on age')
plt.grid(True)
plt.show
