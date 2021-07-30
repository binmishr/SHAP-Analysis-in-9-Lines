# SHAP-Analysis-in-9-Lines

Recently, we have been investing some time to extend the R package SHAPforxgboost. This package is designed to make beautiful SHAP plots for XGBoost models, using the native treeshap implementation shipped with XGBoost.

Some of the new features of SHAPforxgboost

    Added support for LightGBM models, using the native treeshap implementation for LightGBM. So don’t get tricked by the package name “SHAPforxgboost” :-).
    The function shap.plot.dependence() has received the option to select the heuristically strongest interacting feature on the color scale, see last section for details.
    shap.plot.dependence() now allows jitter and alpha transparency.
    The new function shap.importance() returns SHAP importances without plotting them.
    Added vignette with basic workflow to CRAN.

An interesting alternative to calculate and plot SHAP values for different tree-based models is the treeshap package by Szymon Maksymiuk et al. Keep an eye on this one – it is actively being developed!

The codeset is attached in the .docx file herein with this repository.
