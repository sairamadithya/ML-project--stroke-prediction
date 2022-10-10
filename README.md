# stroke-prediction
This project involves the prediction of stroke from basic lifestyle and bioparameters of the patient. 
The dataset contains 5110 rows and 12 columns, out of which 11 are input features and the last is target variable, Stroke.
The project involves cleaning of data, like dropping unwanted columns, enoding of categorical variables, detection of outliers and normalization of data.
An SVM with polynomial kernel was trained on the data which produced 96% accuracy, but produced a lot of false negatives.
Because the dataset was imbalanced with less samples of stroke. Hence the stroke class was oversampled and then a SVM with rbf kernel was trained.
It produced 93% accuracy but the false negatives greatly reduced.
