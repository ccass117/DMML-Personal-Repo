[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/TnJIQ-Y6)

## Clone of Data Mining and Machine Learning coursework in F20DL, Pokemon Type Predictor using pokemon Stats & Images


# Data Mining and Machine Learning Group Coursework
 
  

## Group Members

1. Hamza Hassan Mooraj - @hamzamooraj99 - H00390746

2. Max Ferstenberg - @Max-Ferstenberg - H00390365

3. Cameron Cassidy - @CobaltEclipse117 - H00369879

4. Chi-ioi Chan - @CICiceINA - H00376665

5. Ines Piot - @InesPiot - H00480289

  

## Initial Project Proposal

Pokemon Type Predictor

  

## Project Objective

The objective of the project is to analyse and understand how various Machine Learning models and Convolutional Neural Networks can handle a complex task such as predicting Pokemon types.

The models will predict the type of Pokemon based on their stats and abilities in a tabular form as well as based on their images. 

The complexity comes from ambiguous relationships and complicated associations in the attributes of pokemon in relation to their types, more of which will be explored in the final report.

  

### Source of Datasets


- National Pokedex Data for every Pokemon:
SOURCE: https://docs.google.com/spreadsheets/d/19Me94k6YLz1_3EO_PwTPsAI9KmdFTh07/edit?gid=353590428#gid=353590428.  
*No license required; fan made database on a reddit forum.*

- Image Database for every Pokemon: 
SOURCE: https://www.kaggle.com/datasets/divyanshusingh369/complete-pokemon-library-32k-images-and-csv
*Open source database repository.*

- Dataset of Textual Descriptions for every Pokemon:
SOURCE:
[wanghaofan/pokemon-wiki-captions · Datasets at Hugging Face](https://huggingface.co/datasets/wanghaofan/pokemon-wiki-captions?row=1)
*Open source database repository*

  

### Milestones

1. Data Pre-processing
	a. Removing redundant data
	b. Handling Missing Values
	c. Merging any datasets that require merging
	F. Complete report writing about Datasets and Data Pre-processing
	

2. Data Analysis & Clustering
	a. Finalise Clustering combinations
	b. Complete clustering models and create graphics 
	F1. Complete report writing on Clustering analysis and implementation
	c. Finalise aspects of data to analyse
	d. Complete analysis descriptions and create graphics
	F2. Complete report writing on data analysis and comprehension


3. Machine Learning Models
	a. Implement and evaluate the Decision Trees model
	b. Implement and evaluate the KNN model
	c. Implement and evaluate the CatBoost model
	F. Complete report writing on model evaluation and implementation


4. Deep Learning Models (CNNs)
	a. Implement and evaluate the following CNN models:  
		i. CNN from Scratch  
		ii. ResNet-50   
		iii. DenseNet-121   
	F. Complete report writing on model evaluation and implementation


5. Testing
	a. Implement K-Fold Cross Validation on the best ML Model
	b. Implement K-Fold Cross Validation on the best DL Model

  
  

## Installing the project

Required Installs
```bash
!pip install catboost
!pip install iterative-stratification
!pip install pytorch
!pip install torchsummary
```

## Data Preparation Pipeline

  
There is not much data preparation required. Both the .csv tabular data, and image data were uploaded directly to the repository and are located and accessed when the programs are run.
  
  

## Coursework Requirements


### R2. Data Analysis and Exploration

  The tabular dataset was acquired from data from a fanmade database found on Reddit (sourced above). The data was confirmed to be accurate by comparing it with the official Pokémon website.
  Unnecessary information was removed.
  
  The image data was found on Kaggle. It consists of 256x256 images of every Pokémon, sorted into their types to be used by the CNNs.
  
  Plot.ly was used to graph some initial tables, determining which data fields most greatly affected the type.
  
  - Tabular Data Location: Data/Tabular Dataset.csv
  - Image Data Location: Data/Imgdata  
  - Data Analysis Location: Notebooks/Data Analysis.ipynb

### R3. Clustering

  This module applies clustering algorithms such as k-means to group Pokémon based on their attributes. It includes functions for algorithm initialization, parameter tuning, and execution to uncover patterns in the dataset.

  Location: notebooks/Clustering.ipynb

### R4. Baseline Training and Evaluation Experiments
  This module focuses on machine learning, including K-Nearest Neighbors (KNN), Decision Trees, and CatBoost, to analyze Pokémon data. It includes code for training models, hyperparameter tuning, and evaluating their performance in predicting Pokémon types.
  
  - K-Nearest Neighbors (KNN) Location: notebooks/Machine Learning/KNN_notebook.ipynb
  - Decision Trees Location: notebooks/Machine Learning/Decision_Tree.ipynb
  - CatBoost Location: notebooks/Machine Learning/Catboost.ipynb

### R5. Neural Networks
Our three models for Deep Learning were DenseNet121, ResNet50 and a model we made from scratch. This includes code for training models and model evaluation.

  - DenseNet121 Location: notebooks/Deep Learning/DenseNet121.ipynb
  - ResNet50 Location: notebooks/Deep Learning/ResNet50.ipynb
  - CNN from Scratch: notebooks/Deep Learning/CNN_Scratch.ipynb
