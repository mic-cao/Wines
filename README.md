# Supervised Learning: Vinho Verde Wine Quality Prediction

Authors: Michael Cao (yc849), Chang Chen (cc992), Aristotle Kolefas (aak99)  
Course: STSCI 4740  
Date: December 5, 2022

## Abstract

Wine quality prediction plays a crucial role in the winemaking industry. In this project, we focus on predicting the quality of red and white variants of Portuguese Vinho Verde wine. Utilizing machine learning methods, we analyze physicochemical variables to identify key factors influencing wine quality. Our research highlights the significance of volatile acidity and alcohol in predicting wine quality and provides insights valuable for winemakers and wine store owners.

## Introduction

The aim of this project is to identify the most influential physicochemical variables affecting the quality of red and white Vinho Verde wines. We employ both parametric and non-parametric machine learning techniques to select the optimal predictive models. Through our analysis, we aim to offer actionable insights to stakeholders in the wine industry.

## Description of Subjects

We utilize datasets containing physicochemical variables and quality ratings for red and white Vinho Verde wines. The datasets are pre-processed, eliminating the need for further cleaning. Key variables include fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulfates, and alcohol. Wine quality ratings are determined through sensory evaluations.

## Results

### Multiple Linear Regression

Multiple Linear Regression (MLR) identifies significant predictors for wine quality. For red wine, the model includes volatile acidity, chlorides, free sulfur dioxide, total sulfur dioxide, pH, sulphates, and alcohol. For white wine, fixed acidity, volatile acidity, total sulfur dioxide, density, sulphates, and alcohol are significant predictors.

### Ridge Regression

Ridge Regression shrinks coefficient estimates to reduce variance. It indicates fixed acidity, total sulfur dioxide, and density as influential predictors for wine quality, with differing effects between red and white wines.

### Lasso Regression

Lasso Regression performs variable selection by forcing some coefficients to zero. It identifies volatile acidity and total sulfur dioxide as influential predictors for white wine quality, with differing effects compared to red wine.

### Principal Component Regression

Principal Component Regression aims to reduce dimensionality but lacks effectiveness due to the dataset's characteristics.

### Local Regression

Local Regression combines linear and nonlinear regression but is computationally expensive. It identifies volatile acidity and sulphates as significant predictors for red wine quality.

### Generalized Additive Models

Generalized Additive Models (GAMs) model nonlinear relationships effectively. GAMs highlight volatile acidity, sulphates, and alcohol as key predictors for both red and white wines.

## Conclusion

Our analysis suggests that GAMs are the most effective models for predicting wine quality, with volatile acidity and alcohol playing significant roles. These findings offer valuable insights for winemakers and wine store owners. Future research could explore additional predictors and analyze long-term trends in wine quality.

## References

- Annie. (2022, November 18). Vinho Verde Wine Guide: Portugal's prominent wine. Wineries Guide & Wine Tips. [Link](https://sonomawinegarden.com/vinho-verde-wine/)
- Twohig, A. (2009, May 28). Wine-tasting 101: The Four Factors. Press Banner. [Link](https://pressbanner.com/wine-tasting-101-the-four-factors/)
- Wine Quality Data Set. UCI Machine Learning Repository: Wine quality data set. [Link](https://archive.ics.uci.edu/ml/datasets/wine+quality)

---

For more details, refer to the [full report](https://github.com/mic-cao/Wines/blob/main/Written%20Report.pdf).
