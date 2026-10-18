
# Lab 05 – Reflection Journal
## ITAI 1371 – Introduction to Machine Learning
### Group 4

**Lab Topic:** Data Preparation


## Member 1: Patrick Rostand Gandjouon Tchassem. 

In this lab, I learned how important data preparation is before building a machine learning model. Working with the Titanic dataset helped me understand that real-world data is not always complete or ready to use. One thing I found interesting was learning how to handle missing values using the median instead of deleting rows. Our dataset had 177 missing values in the Age column, and after applying the code, the output showed zero missing values.

I also learned how One-Hot Encoding converts categorical information, such as Sex and Embarked, into numerical features that machine learning models can understand. Another important part was using StandardScaler to bring Age and Fare values onto a similar scale. At first, some of these concepts were confusing, but reviewing the code and outputs helped me understand them better.

Overall, this lab helped me see why data preparation is an important step in machine learning. I now understand that cleaning and preparing data properly can help improve the quality of a machine learning model.

---

## Member 2: Saimi Manasiya


In this lab, I learned about the importance of data preparation in machine learning using the Titanic dataset. I understood how to handle missing values, encode categorical data, and scale numerical features. I learned that preparing data properly is an important step before building a machine learning model because the quality of the data can affect the results. This lab also helped me understand how Python and pandas can be used to clean and organize a dataset.

I also gained a better understanding of how different data preparation techniques work and why they are needed. I learned that missing values can be handled using the median, categorical data can be converted into numerical form through encoding, and numerical features can be scaled using StandardScaler. Overall, this lab improved my practical knowledge and helped me feel more confident working with datasets. It also taught me the importance of teamwork, communication, and learning from other group members.


---

## Member 3: [Full Name]

### Tasks Completed


---

## Member 4: [Full Name]

### Tasks Completed

---

## Member 5: Hashim Sayed Hoosini

Course: 1371- Intro to Machine Learning

Professor: Viswanatha Rao

18 Oct 2026

Introduction

data preparation is a critical and time-consuming stage of every machine learning project. This lab perfectly demonstrated why real-world data is rarely model-ready and showed how we systematically prepare data for machine learning pipelines. Through this lab, I dove deep into the data preparation process, which gave me a better understanding of each technique and concept. I worked with the Titanic dataset, which I previously had the chance to work with in another project. It contains passenger information but is riddled with missing values. The goal of this project was to go through the data preprocessing steps and clean the data thoroughly for machine learning projects.

Phase 1: Initial Data Ingestion and Exploratory Visualization
First, I imported the necessary libraries, such as pandas and numpy, and loaded the Titanic dataset directly from a public URL using pd.read_csv(). Then, I displayed the first five rows of the dataset using display(df.head()). I noticed that there were several missing values in the dataset. In order to better analyze the data before cleaning it, I used matplotlib and seaborn to visualize the data through a missing value heatmap and a count of missing values per column.

Phase 2: Missing Data Mitigation and Strategic Imputation
Second, I had to handle the missing values and drop redundant columns, because most machine learning models cannot handle missing data. I dropped the redundant text columns that were missing too many values. I also used imputation techniques, which means filling missing values with a calculated guess, to fill the remaining empty columns. Specifically, I used the median age to fill the missing Age values and the mode to fill the missing Embarked port values. Afterward, I verified the Age column imputation to ensure that there were no missing values remaining.

Phase 3: Categorical Feature Transformation via One-Hot Encoding
Then, I had to encode the categorical features. Because machine learning models are mathematical, they need numbers instead of text. I converted categorical columns such as Sex and Embarked into a numerical format using the one-hot encoding method. This method turns categorical values into numerical values like 1 and 0, and transforms the text fields into binary True and False indicators. Finally, I verified the encoded features to ensure Sex and Embarked columns successfully transformed into clean numerical indicators.

Phase 4: Feature scaling concept:
Models are sensitive to the scale of features. For instance, age (0-80) and fare (0-512) are on two different scales. This can cause the model to be biased toward fare; because fare has bigger numbers, the model will assume fare is more important. To solve this issue, we use feature scaling. Feature scaling puts all the values on the same scale. Standardization is a common method which uses StandardScaler in Scikit-learn. This puts all the numbers to have a mean of zero and a standard deviation of 1.

Phase 5: Post-Preprocessing Diagnostic Analysis and Insights
For plotting post-preprocessing insights, I used code to visualize two updated diagnostic charts: the new missing value heatmap and a correlation matrix of the numerical and encoded features. This insight confirms that no missing values remain in the dataset. Additionally, the correlation heatmap measures the strength of the relationships between all numerical features.
Challenges: For this lab, I faced different challenges, from code issues and indentation errors to searching for ‘Age’ or ‘Sex’ instead of ‘age’ and ‘sex’, which I had to use the code copilot to overcome. These debugging experiences and working through these issues helped me to develop my diagnostic skills. Furthermore, to develop my skills beyond the assignment, I split the dataset into train and test sets. Splitting the dataset into 80% training data and 20% testing data allows us to evaluate the performance on unseen data.

Overall, this lab showed me the gap between raw and messy data and structured model deployment. Through this lab, I dove deep into the data preparation process, which provided me a better understanding of each technique. Now I feel confident using these techniques in future projects. I will always follow each step to build a clean, modular preprocessing pipeline.

LLM used:

GoogleColab copilot and Google AI mode

Purpose: writing the code and fixing spelling and grammar errors.



---


