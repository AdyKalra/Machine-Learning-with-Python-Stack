# Tidy Data
- Tidy datasets are easy to manipulate model and visualize
and have a specific structure. 
- Data Normalization 
-- each var in a column
-- each observation in a row
-- each type of observation unit is aa table

# Getting Data
- Data Rule #1 - Closer the data is to what you are predicting, the better!
- Data Rule #2 - The data will never be in the format you need - pandas for this
- github.com/JerryKurata/MachineLearningWithPython

# Loading Cleaning and Inspecting Data
## Import Libs
- import pandas as pd ### pandas isa dataframe lib
- import mathplotlib.pyplot as plt ### matplotlib.pyplot plots data
- import numpy as np ### numpy provides N dimensional object support 

### do plotting inline instead of a seperate window
- matplotlib inline

## Load and review data
- df = pd.read_csv ("./data/pima-data.csv")
- df.shape ### structure number of rows and columns
- df.head (5) ### start of data
- df.tail (5) ### tailof data



