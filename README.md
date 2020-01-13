# mobile-payment-adoption

**PLEASE NOTE:** 

This project will no longer be developed and should now be considered deprecated in favor of the newer project repository https://github.com/sedelmeyer/rare-events-analysis.

## Summary

This repository contains an original statistical analysis I authored in 2012 while in graduate school, titled "[Conditions for Consumer Acceptance of Mobile Payment Methods In the United States](https://github.com/sedelmeyer/mobile-payment-adoption/blob/master/Sedelmeyer_MobilePayment_20120503.pdf)." Please excuse errors and questionable choices regarding factor selection and interpretation. 

My original analysis was conducted using Stata version 11, which has been commited to this repository as: [SCPC2009_stata.do](https://github.com/sedelmeyer/mobile-payment-adoption/blob/master/SCPC2009_stata.do)

**For practice in R and Python, I am attempting to:**
1. replicate my original Rare Event Logit (relogit) statistical analysis in both of those languages,
1. extend the analysis training other models for analysis (e.g. random forests, LDA, etc.), and
1. then (if possible) test model performance against additional years of survey data.

**Replication/extension attempts in R and Python are documented in the attached Jupyter notebooks (file extension .ipynb).**

## Data Source
The data source used for the original analysis is the Federal Reserve Bank of Boston's 2009 Survey of Consumer Payment Choice. While it appears that the original .dta file is no longer available on the BOS FED's website, the original source URL for that data was: http://www.bos.frb.org/economic/cprc/SCPC/index.htm 

## See Also

Gary King and Langche Zeng. 2001. “Logistic Regression in Rare Events Data.” Political Analysis, 9, Pp. 137–163: https://gking.harvard.edu/files/abs/0s-abs.shtml

Michael Tomz, Gary King, & Langche Zeng. "ReLogit: Rare Events Logistic Regression." Journal of Statistical Software [Online], 8.2 (2003): 1 - 27. Web. 9 Sep. 2017: https://www.jstatsoft.org/article/view/v008i02

Federal Reserve Bank of Boston, Survey of Consumer Payment Choice: https://www.bostonfed.org/publications/survey-of-consumer-payment-choice.aspx
