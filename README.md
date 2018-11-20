# Bayesian Optimization for Machine Learning

Bayesian optimization is a sequential design strategy for global optimization of black-box functions that doesn't require derivatives.

## Strategy:
The Bayesian strategy in optimization:

* Objective function is unknown so the Bayesian methods treat it as a random function.
* Place a prior over it. The prior captures our beliefs about the behaviour of the function. 
* Gather function evaluations , which are treated as data.
* Update priors to form the posterior distribution over the objective function. 
* Construct an acquisition function using posterior distribution.
* Use posteriro destribution to determines what the next query point should be.

## Acquisition functions:


## Resource:
* http://neupy.com/2016/12/17/hyperparameter_optimization_for_neural_networks.html
* http://krasserm.github.io/2018/03/21/bayesian-optimization/
* http://krasserm.github.io/2018/03/19/gaussian-processes/
* https://github.com/krasserm/bayesian-machine-learning
* https://towardsdatascience.com/a-conceptual-explanation-of-bayesian-model-based-hyperparameter-optimization-for-machine-learning-b8172278050f
* https://jmhessel.github.io/Bayesian-Optimization/
* https://thuijskens.github.io/2016/12/29/bayesian-optimisation/
*
*

