<p float="left">
  <img src="https://github.com/CosimoFaeti/causal-impact-analysis/assets/99746565/5febfca1-5af7-41c5-9684-a2410c1c8c23" alt="unipi" width="30%">
  <img src="https://github.com/CosimoFaeti/causal-impact-analysis/assets/99746565/2f1a5bb2-b77c-4845-ace7-c8eca89ad336" alt="Eliq logo" width="70%">
</p>


# Causal Impact Analysis
This repository contains my Master's thesis in Data Science and Business Informatics at Università di Pisa, developed in collaboration with Eliq AB.

## Abstract
This thesis explores the application of causal inference methodologies to measure the impact of Eliq's energy management solutions on end-users' electricity consumption. With the increasing demand for electricity and the imperative to reduce greenhouse gas emissions, understanding the causal effects of energy management solutions becomes indispensable. Leveraging causal inference techniques, this research investigates whether Eliq's solutions lead to changes, particularly reductions, in energy consumption among customers. Through counterfactual estimators such as Bayesian Structural Time Series and Interrupted Time Series models, the study analyzes multi-dimensional data collected from various locations to estimate the causal impact. Results demonstrate a significant negative causal impact in the majority of cases, indicating a reduction in electricity consumption attributed to Eliq's insights platform. However, a smaller portion of locations exhibit a positive causal impact, suggesting an increase in consumption due to factors not always controllable by Eliq. Overall, this research contributes to advancing the understanding of energy management solutions' effectiveness and their role in promoting energy efficiency and sustainability.

## Thesis Structure
The structure of the thesis is organized as follows:
* **Literature Review**: Defines and explains the background knowledge and concepts on which this thesis is based.
* **Identification**: Determines how to represent the causal quantity of interest in terms of observable data.
* **Data Collection**: Describes the data used and how it was collected.
* **Estimation**: Utilizes the data to estimate the identified causal quantity through causal inference models.
* **Conclusions**: Wraps up the discussion with concluding remarks and advises possible future works.

## Repository Overview
In this repository, in the root level, you can find the pdf version of the thesis, the Power Point final presentation and the code for the pre-processing step, implementation of Interrupted Time Series (ITS) and Bayesian Structural Time Series (BSTS) models, and inference analysis. More specifically:

Pre-processing
* CausalInference_preprocessing.ipynb : contains the pre-processing step

Interrupted Time Series model:
* CausalInference_ITS.ipynb : contains the implementation of ITS model (Ordinary Least Squares, OLS)

Bayesian Structural Time Series model:
* CausalInference_BSTS_1.ipynb : contains the implementation of BSTS model (Maximum Likelihood Estimation, MLE)
* CausalInference_BSTS_2.ipynb : contains the implementation of BSTS model (Variational Inference, VI)
* CausalInference_BSTS_3.ipynb : contains the implementation of BSTS model (Hamiltonian Monte Carlo, HMC)

Inference analysis:
* Inference_FINAL.ipynb : contains the inference analysis
