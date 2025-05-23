# Portfolio
---
## NYC Data Science Academy
### Acquisition Due Dilligence Automation for Smaller Firms: PCA, KMeans, and ARIMA

[![View Blog Post](https://img.shields.io/badge/NYCDSA-View_Blog_Post-blue)](https://nycdatascience.com/blog/student-works/capstone/acquisition-due-dilligence-automation-for-smaller-firms/)
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/lelandjmurrin/Acquisition_Due_Dilligence_Capstone_Project.git)

The creation of a methodology to automate the due diligence process for acquiring small or midsize target firms. This allows for more informed decision-making on these firms, similar to what would be performed for larger ones, but with far less overhead. I served as a lead on a project commissioned by an accounting firm to propose innovative data science automation methods. 

<center><img src="images/time_series_decomp.png"/></center>
<div style = "font-size:12px; color:grey">Image Citation: Dancho, M. (2024, February 15). When learning Time Series, I struggled to understand Time Series Decomposition. (LinkedIn)</div>

---
### Pandemic Effects on the Ames Housing Market and Lifestyle: RF, GradientBoosting, GeoPandas, REST API, and A/B Testing

[![View Blog Post](https://img.shields.io/badge/NYCDSA-View_Blog_Post-blue)](https://nycdatascience.com/blog/student-works/machine-learning/pandemic-effects-on-the-ames-housing-market-and-lifestyle/)
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/lelandjmurrin/Ames_Housing_Project)

A prediction model to assist real estate agents in their service to out-of-town clients who are planning to move to Ames from a more urban setting. To assess the factors that affect the sale price of each home, consideration will be given to the proximity of desired services (e.g., gyms, spas, organic groceries, hospitals, etc.) as well as other housing features. Additionally, the project will analyze the housing market change due to the pandemic (i.e., 2019 vs 2021 data) and determine the neighborhood preferences for this particular client group. I analyzed the pandemic effects on Ames, Iowa housing through sensitivity analysis forecasts and pre vs. post
pandemic A/B testing in Python. I also created Python API wrapper functions to request lat/long and drive time data in JSON format.

<center><img src="images/GradientBoosting.png"/></center>
<div style = "font-size:12px; color:grey">Image Citation: Deng, Haowen & Zhou, Youyou & Wang, Lin & Zhang, Cheng. (2021). Ensemble learning for the early prediction of neonatal jaundice with genetic features.</div>

---
### Forecasting App for NY State Tax Credits: R Shiny, Lasso, and Ridge

[![View Blog Post](https://img.shields.io/badge/NYCDSA-View_Blog_Post-blue)](https://nycdatascience.com/blog/student-works/r-shiny/forecasting-ny-state-tax-credits-r-shiny-app-for-businesses/)
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/lelandjmurrin/NYS_tax_credit_Rshiny_project)
[![Open App](https://img.shields.io/badge/R_Shiny-Open_App-blue?logo=r&logoColor=blue)](https://ljmurrin.shinyapps.io/NYS_Article_9A_Tax_Credit_Predictions_Analysis/)

An interactive, dynamic R Shiny dashboard application to forecast NY State Corporate Tax Credits across multiple datasets. This provides tax consultants with an insightful tool to advise these corporations, helping them make the most appropriate current and future business decisions when considering ways to offset their tax liabilities. The data used to drive this application came from an annual New York State corporation tax returns study, which only included businesses with a yearly tax liability timeframe between January 1st and December 31st. I optimized predictive models using hyper-parametrization, cross-validation, and regularization.

<center><img src="images/ElNet_Regression.webp"/></center>
<div style = "font-size:12px; color:grey">Image Citation: Zou, H., & Hastie, T. (2005). Regularization and variable selection via the elastic net.</div>

---
## Artificial Intelligence
### Credit Card Fraud Detection: PyTorch and GANs

[![Open Notebook](https://img.shields.io/badge/Jupyter-Open%20Notebook-blue?logo=jupyter)](projects/Fraud_Detection_GAN.html)
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/lelandjmurrin/Generative_AI_Fraud_Detection)

Fraud detection is notoriously challenging due to the scarcity of positive (deceptive) examples. Generative Adversarial Networks (GANs) offer solutions to class bias by learning the distribution of minority class data and generating realistic synthetic examples, thus augmenting training and improving detection. This project explored the use of GANS to detect fraudulent credit card transactions (~1.6%) in an imbalanced dataset. The goal was to boost recall—our ability to correctly identify fraud cases—by synthetically generating deceptive samples and training a discriminator to distinguish them from valid transactions.

<center><img src="images/GANs.jpg"/></center>
<div style = "font-size:12px; color:grey">Image Citation: Lee et al.,
Advanced R-GAN: Generating anomaly data for improved detection in imbalanced datasets using regularized generative adversarial networks,
Alexandria Engineering Journal.</div>