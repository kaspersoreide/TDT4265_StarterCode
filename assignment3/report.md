# TDT4265 Assignment 3
### Kasper Midttun Søreide

## Task 1
a)
![task1a](./convolution.jpg)
b)<br>
Convolutional layer
<br><br>
c)<br>
padding of 3, because the convolution should be done on the edges.
<br><br>
d)<br>
5x5
<br><br>
e)<br>
254*254
<br><br>
f)<br>
For each convolutional layer, the number of parameters is: filter size * number of filters. So for just the convolutions we get:<br>
5*5*32 + 5*5*64 + 5*5*128 = 5600<br>
For the fully connected we have get the number of inputs * number of outputs + biases. The number of inputs for the fully connected layer is 4*4*128. So we get:<br>
4*4*128 * 64 + 64 = 2112<br>
So, in total we get 5600 + 2112 = 7712


## Task 2
Below is a plot of training, validation and test accuracy
![task2b](./plots/task2_plot.png)

## Task 3

## Task 4
When training stopped, these were the final results:<br>
Validation Loss: 0.33, Validation Accuracy: 0.902<br>
Figure showing validation and test loss during training:<br>

