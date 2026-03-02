## Titanic Dataset Exploratory Data Analysis (EDA)

This project is part of the **Syntecxhub Internship Program**. It focuses on performing a comprehensive analysis of the Titanic dataset to determine the factors that influenced passenger survival.

---

### Project Overview

The primary goal is to apply data science techniques to extract meaningful patterns from historical data. As per the internship guidelines, the analysis involves several critical stages:


**Data Acquisition and Inspection**: Loading the dataset and examining basic structures, including data types and missingness.



**Statistical Analysis**: Calculating survival rates based on demographic and categorical factors like sex, passenger class, and age.



**Data Visualization**: Creating visual representations of the data to make trends easily identifiable.



**Insight Generation**: Summarizing findings into a short report.



---

### Technical Requirements

To run this project, you must have the following environment and libraries installed:

* **Python 3.x**: The core programming language used.
* **Jupyter Notebook/Lab**: The environment used to execute the `.ipynb` file.
  
**Pandas**: Used for loading CSV files and performing data manipulation.


* **NumPy**: Used for efficient numerical operations.
  
**Matplotlib & Seaborn**: Essential libraries for generating required visualizations like bar charts and boxplots.



---

### Project Outputs

Upon executing the notebook, the following results and assets are generated:

#### 1. Data Profile & Quality Report

* **Dataset Shape**: A summary of total rows and columns for the training set.
  
**Missing Value Analysis**: A detailed breakdown of features with null values and their corresponding percentages.


* **Statistical Summary**: Overview of mean, standard deviation, and quartiles for numerical features.

#### 2. Visualizations

The project produces high-quality charts to represent the data:

* **Survival by Class/Sex**: A bar chart illustrating the survival disparity between genders across different classes.
* **Age Density Plots**: Box or Violin plots showing the age distribution of survivors compared to non-survivors.

#### 3. Final Insight Report

 
**Gender Bias**: Females had a significantly higher survival rate compared to males.



**Socio-Economic Impact**: Passengers in 1st Class had better survival odds compared to 3rd Class.



**Age Vulnerability**: Younger passengers (children) showed specific survival trends within certain classes.



**Data Integrity**: Significant missing data was identified in columns like 'Age', requiring careful inspection.



---

### Repository Structure

* `Untitled-1.ipynb`: The primary Jupyter Notebook containing the Python implementation.
* `train.csv`: The training dataset containing survival labels.
* `test.csv`: The test dataset used for analysis.

---

### Internship Compliance


**Organization**: Syntecxhub.


 
**Program**: Data Science Internship.


  
**Repository Name**: Syntecxhub_Titanic_dataset_EDA.


  
**Requirement**: Completion of at least one project per task is mandatory for certification.
