---
layout: default
title: Statistical Genomics
---

![IntroFig](./pages/figs/IntroFig.png)

### Course Description
High throughput statOmics studies generate ever larger datasets and, as a consequence, complex data interpretation challenges. This course focuses on the statistical concepts involved in preprocessing, quantification and differential analysis of high throughput omics data. Moreover, more advanced experimental designs and blocking will also be introduced. The core focus will be on shotgun proteomics and next generation sequencing. The course will rely exclusively on free and userfriendly opensource tools in R/Bioconductor. The course will provide a solid basis for beginners, but will also bring new perspectives to those already familiar with standard data interpretation procedures in proteomics and NGS.

Students can sharpen their background knowledge on Mass Spectrometry, Proteomics & Bioinformatics for Proteomics
 here:
[Mass Spectrometry and Bioinformatics for Proteomics](pages/techVideos.md)



### Target Audience
This course is oriented towards biologists and bioinformaticians with a particular interest in differential analysis for quantitative 'omics.

### Prerequisites
The prerequisites for the Statistical Genomics course are the successful completion of a basic course of statistics that covers topics on data exploration and descriptive statistics, statistical modeling, and inference: linear models, confidence intervals, t-tests, F-tests, anova, chi-squared test.

The basis concepts may be revisited in the free e-book Practical Regression and Anova using R of J. Faraway. The book and additional material is freely available on
http://www.maths.bath.ac.uk/~jjf23/book/​

- Brief introduction to R: appendix C
- Linear models: Chapter 1-3, 7, 8.1-8.2, 12
- Anova: Chapter 16.1-16.2


---

#### Software

#### Topics

**Introduction**

  1. Intro
  - Slides: [Intro](assets/intro.pdf)

  2. Recap of linear models
  - Slides:  [Recap Linear Model](assets/lm.pdf)
  - Tutorial1: [Linear Model Tutorial](pages/lmTutorial.md)
  - **Homework 1**: Complete the [Rmarkdown notebook](pages/tutorialI_KPNA2_solutionPartI.nb.html). The source notebook for the partial solution can be found on [Rmarkdown notebook](assets/tutorialI_KPNA2_solutionPartI.Rmd). More details can be found in [Tutorial1](pages/lmTutorial.md). 
  - **Due date Homework Sunday 14/10/2018 midnight**:  Work in groups of 4-5 students. Upload the html file from your notebook on minerva. Only upload one file per group.   

**Part I: Quantitative proteomics**
 
  0. Software and Data
  - [Install and Launch Statistical Software](pages/software4stats.md)
  - [Download Tutorial Data](https://github.com/statOmics/pda/tree/data)
 

  1. Bioinformatics for proteomics
  - Slides: [Bioinformatics for Proteomics](assets/martens_proteomics_bioinformatics_20171001.pdf)

  2. Identification
  - Slides:  [False Discovery Rate and Target Decoy Approach](assets/1_Identification_Evaluation_Target_Decoy_Approach.pdf)
  - Tutorial: [Evaluating Target Decoy Quality](pages/Identification.md)  


  3. Preprocessing & Analysis of Label Free Quantitative Proteomics Experiments with Simple Designs
  - Slides: [Preprocessing](assets/2_MSqRob_data_analysisI.pdf), [Results of Preprocessing](assets/2_MSqRob_data_analysisIb.pdf)
  - Tutorial: [preprocessing](pages/sdaMsqrobSimple.md)
  
  4. Statistical Inference & Analysis of Experiments with Factorial Designs
  - Slides: [Inference](assets/2_MSqRob_data_analysisII.pdf) 
  - Tutorial: [Statistical Data Analysis with MSqRob for Factorial Designs](pages/sdaMsqrobDesign.md)
  - [Robust Regression Notebook](pages/robustRegression.nb.html)
  - **Homework 2**: Perform the analysis for the entire CPTAC6 spike-in study. More details can be found in the [tutorial page](pages/sdaMsqrobDesign.md). Also assess the performance using MA-plots.  
  - **Due date Howework 2 Sunday 11/11/2018 midnight**:  Work in groups of 4-5 students. Upload the html file from your notebook on minerva. Only upload one file per group.   

**Part II: Next-generation sequencing**

  1. Introduction to RNA-seq
  - Slides: [Intro to RNA-seq](assets/rna-seq1.pdf), [Multiple testing](assets/multipleTesting.pdf), [Stagewise testing](assets/stagewiseTesting.pdf) 
  - Tutorial: [Intro to RNA-seq](pages/introToRNA-seqDE.html), [Temporary Hammer Analysis](pages/hammer_tmp.nb.html)

  2. Algorithms and inference for RNA-seq differential analysis
  - Slides: [Algorithms and inference for RNA-seq](assets/rna-seq2.pdf) 

---

##### [Instructors](pages/instructors.md)
