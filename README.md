# Week 1
## Machine Learning - Coursera 
[Classroom Link](https://www.coursera.org/learn/machine-learning/home/welcome)
### Introduction
[Lecture slides](https://d18ky98rnyall9.cloudfront.net/_974fa7509d583eabb592839f9716fe25_Lecture1.pdf?Expires=1601683200&Signature=jdlQS9QmiQ9Zffbje~qneQnVf79WF0-a4IOS22D0a1ivSQ2BthZaNSkAowYDkR47Hz-L1J1r8QYzACRBDnhA5dy1hokPhdrCmBK5qroykV5O8z2ZVbNapDIC1kQw4SdG0quPTJuTqiKH5KsXmtiFjHbVoDaCRHYEpW29zSK9kHs_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)

**1. Two definitions**
  * Arthur Samuel 1959:  Field of study that gives computers the ability to learn without being explicitly programmed. 
  * Tom Mitchell 1998: Well-posed Learning Problem: A computer program is said to learn from **experience E** with respect to some **task T** and some **performance measure P**, if its performance on T, as measured by P, improves with experience E. 
  
**2. Supervised learning**
  * Classification: discrete valued output (0 or 1)
  * Regression: predict continuous valued output 
  
**3. Unsupervised learning**
  * Clusters
  * Unclusters
  
**4. Others**
  * Reinforcement learning 
  * Recommender systems
  
### Linear Model 
[Lecture slides](https://d18ky98rnyall9.cloudfront.net/_ec21cea314b2ac7d9e627706501b5baa_Lecture2.pdf?Expires=1601683200&Signature=YC3kVU2q9f9IoHW1jiu9t-SljWNY-nzV8FxWfCiVjICnFVOVsLiWABRcmOY2oqUX6xrS3NGRdRranjr~ecpGhwMKKdb7kibzDuUv8UzhLS4BRzbSEQykWwLUwhg7CqHsqMhUCqmbk4OxxQRwluKG3PaabO7q3Puxc7YzE9URWE4_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)

![alt text](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/H6qTdZmYEeaagxL7xdFKxA_2f0f671110e8f7446bb2b5b2f75a8874_Screenshot-2016-10-23-20.14.58.png?expiry=1601683200000&hmac=d_h2MUmv5OBq4mnDBRZsxmRO7Tq8XLYdfYe3O0AbS4E)

If the target value y we are trying to predict is continuous, then it's a regression problem;

If y is of discrete values, then it's a classification problem. 

**1. Determining parameters**
 * Cost function, or square error function: the difference between the sum of the predicted outcome and the real output is minimized 
 
 ![alt text](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/R2YF5Lj3EeajLxLfjQiSjg_110c901f58043f995a35b31431935290_Screen-Shot-2016-12-02-at-5.23.31-PM.png?expiry=1601683200000&hmac=53dl4kVhs0vbs39XGzOiZ5ZmBEgS79ZjGcJrMfCFZtY)
 
**2. Gradient descent: minimizing functions**

 * Start with some initial values of (theta0, theta1), keep changing theta 0 and theta 1 to reduce the value of J(theta0, theta1), until end up at a minimum J

 * Simultananeous updates of theta 0 and theta 1

 * Batch gradient descent: each step uses all training data

**3. Gradient descent algorithm** 

![alt text](https://2.bp.blogspot.com/-AdV-O-MoZHE/TtLibFTaf9I/AAAAAAAAAVM/aOxUGP7zl98/s1600/gradient+descent+algorithm+OLS.png)

### Linear Algebra Review

**1. Matrix**
