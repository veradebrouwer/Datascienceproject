# Data Science Project 2021/2022
## Group F2

# Extracting Modus Operandi from court documents

## Steps taken in notebook:
* Import all needed libraries

#### Data Preparation:
* Extract all court convictions from rechtspraak.nl, regarding a search term. These convictions are then put in a DataFrame, with the ID, Text \& Date as columns. *This takes a very long time*
* Load the vehicle file to extract the types and labels.
* Add ruler to pipeline
* Establish list of irrelevant entities & 'prefixes'
* Extract route from court conviction, put into dataframe
* Extract distict vehicles per court case

#### Similarity, Clustering & Plotting
* Create similarity scores for each document
* Create similarity dataframe
* Plot similarity in heatmap
* Plot clustering in scatterplot
* Plot vehicle count per year
