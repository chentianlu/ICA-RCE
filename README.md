# ICA-RCE
This matlab based software (ICA-RCE) is to correct the baseline of metabolic dataset by using ICA (independant component analysis). That is, to remove the unwanted effect of known confactors (covariants) such as age, BMI, gender and so on. The aim of this software is same to that of MCEE (https://github.com/chentianlu/MCEE) although their algothrim are quite different. Additionally, this software has more functions and friendly GUI.

Main functions (modules):
1) Data preprocessing functions: normalization and log transform. 
2) Workflow of ICA based confounding effect removal method(ICA-RCE): Decompose the complete dataset by using ICA to generate some ICs. Select ICs related to confounding factors by the correlation coefficient, P values and AUCs (or by user).Reconstruct the dataset by using remaining ICS.
3) Methods for ICA-RCE performance evaluation and ICs selection: PC-OSC, OSC, PLS, PCA, ANOVA, ROC, Logistic regression, Mann-Whitney, CPU time and Spearman correlation. 

This software is protected by CPCC, Copyright Center of China.
It is freely available for academic study. Advices and suggestions are welcome.
