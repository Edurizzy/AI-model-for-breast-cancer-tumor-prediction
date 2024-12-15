This repository contains the implementation of a university Artificial Intelligence project, with the objective of applying data analysis and preprocessing techniques to the Breast Cancer Wisconsin Diagnostic Dataset. The project involves organizing the data, manipulating attributes, and creating a clean base ready for machine learning tasks, such as classification.

The focus is to ensure a solid understanding of the data and structure it appropriately for future applications.

The dataset used is available in the UCI Machine Learning Repository. It is widely used in academic studies and presents information about breast tumors, including statistical characteristics that help determine whether the tumor is malignant or benign.

The dataset has diagnostic attributes, malignant (1) or benign (0), and feature attributes, such as "mean radius", "texture", "perimeter", among others, to describe the behavior of the tumor.

Dataset Link: https://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/wdbc.data

--Implemented Functionalities--

==Loading Data:

--Using pandas to load data directly from the provided URL.

--Renaming of columns to descriptive names and translated into Portuguese.

==Initial Exploration:

--Visualization of the first rows of the dataset (head).

--Analysis of data formats and dimensions.

==Pre-Processing:

--Removal of irrelevant columns: The ID column is excluded because it is a unique identifier and does not contribute to the classification task.

--Conversion of categorical variables: The Diagnosis column is mapped to binary values ​​(M = 1, B = 0).

--Separate dependent and independent variables: X: Represents the features used for prediction. Y: Represents the classification target.

--Visualization and Verification: Print the dimensions of the variables to ensure the correct organization of the data.

---Technologies and Tools--

Python 3.9+

Libraries:

-pandas: For data manipulation and analysis.

-scikit-learn (optional): For machine learning tasks in future projects.

Please note that the project is in Brazilian Portuguese as it is my native language, please be empathetic to an English learner.
