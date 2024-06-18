# Pet Adoption
This is my first machine learning project. Its called "Pet adoption". I've applied a decision tree classifier to predict the _breed_category_ and _pet_category_ from your dataset.

## Summary

### Data Loading and Splitting
* Loaded dataset (train.csv), split it into features (X) and labels (y) for breed_category and pet_category. 
* Further split the data into training and testing sets using train_test_split.

### Data Preprocessing
* Handled missing values in the condition column using SimpleImputer.
* Encoded categorical variable color_type using LabelEncoder.
* Standardized the numerical features using StandardScaler.

### Model Training:

* Utilized a Decision Tree Classifier (DecisionTreeClassifier) to train two separate models for predicting breed_category and pet_category.

### Model Evaluation:

* Evaluated models on the test set using accuracy scores, confusion matrices, and classification reports.
