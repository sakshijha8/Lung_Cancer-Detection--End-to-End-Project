# Lung_Cancer-Detection
## Context -
Lung cancer can cause complications, such as: Shortness of breath. People with lung cancer can experience shortness of breath if cancer grows to block the major airways. Lung cancer can also cause fluid to accumulate around the lungs, making it harder for the affected lung to expand fully when you inhale.The effectiveness of cancer prediction system helps the people to know their cancer risk with low cost and it also helps the people to take the appropriate decision based on their cancer risk status. The data is collected from the website online lung cancer prediction system.


<img align = "center" height = "300" width = "700" src = "https://repository-images.githubusercontent.com/474572546/d2b783f4-a08f-4b2a-b26b-4989404f9304">

## Problem Statement -
In this project , We predict whether the person is diagnosed with Lung cancer or not using different - different Algorithm's.

## Technical aspect -
*  Python 3.9
*	Front-end: HTML, CSS
*	Back-end: Flask
*	IDE: Jupyter Notebook, Visual Studio

## How to run this app -
Code is written in Python 3.9. If you don't have python installed on your system, click here https://www.python.org/downloads/ to install.
* Create virtual environment - *conda create -n myenv python=3.9*
*	Activate the environment - *conda activate myenv*
*	Install the packages - *pip install -r requirements.txt*
*	Run the app - *python main.py*

# Workflow-
## Libraries Used in This Project - 
   
● Numpy: Used for Mathematical Operations.

● Pandas: Used for DataFrame Operations.

● Seaborn and Matplotlib: Used for Data Visualizations.

● Ipywidgets: Used for Interactive Analysis.

● Sklearn: Used for Machine Learning Algorithms

 ## Data Collection -
   You can Download the data from here- [LungCancer](https://www.kaggle.com/datasets/sakshi20008/survey-lung-cancer-prediction)
   
 ## Data Pre-processing
*	Outliers detection and removal by boxplot and percentile methods
*	Categorical features handling by ordinal encoding and label encoding
*	Feature scaling done by Standard Scalar method
*	Imbalanced dataset handled by SMOTE

## Model Creation and Evaluation
* Used classification algorithms like Support Vector Machine & K- Nearest Neighbour.
* Support Vector Machine gives better result.
* Hyper parameter tuning was performed for better accuracy.
* Model performance evaluated based on accuracy, confusion matrix & classification report.

### Confusion Matrix of KNN and SVM -
![cm knn](https://user-images.githubusercontent.com/84726790/184611490-2011ad19-633f-4887-bc6b-63e390ae27d3.png)![cm svc](https://user-images.githubusercontent.com/84726790/184611675-d6ebd8ce-6b12-4f72-a68d-a651381310a2.png)

## Result & Comparison  Graph -
The SVM Model Gives better result then KNN by applying hyperparameter tuning on both.

![camparison](https://user-images.githubusercontent.com/84726790/184611901-25399da2-3e56-4198-ad56-59be0db1663e.png)

## Project Report -
You can download the project report here : [projct report.pdf](https://github.com/sakshijha8/Lung_Cancer-Detection--End-to-End-Project/files/9336348/projct.report.pdf)

## Website Link -  
http://127.0.0.1:7368/
