# Trace norm regularization for the estimation of low-rank tensors

You can download Matlab scripts that reproduce the results in our technical report [[http://arxiv.org/abs/1010.0789|"On the extension of trace norm to tensors"]] from this page.

## Instructions
 1. Download the [[attachment:tensor.tar.gz|scripts]], and extract them. You can also [[http://www.ibis.t.u-tokyo.ac.jp/ryotat/tensor/release/|preview]] them before downloading.
 1. Also download the [[http://www.models.life.ku.dk/nwaytoolbox|N-way toolbox]] (for comparison).
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

{{attachment:fig1.png}}


## References
 * Nathan Halko, Per-Gunnar Martinsson, and Joel Tropp, Finding structure with randomness: Stochastic algorithms for constructing approximate matrix decompositions, arXiv:0909.4061 [math.NA; math.PR], 2009 (available at http://arxiv.org). We have included the implementation by Mark Tygert http://cims.nyu.edu/~tygert/software.html
 * Rasmus Bro & Claus A. Andersson, [[http://www.models.life.ku.dk/nwaytoolbox|The N-way toolbox for MATLAB]], Chemometrics & Intelligent Laboratory Systems, vol. 52, no. 1, pp. 1–4, 2000
