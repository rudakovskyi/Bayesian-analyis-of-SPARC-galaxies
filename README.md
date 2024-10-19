This repository contains the results of the Bayesian analysis of the [SPARC galaxy catalogue](http://astroweb.cwru.edu/SPARC/).  
These findings are summarized in our paper: [https://arxiv.org/abs/2401.10202](https://arxiv.org/abs/2401.10202).

The folders **Bukert**, **NFW**, **RAR_fixed_a0_prior**, **RAR_flat_a0_prior**, and **RAR_gauss_a0_prior** contain corner plots with 1 and 2 sigma contours.  
The folder **Last_iter** contains last iteration outputs of DYNESTY package for models and galaxies for which sampling procedure did not converge.
The folder **Tables** contains the CSV files with:
- the calculated evidences,  
- log-likelihoods corresponding to the maximum a posteriori (MAP) parameter values,  
- MAP extended log-likelihoods (see definition in Eq. B1 of Appendix B in [arXiv:2401.10202](https://arxiv.org/abs/2401.10202)),  
- Bayesian information criteria for MAP parameter values,  
- labels regarding convergence criteria of dynamical and "usual" nested sampling,  
- MAP parameter values.
