# Diabetes Detection

***This repository contains Machine learning models that have been used in diabetes detection***

# Dataset
"diabetes.csv" file contain 520 samples of people with 16 different features :
***(Age, Gender, Polyuria, Polydipsia, sudden weight loss, weakness, Polyphagia, Genital thrush, visual blurring, Itching, Irritability, delayed healing, partial, paresis, muscle stiffness, Alopecia, Obesity)***
based on this features It determines whether the person is diabetic or not .

 # Getting Started 
 ### Prerequisites
 -   Python 3.x
-   Matplotlib :  `pip install matplotlib`
-   scikit-learn:  `!pip install -U scikit-learn`
-  seaborn:  `!pip install seaborn`
-   Additional dependencies:  `pip install -r requirements.txt`
 ### Installing Dependencies

Install the required Python packages using the following command: pip install -r requirements.txt

 # Machine learning models 
 
 A different set of ML algorithms were used and the accuracy of each algorithm was compared when applied to dataset

| Algorithm |  accuracy |
|--|--|
| _**Logistic Regression**_ | 0.94 |
|**_**K-nearst neighbor**_**|0.94|
| _**Decision tree**_ | 0.98 |
| _**SVM**_| 0.98 |
| _**Random forest**_ | 0.99 |

From this comparison it was found that the **Random forest** algorithm gave the greatest accuracy of **0.99** for this classification problem
