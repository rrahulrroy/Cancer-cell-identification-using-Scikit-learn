# Cancer-cell-identification-using-Scikit-learn
Steps followed to complete the program:  

Step 1: Installing the necessary module.We are required to install the module "scikit-learn" for the following project.You can install it by running the command "pip install sklearn" from the terminal.  

Step 2: Importing Scikit-learn's Dataset. The dataset we will be working with in this tutorial is the Breast Cancer Wisconsin Diagnostic Database. The dataset includes various information about breast cancer tumors, as well as classification labels of malignant or benign. The dataset has 569 instances, or data, on 569 tumors and includes information on 30 attributes, or features, such as the radius of the tumor, texture, smoothness, and area.Scikit-learn comes installed with various datasets which we can load into Python, and the dataset we want is included. Import and load the dataset:  
```
from sklearn.datasets import load_breast_cancer

# Load dataset
data = load_breast_cancer()
```

Step 3: 
