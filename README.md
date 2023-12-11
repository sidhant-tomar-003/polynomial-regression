# polynomial-regression
- Making a polynomial regression model from scratch, using numpy and pyplot (for utility).
- It has functionality to split datasets into train and test, with user specified ratios
- It also has a intermediate step visualization functionality, where an option in the training function allows the user to see every intermediate model
- The ipynbs themselves provide some additional tutorials to intepreting the input and output of the models. Here is a basic run down:
    - [coeff of $x^0$, coeff of $x^1$, coeff of $x^2$, coeff of $x^3$, ...]


Note:
- The "polynomial regression" ipynb has the final code in it.
- The "polynomial regression playground" ipynb was used for development. You can check that out if you want to learn how I made the library, but it is a bit disorganized.

## Goals:
- [x]  To make a model that would scan the search space for the degree of the model fitted, and return the one with the lowest RMSE. 
- [ ]  To implement this use Cython (or however they use C/C++ to accelerate libraries in python) to make this a proper lib
