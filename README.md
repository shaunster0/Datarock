# Machine Learning test

## My solution
- NN_for_Datarock_test.ipynb contains all work.
	- data exploration
	- data preparation
	- model definition
	- model training
	- model testing and output of results
	
- best_val_loss.pth contains a reference trained model which 
acieved MAE of 1.32 on Test set

- test_pred.csv is the prediction outputs

## Test 1
- Download the train.csv and `test.csv` datasets from the `test_1` folder.
- Each dataset has 11 columns: X1, X2, X3, X4, X5, X6, X7, X8, X9, X10 and Y.
- Build a deep neural network model from scratch (i.e. not using a canned or built-in model) to predict the Y values from the X* values.
- Train the model on the `train.csv` dataset and report the mean absolute error (MAE) of the model (it would be a good signal if the MAE is less than 2) .
- Run the model to predict the Y values for the samples in the `test.csv` dataset and save the results in the `test_pred.csv` file.
- Please provide your git repository, the `test_pred.csv` file 
