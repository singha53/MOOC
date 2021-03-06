Ch1-Ch2 Overview of Statistical Learning
================
Amrit Singh
February 9, 2017

-   [Chapter 1: Introduction](#chapter-1-introduction)
-   [Chapter 2: Statistical Leanring](#chapter-2-statistical-leanring)
    -   [Quiz question](#quiz-question)
    -   [2.2 R1](#r1)
    -   [2.3 R1](#r1-1)
    -   [2.3 R2](#r2)

Chapter 1: Introduction
=======================

-   opening remarks

Notes: Supervised Learning - Y: outcome measurement - X: predictor measurements - training data: (x1, y1), ..., (xN, yN)

Chapter 2: Statistical Leanring
===============================

Quiz question
-------------

2.2 R1
------

(1 point possible) A hypercube with side length 1 in d dimensions is defined to be the set of points (x1, x2, ..., xd) such that 0≤xj≤1 for all j = 1, 2, ..., d. The boundary of the hypercube is defined to be the set of all points such that there exists a j for which 0≤xj≤.05 or .95≤xj≤1 (namely, the boundary is the set of all points that have at least one dimension in the most extreme 10% of possible values). What proportion of the points in a hypercube of dimension 50 are in the boundary? (hint: you may want to calculate the volume of the non-boundary region)

Please give your answer as a value between 0 and 1 with 3 significant digits. If you think the answer is 50.52%, you should say 0.505:

> We know that the volume of the whole hypercube is 150 = 1. The volume of the interior of the hypercube is 0.950 = 0.005. Thus, the volume of the boundary is 1-0.005 = 0.995.

2.3 R1
------

(1 point possible) True or False: A fitted model with more predictors will necessarily have a lower Training Set Error than a model with fewer predictors. &gt; A: TRUE (WRONG!!) &gt; EXPLANATION &gt; False. While we typically expect a model with more predictors to have lower Training Set Error, it is not necessarily the case. An extreme counterexample would be a case where you have a model with one predictor that is always equal to the response, compared to a model with many predictors that are random.

2.3 R2
------

(1/1 point) While doing a homework assignment, you fit a Linear Model to your data set. You are thinking about changing the Linear Model to a Quadratic one. Which of the following is most likely true:

> as flexibility increases, bias decreases, variance increaes Using the Quadratic Model will decrease the Bias of your model. Using the Quadratic Model will decrease the Bias of your model. - correct
