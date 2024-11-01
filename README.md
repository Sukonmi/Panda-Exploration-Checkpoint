# 🎯OVERVIEW.
This repository showcases my work on a Data Pre-Processsing Checkpoint. The goal of this project is to apply key techniques using Python’s Pandas library, aiming to derive meaningful insights from the dataset provided.

# 📢DESCRIPTION.
In this checkpoint, I worked on the billing history of the Tunisian electricity and gas company and applied what I learned in pre-processing chapter.

# ℹ️INSTRUCTIONS.
- Load the dataset, display the ten first lines, store the results in a variable called 'client_0_bills'.
- What is the data type of the 'client_0_bills' variable ?
- Display the general information of the dataset and try to answer the following questions : 
  - How many rows and columns do we have in this dataset ?
  - How many categorical features are present in the dataset ?
  - How much memory space does the dataset consume ?
- Inspect the dataset for potential missing values.
- Select your strategy to handle missing values, and tell us why you had made that choice.
- Run a descriptive analysis on numeric features (columns).
- Select the bills records for the client with an id ='train_Client_0', using 2 methods.
- Transform the 'counter_type' feature to a numeric variable using the encoder of your choice.
- Delete the 'counter_statue' feature from the Dataframe

# 🛠️TOOLS USED.
- Anaconda.
- VSCode.
- Python.
- Git.
- GitHub.
- LabelEncoder.

```
import pandas as pd
from sklearn.preprocessing import LabelEncoder
client_0_bills = pd.read_csv("STEG_BILLING_HISTORY.csv")
client_0_bills.head(10)
client_0_bills.dtypes
```
