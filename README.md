# GUI_DecisionTreeClassifier

# Provided features : 

**Upload Dataset :**
Here User can upload dataset by clicking the upload button.
The checkbox above the upload button is to be checked if your dataset already have column/attribute name.
In case your dataset does not contain any attribute name, you can unchecked the checkbox and this will create dummy column name inside automatically
to avoid any unwanted errors.

**Encoding :**
Here it use **label encoding** in case the value of an attribute is categorical
user can select the multiple features at once to label encode them

**Train model :**
By clicking train model button you can train and build your own dicision tree.
Make sure you alreay upload a valid dataset before clicking on train button.

**Predict :**
Predict button just simply evaluate the decision tree model with a test dataset
and show the result on the console

**Plot_tree :**
Plot tree button plot the decision tree on the console after training
(Make sure to upload and train your model first before plotting)

**Compare Result :**
Compare result button compare the results using Gini and Entropy as a splitting criteria. 
and show the result in each case side by side for better judgement



# Parameters :


**Train_test_split :**
Through Train test split we can set how much % we can take as a test set**
As example : Train_test_split = 0.2 means we want 20% data as our test data

**Random state :**
Random state to fixed the psudo random number genereated each time when we run the program
so that our result persists same each time we run, unless we change the random state parameter

**Partitioning method :**
You can choose between two partiotioning method (Gini or Entropy) to build your decision tree model
random state and partitioning method (gini/entropy) also through this GUI.
