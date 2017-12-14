# GmAMisc (Gianmarco Alberti Miscellaneous)
vers 0.1

`GmAMisc` is a collection of functions that I have built in different points in time. The functions' aim spans from univariate outlier detection, to permutation t test, permutation chi-square test, calculation of Brainerd-Robinson similarity coefficient, validation of logistic regression models, and more. 

The package comes with some toy datasets:

`assemblage`: distribution of 7 archaeological objects across 9 assemblages.

`log_regr_data`: admission to graduate school.

`phases`: posterior probabilities for the chronological relation of the Starting and Ending boundaries of two Bayesian independent 14C phases.

`radioc_data`: posterior probabilities for the Starting and Ending boundaries of two 14C phases.


## List of implemented functions
`aucadj()`: function for optimism-adjusted AUC (internal validation).

<br>
`BRsim()`: unction for Brainerd-Robinson simiarity coefficient.

<br>
`chiperm()`: function for permutation-based chi-square test of independence.

<br>
`kwPlot()`: function for visually displaying Kruskal-Wallis test's results.

<br>
`logregr()`: function easy binary Logistic Regression and model diagnostics.

<br>
`modelvalid()`: function for binary Logistic Regression internal validation.

<br>
`mwPlot()`: function for visually displaying Mann-Whitney test's results.

<br>
`outlier`: function for univariate outliers detection.

<br>
`perm.t.test()`: function for permutation-based t-test.

<br>
`plotJenks()`: function for plotting univariate classification using Jenks' natural break method.

<br>
`ppdPlot()`: function for plotting Posterior Probability Densities for Bayesian modeled 14C dates/parameters.

<br>
`prob.phases.relat()`: unction to calculate the Posterior Probability for different chronological relations between two Bayesian radiocarbon phases.

<br>
`robustBAplot()`: function to plot a robust version of the Bland-Altman plot.


<br>
## History
`version 0.1`: first release.


## Installation
To install the package in R, just follow the few steps listed below:

1) install the `devtools` package:  
```r
install.packages("devtools", dependencies=TRUE)
```
2) load that package: 
```r
library(devtools)
```
3) download the `GmAMisc` package from GitHub via the `devtools`'s command: 
```r
install_github("gianmarcoalberti/GmAMisc@v0.1")
```
4) load the package: 
```r
library(GmAMisc)
```
5) enjoy!