Titanic Survival Prediction - Machine Learning Project

Uncovered key insights on passenger demographics and features to predict survival outcomes with optimal accuracy.

Dataset & Problem Statement
Dataset: 891 training samples, 418 test samples. Binary classification (Survived: 0/1). 12 original features including passenger class, age, gender, fare, cabin, etc. Challenge: Predict passenger survival with maximum accuracy.

Stack
Python (pandas, numpy, matplotlib, seaborn); Scikit-learn (LogisticRegression, DecisionTreeClassifier, RandomForestClassifier); Machine Learning: Classification, Cross-validation, GridSearchCV; Data Analysis: EDA, Statistical Analysis, Correlation Analysis; Data Preprocessing: Feature Engineering, Encoding, Missing Value Imputation.

Prep
Missing value imputation (Age, Cabin, Embarked), Advanced Feature Engineering (FamilySize, FarePerPerson, Title Extraction, AgeGroup Categorization, CabinDeck), Feature Encoding (One-hot, Ordinal), Log Transformation (FarePerPerson), Correlation Analysis.

Analysis
Gender Effect: Female survival rate (74.2%) >> Male (18.9%); Class Hierarchy: 1st class (63%) > 2nd class (47%) > 3rd class (24%); Age Patterns: Children (57.4%) highest survival; Family Dynamics: Small families (2-4 members) better survival; Cabin Location: Decks D, E, B highest survival rates.

Outcome
Best Model: Tuned Logistic Regression. Test Accuracy: 78.65%. F1-Score: 0.786. Precision: 0.83 (Class 0), 0.72 (Class 1). Recall: 0.85 (Class 0), 0.69 (Class 1). Overfitting prevention achieved.

Impact
Identified key demographic and socioeconomic factors affecting survival, validated historical context of "women and children first", demonstrated the economic and spatial influence on survival chances.

Steps
Clean & standardize columns → Handle missing values & outliers → Answer 12+ business questions → Visualize trends → Insights & recommendations

Skills Gained
Data Preprocessing, Feature Engineering, Model Selection & Evaluation, Hyperparameter Optimization, Statistical Analysis, Data Visualization, Overfitting Prevention.
