![image-20191104123037890](C:\Users\설계경영\AppData\Roaming\Typora\typora-user-images\image-20191104123037890.png)

Trying to make thinking machine, people tries to emitate human brain’s neuron signal method. 

AND/OR operations works well, but XOR operation cannot be linearly seperable.



![image-20191104123113086](C:\Users\설계경영\AppData\Roaming\Typora\typora-user-images\image-20191104123113086.png)

Perceptron: A type of Neural Network that draw a binary conclusion by 0/1. Emitates neuron’s signal.

1969 Marvin Minsky(MIT AI Lab founder) proved W,b coefficients cannot be controled at Y=wX+b.



![image-20191104123117777](C:\Users\설계경영\AppData\Roaming\Typora\typora-user-images\image-20191104123117777.png)

<multi layered perceptron>

Backpropagation

(1974,1982 suggested by Paul Werbos, 1986 Hinton discovered way to improve errors from backward.)

pros- able to improve errors from backwards.

cons- Backpropagation didn't work well for normal neural networks with many layers.



2006,2007 Hinton suggested Neural Network(Deep-Learning).

pros- decrease ImageNet classification error rate about 26% to 15% using Convolutional Neural Network(CNN). 

what's different?

1) labeled dataset is too small.

2) computer velocity.

3) initializing data at first is important

4) used wrong type of sigmoid(non-linearity function)