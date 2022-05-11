# clustering1

## 
This Data set contains the information related red wine , Various factors affecting the quality. This data set was prepossessed and downloaded from the UCI Machine Learning Repository. This data set was simple, cleaned, practice data set for classification modelling. Source of this Dataset: https://archive.ics.uci.edu/ml/datasets/wine+quality

Attribute Information: Input variables (based on physicochemical tests): 1 - fixed acidity 2 - volatile acidity 3 - citric acid 4 - residual sugar 5 - chlorides 6 - free sulfur dioxide 7 - total sulfur dioxide 8 - density 9 - pH 10 - sulphates 11 - alcohol Output variable (based on sensory data): 12 - quality ('good' and 'bad' based on score >5 and <5)

Sources
P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.

So, we took out the quality which is the target variable in this dataset and we contacted classification to the rest of the dataset. Then in the end we added back the quality variable to see how is cluster divides the dataset according to quality and actually found interesting results, as one of the clusters had many good quality and few bad entries. meaning the clustering was rather successful.

In our effort in clustering we contacted k means and hierarchical clustering, and then we did some eda to explore further by 2 relationships.
