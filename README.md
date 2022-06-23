# Machine Learning Project - Formula One Race Predictor

Group Members - Aaaron Simpson, Paaras Dhaliwal, Cragi Braganza , Gaetano Buongiorno , Luke Evans

## Project Outline

Hypothesis: Predict the outcome of a Grand Prix in the 2022 Formula One Season and analyse different machine learning models to find
an optimal strategy that can be applied for sports betting

Model Summary: Compare different machine learning models such as logistic regression, DecisionTreeClassifier, RandomForestClassifier, KNeighborsClassifier, GaussianNB and SGDClassifier to find an optimal model for predicting race outcome and compare the expected returns 

### Data Cleanup and Model Training

a) Data exploration and cleanup process 

By utilising the Ergast Developer API with F1 race results from 1950-2022, we will utilise only relevant data to individual race outcomes and not "constructor"  championship standings


b) Problems that may arise

The main problem that arose was the limitations of the data set

+ Potential accuracy issues with data

+ Data had no subjective indicators of performance, e.g. Cognitive Abilities on Race Day

c) Training processes of interest

We scaled the data using StandardScaler and compared six different models to see which combination was performing better

### Models used

- Logistic Regression

- DecisionTreeClassifier

- RandomForestClassifier

- KNeighborsClassifier

- SGDClassifier

- GaussianNB

![images](images/y_dist_boxplot.PNG)

### Final discussion

a) Findings and results

The best performing model was the RandomForestClassifier with an accuracy of 86.3315 

The worse performer model was GaussianNB with an accuracy of 62.3880

![images](images/models_comparison.png)

---
