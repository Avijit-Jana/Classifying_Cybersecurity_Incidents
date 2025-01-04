<h1 align="center">Data Exploration & EDA</h1>

1. **Load data :** First we import some libraries and load GUIDE_Train Dataset.
2. **Check the Dataset size and datatypes.**
3. **EDA :** print some visualization based on dataset.


<h1 align="center">Data Preprocessing</h1>

1. **Load data :** Load the GUIDE_Train Dataset again.
2. **Handle Missing Values :** Remove the columns with 50% missing values. Drop the duplicates and used mode method for Target column.
3. **Remove Outliers :** Remove Outliers using Z-score.
4. **Feature Enginnering :** Remove unnecessary  columns using ANOVA and Chi-squared test.
5. **Encoding :** Encode the catagorical columns using label, ordinal, one-hot encoding.
6. **Zip File** : After preprocessing save the data in csv file. The processed data is in zip file, you can unzip the cleaned_data.zip.

<h1 align="center">Model Training & Evaluation</h1>

1. **Load data :** Load the cleaned Dataset.
2. **Data Splitting :** Split the dataset into 70:30 for train and test with stratify. Use only 5% of the dataset because its huge so it will take too much time.
3. **Balancing Target Class :** Use SMOTE and SMOTEENN method to balance the target values of train and test set.
4. **Scaling :** Use standard scaling to scale the numerical features.
5. **Model Training :** Train different models like Logistic Regression, Decision Tree, Random Forest, Xgboost, LightGBM etc.
6. **Random Forest :** After choosing the random forest hypertune the model for better performance.
7. **Save :** Save the model into a pickle file.
  
<h1 align="center">Final Evaluation</h1>

1. **Load Test Data :** Now Load the GUIDE_TEST dataset.
2. **Preprocessing :** Now do all the preprocessing I did earlier before train the model.
3. **Model Load :** Load the model from the saved pickle file.
4. **Predict the testset :** Finally predict the test set.

