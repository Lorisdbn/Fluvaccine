## H1N1 and Seasonal Flu Vaccines Learning and Predictions

Project Overview
This project aims to predict whether individuals received the H1N1 and seasonal flu vaccines using a variety of machine learning models. Leveraging data from a public health survey conducted during the H1N1 pandemic, this project explores key factors influencing vaccination behavior, such as demographic information, health beliefs, and behaviors.

Key Features
Data Exploration and Visualization: The project begins with a thorough exploration of the dataset, identifying key variables and patterns through various visualizations.

Data Processing: We meticulously handle missing values, encode categorical variables, and standardize the dataset to prepare it for effective machine learning model training.

Model Training and Evaluation: Multiple machine learning models, including Logistic Regression, Random Forest, Gradient Boosting, and Neural Networks, are trained and evaluated to identify the most accurate predictors of vaccine uptake. Techniques like SMOTE are applied to address class imbalance.

Prediction and Interpretation: The best-performing models are used to predict vaccine uptake on a test set. The project includes detailed interpretations of the predictions and their implications for public health strategies.

Methodology
Data Exploration: Understanding the structure and distribution of the dataset, including handling missing data and identifying relevant features.

Data Visualization: Using tools like Plotly to create interactive visualizations that reveal insights into the data, such as demographic distributions and the impact of public perception on vaccination rates.

Model Training: A variety of models are trained, including advanced techniques like Stacking and Voting Classifiers, with a focus on optimizing performance on an unbalanced dataset.

Evaluation: Models are evaluated using metrics like ROC-AUC to ensure they effectively distinguish between vaccinated and non-vaccinated individuals.

Recommendations: Based on the analysis, actionable insights are provided to inform public health strategies, emphasizing targeted interventions and the importance of addressing public perception.

Technologies Used
Python: The core programming language used for data processing, modeling, and visualization.
Streamlit: For building the interactive web application that showcases the project's findings.
TensorFlow: Used for implementing and running the neural network models.
Scikit-Learn: Essential for data processing and model evaluation.
Plotly: For creating dynamic and interactive visualizations.
