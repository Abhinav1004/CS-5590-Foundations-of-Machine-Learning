# Assignment 2 CS5590

It includes the solution to Kaggle proble (https://www.kaggle.com/competitions/iith-foml-2023/overview) of CS5590 Foundations of Machine Learning Course

# Installation Instructions

1. Unzip the file **cs23mtech15001_kaggle.zip** in a directory
2. Please find 
	a. cs23mtech15001_TopScore.ipynb -  Ipython notebook to generate the top Score
	b. cs23mtech15001_secondTopScore.ipynb - Ipython notebook to generate second Top Score
	c. data folder -  folder containing 
		(i) iith_foml_2023_train.csv -  csv file used for training ml model
		(ii) test_input.csv - csv file to take as input to generate results `test_output.csv` 
	d. requirements.txt - list of libraries required to be installed in the virtual environment
	
3. Please create a virtual environment using the command `virtualenv venv` and use `source bin/activate` to activate the same
4. Install the required libraries using the command `pip install -r requirements.txt`
5. Launch the jupyter notebook by executing `jupyter notebook` in the current directory

# Code

1. The required jupyter notebook is present in the folder created and associated dataset is present in the data folder inside folder created.
2. The data folder expects 
	a. iith_foml_2023_train.csv - file used for training model
	b. test_input.csv  - input file used for generating test_output.csv i.e submission to kaggle
3. Please execute all the cells of jupyter notebook named `cs23mtech15001.ipynb` to train the model and generate test_output.csv file which was submitted on kaggle


# Results

1. We produced following results on the leaderboard 




# Team Members
Group No: 6
Abhinav Kumar Jha (cs23mtech15001@iith.ac.in)
Upendra Kumar Roul (cs23mtech15025@iith.ac.in)