# Decision-Tree<br>
This repository contains R code for building and evaluating a decision tree model on the Carseats dataset. The goal is to predict whether car seat sales are high based on various features.<br><br>

Files<br>
R script containing the code for data preparation, model building, and evaluation.<br>
README.md: This file providing an overview of the project.<br>

Instructions<br>
1.Dependencies:<br>
Ensure that the required R libraries (tree and ISLR) are installed.<br>
install.packages("tree")<br>
install.packages("ISLR")<br>

2.Execution:<br>
Run the decision_tree_code.R script to execute the decision tree analysis on the Carseats dataset.<br>

3.Results:
The script generates various plots, including the decision tree and pruned trees.<br>
Confusion matrices and accuracy scores are displayed to assess the model's performance.<br>

4.Interpretation:<br>
Review the code comments for explanations of each step.<br>
Explore the results to understand the predictive capabilities of the decision tree.<br>

Notes <br>
The dataset used is the Carseats dataset, and the response variable is created based on the 'Sales' variable.<br>
Cross-validation and pruning techniques are employed to optimize the decision tree model.<br>

References<br>
The dataset is sourced from the ISLR library.
