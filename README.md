# Classification-Of-Articles

 1: Intro to Bayes Theorem and how we want to find p(y = ci/ X = x)
 2: Naive assumption and how that simplifies our work
 3: How to estimate probabilities using training data assuming discrete valued features
 4: Handling zeroes using Laplace correction

## INTRODUCTION TO BAYES THEOREM
Bayes Theorem defines probability of an event based on the prior knowledge of factors that might be related to an event.

#### Mathematical Statement of Bayes Theorem is as follows :
![image](https://user-images.githubusercontent.com/40559132/42380984-4c58f854-814d-11e8-8ab5-f6c64c392f56.png)

Now, basically  for a data point xi, we have to predict the class that the current output Y belongs to. Assume, there are total 'j' number of classes for output.<br/>
Then, <br/>
P(y=c1|x=xi) ---> tells us that for given input xi what is the probability that y is c1. <br/>
P(y=c2|x=xi) ---> tells us that for given input xi what is the probability that y is c2. <br/>
and so on till cj. <br/><br/>

Out of all these probabilities calculations, y belongs to that particular class which has maximum probability.


