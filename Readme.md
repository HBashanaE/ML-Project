Preprocessing

In the first model(random forest), categorical and numerical features were seperately selected. 
Categorical field with more than 6 values was excluded. Numerical data were normalized and categorical data were imputed by mode and one hot encoded.

In the final model(cat boost), funder field was cleaned for noisy data. Scheme, subvillage and geocode was encoded with the median of latitude and longitude values.


Feature selection


Model

Random forest model trainde with 5 fold cross validation and grid search couldn't achieve classification rate mode than 0.77

Then cat boost calssifier was used. Using default parameters and basic data preprocessing it could achieve classification rate over 0.8.
