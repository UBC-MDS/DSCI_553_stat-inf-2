Welcome to DSCI 553: Statistical Inference and Computation II
============================

This course will introduce Bayesian reasoning for Data Science on an inferential and predictive framework while eventually emphasizing regression analysis. We will learn how to formulate and implement inference using the prior-to-posterior paradigm.

## High-Level Goals

By the end of the course, students are expected to:

- Use Bayesian reasoning when modelling data.
- Apply Bayesian statistics to regression models.
- Compare and contrast Bayesian and frequentist methods, and evaluate their relative strengths.
- Use appropriate statistical libraries and packages for performing Bayesian inference.

## Lecture Schedule

This course occurs during **Block 5** in the 2024/25 school year. Course notes can be accessed [**here**](https://ubc-mds.github.io/DSCI_553_stat-inf-2/). **Typically, you should review these notes before each lecture.** There are also optional textbook readings we suggest reviewing before each lecture (if possible).

| Lecture | Topic | Optional Reading Material |
| :---:   | --- | --- |
| 1 | [**Frequentist and Bayesian Overview, Probabilistic Generative Models, and `Stan`**](https://ubc-mds.github.io/DSCI_553_stat-inf-2/notes/lecture1_intro_and_stan.html) | <ul><li>Bayes Rules! [Chapter 1: The Big (Bayesian) Picture](https://www.bayesrulesbook.com/chapter-1.html)<li>[Getting started with `rstan`](https://github.com/stan-dev/rstan/wiki/RStan-Getting-Started)</ul> |
| 2 | [**Conditional Probabilities, Bayes' Rule, and Maximum a Posteriori Estimation**](https://ubc-mds.github.io/DSCI_553_stat-inf-2/notes/lecture2_Bayes_MAP.html) | <ul><li>Bayes Rules! [2.1 Building a Bayesian model for events](https://www.bayesrulesbook.com/chapter-2.html#building-a-bayesian-model-for-events)<li>Bayes Rules! [2.2 Example: Pop vs soda vs coke](https://www.bayesrulesbook.com/chapter-2.html#michelle-simple)</ul> |
| 3 | [**Bayesian Statistics in Action: The Beta-Binomial Model**](https://ubc-mds.github.io/DSCI_553_stat-inf-2/notes/lecture3_beta_binomial_Bayesian_modelling.html) | <ul><li>Bayes Rules! [Chapter 3: The Beta-Binomial Bayesian Model](https://www.bayesrulesbook.com/chapter-3.html)<li>Bayes Rules! [Chapter 8: Posterior Inference & Prediction (Introduction)](https://www.bayesrulesbook.com/chapter-8.html)<li>Bayes Rules! [8.1 Posterior estimation](https://www.bayesrulesbook.com/chapter-8.html#chapter-8-estimation)</ul>|
| 4 | [**Markov Chain Monte Carlo, `Stan`, and Complex Bayesian Models**](https://ubc-mds.github.io/DSCI_553_stat-inf-2/notes/lecture4_MCMC_Poisson_Gamma_Normal.html) | <ul><li>Bayes Rules! [Chapter 6: Approximating the Posterior (Introduction)](https://www.bayesrulesbook.com/chapter-6.html)<li>Bayes Rules! [6.2 Markov chains via `rstan`](https://www.bayesrulesbook.com/chapter-6.html#markov-chains-via-rstan)<li>Bayes Rules! [6.2.1 A Beta-Binomial example](https://www.bayesrulesbook.com/chapter-6.html#a-beta-binomial-example)<li>Bayes Rules! [Chapter 7: MCMC under the Hood (Introduction)](https://www.bayesrulesbook.com/chapter-7.html)<li>Bayes Rules! [7.1 The big idea](https://www.bayesrulesbook.com/chapter-7.html#the-big-idea)<li>Bayes Rules! [7.2 The Metropolis-Hastings algorithm](https://www.bayesrulesbook.com/chapter-7.html#the-metropolis-hastings-algorithm)<li>Bayes Rules! [7.6 Why the algorithm works](https://www.bayesrulesbook.com/chapter-7.html#why-the-algorithm-works)</ul>|
| 5 | [**Bayesian Normal Linear Regression and Hypothesis Testing**](https://ubc-mds.github.io/DSCI_553_stat-inf-2/notes/lecture5_hypothesis_testing_intro_regression.html) | <ul><li>Bayes Rules! [8.2 Posterior hypothesis testing](https://www.bayesrulesbook.com/chapter-8.html#posterior-hypothesis-testing)<li>Bayes Rules! [Chapter 9: Simple Normal Regression (Sections 9.1 to 9.5)](https://www.bayesrulesbook.com/chapter-9.html)</ul>|
| 6 | [**Bayesian Binary Logistic Regression**](https://ubc-mds.github.io/DSCI_553_stat-inf-2/notes/lecture6_binary_logistic_regression.html) | <ul><li>Bayes Rules! [Chapter 13:  Logistic Regression (Sections 13.1 to 13.3)](https://www.bayesrulesbook.com/chapter-13.html#ch13-post-sim-sec)</ul>|
| 7 | [**Bayesian Hierarchical Models**](https://ubc-mds.github.io/DSCI_553_stat-inf-2/notes/lecture7_hierarchical_models.html) | <ul><li>Bayes Rules! [Chapter 15:  Hierarchical Models are Exciting](https://www.bayesrulesbook.com/chapter-15.html#no-pooling)</ul>|
| 8 | [**More Hierarchical Modelling and MCMC Diagnostics**](https://ubc-mds.github.io/DSCI_553_stat-inf-2/notes/lecture8_model_diagnostics.html) | <ul><li>Bayes Rules! [Chapter 6:  Approximating the Posterior (Section 6.3)](https://www.bayesrulesbook.com/chapter-6.html#diagnostics)</ul>|

See the [lecture learning objectives](lecture-learning-objectives.md) for a detailed breakdown of lecture-by-lecture learning objectives.

## Deliverables

This is an **assignment-based course**. The following deliverables will determine your course grade:

| Assessment       | Weight  | 
| :---:            | :---:   |
| Lab Assignment 1 | 12%     |
| Lab Assignment 2 | 12%     |
| Lab Assignment 3 | 12%     |
| Lab Assignment 4 | 12%     |
| Quiz 1           | 25%     |
| Quiz 2           | 25%     |
| Lecture Attendance | 2% |

## Use of LLMs

LLMs, such as ChatGPT, can be helpful tools if we use them responsibly. In this course, students are permitted to use these tools to gather more information, review concepts, or brainstorm, and students must cite these tools if they use them for assignment. Having said all this, it is **not** permitted to write any given assignment via copying and pasting AI-generated responses.

## Installation

In this course, we will be using `Stan` as our inference engine along with the `R` package `rstan`. If you did not installed the software last term, [**follow the installation instructions here**](https://ubc-mds.github.io/resources_pages/installation_instructions/).

If you have installation troubles, please seek our help as soon as possible! **You can also use the #installation channel on Slack.**

## Reference Material

### Course textbook:

* [Bayes Rules! An Introduction to Bayesian Modeling with R](https://www.bayesrulesbook.com/)

### Other books:

* [ThinkBayes](https://allendowney.github.io/ThinkBayes2/) (Python)
* [Doing Bayesian Data Analysis in brms and the tidyverse](https://bookdown.org/ajkurz/DBDA_recoded/) (R)
* [Probabilistic Programming and Bayesian Methods for Hackers](https://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/) (Python)
* [Introduction to Empirical Bayes: Examples from Baseball Statistics](https://gumroad.com/l/empirical-bayes) (R)
* [Statistical Rethinking: A Bayesian Course with Examples in R and Stan](http://xcelab.net/rm/statistical-rethinking/) (R)

### Blog posts / other:

* [Quora: For a non-expert, what is the difference between Bayesian and frequentist approaches?](https://www.quora.com/For-a-non-expert-what-is-the-difference-between-Bayesian-and-frequentist-approaches)
* [Probability concepts explained: Bayesian inference for parameter estimation](https://towardsdatascience.com/probability-concepts-explained-bayesian-inference-for-parameter-estimation-90e8930e5348)
* [MLE and MAP video](https://www.youtube.com/watch?v=y7KJcCltR5Y&list=PLWmXHcz_53Q02ZLeAxigki1JZFfCO6M-b&index=24&t=0s) from Mike Gelbart's CPSC 340.
* Web apps for visualizing probability distributions: [one](https://www.essycode.com/distribution-viewer/), [another](https://homepage.divms.uiowa.edu/~mbognar/)
* [How Statisticians Found Air France Flight 447 Two Years After It Crashed Into Atlantic](https://www.technologyreview.com/2014/05/27/13283/how-statisticians-found-air-france-flight-447-two-years-after-it-crashed-into-atlantic/)

## Recommended Course Reviews

This course is taught in `R` (we will follow the [`tidyverse` style guide](https://style.tidyverse.org/index.html)) and `Stan` with a reasonable mathematical, statistical, and programming basis. We strongly recommend reviewing the following courses:

- *DSCI 551: Descriptive Statistics and Probability for Data Science*, for basic statistical and probabilistic concepts, and familiarity with the mathematical notation.
- *DSCI 552: Statistical Inference and Computation I*, for statistical inference concepts with a frequentist approach.
- *DSCI 561: Regression I*, for ordinary ordinary least-squares (OLS).
- *DSCI 562: Regression II*, for generalized linear models (GLMs).
- *DSCI 531: Data Visualization I*, for plotting tools using the package `ggplot2`.

## Policies

See the general [MDS policies](https://ubc-mds.github.io/policies/).

## Attribution
    
The course is built upon previous years' materials developed by previous instructors.

## License

© 2025 G. Alexi Rodríguez-Arelis, Hedayat Zarkoob, Michael Gelbart, and Trevor Campbell

Software licensed under [the MIT License](https://spdx.org/licenses/MIT.html), non-software content licensed under [the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) License](https://creativecommons.org/licenses/by-nc-sa/4.0/). See the [license file](LICENSE.md) for more information.
