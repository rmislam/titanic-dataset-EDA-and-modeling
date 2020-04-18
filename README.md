# Titanic Dataset EDA and Modeling
Exploratory data analysis and modeling for the Kaggle Titanic challenge.

This repo demonstrates exploratory data analysis and modeling in R for the Titanic dataset from Kaggle (https://www.kaggle.com/c/titanic).
You'll find an R notebook showing you step-by-step how to preprocess the data set, visualize the data with `ggplot2`, train and evaluate several common modeling algorithms, and perform test set prediction and submission. The final submission produced by this R notebook will land you a score of `0.78947` on Kaggle's public leaderboard, the top 22% of participants.

The code takes several minutes to run, so instead you can view the knitted HTML document containing the complete code and output, all nicely formatted. Just download the HTML file and view it locally on your browser.

This is meant to be educational and to serve as a starting point for others. Anyone is welcome to open issues and to suggest improvements.

## Requirements
You'll need to install the following packages in your R environment.
```r
install.packages("tidyverse", "caTools", "pROC", "class", "randomForest", "gbm", "e1071", "MASS")
```
