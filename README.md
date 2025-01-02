# Analyzing and Predicting Dwelling Occupancy in Washington State

## Table of Contents
- [Abstract](#abstract)
- [Introduction](#introduction)
- [Theoretical Background](#theoretical-background)
- [Methodology](#methodology)
- [Computational Results](#computational-results)
- [Discussion](#discussion)
- [Conclusion](#conclusion)
- [References](#references)

---

## Abstract
The aim of this study is to predict whether a dwelling is occupied by owners or renters based on several features related to individual demographics and housing characteristics. We have used Support Vector Machines (SVM) to classify the dataset. Our models achieved up to 82% accuracy in classifying dwellings. It was observed that factors such as Age and Number of bedrooms were significant predictors in determining whether a dwelling is owned or rented followed by other predictors like average house income and cost of utilities. Among the models we built, the linear kernel was recommended for its robustness and simplicity. The findings of this study provide a thorough analysis of the factors influencing dwelling occupancy and uncover deeper patterns which will be useful to real estate professionals in understanding housing trends.  
[Back to Top](#analyzing-and-predicting-dwelling-occupancy-in-washington-state)

---

## Introduction
Renters tend to skew toward the lower ends of the economic scale when it comes to income and wealth, according to data from the Federal Reserve’s 2019 Survey of Consumer Finances[1]. The primary goal of this study is to predict whether dwellings are occupied by owners or renters based on various demographic and housing-related factors. By using three different Support Vector Machines (SVM) kernels—linear, radial basis function (RBF), and polynomial, we not only seek to explore the predictive capabilities of these models but also gain insights into the underlying patterns within the data.  
[Back to Top](#analyzing-and-predicting-dwelling-occupancy-in-washington-state)

---

## Theoretical Background
Support Vector Machines (SVMs) are supervised learning methods used for classification and regression problems. SVM is a common term used to refer to the maximal margin classifier, support vector machine, and the support vector machine. However, Support vector machine is a generalization of maximal margin classifier which requires data to be linearly separable. The support vector classifier is an extension of the maximal margin classifier which can be applied to a broader variety of datasets. The support vector machine is an extension of the support vector classifier and SVM can be used in cases where the data has a non-linear boundary.  
[Back to Top](#analyzing-and-predicting-dwelling-occupancy-in-washington-state)

---

## Methodology
The dataset provided a unique challenge as each row represented a dwelling with multiple occupants living in the same house. SERIAL provides a unique identification number for each household in a dwelling, and we observed that there are multiple records for a single household. More than 50% of the dataset is redundant with only ~30k unique households.  
[Back to Top](#analyzing-and-predicting-dwelling-occupancy-in-washington-state)

---

## Computational Results
To build the model to classify the dwelling as rented or owned, we have used various variables like income, marital status, education, and the cost involved in the household, such as gas, electricity, and fuel. We have achieved 82% accuracy in classifying the dwelling. We have used linear, RBF, and polynomial kernels to train the machine learning model.  
[Back to Top](#analyzing-and-predicting-dwelling-occupancy-in-washington-state)

---

## Discussion
It is worth noting that the IPUMS USA dataset includes a vast array of data that can be used to answer many more questions related to the dwelling’s ownership. This study concentrated specifically on people's income, age, and education, which was just one component of the data.  
[Back to Top](#analyzing-and-predicting-dwelling-occupancy-in-washington-state)

---

## Conclusion
This study focused on using Support Vector Machine (SVM) models and their kernel extensions, like RBF and polynomial, to predict ownership of a dwelling. We used data sourced from IPUMS USA, originally collected by the US Census. The results were promising, with the models reaching an accuracy of 82% (radial kernel) for the binary classification task of predicting home purchases versus rentals.  
[Back to Top](#analyzing-and-predicting-dwelling-occupancy-in-washington-state)

---

## References
1. Pew Research Center. (2022, March 23). Key facts about housing affordability in the U.S. Pew Research Center: Short Reads. [Link](https://www.pewresearch.org/short-reads/2022/03/23/key-facts-about-housing-affordability-in-the-u-s/)  
2. Steven Ruggles, Sarah Flood, Matthew Sobek, Danika Brockman, Grace Cooper, Stephanie Richards, and Megan Schouweiler. IPUMS USA: Version 13.0 [dataset]. Minneapolis, MN: IPUMS, 2023. [Link](https://doi.org/10.18128/D010.V13.0)  
3. James, G., Witten, D., Hastie, T., Tibshirani, R., & Taylor, J. (2023). An Introduction to Statistical Learning with Applications in Python. [Link](https://hastie.su.domains/ISLP/ISLP_website.pdf.download.html)  
[Back to Top](#analyzing-and-predicting-dwelling-occupancy-in-washington-state)
