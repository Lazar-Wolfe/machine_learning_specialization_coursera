## Week 1 Quiz - Neural Network Model

1. For a neural network, what is the expression for calculating the activation of the third neuron in layer 2? Note, this is different from the question that you saw in the lecture video.

- [x] a<sup>[2]</sup><sub>{3}</sub>=g( \vec{w}<sup>[2]</sup><sub>3</sub> ⋅ \vec{a}<sup>[1]</sup> + b<sup>[2]</sup><sub>3</sub> )a 3[2] =g(w3[2] ⋅ a[1] +b3[2] ) 

Correct
Yes! The superscript [2] refers to layer 2. The subscript 3 refers to the neuron in that layer. The input to layer 2 is the activation vector from layer 1.

2. For the handwriting recognition task discussed in lecture, what is the output a^{[3]}_1a 1[3]
 ?
- [ ] A vector of several numbers, each of which is either exactly 0 or 1 
- [x] The estimated probability that the input image is of a number 1, a number that ranges from 0 to 1.
- [ ] A vector of several numbers that take values between 0 and 1 
- [ ] A number that is either exactly 0 or 1, comprising the network’s prediction 
Correct
Yes! The neural network outputs a single number between 0 and 1.
