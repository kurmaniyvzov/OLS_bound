# Proof of the OLS bound

*Contributors: Ulanbek Kurmaniyazov, [Nadir Nuralin](https://github.com/nadir2k)*

### Project description:
The aim of this project is to prove the thorem of the OLS upper bound from the book of Mehryar Mohri, Afshin Rostamizadeh, and Ameet Talwalkar called ["Foundations of Machine Learning"](https://cs.nyu.edu/~mohri/mlbook/). The theorem is included in the ipynb file with the description. 

We

### Requirements:
The code was written in Python, and uses these libraries: `numpy`, `sklearn`, `pandas`, `matplotlib`.

### Data:
`cancer_reg.csv` - in order to verify the results of the experiment, we have used real dataset on cancer death rates in the US, that was aggregated from a number of sources including the American Community Survey. Dataset contains of 33 columns with 3400 rows of data and is licensed in the public domain and is freely available. 

### Specific functions:
`LinearRegression()` - function of the `sklearn.linear_models` module that fits the linear model.
`make_regression()` - function of the `sklearn.datasets` module that generates the dataset of regression problem with the certain parameters.
`mean_squared_error` - function of the `sklearn.metrics` module that returns the Mean-Squared-Error regression loss.
