1. Which of the following is a valid step used during feature scaling? 

- [ ]Add the mean (average) from each value and and then divide by the (max - min).
- [x]Subtract the mean (average) from each value and then divide by the (max - min).
Correct
This is called mean normalization.

2. Suppose a friend ran gradient descent three separate times with three choices of the learning rate \alphaα and plotted the learning curves for each (cost J for each iteration).
For which case, A or B, was the learning rate \alphaα likely too large?

- [x]case B only
- [ ]Both Cases A and B
- [ ]case A only 
- [ ]Neither Case A nor B 

Correct
The cost is increasing as training continues, which likely indicates that the learning rate alpha is too large.

3. Of the circumstances below, for which one is feature scaling particularly helpful?

- [x]Feature scaling is helpful when one feature is much larger (or smaller) than another feature.
- [ ]Feature scaling is helpful when all the features in the original data (before scaling is applied) range from 0 to 1.

Correct
For example, the “house size” in square feet may be as high as 2,000, which is much larger than the feature “number of bedrooms” having a value between 1 and 5 for most houses in the modern era.

4. You are helping a grocery store predict its revenue, and have data on its items sold per week, and price per item. What could be a useful engineered feature?

- [ ]For each product, calculate the number of items sold divided by the price per item.
- [x]For each product, calculate the number of items sold times price per item.

Correct
This feature can be interpreted as the revenue generated for each product.

5.
Question 5
True/False? With polynomial regression, the predicted values f_w,b(x) does not necessarily have to be a straight line (or linear) function of the input feature x.

- [ ]False 
- [x]True

Correct
A polynomial function can be non-linear.  This can potentially help the model to fit the training data better.