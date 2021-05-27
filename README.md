## Predicting the Outcome of Food Re-Inspections in Chicago

This repository contains code exploring methods of predicting the outcome of food re-inspections in the city of Chicago. Using inspection data from Chicago's open data portal, we attempt to use the violation comments from failed inspections to predict the outcome of the resultant re-inspection.

### Files

There are four Jupyter notebooks that we worked with during our project:

- `data_prep.ipynb`: Makes an API call to the [Food Inspections dataset](https://data.cityofchicago.org/Health-Human-Services/Food-Inspections/4ijn-s7e5) from the City of Chicago Open Data Portal. (86 lines of code)
- `early_models.ipynb`: Explores initial models, including Naive Bayes, logistic regression, and SVM. (319 lines)
- `nn_models.ipynb`: Build, trains, and evaluates feed-forward neural net models. (476 lines)
- `cnn_models.ipynb`: Builds, trains, and evaluates convolutional neural net models. (372 lines)
- `data_noise_investigation.ipynb`: Investigating some causes of poor model performance. (76 lines)

### Authors

The authors of this repository are Ali Pelczar and Mike Feldman, graduate students at the University of Chicago.

### License

[MIT](https://choosealicense.com/licenses/mit/)
