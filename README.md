# Feature-Selection-Causal-Inference

Feature Selection for Causal Inference from High Dimensional Observational Data with Outcome Adaptive Elastic Net

Authors: Md saiful Islam, Sahil Shikalgar, Md. Noor-E-Alam

Feature selection is an extensively studied technique in the machine learning literature
where the main objective is to identify the subset of features that provides the highest
predictive power.
However, in causal inference, our goal is to identify the set of variables
that are associated with both the treatment variable and outcome (i.e., the confounders).
While controlling for the confounding variables helps us to achieve an unbiased estimate
of causal effect, recent research shows that controlling for purely outcome predictors
along with the confounders can reduce the variance of the estimate. In this paper,
we propose an Outcome Adaptive Elastic-Net (OAENet) method specifically designed for causal inference to select the confounders and outcome predictors for inclusion in the propensity score model or in the matching mechanism.
OAENet provides two major advantages over existing methods: it performs superiorly on correlated data, and it can be applied to any matching method and any estimates
