# Dual-Audience Decision Tree Analysis

**Google Colab link:** https://colab.research.google.com/drive/1JpJvi5CK_-_VEBuz7TBrJshYOOQEfyP7?usp=sharing

## Overview
This project demonstrates how predictive analytics can inform both technical and business decision-making. Using a real-world dataset from the insurance industry, I built and evaluated decision tree models to predict a key business outcome. The analysis is presented in a single Jupyter notebook with two distinct reporting styles: one for technical stakeholders and one for non-technical business leaders.  This mirrors the dual communication demands of modern data roles.

## Project Goals
* Build and compare decision tree models with varying complexity
* Evaluate model performance using accuracy and confusion matrices
* Visualize tree structures and feature importance
* Translate technical findings into actionable business insights
* Reflect on the challenges of cross-audience communication

## Technical Highlights
* Three decision tree models trained with max_depth values of 3, 5, and 10
* Accuracy scores and confusion matrices for both training and test sets
* Tree visualizations (shallow and medium depth)
* Feature importance chart for the final selected model
* Bias-variance tradeoff analysis and overfitting detection

## Business Insights
* Clear explanation of the business problem and prediction goal
* Top predictive factors translated into plain language
* Real-world example of how the analysis informs decision-making
* Actionable recommendations for business strategy
* Limitations explained in accessible terms

## Notebook Structure
**Section 1:** Technical Analysis & Code  
* Full modeling workflow with code, metrics, and visualizations

**Section 2:** Technical Stakeholder Report  
* Markdown summary using machine learning terminology

**Section 3:** Non-Technical Stakeholder Report  
* Plain-language summary with business recommendations

**Section 4:** Reflection  
* Personal reflection on translating technical findings for non-technical audiences

## How to Run
Open the .ipynb notebook in Jupyter or VS Code. All code and markdown are self-contained. No external dependencies beyond scikit-learn, pandas, matplotlib, and seaborn.

## Repository Contents
* Dual Audience Decision Tree Analysis.ipynb — Main notebook
* README.md — Project overview and structure
