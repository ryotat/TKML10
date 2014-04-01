# Trace norm regularization for the estimation of low-rank tensors

Note: this is made available mainly for reproducibility. Please have a look into the [latest version](https://github.com/ryotat/tensor).

You can download Matlab scripts that reproduce the results in our technical report ["On the extension of trace norm to tensors"](http://arxiv.org/abs/1010.0789) from this page.

## Instructions
 1. Download and extract. 
 1. Also download the [N-way toolbox](http://www.models.life.ku.dk/nwaytoolbox) (for comparison).
 1. Open Matlab and type
```matlab
 test_compare;
```
 to get Figure 1, 
```matlab
 test_threshold;
```
 to get Figure 2.

## Results
You should get something like this

 ![fig1](https://raw.github.com/ryotat/TKML10/master/fig1.png)

## References
 * Nathan Halko, Per-Gunnar Martinsson, and Joel Tropp, Finding structure with randomness: Stochastic algorithms for constructing approximate matrix decompositions, arXiv:0909.4061 [math.NA; math.PR], 2009 (available at http://arxiv.org). We have included the implementation by Mark Tygert http://cims.nyu.edu/~tygert/software.html
 * Rasmus Bro & Claus A. Andersson, [The N-way toolbox for MATLAB](http://www.models.life.ku.dk/nwaytoolbox), Chemometrics & Intelligent Laboratory Systems, vol. 52, no. 1, pp. 1–4, 2000
