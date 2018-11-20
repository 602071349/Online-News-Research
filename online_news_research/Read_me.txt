project.ipynb includes the code for training models, and project_analysis.ipynb includes the code for feature selection. 

project_analysis.ipynb: notice that based on different parameters choices for model fitting, the selected subset of features isn’t always the same, and the number of features included can be different. Here, we use the subset of 13 features as our basis, and use those features to train our models in the second stage of training.

project.ipynb: Since the data is shuffled before the training, training set and testing set change for each time of running, which means the output statistics although similar, aren’t always the same.
