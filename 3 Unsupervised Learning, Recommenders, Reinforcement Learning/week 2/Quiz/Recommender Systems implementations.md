### 1. Lecture described using ‘mean normalization’ to do feature scaling of the ratings. What equation below best describes this algorithm?

- [ ] $\begin{align}y_{norm}(i,j) &= \frac {y(i,j) - \mu_i}{max_i - min_i} \quad \text{where}\\ \mu_i &= \frac{1}{\sum_{j} r(i,j)} \sum_{j:r(i,j)=1} y(i,j) \end{align}$

- [x] $\begin{align}y_{norm}(i,j) &= y(i,j) - \mu_i \quad \quad \text{where}\\ \mu_i &= \frac{1}{\sum_{j} r(i,j)} \sum_{j:r(i,j)=1} y(i,j) \end{align}$

- [ ] $\begin{align}y_{norm}(i,j) &= \frac {y(i,j) - \mu_i}{\sigma_i} \quad \text{where}\\ \mu_i &= \frac{1}{\sum_{j} r(i,j)} \sum_{j:r(i,j)=1} y(i,j) \\ \sigma^2_i &= \frac{1}{\sum_{j} r(i,j)} \sum_{j:r(i,j)=1} (y(i,j) - \mu_j)^2 \end{align}$

Correct

This is the mean normalization algorithm described in lecture. This will result in a zero average value on a per-row basis.

### 2. The implementation of collaborative filtering utilized a custom training loop in TensorFlow. Is it true that TensorFlow always requires a custom training loop?

- [x] No: TensorFlow provides simplified training operations for some applications.
- [ ] Yes. TensorFlow gains flexibility by providing the user primitive operations they can combine in many ways.

Correct

Recall in Course 2, you were able to build a neural network using a ‘model’, ‘compile’, ‘fit’, sequence which managed the training for you. A custom training loop was utilized in this situation because training www, bbb, and xxx does not fit the standard layer paradigm of TensorFlow's neural network flow. There are alternate solutions such as custom layers, however, it is useful in this course to introduce you to this powerful feature of TensorFlow.

### 3. Once a model is trained, the 'distance' between features vectors gives an indication of how similar items are.

The squared distance between the two vectors x(k)\\mathbf{x}^{(k)}x(k) and x(i)\\mathbf{x}^{(i)}x(i) is:
distance=∥x(k)−x(i)∥2=∑l=1n(xl(k)−xl(i))2 distance = \\left\\Vert \\mathbf{x^{(k)}} - \\mathbf{x^{(i)}} \\right\\Vert^2 = \\sum_{l=1}^{n}(x\_l^{(k)} -x\_l^{(i)})^2distance=∥∥∥​x(k)−x(i)∥∥∥​2=∑l=1n​(xl(k)​−xl(i)​)2

Using the table below, find the closest item to the movie "Pies, Pies, Pies".

|     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- |
| Movie | User 1 | …   | User n | x0x_0x0​ | x1x_1x1​ | x2x_2x2​ |
| Pastries for Supper |     |     |     | 2.0 | 2.0 | 1.0 |
| Pies, Pies, Pies |     |     |     | 2.0 | 3.0 | 4.0 |
| Pies and You |     |     |     | 5.0 | 3.0 | 4.0 |

- [ ] Pastries for Supper
- [x] Pies and You

Correct

The distance from ‘Pies, Pies, Pies’ is 9 + 0 + 0 = 9.

### 4. Which of these is an example of the cold start problem? (Check all that apply.)

- [ ] A recommendation system takes so long to train that users get bored and leave.
- [ ] A recommendation system is so computationally expensive that it causes your computer CPU to heat up, causing your computer to need to be cooled down and restarted.
- [x] A recommendation system is unable to give accurate rating predictions for a new user that has rated few products.
Correct
A recommendation system uses user feedback to fit the prediction model.
- [x] A recommendation system is unable to give accurate rating predictions for a new product that no users have rated.
Correct
A recommendation system uses product feedback to fit the prediction model.