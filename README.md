# st-art-rec
Code for Artwork Recommender Thesis Project

The thesis can be read here:
https://scripties.uba.uva.nl/search?id=723723


Currently there are four notebooks that contain the code needed to create the dataset and run the experiments. 
    - The Scraper notebook is a small script that downloads the initial data.
    - The Dataset notebook contains the functions needed for cleaning the data and downloading the images.
    - The Analyze notebook contains mostly statistical analysis using pyspark.
    - The Experiments notebook contains the classes uses for handling the dataset for machine learning purposes, creating models using keras and tensorflow, and running the experiments using grid search and multiple runs.


The dataset is made of three files. The comments, submissions, and raw images as numpy arrays.
In order to load the data correctly we need to make use of the Dataset class found in the Experiments notebook. The dataset was last updated in April 2021.

https://storage.googleapis.com/pushshift_reddit/comment_april.json
https://storage.googleapis.com/pushshift_reddit/submission_april.json
https://storage.googleapis.com/pushshift_reddit/images75388.mymemmap


