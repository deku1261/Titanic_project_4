# Titanic Survivability Prediction
🚢 Predicting the tragic fate of passengers aboard the RMS Titanic in 1912.

On April 10, 1912 the ship known as the Titanic set off on a maiden voyage across the Atlantic in the largest man made object ever to be built at the time. At the time its construction was considered to have made the Titanic "virtually unsinkable" due to its 15 watertight bulkheads that divided the ship into 16 compartments. It's believed that a basic steering error contributed to the main reason the Titanic struck an iceberg and only sank as fast as it did because of an official persuading the captain to continue sailing.

# Dataset Description
For the project presented our teams main objective was to preprocess the dataset so we could train the RandomForestClassifier for a more accurate evaluation. The dataset we retrieved from Kaggle is one of the most famous datasets used for machine learning and data analysis. It provides information about the passengers aboard the RMS (Royal Mail Ship) Titanic. 
By analyzing the dataset we were able gain insight into 1300+ passengers who boarded the ship, detailing aspects like age, gender, ticket class, and fare. The primary objective is to predict the 'Survived' column based on the features. The sinking of the Titanic is one of the most infamous shipwrecks in history. This project seeks to delve deep into the data of the passengers onboard and predict whether a passenger survived or not.

# Data Preprocessing
Our team used a custom imputer to fill missing ages with the mean and standardized the dataset for optimal model performance.

# Model Training and Evaluation
We used the Random Foreset Classifier for its ability to handle both continuous and categorical data, and its resilience against overfitting. While making use of hyperparameter tuning we optimized the parameters using GridSearchCV for the best model performance. Finally we were able to evaluate using the accuracy given the binary nature of the target varibale.

# Conclusion

Through preprocessing, visualization, and modeling techniques for this project, insights about the kind of passengers that were more likely to survive were collected, and the importance of data preparation in machine learning was emphasized.

# Prerequisites
Python 3.x
Libraries:
numpy
pandas
scikit-learn
seaborn
matplotlib
