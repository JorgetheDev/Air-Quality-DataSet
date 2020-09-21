# Student-Performance-Dataset
Holds UCI Wine data set

General Information
The program was created and run in Pycharm IDE.
The data set can be found here: https://raw.githubusercontent.com/JorgetheDev/public-dataset/master/winequality-red.csv
The program has three files
-	Execute.py
o	Main script to run program
-	Part1.py
o	Holds classes and functions for part 1
-	Part2.py
o	Holds class and function for part 2
o	Uses sklearn for regression
	Linear_model
o	Uses sklearn.metrics for statistical values
	Mean_square_error
	R2_score
	Explained_variance_score
o	Generates graph using matplotlib
	Matplotlib.pyplot
Execute is the main file that will run the program
-	It will ask for step size, iterations, and if you would like to view the graph that is in the document.
-	Once given proper values, the program will do the rest
-	Note – since it is a big dataset, it will take a couple seconds to finish

How to build and run
In order to build and run the program
-	 Create a new project in an IDE, such as pycharm
-	Place files in the directory
-	download the necessary libraries
o	numpy
o	pandas
o	sklearn
o	matplotlib
-	run the program from execute.py
o	this is the main python file
-	the program will ask for iterations, learning rate and in the end will ask you if you would like to see the graph.
-	Will also generate the log file in the local directory 


