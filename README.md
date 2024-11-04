# IPL-Data-Analysis

#loading the required libraries
import pandas as pd
from matplotlib import pyplot as plt
import seaborn as sns

#loading the ipl matches dataset
ipl=pd.read_csv('matches.csv')

#having a glance at the first five records of the dataset
ipl.head()

#Lookin at the number of rows and columns in the dataset
ipl.shape

#Getting the frequency of most man of the match awards
ipl['player_of_match'].value_counts()
