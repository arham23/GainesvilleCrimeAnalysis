# **Data Science Final Project - Gainesville Crime Analysis**

#### **GainesvilleCrimeAnalysis.ipynb:**
Notebook where initial experiments were run as well as where we began to analyze and visualize the data. Here we determined things such as the most common crime type, the relationship between the number of incidents and time of day, number of incidents and day of week, and number of incidents in each police district. We also began our classification tasks here by experimenting with various models outlined in the report and assessing their accuracy.

#### **FrequentPatternMining.ipynb:**
Here we did data wrangling and use Frequent Pattern Growth Algorithm to find frequent patterns of crimes. Four types of data are used, Gainesville Police District, Time Interval, Report day of week and Incident Type. We get the most frequent itemsets for each length of itemsets.

#### **Preprocessing_Classification.ipynb:**
This is where the initial data is cleaned, reduced, and transformed. Classification is contucted with 6 different algorithms and baseline results are obtained with accuracy and runtime metrics, as well as confusion matrices. 

#### **Improvements.ipynb:**
This is where the classifiers were run on the dataset with reduced number of classes. Parameter tuning was performed on the classifier that scored the highest accuracy - LightGBM. Different resampling techniques were explored. 
