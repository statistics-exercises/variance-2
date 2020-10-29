# Least-squares for Geometric random variable

__To complete this exercise you need to what you just did for the Bernoulli random variable for a geometric random variable.  You will need to look up the expression for the expectation of the geometric random variable.__  This expression should then be inserted into the expression for the "spread" that was introduced in the last exercise.  To arrive at the estimator you then need to minimise the expression for the spread as was demonstrated in the explanation for the last exercise. 

__Once you have derived an expression for the estimator you will need to write code in the panel on the left that shows how the estimator for p depends on the number of samples it is computed from.__  To complete the exercise you will need to  

1. Finish the function `geometric`. This function should take a single argument ``p. It should return a geometric random variable from a distribution with parameter `p`. 
2. Set the first element of the array called `indices` equal to 1, the second element of the array called `indices` to 2 and so on.
3.Set the first element of the array called `estimator` equal to an estimate of the parameter of the distribution that is calculated by generating 1 geometric random variable with parameter `pval`, the second element of the array called `estimator` equal to an estimate of the parameter of the distribution that is calculated by generating 2 geometric random variables with parameter `pval`, set the third element of the array called `estimator` equal to an estimate of the parameter of the distribution that is calculated by generating 3 geometric random variables with parameter `pval` and so on until you have computed an estimate of the parameter of the distribution from 200 geometric random variables. 

When your code is complete a graph will be generated.  The red dots are the values of the least-squares estimator for the parameter of the distribution you sampled from.  The black dashed line is then the true value of the parameter.  You should see that the estimator converges to the true value of the parameter.  
