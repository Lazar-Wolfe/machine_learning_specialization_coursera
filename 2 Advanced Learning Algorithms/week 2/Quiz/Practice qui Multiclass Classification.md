1. For a multiclass classification task that has 4 possible outputs, the sum of all the activations adds up to 1. For a multiclass classification task that has 3 possible outputs, the sum of all the activations should add up to ….

- [ ] It will vary, depending on the input x. 
- [x] 1
- [ ] More than 1
- [ ] Less than 1

Correct
Yes! The sum of all the softmax activations should add up to 1.

2. For multiclass classification, the cross entropy loss is used for training the model. If there are 4 possible classes for the output, and for a particular training example, the true class of the example is class 3 (y=3), then what does the cross entropy loss simplify to? [Hint: This loss should get smaller when a_3a 
3
​
  gets larger.]

- [x] -log(a3)

Correct
Correct. When the true label is 3, then the cross entropy loss for that training example is just the negative of the log of the activation for the third neuron of the softmax. All other terms of the cross entropy loss equation (-log(a_1),-log(a_2), and -log(a_4) −log(a 
1
​
 ),−log(a 
2
​
 ),and−log(a 
4
​
 )) are ignored

3. For multiclass classification, the recommended way to implement softmax regression is to set from_logits=True in the loss function, and also to define the model's output layer with…

- [ ] a 'softmax' activation
- [x] a 'linear' activation

Correct
Yes! Set the output as linear, because the loss function handles the calculation of the softmax with a more numerically stable method.