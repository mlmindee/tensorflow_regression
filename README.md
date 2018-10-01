# tensorflow_regression

You can open the files in linear and polynomimal folders by using numpy.load function.

In each folder you have 2 train files and 2 validation files : one corresponding to the features and the other for the labels 


```python
import numpy as np 

x_train = np.load('./linear/x_train.npy')
y_train = np.load('./linear/y_train.npy')

x_val = np.load('./linear/x_val.npy')
y_val = np.load('./linear/y_val.npy')

```
