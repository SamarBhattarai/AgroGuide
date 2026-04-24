AgroGuide: AI-Based Crop Recommendation
A machine learning system that predicts the most suitable crops to grow based on soil nutrients and climatic conditions.
This project aims to bring precision agriculture to the Nepalese context through data-driven insights.

Key Features
Exploratory Data Analysis (EDA): Statistical visualization of soil (N, P, K) and environmental (Temp, Humidity, pH, Rainfall) 
features.
Model Optimization: 
Exhaustive hyperparameter tuning using GridSearchCV for peak performance.
Model Comparison: Evaluated multiple classifiers including Random Forest, SVM, Decision Tree, and Naive Bayes.

Serialization: Models are serialized using Pickle for easy deployment. 

Tech StackPython | Scikit-learn | Pandas | NumPy | Matplotlib | Seaborn | Pickle

Model PerformanceBased on rigorous testing, the models achieved the following accuracy scores:
Algorithm Accuracy
Gaussian Naive Bayes99.3%
Random Forest98.8
% Decision Tree97.9%
SVM97.2%
