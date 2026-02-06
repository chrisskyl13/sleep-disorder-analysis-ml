# Sleep Health and Lifestyle Analysis using Machine Learning

This project analyzes the "Sleep Health and Lifestyle Dataset" to identify patterns related to sleep disorders and overall health using various data mining techniques.

##  Project Structure
The repository contains a complete pipeline for data analysis:

* **`preprocessing.py`**: Data cleaning, handling missing values, and encoding categorical variables like Gender, Occupation, and BMI Category.
* **`classification.py`**: Predicts the presence of sleep disorders using algorithms such as Decision Trees or Random Forests.
* **`clustering.py`**: Groups individuals based on sleep patterns and health metrics using K-Means clustering.
* **`apriori.py`**: Discovers association rules between lifestyle habits (e.g., physical activity, stress levels) and sleep quality.

##  Key Objectives
* **Classification**: Accurately predict if a person has Insomnia, Sleep Apnea, or no disorder.
* **Clustering**: Discover hidden segments in the population based on health characteristics.
* **Association Rules**: Identify which factors (e.g., high stress and low sleep duration) frequently occur together.

##  Technologies Used
* **Python**
* **Pandas / Numpy** (Data manipulation)
* **Scikit-learn** (Machine Learning)
* **MLxtend** (Apriori algorithm)
* **Matplotlib / Seaborn** (Visualizations)

##  Dataset Information
The dataset includes variables such as:
* Sleep Duration & Quality
* Physical Activity Level & Stress Level
* BMI Category & Blood Pressure
* Heart Rate & Daily Steps
* Sleep Disorder (Target variable)
