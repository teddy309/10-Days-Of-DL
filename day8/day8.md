# [lec08]Deep-learning: appearance of Backpropagation
Trying to make thinking machine, people tries to emitate human brain’s neuron signal method. <br>
​<img src="https://github.com/teddy309/10-Days-Of-DL/blob/master/day8/images/day8_NeuronStructure.png" style="zoom:40%;"/> <br>
<i>Neuron Structure</i>

### XOR Problem
<br>
​<img src="https://github.com/teddy309/10-Days-Of-DL/blob/master/day8/images/day8_XORproblem.png" style="zoom:40%;"/> <br>
AND/OR operations works well, but XOR operation cannot be linearly seperable.

***
### Perceptron
> A type of Neural Network that draw a binary conclusion by 0/1. Emitates neuron’s signal.
> 1969 - Marvin Minsky(MIT AI Lab founder) proved <i>W,b</i> coefficients cannot be controled at <i>Y=wX+b</i>.<br>


​<img src="https://github.com/teddy309/10-Days-Of-DL/blob/master/day8/images/day8_MultiLayeredPerceptron.png" style="zoom:40%;"/> <br>
<multi layered perceptron><br>
  
***
### Backpropagation
> 1974,1982 - suggested by Paul Werbos
> 1986 - Hinton discovered way to improve errors from backward.
>> <b>pros- able to improve errors from backwards.</b>
>> <b>cons- Backpropagation didn't work well for normal neural networks with many layers.</b>

***
### Neural Network
> 2006,2007 - Hinton suggested <b>Neural Network(Deep-Learning)</b>.
>> <b>pros- decrease ImageNet classification error rate about 26% to 15% using Convolutional Neural Network(CNN).</b>
> <b>what's different?</b>
>> 1) labeled dataset is too small.
>> 2) computer velocity.
>> 3) initializing data at first is important
>> 4) used wrong type of sigmoid(non-linearity function)
