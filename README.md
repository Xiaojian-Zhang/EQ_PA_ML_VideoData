# Modeling Protective Action Decision-Making in Earthquakes by Using Explainable Machine Learning and Video Data
Submitted to Natural Scientific Reports
Implemented by Xiaojian Zhang, Department of Civil and Coastal Engineering, University of Florida

# Required Softwares

Video annotation: **ELAN** (European Distributed Corpora Project [EUDICO] Linguistic Annotator)  
Annotation recoding: **Python 3.9.16**  
Modeling: **Python 3.9.16**  

# Required Libraries

Data preprocessing: **pandas**  
Machine learning model development: **xgboost**, **scikit-learn**  
Plots: **seaborn**, **matplotlib**

# Data

The training and testing datasets have the same data structure as detailed below:  
1. Each row is an observation and each column is a variable  
2. There are 14 variables (i.e., 14 columns) in total. Please refer to the paper for more details  

A simulated dataset with 5 observations (i.e., demo.csv) is provided as an example dataset to guide readers the data structure.  
For any questions regarding the dataset, please contact xiaojianzhang@ufl.edu  

# Code

The code scripts for processing the annotation, modeling development and interpretations are uploaded. If you want to open them in your local environment, please make sure **Jupyter Notebook** is installed.  

Preprocessing_Data.ipynb: preprocessing data, transforming annotations into numeric variables  
Modeling_Plotting.ipynb: Train-test data splitting, machine learning model development, MNL model development, performance comparison, variable importance calculation, partial dependence plots generation, and all generating all figures.
