A capstone project of the datascience nanodegree by Udacity Project overview This is the final project of the datascience nanodegree (DSND). We have an example of a virtual company called 'Sparkify' who offers paid and free listening service, the customers can switch between either service, and they can cancel their subscription at any time. The given customers dataset is huge (12GB), thus the standard tools for analysis and machine learning will not be useful here as it will not fit in the computer's memory (even the data can fit in the memory of a 32GB computer, the analysis, and computations require way more than that amount, and the analysis will crash the system). The safe way to perform such analysis is to do it using Big Data tools like Apache Spark which is one of the fastest big data tools.

For this tutorial, we worked with only a 128MB slice of the original dataset.

The problem is to create a machine learning model to predict the user intent to unsubscribe (Called customers' churn) before this happens.

Files in this repo
Folders
readme.md
Sparkify.ipynb : The main coding file in jypyter notebook format to work in Udacity workspace.
Sparkify.html  : HTML file of Jupyter Notebook

Used resources
Python 3.6.x (The programing language)
pySpark 2.4.x (Machine learning library for big data)
matplotlib 3.03 (A plotting library)
pandas 0.23 (numerical calculations library)
jupyter (The programming notebook interface)


Steps:

1) Loading & Cleaning of Data
2) EDA 
3) Feature Engineering
4 ) Modelling



Link to the Blog:https://medium.com/@paritesh93/prediction-of-churn-sparkify-a23e69d578ca
