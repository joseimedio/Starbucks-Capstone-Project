# Starbucks-Capstone-Project
This project was completed as part of the Data Science Nanodegree (Udacity) in January 2023 by José Imedio.

It consists on an analysis of some datasets containing information about Starbucks offers and how some users interacted with them. The final goal is finding out which offers work best for different demographic groups.

#### Blog post on Medium: https://medium.com/@jose.adan.imedio/did-you-ghost-starbucks-26b928cd8334

## List of files

#### Starbucks_Capstone_notebook
Jupyter Notebook, main code file.
#### pic1, pic2 
images contained in the instructions of the notebook
#### data
rar folder containing the json files. It needs to be extracted.
##### \data\portfolio.json 
containing offer ids and meta data about each offer (duration, type, etc.)
##### \data\profile.json 
demographic data for each customer
##### \data\transcript.json 
records for transactions, offers received, offers viewed, and offers completed


## Libraries used

#### pandas 
Data analysis.
#### numpy
Mathematical and logical operations on arrays.
#### json
Needed to read in the json files.
#### matplotlib
Data visualization.
#### math
Additional mathematical operations.
#### datetime
Calculate current date to compare with value on became_member_on column.


## Comments on the process
The following process was followed to complete this project:
#### Step 1: Data exploration
Take a look at the datasets and plan actions for later steps.
#### Step 2: Data wrangling
Clean datasets and modify some field.
#### Step 3: Data processing
Generate new data by treating and comparing the data already provided.
#### Step 4: Data analysis
Draw conclusions.

## Conclusion
All demographic groups had very similar preferences. There were three offers that performed much better than the rest. Also, the amount of money spent by a user turned out to be more relevant than anything else.

## Possible improvements
Adding Step 5, which would consist on a supervised learning model. 


