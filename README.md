# Project1
Casual respository
import numpy as np # linear algebra
import pandas as pd # data processing, CSV file I/O (e.g. pd.read_csv)
import matplotlib.pyplot as plt

# Input data files are available in the "../input/" directory.
# For example, running this (by clicking run or pressing Shift+Enter) will list the files in the input directory

from subprocess import check_output
print(check_output(["ls", "../input"]).decode("utf8"))
iris_df = pd.read_csv("../input/Iris.csv") # load iris data into a dataframe
iris_df.head(5) # Let's take peak on the first 5 rows of iris dataframe
