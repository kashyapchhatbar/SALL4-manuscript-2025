# SALL4-manuscript-2025

Models &amp; SHAP analysis highlighting SALL4 gene body role in transcription

For comparative analysis of SHAP values, genes in the test sets were stratified based on statistical significance from a TT-seq differential expression experiment following acute SALL4 depletion, using adjusted p-value thresholds of 0.05, 0.5, 0.9, and 1.0. To further assess variability in SHAP values among subsets of significant genes, we randomly sampled 50 genes from each significance threshold group and computed the mean and median SHAP values across 50 iterations. This resampling approach allowed us to evaluate the stability of feature importance within specific transcriptional response categories.

SHAP values and model weights for the 5 cross-validation splits are stored in individual subdirectories within `torch_mlp_deepshap/splits`.
