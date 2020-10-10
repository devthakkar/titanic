# Predict the Survival of Titanic Passengers - Kaggle Competition

## Skills utilized: NumPy, Pandas, Seaborn, scikit-learn(Decision Tree Classifier, SVM), xgboost(XGBClassifier), Ensemble Learning

##The Challenge
The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

In this challenge, we ask you to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

##My Approach to Solving the Challenge
1. Process the data to account for 0s, NaNs, etc. 
2. Conduct Exploratory Data Analysis to perform feature selection and engineering
3. Randomly choose a train/test split
4. Train a decision tree classifier, XGB classifier, and SVM and calculate accuracy scores
5. Calculate ensemble predictions and calculate corresponding accuracy 
6. Use ensemble model to predict test X values and generate result CSV

##Results
Received ~77% accuracy on predicting if the given Titanic boarder survives or dies. 
