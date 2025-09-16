# Sleep_AI-Disorder-Detection

**Overview**

The Intelligent Sleep Health and Disorder Prediction platform is a machine learning solution that predicts sleep disorders based on personal health and lifestyle data. It helps identify potential sleep issues like Sleep Apnea and Insomnia, enabling preventive measures and personalized recommendations. The platform uses ML models along with interactive input and visualizations to support data-driven health insights.

**Key Features**

- Sleep Disorder Prediction: Predicts No Disorder, Sleep Apnea, or Insomnia using features like age, gender, BMI, physical activity, stress level, heart rate, and sleep duration.

- Multiple ML Models: Implements Logistic Regression, Decision Tree, and Random Forest for accurate predictions.

- Interactive Input: Users can input personal health data to get real-time predictions.

- Feature Importance Analysis: Identifies which health and lifestyle factors most influence sleep disorders.

- Visualizations: Confusion matrices, accuracy comparisons, and feature importance plots for model evaluation.

- Data Handling: Uses SMOTE to handle imbalanced classes, improving prediction reliability.

**Problem Statement**

Sleep health is crucial but often neglected. Challenges include:

- Difficulty in early detection of sleep disorders.

- Limited understanding of lifestyle factors affecting sleep.

- Lack of personalized predictions based on individual health data.

This platform addresses these problems by offering AI-driven predictions and insights for better sleep management.

**Tech Stack**

- Programming Language: Python

- Machine Learning: Logistic Regression, Decision Tree, Random Forest

- Data Balancing: SMOTE (Imbalanced-learn)

- Visualization: Matplotlib, Seaborn

- Data Handling: Pandas, NumPy

**Dataset Structure**

The dataset contains the following key variables:

- Personal details: Gender, Age, Occupation

- Sleep and lifestyle: Sleep Duration, Quality of Sleep, Physical Activity Level, Stress Level, Daily Steps

- Health metrics: BMI Category, Blood Pressure, Heart Rate

- Target variable: Sleep Disorder (No Disorder, Sleep Apnea, Insomnia)

**Project Workflow**

**1. Data Collection and Preprocessing**

- Handle missing values, encode categorical features, and balance classes using SMOTE.

**2. Model Training and Evaluation**

- Train Logistic Regression, Decision Tree, and Random Forest models.
- Evaluate using accuracy, classification reports, and confusion matrices.

**3. Feature Analysis**

- Calculate feature importance to identify key contributors to sleep disorders.

**4. Interactive Prediction**

- Accept manual inputs for real-time disorder prediction.

**5. Visualization**

- Plot confusion matrices, accuracy comparison charts, and feature importance.

**Impact**

- Early detection of potential sleep disorders

- Personalized lifestyle and health recommendations

- Increased awareness of lifestyle factors affecting sleep

**Future Enhancements**

- Integration with wearable device data for continuous monitoring

- Deployment as a web or mobile app for interactive use

- Inclusion of additional physiological parameters like oxygen saturation, snoring patterns, or sleep cycles
