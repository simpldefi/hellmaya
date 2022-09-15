<h2> How to read a CSV file in python?</h2> <br />
<a href="https://simpledefinitions.com/abbreviation/csv/">CSV</a> stands for comma-separated values. CSV file contains the .csv extension contain a collection of comma-separated values used to store data.

<h3>Ways to read CSV file:</h3>

<b>1. Using CSV library</b>

<p>with open("./bwq.csv", 'r') as file:</p>
<p>csvreader = csv.reader(file) </p>
<p>  for row in csvreader: </p>
<p> print(row)</p>

<b>2. Using Pands Library</b>

import pandas as pd
data = pd.read_csv("bwq.csv")
data
