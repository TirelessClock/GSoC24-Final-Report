# Final Report GSoC'24

#### Organization: [mlpack](https://github.com/mlpack/mlpack)
#### Project: [Implementing XGBoost](https://summerofcode.withgoogle.com/myprojects/details/6Pa6XrQM)
#### Mentors: [Marcus Edel](https://github.com/zoq), [Omar Shrit](https://github.com/shrit), [Tarek Elsayed](https://github.com/tareknaser)

## Abstract

For GSoC'24, my project `Implementing XGBoost` was approved by mlpack. XGBoost (by Tianqi Chen et al.), short for eXtreme Gradient Boosting, became famous for its efficiency and speed, gaining traction for its performance in hackathons and ML competitive circles. As the name indicates, XGBoost was built on the Gradient Boosting framework, providing a number of additional features that optimised its performance.

## Goal

The goal of this project was to finish the XGBoost implementation inside of mlpack. Additionally, I aimed at implementing the Gradient Boosting algorithm, as well as make any relevant improvements on the mlpack's tree ensemble.

## Result

A fully functional `XGBoost` and `GradBoosting` classes were implemented and thoroughly tested. Built an `XGBTree` class as an XGBoost specific customisable Decision Tree Regressor with additional functionalities and arguments. Implemented additional functionalities like Feature Importance Measurement through XGBoost and Tree Pruning. Complex interfaces, documentation and test suites for all associated functionalities. 

## Pull Requests

### 1. XGBoost (REVIEW) [[PR#3736](https://github.com/mlpack/mlpack/pull/3736)]
In this PR, I implemented the `XGBoost` class. This included the following:

### 2. Gradient Boosting (REVIEW) [[PR#3735](https://github.com/mlpack/mlpack/pull/3735)]

### 3. Decision Tree File Organization (MERGED) [[PR#3747](https://github.com/mlpack/mlpack/pull/3747)]
In this PR, I organised several files within the Decision Tree module and changed the access paths to make them easier to access and use. 

### 4. Documentation fixes (MERGED) [[PR#3668](https://github.com/mlpack/mlpack/pull/3668) and [PR#3674](https://github.com/mlpack/mlpack/pull/3674)]
In these PRs, I made a few changes to the existing documentation. 

## Future Work
I intend to continue working on mlpack and XGBoost. My primary objective going forward would be to keep tuning my implementation of XGBoost to meet competitive benchmarks. I will also implement other features such as parallel computing, XGBoost regressor, Gradient Boosting regressor, and dataset based tree construction. I am also interested in implementing other projects within mlpack, such as improving scope for Natural Language Processing through various NLP specific algorithms. 

## Acknowledgements
I would like to take this opportunity to thank my mentors Marcus Edel, Omar Shrit and Tarek Elsayed, for their unwavering support throughout my project. They made my GSoC experience extremely comfortable and enjoyable, and I was only able to complete my goals because of their help. I also want to thank Ryan Curtin for directing me in the right direction on several occasions. Further, I thank the mlpack family for taking a chance on me and giving me this wonderful opportunity. This was truly a once-in-lifetime experience, and I discovered a lot about myself and my passions in the field. 
