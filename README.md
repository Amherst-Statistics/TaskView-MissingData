# TaskView-MissingData
possible materials for CRAN Task View on Missing Data

Source: https://www.analyticsvidhya.com/blog/2016/03/tutorial-powerful-packages-imputing-missing-values/ 

**MICE**
- Multiple imputation by chained equations, assumes data are missing at random

Ref: https://cran.r-project.org/web/packages/mice/mice.pdf


**Amelia**
- Uses a bootstrapping algorithm to do multiple imputations. Assumes variables in dataset have multivariate normal distribution

Ref: https://cran.r-project.org/web/packages/Amelia/Amelia.pdf 


**missForest**
- Nonparametric imputation method using the random forest algorithm.

Ref: https://cran.r-project.org/web/packages/missForest/missForest.pdf 


**Hmisc**
- The impute function imputes missing values with a user-defined statistical method, with the default being the median. The aregImpute method performs mean imputation using additive regression, bootstrapping, and predictive mean matching. It assumes linearity in the variables predicted and uses Fisher's optimum scoring to predict categorical variables.

Ref: https://cran.r-project.org/web/packages/Hmisc/Hmisc.pdf 


**mi**
- Performs multiple imputations and uses predictive mean matching method. Additionally, this package also bayesian version of regression models to handle issue of separation, looks for irregularities in data, and adds noise to imputation process to deal with additive constraints.

Ref: https://cran.r-project.org/web/packages/mi/mi.pdf


**missMDA**
- Does multiple imputations with and in principal component analysis (PCA), multiple correspondence analy-
sis (MCA) model and multiple factor analysis (MFA) models.

Ref: https://cran.r-project.org/web/packages/missMDA/missMDA.pdf 

**VIM**
- Functions to visualize missing and imputed values for further data exploration.

Ref: https://cran.r-project.org/web/packages/VIM/VIM.pdf 


**imputeTS**
- Imputation in univariate time series data.

Ref: https://cran.r-project.org/web/packages/imputeTS/imputeTS.pdf 