### 1. You have the following table of movie ratings:

|     |     |     |     |     |
| --- | --- | --- | --- | --- |
| Movie | Elissa | Zach | Barry | Terry |
| Football Forever | 5   | 4   | 3   | ?   |
| Pies, Pies, Pies | 1   | ?   | 5   | 4   |
| Linear Algebra Live | 4   | 5   | ?   | 1   |

Refer to the table above for question 1 and 2. Assume numbering starts at 1 for this quiz, so the rating for Football Forever by Elissa is at (1,1)

What is the value of nun_unu​

- [x] 4

Correct

This is the number of users. nmn_mnm​ is the number of movies/items and is 3 in this table.

### 2. What is the value of r(2,2)
- [x] 0

Correct

r(i,j)r(i,j)r(i,j) is a 1 if the movie has a rating and 0 if it does not. In the table above, a question mark indicates there is no rating.

### 3.

Question 3

In which of the following situations will a collaborative filtering system be the most appropriate learning algorithm (compared to linear or logistic regression)?
- [x] You run an online bookstore and collect the ratings of many users. You want to use this to identify what books are "similar" to each other (i.e., if a user likes a certain book, what are other books that they might also like?)
- [ ] You subscribe to an online video streaming service, and are not satisfied with their movie suggestions. You download all your viewing for the last 10 years and rate each item. You assign each item a genre. Using your ratings and genre assignment, you learn to predict how you will rate new movies based on the genre.
- [ ] You're an artist and hand-paint portraits for your clients. Each client gets a different portrait (of themselves) and gives you 1-5 star rating feedback, and each client purchases at most 1 portrait. You'd like to predict what rating your next customer will give you.
- [ ] You manage an online bookstore and you have the book ratings from many users. You want to learn to predict the expected sales volume (number of books sold) as a function of the average rating of a book.

Correct

You can find "similar" books by learning feature values using collaborative filtering.

### 4. For recommender systems with binary labels y, which of these are reasonable ways for defining when yyy should be 1 for a given user jjj and item iii? (Check all that apply.)

- [x] y is 1 if user j purchases item i (after being shown the item)

Correct

Purchasing an item shows a user's preference for that item. It also shows that an item is preferred by a user.
- [ ] y is 1 if user j has been shown item i by the recommendation engine
- [x] y is 1 if user j fav/likes/clicks on item i (after being shown the item)

Correct
fav/likes/clicks on an item shows a user's interest in that item. It also shows that an item is interesting to a user.
- [ ] y is 1 if user j has not yet been shown item i by the recommendation engine