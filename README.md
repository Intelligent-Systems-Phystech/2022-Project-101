<div align="center">
  <H1>
    Stochastic Newton with Arbitrary Sampling
  </H1>
  Melnikov Igor
</div>
<div align="center">
 <br>Scientific advisors: Islamov Rustem, Vadim Strijov<br>
</div>

## Annotation
Empirical Risk Minimization problem is a common problem in machine learning methods. In the article we analyze Newton-type methods of Empirical Risk Minimization problem for some Machine Learning model using Newton-type method accessing one data point per iteration. Specifically, by applying existing sampling strategies we plan to improve stochastic second-order method presented in the paper Stochastic Newton and Cubic Newton Methods with Simple Local Linear-Quadratic Rates. We focus on sampling strategies from Parallel coordinate descent methods for big data optimization.


## Experiment
To run experiment use *run_experiment* function in Experiment.ipynb file. It takes batch sizes list, lambda list, sampling type.

## Plots
To draw a plot you could use methods *speed_batch_plot*, *speed_lambda_plot*, *convergwnce_plot* from draw.ipynb file. 
Each method takes input (experiment data) file and output file.
