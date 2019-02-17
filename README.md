# Classifying-Song-Genres-from-Audio-Data

Data preparation is done by merging the csv and json file based on 'track_id' attribute present in both the input files. Data is scaled before splitting into training and test set, then Principal Component Analysis (PCA) to de-correlate the data into 2-D plane. Components explaining more that 90% of the variance are retained and the rest are removed. 

Data is then split into training and test set and fit with Decision Trees and Logistic Regression classifiers. Comparison is made on both the models and data is made more 'representative' of both the labels in the subsequent steps. K-fold cross-validation is done after fitting the models and average model score is printed to compare both the algorithms.

Python libraries used:

- pandas
- numpy
- scikit-learn
- matplotlib

