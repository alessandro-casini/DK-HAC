## DK-HAC: *D*ouble *K*ernel *H*eteroskedasticity and *A*utocorrelation *C*onsisstent Estimator/Standard Errors 

**Keywords:** HAC, Robust Standard Errors, HAR, Long-run variance, Prewhitening, Covariance Matrix.

This software implements the DK-HAC covariance matrix estimators/standard errors in [Casini (2021)](https://alessandro-casini.com/wp-content/uploads/2021/03/CASINI_HAC.pdf) and [Casini and Perron (2021b)](https://alessandro-casini.com/wp-content/uploads/2021/03/CASINI_PERRON_DKHAC_Prewhitening.pdf). 

The DK-HAC estimator extends the [Newey-West's (1987, 1994)](https://en.wikipedia.org/wiki/Newey%E2%80%93West_estimator) and [Andrews' (1991)](https://www.jstor.org/stable/2938229?seq=1) HAC estimators to account flexibly for nonstationarity (i.e., breaks, time-varying parameters/volatility, regime swicthing, misspecification, outliers, etc.). See [Casini et al. (2021)](https://alessandro-casini.com/wp-content/uploads/2021/03/CASINI_et_al_Low_Freq_Contamination_HAR.pdf) for a tecnical comparison.  

The software includes ordinary functions for regression analysis with robust (DK-HAC) standard errors including t-test, F-test, standard errors, R-squared and other popular regression outputs.

The software includes also the following tools:
* Data-dependent methods for the choice of the number of lagged autocovariances as developed in [Casini (2021)](https://alessandro-casini.com/wp content/uploads/2021/03/CASINI_HAC.pdf) and [Belotti et al. (2021)](https://alessandro-casini.com/research/). 
* Prewhitening procedure as developed in [Casini and Perron (2021b)](https://alessandro-casini.com/wp-content/uploads/2021/03/CASINI_PERRON_DKHAC_Prewhitening.pdf).
* Pre-test for nonstationarity to improve finite-sample performance as developed in [Casini and Perron (2021a)](https://alessandro-casini.com/wp-content/uploads/2021/03/CASINI_PERRON_Change-Point_Spectrum_SLS.pdf).

## Non-Technical Summary for Empirical Research
In preparation.

## Software available in Matlab, R and Stata

* Matlab Package (to be uploaded later)
* R Package (to be uploaded later)
* Stata Package (to be uploaded later)

## Contributors
* [Federico Belotti](https://economia.uniroma2.it/faculty/333/belotti-federico), University of Rome Tor Vergata.
* [Alessandro Casini](https://alessandro-casini.com), University of Rome Tor Vergata.
* [Leopoldo Catania](https://pure.au.dk/portal/en/persons/id(5d29f2ff-3942-4a3d-a74d-006b55ae3836).html), Aarhus University.
* [Taosong Deng](https://tsdeng.mystrikingly.com/), Boston University.
* [Stefano Grassi](https://economia.uniroma2.it/faculty/412/grassi-stefano), University of Rome Tor Vergata.
* [Pierre Perron](http://blogs.bu.edu/perron/), Boston University.

## Background Papers
* Belotti, F., A. Casini, L. Catania, S. Grassi and P. Perron, ["Simultaneous Bandwidths Determination for DK-HAC Estimators and Long-Run Variance Estimation in Nonparametric Settings"].(https://alessandro-casini.com/research/) arXiv preprint arXiv. 
* Casini, A. (2019), ["Improved Methods for Statistical Inference in the Context Various Type of Parameter Variation"](https://open.bu.edu/handle/2144/38750). Ph.D Dissertation, Boston University.
* Casini, A. (2021), ["Theory of Evolutionary Spectra for Heteroskedasticity and Autocorrelation Robust Inference in Possibly Misspecified and Nonstationary Models"](https://alessandro-casini.com/research/). arXiv preprint arXiv.
* Casini, A. and P. Perron (2021a), ["Theory of Low Frequency Contamination from Nonstationarity and Misspecification: Consequences for HAR Inference"](https://alessandro-casini.com/wp-content/uploads/2021/03/CASINI_et_al_Low_Freq_Contamination_HAR.pdf). arXiv preprint arXiv 
* Casini, A. and P. Perron (2021a), ["Change-Point Analysis of Time Series with Evolutionary Spectra"](https://alessandro-casini.com/wp-content/uploads/2021/03/CASINI_PERRON_Change-Point_Spectrum_SLS.pdf). arXiv preprint arXiv 
* Casini, A. and P. Perron (2021b), ["Minimax MSE Bounds and Nonlinear VAR Prewhitening for Long-Run Variance Estimation Under Nonstationarity"](https://alessandro-casini.com/wp-content/uploads/2021/03/CASINI_PERRON_DKHAC_Prewhitening.pdf). arXiv preprint arXiv 

## Maintaner and Correspondence
* [Alessandro Casini](https://alessandro-casini.com), University of Rome Tor Vergata.


