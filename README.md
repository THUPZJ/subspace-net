# Subspace Network: Deep Multi-Task Censored Regression

## Abstract
Over the past decade a wide spectrum of machine learning models have been 
developed to model the neurodegenerative diseases, associating biomarkers, especially
non-intrusive neuroimaging markers, with key clinical scores measuring
the cognitive status of patients. Multi-task learning (MTL) has been commonly utilized by these studies to address high dimensionality and small cohort size challenges. However, most existing MTL 
approaches are based on linear models and suffer from two major limitations: 1) they cannot
explicitly consider upper/lower bounds in these clinical scores; 2) they lack the capability to capture complicated non-linear interactions among the variables. In this paper, we propose *Subspace Network*, an efficient
deep modeling approach for non-linear multi-task censored regression. Each
layer of the subspace network performs a multi-task censored regression to
improve upon the predictions from the last layer via sketching a 
low-dimensional subspace to perform knowledge transfer among learning tasks. Under mild assumptions, for each layer the parametric
subspace can be recovered using only one pass of training data. Empirical results demonstrate that the proposed subspace network quickly picks up 
the correct parameter subspaces, and outperforms state-of-the-arts in predicting 
neurodegenerative clinical scores using information in brain imaging. 


