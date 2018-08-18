# DS_Session27Project3_Classification

Since Jupyter Notebook has been giving error when I used the following command load data into the dataframe, I have downloaded the data and used the downloaded data to create the train_set and test_set dataframe.

However, if the problem is resolved at the server side, we could use the following commands in the notebook to load data into the dataframe.

train_set = pd.read_csv('http://archive.ics.uci.edu/ml/machine-learning-databases/adult/adult.data', header = None)
test_set =  pd.read_csv('http://archive.ics.uci.edu/ml/machine-learning-databases/adult/adult.test', skiprows = 1, 
                header = None)
