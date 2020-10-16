# humpty-numpy-comp472-A1

To run the models and get some data outputs, here are the steps to follow:

1 - Make sure you have Python installed on your machine and an IDE of your choice.
We recommend Visual Studio Code or PyCharm.
We also recommend adding Python to environment variables if you are on Windows, as it makes
using the jupyter notebook command easier.

2 - Open our project. You should see multiple folders, including A1-Output and Assig1-Dataset. 
You should also see multiple files with the extension ".ipynb". Those are jupyter notebooks, used to run our code.

3 - Make sure the project in your IDE has the following packages installed:

	- numpy
	- sklearn
	- matplotlib
	- jupyter
	
If they are not installed, please install them.

4 - Using the terminal, navigate to the folder of our project.
Then enter the command:

jupyter notebook

If you did step 3 correctly, and you have Python in your environment variables, a web browser will open with a list of files. 
This is where we can launch each model.

5 - Click on the model you would like to run, with file extension ".ipynb". 
Here are the models available and their name:

	- A1_Base-MLP : Contains the base Multilayer Perceptron model.
	- A1_Base_DT : Contains the base Decision Tree model.
	- A1_Best_DT : Contains the Best Decision Tree model.
	- A1_Best_MLP : Contains the Best Multilayer Perceptron model.
	- A1_GNB : Contains the Gaussian Naive Bayes model.
	- A1_plot_dist : Contains the code to generate bar graphs of the distribution of classes in the dataset 1 and 2.
	
Once you click on a model, a new page with the python code will open.
If the code asks you to choose a version a Python, choose Python 3.
If you do not have python 3, please check your step 1 again.

6 - To run the model and see results or generate output, you will have
to execute each cell, one after the other, in order (from top to bottom).

To execute a cell, click anywhere on the cell (the grey spaced rectangle that represents it) and
either click the "Run" button, or press CTRL+Enter.

A blue bar to the left of the cell will appear. This indicates the cell has been run or is running.
To the left of the cell will also be some text. It will say "In []".
Between the brackets, if a number appears, it means the code has run successfully.
If a * appears, it means the code is still running.

Before executing a new cell, always wait for the * to disappear, so that the code is fully run.

As you execute cells, you will see some textual feedback appear, indicating the confusion matrix and several metrics
to evaluate each model's performance based on the data set. Dataset 1 is run first, then dataset 2.

Once you have executed all the cells, you will be able to see the output file.

NOTE: There are some cells, notably in A1_Best-MLP and A1_Best_DT, that have a comment about using Grid Search.
Those cells execute a grid search for the best hyperparameters for a model.
Those cells take a very, very long time to run. Beware.

7 - The output files will appear in the folder A1-Output where you have extracted our project, and are
also visible in the main page where you can choose a model.
