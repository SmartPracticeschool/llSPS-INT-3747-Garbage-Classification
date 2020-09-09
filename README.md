# llSPS-INT-3747-Garbage-Classification
Garbage Classification
. The problem of segregation of renewable waste is a big challenge for many countries around the world. Apart from segregating waste using human hands, there are several methods for automatic segregation. The article proposes a system for classifying waste with the following classes: cardboard,glass,metal,plastic,trash,paper. The obtained results show that automatic waste classification, using image processing and artificial intelligence methods, allows building effective systems that operate in the real world.
The accuracy of the result is about 75% which can be further modified with the help of the number of epochs given.

Execution Instructions:

1.first set ur environment in anaconda navigator
create the pyhton version as 3.6   note:you can use python 3.5 aswell as per your compatibility

2.open anaconda prompt
activate envipython (your environment name )

pip install tensorflow==1.14

3.after installing the tensorflow install keras
pip install keras==2.2.4

4.after installing keras install pandas

pip install pandas and same for other module ....!!

5.open jupyter notebook

jupyter notebook

6.import these modules

import tensorflow as tf
import numpy as np
import pandas as pd 
from keras.models import Sequential 
from keras.layers import Dense 
from keras.layers import Convolution2D 
from keras.layers import MaxPooling2D 
from keras.layers import Flatten

7.train the model
model.fit_generator(x_train,samples_per_epoch=noumber of train datasets/batch size,epochs=100,validation_data=x_test,validation_steps=number of test data set/batch size) 
NOTE: The batch size I have taken is 32 which works good for almost all datasets

You can also refer to the source code in this folder.

