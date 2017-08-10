Perceptron step works as follows. For a point with coordinates (p,q) , label y, and prediction given by the equation 
Y_hat= step(w1x1 + w2x2 +b)

* If the point is correctly classified, do nothing.
* If the point is classified positive, but it has a negative label, subtract alpha*p,alpha*q, and alpha to w1, w2 and b respectively.
* If the point is classified negative, but it has a positive label, add alpha*p,alpha*q, and alpha to w1, w2 and b respectively.

![Screenshot](../img/output.jpg)