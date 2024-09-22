# datafun-04-jupyter

# Step 1: Data Acquisition
import matplotlib.pyplot as plt
import pandas as pd
import seaborn as sns

# Load the Iris dataset into DataFrame
df = sns.load_dataset('iris')

# Inspect first 10 rows of the DataFrame
print(df.head())