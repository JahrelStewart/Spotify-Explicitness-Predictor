# Spotify-Explicitness-Predictor
This is a repository containing code for predicting the explicitness of songs on Spotify. The code uses machine learning algorithms to classify songs as either explicit or non-explicit.

## Dataset
The dataset used in this project is the Spotify Tracks Dataset, which includes over 170,000 songs from various genres and artists. The dataset is available on Kaggle here.

## Dependencies
To run the code in this repository, you will need the following dependencies:

* Python 3
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn
* Numpy
* Collections
* Scipy
* Scikit-learn
* Datetime
* Imblearn
* Statsmodels
* Joblib

## Usage

To use the code in this repository with the Kaggle dataset, simply download the CSV file and save it in your local directory. Next, run the main.ipynb script to train the machine learning model and predict the explicitness of songs. You can specify the path to the Spotify Tracks Dataset CSV file as a command-line argument. For example:

```
python main.ipynb "dataset.csv"
```

This will train the model on the songs in the Spotify Tracks Dataset and predict the explicitness of songs.

## Results
The results of the experiment can be found in the results folder. The graph visualizes the importance of each feature, while the confusion_matrix.png file shows the confusion matrix for the model.
