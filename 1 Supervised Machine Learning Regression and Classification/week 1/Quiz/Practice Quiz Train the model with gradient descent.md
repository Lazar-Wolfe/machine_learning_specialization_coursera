1. Gradient descent is an algorithm for finding values of parameters w and b that minimize the cost function J. 
When \frac{\partial J(w,b)}{\partial w} 
∂w
∂J(w,b)
  is a negative number (less than zero), what happens to w after one update step?

- [x] w increases.
- [ ] w stays the same 
- [ ] w decreases
- [ ] It is not possible to tell if w will increase or decrease. 

Correct
The learning rate is always a positive number, so if you take W minus a negative number, you end up with a new value for W that is larger (more positive).

2. For linear regression, what is the update step for parameter b?


b = b - \alpha \frac{1}{m} \sum\limits_{i=1}^{m} (f_{w,b}(x^{(i)}) - y^{(i)})b=b−α 
m
1
​
  
i=1
∑
m
​
 (f 
w,b
​
 (x 
(i)
 )−y 
(i)
 )
 
Correct
The update step is b = b - \alpha \frac{\partial J(w,b)}{\partial w}b=b−α 
∂w
∂J(w,b)
​
  where \frac{\partial J(w,b)}{\partial b} 
∂b
∂J(w,b)
​
  can be computed with this expression: \sum\limits_{i=1}^{m} (f_{w,b}(x^{(i)}) - y^{(i)}) 
i=1
∑
m
​
 (f 
w,b
​
 (x 
(i)
 )−y 
(i)
 )