## Corruption in Niger
The goal of this project is to understand corruption in Niger using Machine Learning. The article related to the project is available 
[here](https://www.linkedin.com/pulse/corruption-machine-learning-can-predict-accuracy-91-abdoul-jalil/).

## Files in the repository
1. __Niger.ipynb__: the Jupiter Notebook code.
2. __converting_sav_file_to_csv.R__: R code to convert a .sav file to .csv.
3. __set_values.py__: a Python module contenaing a dictionnary that could be use to merge some questions responses.

## Data source
I used an [open data](http://www.afrobarometer.org/fr/data/donnees-fusionnees-de-la-serie-5-34-pays-2015) from an opinion survey by [Afro Barometer](http://www.afrobarometer.org/fr).

## Problematics
1. What are the most common types of bribe in Africa and Niger and at which frequency ?
2. Does the education level links to corruption ?
4. Which region and gender are the most affected ?
3. Is it possible to predict an election corruption in Niger ?

## Methodology
1. Data cleansing
2. Data exploration
4. Outliers detection (Isolation Forest)
3. Data visualisation and dimentionality reduction (PCA, t-SNE)
4. Supervised learning (Random Forest, K-NN, Multi Layers Perceptrons, Gradient Boosting)
5. Exporting best model

## Results 
1. The most common type of corruption in Niger in 2011 is election corruption.
2. People with no formal schooling or informal schooling (including Koranic schooling) are the most affected, particularly women.
3. The region Tillabérie is the most affected by this kind of corruption.
4. A random forest classifier is able to predict with an accuracy of __91%__ if a person had at least once experienced an election corruption
or not with a sensivity respectively of __88%__ and __94%__.
