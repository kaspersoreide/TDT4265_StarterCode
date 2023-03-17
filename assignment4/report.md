# TDT4265 Assignment 4
*Kasper Midttun Søreide*

## Task 1
a)<br>
IoU is short for Intersection over Union. It is the ratio between the intersection and the union of the guessed bounding box and the actual bounding box. In the figure below the green box is the actual bounding box and the blue one a guess. The intersection is the light blue area and the union is the gray area plus the light blue area.

![task1a](./images/IoU.png)
<br><br>
b)<br>

$$Precision = {TP \over TP + FP} $$ 

$$Recall = {TP \over TP + FN} $$ 

TP stands for true positive, FP stands for false positive, and FN stands for false negative. A true positive is when a neural net recognizes an object and is correct. A false positive occurs when the NN recognizes an object that isn't present.

<br>
c)<br>

## Task 2
f) 
![task2f](./task2/precision_recall_curve.png)

## Task 3
b)<br>
False. The deeper levels have lower resolution images, therefore recognizing bigger objects.
<br>

## Task 4