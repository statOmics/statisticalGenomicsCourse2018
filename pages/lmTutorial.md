---
layout: default
title: Linear models and contrasts
mathjax: true
---
#### 1. Introdution

The linear model is one of the most widely used methods in data analysis. In this tutorial we will revisit the linear model. In particular, we will show how to incorporate both continuous and factor variables in the model. We will touroughly focus on the interpretation of the model parameters, i.e. main effects and interactions and we will show how research hypotheses can be translated into linear combinations of the model parameters.
Finally, we will implement the linear regression and statistical inference in matrix form in order to get a deep understanding of the theory of the linear model.

We will work on a dataset on the KPNA2 gene, one of the genes that was studied in a large scale microarray involving breast cancer patients.

#### 2. KPNA2 Example

Background: Histologic grade in breast cancer provides clinically important prognostic information. Researchers examined whether histologic grade was associated with gene expression profiles of breast cancers and whether such profiles could be used to improve histologic grading. In this tutorial we will assess the impact of histologic grade on expression of the KPNA2 gene that is known to be associated with poor BC prognosis.
The patients, however, do not only differ in the histologic grade, but also on their lymph node status. The lymph nodes were not affected (0) or surgically removed (1).

 1. Use the sample R-markdown file and conduct the entire analysis.
  - Perform data exploration
  - Fit the appropriate model
  - Interpret all model parameters
  - Interpret the statistical tests in the lm output
  - Formulate all research questions of interest and translate them in terms of linear combinations of the model paramaters
  - Assess all hypothesis of interest
  - Formulate a general conclusion

2. Homework: Reimplement the analysis using matrix regression
 - model parameters and contrasts of interest
 - standard errors on parameters and contrasts
 - t-test statistics on the model parameters and contrasts of interest
 - compare your results with the output of the lm(.) function
 - Details on the implementation can be found in the book Linear Models with R of Faraway (chapter 2). A free early version of the book can be found on [Practical Regression in R](http://www.maths.bath.ac.uk/~jjf23/book/)

3. Data and R markdown File
 - You can download the data and the R-markdown file on the github repository of the course. [Resources tutorial 1](https://github.com/statOmics/statisticalGenomicsCourse2018/tree/master/tutorial1)
 - You can download a file by clicking on it
 ![Figure 1.](./figs/downloadFileFig1.png)

 - Then you right click on the raw button and hitting the download linked file button.
 ![Figure 1.](./figs/downloadFileFig2.png)




#### 3. Software
All developments will be done using R/Bioconductor via the [Rstudio](https://www.rstudio.com) interface. This can be installed locally or can be launched in a browser by hitting on
[![Binder](http://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/statOmics/statisticalGenomicsCourse2018/master?urlpath=rstudio)
