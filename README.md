# Analyzing the impact of fireworks on birdsong
This repository contains the code for the analysis done as part of my Master's Information Studies: Data Science at the University of Amsterdam.

## Overview of the code
The analysis is separated over multiple notebook files, the following table gives a quick overview of the relevant notebooks.

| **Filename**                       | **Description**                                                                                                               |
|------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|
| data_collection.ipynb              | Contains the code for collecting and processing the data from different sources like GBIF and xeno-canto                      |
| eda.ipynb                          | Contains the exploratory data analysis and code for saving audio fragments for validation                                     |
| convert_audio.ipynb                | Contains code for converting the WAV soundscapes to OGG                                                                       |
| bird_vocalization_classifier.ipynb | Contains the code classifying the birdsong in the soundscapes based on Google their Bird Vocalization Classifier              |
| three_bird_classifier.ipynb        | Contains the code for training and validating a custom classifier for the birds not covered by the BVC                        |
| explore_results.ipynb              | Contains the code for creating the timeline, exploring the results and running a regression to determine the firework effects |

## Overview of the data
The data of the analysis is concentrated in the data folder, some folders, and files are not in the folder because they are too large for keeping in a GitHub repository.