How to read a CSV file in python?
CSV stands for comma-separated values. Please refere the below link for more such abbrevitions.
https://simpledefinitions.com/abbreviation/csv/

CSV file contains the .csv extension contain a collection of comma-separated values used to store data.

Ways to read CSV file:

1. Using CSV library

import csv

with open("./bwq.csv", 'r') as file:
  csvreader = csv.reader(file)
  for row in csvreader:
    print(row)

2. Using Pands Library

import pandas as pd
data = pd.read_csv("bwq.csv")
data
