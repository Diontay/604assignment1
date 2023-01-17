# 604assignment1
Assignment1: Understanding Your Data for Machine Learning 
The main goal of this assignment is for you to know and prepare your data. It helps you understand the characteristics of data so you can select the correct techniques and technologies to process and analyze the data later and make decisions.

Download the carpet.csv and hardwood.csv data sets from the following website at the end of Chapter Three and describe them. http://www.uncg.edu/cmp/downloads/Links to an external site.

Extract statistical information (e.g., number of observations, dimension of the data, mean of each feature, etc.) from these datasets. Also present visual representations (e.g., histogram, scatter plot, etc.) of the data. Is the data set imbalanced, inaccurate or incomplete? Is it trivial data, or possibly big data? Does it have a scalability problem? Is it high-dimensional? You'll need to write programs to read the data and answer these questions.

Merge carpet.csv and hardwood.csv and create a new .csv file called carwood.csv in which you'll insert a new column with the label 0 for carpet observations 1 for hardwood observations. Now shuffle the observations randomly and create a new file called randcarwood.csv. Then divide this file into 80:20 and name the files Trainrandcarwood80.csv and Testrandcarwood20.csv respectively. You must write a program to perform these processes using a programming language of your choice. The use of R or Python is preferred; however, it's your choice. Include the first and last three observations of each file (instead of all data, which will be too long) in the text so that we know what the data samples look like in the files. Include code/commands and results of showing how many records in each file.

Submit a report file that contain both the code and text to Canvas. You can (but don’t have to) use Jupyter notebook in Colab at https://colab.research.google.com/
