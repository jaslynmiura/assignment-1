# Homework 1 Task 3

---

Answer the following questions based on exercises from *An Introduction to Statistical Learning with Applications in Python*.

## Chapter 2.4 Exercises

---

### Exercise 1 (ISLP exercise 2)

Explain whether each scenario is a **classification or regression** problem, and indicate whether we are most interested in **inference or prediction**. Finally, provide **n** (size of observation dataset) and **p** (number of predictors).

**(a)**  We collect data on 200 protected marine reserves worldwide. For each reserve we record species richness, reserve size, years since establishment, enforcement budget, and proximity to human settlements. We are interested in understanding which factors affect species richness.

> **Your Answer:** 
Regression problem since the response is species richness - a qualitative response.
We are interested in inference since we want to understand the factors that affect species richness, rather than estimating species richness.
n = 200, p = 4

---

**(b)** A conservation agency wants to know whether a proposed habitat corridor will successfully support wildlife movement or fail to do so. They collect data on 30 previously established corridors. For each corridor they have recorded whether wildlife movement was successful or unsuccessful, corridor width, length, surrounding land use type, and eight other variables.

> **Your Answer:**
This is a classification problem since the response is succeed/failure of wildlife movement - a binary, qualitative response.
We are interested in prediction since we want to understand whether the proposed habitat corridor will be successful or not.
n = 30, p = 11

---

**(c)** We are interested in predicting weekly average ground-level ozone concentration in a coastal city. We collect weekly data for all of 2019. For each week we record average ozone concentration, sea surface temperature, wind speed, solar radiation, and atmospheric

> **Your Answer:**
This is a regression problem since the response is weekly average ground-level ozone concentration - a quantitative response.
We are interested in prediction since we want to predict the weekly average ground-level ozone concentration in a coastal city.
n = 52, p = 4

---

### Exercise 2 (ISLP exercise 5)

What are the advantages and disadvantages of a very flexible (versus a less flexible) approach for regression? Under what circumstances might a more flexible approach be preferred to a less flexible approach? When might a less flexible approach be preferred?

> **Your Answer:**

The advantages of a very flexible approach for regression is the ability to fit many different possible functional forms for *f*, such as non-linear relationships. A disadvantage of a flexible model is the fact that it calls for the estimation of a greater number of parameters. With more parameters a model can become more complex and overfit the data. A flexible approach should be applied to models with many observations, where the relationship may be complex and may contain a non-linear relationship. A less flexible approach can be applied in circumstances where there is a smaller amount of observations. We also want a less flexible approach when our goal is inference, where our predictors matter and we're able to interpret our coefficients.

---

### Exercise 3 (ISLP exercise 6)

Describe the differences between a **parametric** and a **non-parametric** statistical learning approach. What are the **advantages** of a parametric approach to regression or classification (as opposed to a non-parametric approach)? What are its **disadvantages**?

> **Your Answer:**

A parametric approach makes an assumption about the functional form or shape of *f*, where training data is used to train or fit the model to obtain parameters that will define the estimate *f-hat*. A non-parametric approach does not make assumptions about the funtional form of *f*. Instead it tries to find estimates that fit the training data, without being too rough. The advantages of parametric approach is that it is easier to draw inferences from, it can be used with small training sets, and it is computationally easier to estimate the parameters. The disadvantages of a parameteric approach, is the fact that the form of *f* that we assume/define, may be far from the true form of *f*, which in turn can influence our predictions and lead us to make inaccurate inferences.