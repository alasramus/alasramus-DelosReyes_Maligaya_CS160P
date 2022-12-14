# Machine Learning Final Project Automated Essay Scoring System
The following four main factors influence an essay's quality: topic relevancy, structure and coherence, word choice and sentence complexity, and syntax and mechanics.
This project uses the essay set 2 from the dataset.

The testing models used consist of the following:
1. Bag of words - Linear, lasso, and Random Forest
2. Bag of words + the rest of the features - Linear, Ridge, Lasso, and Random Forest
3. Only 10 numerical/POS/orthographic features - Linear, Ridge, Lasso, Support Vector, and Random Forest

# Comparison of all approaches
We have observed that the random forest results with the highest kappa scores than other models; Averaging in a 0.5 Cohen's kappa score. 
Linear regression model resulted with the lowest kappa scores; Averaging in 0.30 Cohen's kappa score. But it did substantially improved when tested in only 10 numerical/POS/orthographic features; resulting in a 0.47 Cohen's kappa score.
Lasso regression model was more inconsistent in results as opposed to other models; resulting in 0.39 in Bag of words; 0.41 when added the other features; but it did improve in the last testing resuling in a 0.47 Cohen's kappa score – tied with the linear regression model.
Support vector model, which took the longest time to execute, only resulted in 0.41 on all testings. 
It was also observed that all models resulted in higher scores when only tested in only 10 numerical/POS/orthographic features.
