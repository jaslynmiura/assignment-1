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

What are the advantages and disadvantages of a very flexible (versus a a less flexible) approach for regression? Under what circumstances might a more flexible approach be preferred to a less flexible approach? When might a less flexible approach be preferred?

> **Your Answer:**
More flexible models can fit many different possible functional forms for f. But, the more flexible the model, it more it calls for the estimation of greater number of parameters. Which makes the models more complex and risk overfitting the data, where the model follows the noise in the data too closely.

---

### Exercise 3 (ISLP exercise 6)

Describe the differences between a **parametric** and a **non-parametric** statistical learning approach. What are the **advantages** of a parametric approach to regression or classification (as opposed to a non-parametric approach)? What are its **disadvantages**?

> **Your Answer:**