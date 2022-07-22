1. Which of the following can address overfitting?

- [ ] Remove a random set of training examples
- [x] Collect more training data
Correct
If the model trains on more data, it may generalize better to new examples.
- [x] Select a subset of the more relevant features.
Correct
If the model trains on the more relevant features, and not on the less useful features, it may generalize better to new examples.
- [x] Apply regularization
Correct
Regularization is used to reduce overfitting.

2. You fit logistic regression with polynomial features to a dataset, and your model looks like this. 
What would you conclude? (Pick one)

- [ ] The model has high bias (underfit). Thus, adding data is, by itself, unlikely to help much. 
- [ ] The model has high variance (overfit). Thus, adding data is, by itself, unlikely to help much. 
The model has high variance (overfit). Thus, adding data is likely to help
- [x] The model has high bias (underfit). Thus, adding data is likely to help
Correct
- [ ] The model has high variance (it overfits the training data). Adding data (more training examples) can help.

3. Suppose you have a regularized linear regression model.  If you increase the regularization parameter \lambdaλ, what do you expect to happen to the parameters w_1,w_2,...,w_nw 
1
​
 ,w 
2
​
 ,...,w 
n
​
 ?

- [ ] This will increase the size of the parameters w_1,w_2,..., w_nw 
1
​
 ,w 
2
​
 ,...,w 
n
​
 


- [x] This will reduce the size of the parameters w_1,w_2,..., w_nw 
1
​
 ,w 
2
​
 ,...,w 
n
​
  

Correct
Regularization reduces overfitting by reducing the size of the parameters w_1,w_2,...w_nw 
1
​
 ,w 
2
​
 ,...w 
n
​
 .

