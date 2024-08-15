# Final Report GSoC'24

#### Organization: [mlpack](https://github.com/mlpack/mlpack)
#### Project: [Implementing XGBoost](https://summerofcode.withgoogle.com/myprojects/details/6Pa6XrQM)
#### Mentors: [Marcus Edel](https://github.com/zoq), [Omar Shrit](https://github.com/shrit), [Tarek Elsayed](https://github.com/tareknaser)

## Abstract

For GSoC'24, my project `Implementing XGBoost` was approved by mlpack. XGBoost (by Tianqi Chen et al.), short for eXtreme Gradient Boosting, became famous for its efficiency and speed, gaining traction for its performance in hackathons and ML competitive circles. As the name indicates, XGBoost was built on the Gradient Boosting framework, providing a number of additional features that optimised its performance.

## Goal

The goal of this project was to finish the XGBoost implementation inside of mlpack. Additionally, I aimed at implementing the Gradient Boosting algorithm, as well as make any relevant improvements on the mlpack's tree ensemble.

## Result

A fully functional `XGBoost` and `GradBoosting` classes were implemented and thoroughly tested. Built an `XGBTree` class as a 
