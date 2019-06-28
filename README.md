# Solutions-about-risk-management-problems2

Let’s consider a portfolio of twenty assets. The log-return on each of these assets is an NRIG random variable, with shape parameter
g = 1 (in the Babbs parameterization), mean zero, and variance (0.05)^2.

The portfolio, meant to represent an index, has holdings in each of these assets, with the initial weights proportional to the first
twenty positive Fibonacci numbers (1, 1, 2, 3, 5, etc.).

We will consider two different elliptical copulas joining these random 
variables: a Gaussian copula and a Student’s-t 4 copula. In both cases the (pseudo-)correlation is 0.7 for each pair.

Please write narrative responses to the following questions about both versions of the vector-valued random variable constructed above.
Questions
1. What is the average pair-wise (Pearson’s) correlation between the assets’ log-returns? 
2. What is the average pair-wise (Kendall’s) rank correlation between the assets’ log-returns?
3. What is the standard deviation of the index log-return? 
4. What is the 5% quantile of the index log-return? 
