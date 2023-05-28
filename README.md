# Advanced Analytics in a Big Data World - Group 7

This repository contains the lab report by Group 7, summarizing the results of the four assignments for the course Advanced Analytics in a Big Data World. The assignments were completed using Python as the main programming language. The repository serves as a collaborative platform for all team members, and the code for all assignments, including preliminary, final, and test versions.

## Table of Contents

- [Assignment 1: Predictive Modeling for Airbnb Properties](https://github.com/wentingjiang2022/advanced_analytics_kul/tree/main/assignment1))
- [Assignment 2: Deep Learning for Image Classification](https://github.com/wentingjiang2022/advanced_analytics_kul/tree/main/assignment2) 
- [Assignment 3: Real-Time Sentiment Analysis on Steam Reviews](https://github.com/wentingjiang2022/advanced_analytics_kul/tree/main/assignment3) 
- [Assignment 4: Graph Analytics on Twitch Data](https://github.com/wentingjiang2022/advanced_analytics_kul/tree/main/assignment%204) 

## Assignment 1: Predictive Modeling for Airbnb Properties

Here we develop a predictive model to estimate the "price per night" of Airbnb properties in Belgium. The notebooks present our process of EDA, feature engineering and model evaluation. 

## Assignment 2: Deep Learning for Image Classification

The dataset is downloadable [here](https://drive.google.com/drive/folders/13uqo4de3n0Of1X2Appt_G3WAUXqF3h4J?usp=sharing)

The task focused on image classification using deep learning techniques: distinguishing between food and interior images in the Michelin Guide and predicting cuisine type based on food images. The trained model to classify food vs interior of a restaurant is saved in the same folder with the name `food_interior_classifier.h5`.

## Assignment 3: Real-Time Sentiment Analysis on Steam Reviews

### Installation Guide

To set up on your local machine for this assignment, follow these steps:

1. Download the ZIP file from [this link](http://seppe.net/aa/assignment3/spark.zip) and extract it to a desired location (e.g., Desktop). The ZIP file contains a portable Spark installation with the latest stable version (3.3.2).
2. Make sure you have a Python 3 Anaconda distribution installed on your system.
3. Create a conda environment with Python 3 and Jupyter Notebook installed by running the following command:
```
conda create -n your-environment-name python=3 jupyter
```
4. Activate the conda environment using the command:
```
conda activate your-environment-name
```
5. If you are on Windows, double-click on `letsgo-win.bat` to start Spark. If you encounter a "Microsoft Defender SmartScreen" message, click "More info" and then "Run anyway". A Jupyter session should open up if everything is successful. Note that Java might require access to your Windows firewall, which you can safely allow.
6. If you are on Mac, open a Terminal window and navigate to the unzipped folder using the following command:
```
chmod +x ./letsgo-mac.sh
```
Assignment 3 outlines the findings of the third assignment, which focused on real-time sentiment analysis of reviews from the Steam website. The chapter covers the data collection process, sentiment analysis, and results.

`merge_export_csvfile.ipynb`: To combine the text files from subdirectories and construct a dataset in CSV format

## Assignment 4: Graph Analytics on Twitch Data

Lastly, Assignment 4 presents the outcomes of the fourth assignment, which involved applying graph analytics techniques to Twitch data using Cypher. The chapter highlights the approach, analysis process, and key findings.

## License

This repository is licensed under the [MIT License](LICENSE).





