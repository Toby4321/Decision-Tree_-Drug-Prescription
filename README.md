In this notebook, you will use decision trees to build and train a model using human 
patient records. The decision tree model then predicts the class of drug (A, B, C etc) to prescibe to a patient based on their records. 

1. Set the working directory to the directory where your drug200 csv file is stored.
 This involves modifying this line in the code: "pd.read_csv(r"D:\Data\drug200.csv")"

2. To get the decision tree to run properly, you have to download the following packages within youy
  jupyter notebook:
 (i) pydotplus
 (ii)graphviz
You can easily download these packages by running the following lines of code in your jupyter notebook:
 "pip install graphviz"
"conda install graphviz"
"conda install -c conda-forge pydotplus"
