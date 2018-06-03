# Knee Axis Computation using a Recurrent Neural Network (RNN)

Author: Ryan J. Richards

Description: Calculate the knee joint axis of rotation using a Recurrent Neural Network (RNN).

## 1. Introduction/Methodology

include gif here of stick figure visual (preferably knee motion)


## 2. Code

## 2.1 Create training/test Data Set

Use rotation matrices/tensors to create training and test data set with known AOR vector. The final training/test dataset will be formatted as follows:

| | Point (x,y,z) Sequence  | AOR vector (from origin)  |
| :-------------:  | :-------------:           |:------------:|
|Sequence 0| (x1, y1, z1), (x2, y2, z2), …. , (xn, yn, zn)             | (x,y,z)                  |
|Sequence 1| (x1, y1, z1), (x2, y2, z2), …. , (xn, yn, zn)             | (x,y,z)                  |
|...| ...                   | ..                    |
|Sequence n| (x1, y1, z1), (x2, y2, z2), …. , (xn, yn, zn)             | (x,y,z)                  |

Here's a visual of what we are testing...


## 2.2

 ```python
# Network Parameters
num_input = 3 # spatial point group input
timesteps = 100 # timesteps (amount of points included)
num_hidden = 128 # hidden layer num of features
num_classes = 3 # AOR total classes (single point group)
```




