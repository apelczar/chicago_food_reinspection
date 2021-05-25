## Predicting the Outcome of Food Re-Inspections in Chicago

This repository contains code exploring methods of predicting the outcome of food re-inspections in the city of Chicago. Using inspection data from Chicago's open data portal, we attempt to use the violation comments from failed inspections to predict the outcome of the resultant re-inspection.

#### Files

There are four Jupyter notebooks that we worked with during our project.

- data_prep.ipynb: Makes an API call to the [Food Inspections dataset](https://data.cityofchicago.org/Health-Human-Services/Food-Inspections/4ijn-s7e5) from the City of Chicago Open Data Portal.
- early_models.ipynb: Explores initial models, including Naive Bayes, logistic regression, and SVM.
- nn_models.ipynb: Building feed-forward neural net models.
- cnn_models.ipynb: Building convolutional neural net models.