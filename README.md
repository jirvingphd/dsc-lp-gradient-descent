---
title: 
layout: post
weight: 10
hidden: true
---

===


**Course**: DS   <br/>
**Mod**: Mod 4 V2             <br/>
**Topic**: Gradient Descent / Logistic Regression   <br/>
**Amount of time**: 60  minutes  <br/>
**Author**: Laura Colon-Melendez


***

#### Lesson Summary:

Gradient descent is discussed in more detail in this lesson plan. (Many of the concepts discussed in this lesson have been covered beforehand.) Gradient descent is presented as an iterative numerical technique that allows you to find the minimum of functions of one or more than one variable. The analogy between gradient descent and climbing down a mountain is presented and can be used throughout this lesson to help students develop an intutition surrounding gradient descent. Students are reminded about derivatives and what happens to derivatives of functions close to their optimal points (derivatives tend to zero). Then, gradient descent is used to find the minimum of a function of one variable. Next, the application of gradient descent to simple linear regression is discussed. Students are reminded about the mean squared error and the cost function for linear regression. The partial derivatives of the cost function with respect to its parameters are given to students. Students are asked to write Python code to compute cost (total error) as a prelude to having to write the equations to compute the partial derivatives when applying gradient descent to the cost function. A sample exercise is given to students where they have to use gradient descent to find the parameters for a line of best fit in a simple linear regression. Finally, if time permits, the sigmoid function is presented to students and they're asked brief conceptual questions regarding its use in logistic regression. 



#### Topic:

Gradient Descent; logistic regression

#### Learn.co material:

[Gradient Descent Review](https://github.com/learn-co-curriculum/dsc-gradient-descent-review)

[Gradient Descent - Lab](https://github.com/learn-co-curriculum/dsc-gradient-descent-lab)

Briefly:

[Linear to Logistic Regression](https://github.com/learn-co-curriculum/dsc-linear-to-logistic-regression)


#### Prerequisite knowledge: 

* Students should be familiar with the basics of multiple linear regression, including the cost function. 

* Students should understand the concept of mean squared error.

* Students should understand the concept of derivatives, partial derivatives, and the gradient of a function.

* Students should be able to apply rules such as the addition rule and the chain rule to compute derivatives.

* Students should be familiar with the basics of logistic regression. 

#### Prerequisite Learn.co material:

[Applying Gradient Descent - Lab](https://github.com/learn-co-curriculum/dsc-applying-gradient-descent-lab)

[Linear to Logistic Regression](https://github.com/learn-co-curriculum/dsc-linear-to-logistic-regression)

#### Learning goals for this lesson:

* Students should be able to find the minimum of 1-d functions using gradient descent using Python and compare to analytical results.  

* Students should be able to apply gradient descent to simple linear regression to find the line of best fit. 

* Students should understand why the sigmoid function is used in logistic regression. 

#### Relevant learning goals from Airtable 

* ADVANCED_LOG_REG.3.rechZYJ6Xqnw8TdTX

* LOG_REG.1.recehsK7hhgbVV6Nj

#### Misconceptions / Notes

* Translating some of the equations to Python could be challenging to some students.

* The concept of partial derivatives of a function and of the gradient of a function might need to be reinforced. 

#### Materials

- Ipython notebook

#### External Resources

[StatQuest with Josh Starmer - Gradient Descent, Step-by-Step](https://www.youtube.com/watch?v=sDv4f4s2SB8)

[Reducing Loss: Optimizing Learning Rate](https://developers.google.com/machine-learning/crash-course/fitter/graph)

#### Vocab / Concepts 

* Gradient
* Sigmoid function


#### Lesson Outline:

* Introduction to gradient descent (10-15 minutes)
    * Mountain analogy 
    * Review of partial derivatives and gradient of a function 
    * Importance of learning rate  
    
* Gradient descent in 1-d (15 minutes) 
    * Review: derivatives of functions close to critical values. **Important concept!**
    * Go over the gradient descent algorithm with students step by step.
    
* Application of Gradient Descent to Simple Linear Regression (25 minutes) 
    * Cost function = Mean squared error
    * Starter code is provided to the students. The most challenging part of this exercise is getting the updates for the parameters right, which boils down to coding the partial derivatives of the cost function with respect to m and b correctly. 
    * Students should plot the cost function and notice that as the number of iterations increases, the decrease in the cost "slows down". __It's important to tie this back to what happens to the slope/rate of change of a function close to a critical point; this is why the question is presented in the previous section of questions for gradient descent in 1d.__

* If time permits: (if time runs out, ask students to complete section on their own)
    * Sigmoid function and its connection to logistic regression
    
* Summary (5 minutes)

If you have any wiggle room, go over the sigmoid function. 