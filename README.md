# Driven_Data_Water_Pump_Challenge
Using data from Taarifa and the Tanzanian Ministry of Water, we create a model to predict which pumps are functional, which need some repairs, and which don't work at all based on a number of variables about what kind of pump is operating, when it was installed, and how it is managed. A good understanding of which water pumps will fail can improve maintenance operations and ensure that clean, potable water is available to communities across Tanzania.

This predictive modeling challenge comes from DrivenData, an organization that helps non-profits by hosting data science competitions for social impact. The competition has open licensing: "The data is available for use outside of DrivenData."

Dataset source: DrivenData.org

# File Descriptions
* **train_features.csv**: the training set features
* **train_labels.csv**: the training set labels
* **test_features.csv**: the test set features
* **sample_submission.csv**: a sample submission file in the correct format

# Labels
There are three possible values:

* **functional**: the waterpoint is operational and there are no repairs needed
* **functional needs repair**: the waterpoint is operational, but needs repairs
* **non functional**: the waterpoint is not operational

# Main Features
* Exploratory Data Analysis: documents exploration of data and how decision was made to make each change/keep/drop each column
* Pandas_profiling report
* DecisionTreeClassifier and RandomForestClassifier from sklearn
* Hyperparameter Tuning
* Feature Importances graphed in a horizontal barplot
* RandomizedSearchCV and GridSearchCV
* Analyzes Precision and Recall scores
* Prioritizes top 100 most important pumps to look at first
* Scatterplot showing where the top 100 pumps lie relative to one another.
