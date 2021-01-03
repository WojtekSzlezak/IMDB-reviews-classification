# IMDB-reviews-classification
Data science project containing preprocessing and modeling - NLP - movie reviews classification

# Requirements

The project was developed using python 3.6.9

### Packages

Following packages were used:

- Tensorflow 2.4.0
- Pandas 1.0.5
- Numpy 1.18.5
- Sklearn 0.22.2.post1
- Plotly 4.4.1
- Matplotlib 3.2.2
- NLTK 3.2.5
- Re 2.2.1
- Gensim 3.6.0
- Mlxtend 0.14.0
- Json 2.0.9


### Software

Project was created using Google Colaboratory and this is recommended environment for reviewing and executing the code. Google Colaboratory already have all required packages installed. Google Colab is accessible via google drive, so there is no need to install any software. Otherwise you can use Jupyter Notebook. This option may require to adjust display options for plotly graphics and to install missing libraries with pip install command.

### Data

Dataset used in the project is bigger size than 25mb, therefore couldn't be attached to the repository files on github. Please download it directly from the kaggle:
https://www.kaggle.com/utathya/imdb-review-dataset

Please use download button, unzip file and upload imdb_master.csv to your Google Colaboratory notebook working files using 'Upload to session storage' button in 'Files' section.

### Code

Project code is avalaible in IMDB_reviews_classification.ipynb file. To execute the code please add file to the google drive and open it in Google Colaboratory or open the file directly from github using 'Open in colab' button. Firstly, please change runtime type to GPU in 'Runtime' menu. Then please upload the dataset (please see above) and use 'Run all' option in 'Runtime' menu.

# Project description

The goal of the project was to create an effective model being able to correctly detect and classify sentiment of the movie reviews. Dataset used in the project contains real IMDB website reviews.

The project consists of two parts: prepocessing including data cleaning, data exploring and modeling including models building, models validation, models evaluation and best model dump.

# Summary

Best results from all of the models used in the project (SVM, LSTM RNN with Word2Vec, LSTM RNN) were achieved by LSTM RNN classifier. Accuracy metric was used to evaluate models as classification risk in project problem is symmetrical.

The best model obtained about 90% in the accuracy metric.
