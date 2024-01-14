# Decision-Tree
This repository contains R code for building and evaluating a decision tree model on the Carseats dataset. The goal is to predict whether car seat sales are high based on various features.

Files
decision_tree_code.R: R script containing the code for data preparation, model building, and evaluation.
README.md: This file providing an overview of the project.

Instructions
1.Dependencies:
Ensure that the required R libraries (tree and ISLR) are installed.
install.packages("tree")
install.packages("ISLR")

2.Execution:
Run the decision_tree_code.R script to execute the decision tree analysis on the Carseats dataset.

3.Results:
The script generates various plots, including the decision tree and pruned trees.
Confusion matrices and accuracy scores are displayed to assess the model's performance.

4.Interpretation:
Review the code comments for explanations of each step.
Explore the results to understand the predictive capabilities of the decision tree.

Notes
The dataset used is the Carseats dataset, and the response variable is created based on the 'Sales' variable.
Cross-validation and pruning techniques are employed to optimize the decision tree model.

References
The dataset is sourced from the ISLR library.
