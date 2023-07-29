# Drinking_water_Potability

The "Drinking Water Potability Prediction" project is  focused on predicting the potability of drinking water using machine learning techniques.It involves data exploration, preprocessing, and training models like Logistic Regression, SVM, and Random Forest.The project's primary goal is to develop a model that can assess the safety of water samples based on various water quality parameters.


# Detailed description of the project:

1. Data Loading: The project involves loading the dataset 'drinking_water_potability.csv' using the Pandas library. The dataset contains information about various water quality parameters and whether the water is potable (safe for drinking) or not.

2. Data Exploration: Basic data exploration is performed to understand the structure of the dataset. The first few rows of the dataset are displayed using the 'head()' function to get an overview of the data.

3. Data Preprocessing: Data preprocessing is carried out to handle missing values in the dataset. The missing values in columns like 'ph', 'Sulfate', and 'Trihalomethanes' are replaced with their respective mean values.

4. Data Visualization: Data visualization is done using various Python libraries such as Matplotlib and Seaborn. Count plots are created to visualize the distribution of potable and non-potable water samples. Histograms and pair plots are used to visualize the distributions and relationships between different water quality parameters.

5. Feature Importance: The ExtraTreesClassifier algorithm is used to determine the importance of features in predicting water potability. The feature importances are plotted using a horizontal bar chart.

6. Data Scaling: The features in the dataset are standardized using StandardScaler from sklearn to bring all the features to a common scale.

7. Data Splitting: The dataset is split into training and testing sets using train_test_split function from sklearn.

8. Model Building and Evaluation: Three different classifiers are trained on the dataset - Logistic Regression, Support Vector Machine (SVM), and Random Forest Classifier. The models' performances are evaluated using metrics like precision, recall, F1-score, and ROC-AUC score. Confusion matrices are also used to analyze the model's predictions.

9. H2O AutoML: H2O AutoML is used for automated machine learning. The H2O library is installed, and the dataset is imported into the H2O environment. H2O AutoML is applied to the dataset to automatically train and evaluate multiple machine learning models, providing insights into the best-performing model.

 knowledge demonstrated during  project, such as data preprocessing, data visualization, model building, and evaluation, as well as experience with libraries like Pandas, NumPy, Matplotlib, Seaborn, scikit-learn, and H2O.
