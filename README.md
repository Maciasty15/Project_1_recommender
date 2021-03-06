# Project_1_recommender

The project is carried out as a part of the Recommendation Systems at the University of Adam Mickiewicz in Poznań. \
Based on materials from the repository https://github.com/PiotrZiolo/recommender-systems-class \
Author: Maciej Barabasz 

## Goal

The aim of the project are:
- preparing dataset of hotel recommendations for content based recommender,
- selecting best features for the model,
- finding the best HR@10 in the final evaluation for recommended hotels for users,
- comparing the results against Amazon recommender.

## Scores
![2022-05-07_19h01_52](https://user-images.githubusercontent.com/25958431/167265076-82f90807-4ead-47e7-8b8a-bb65f9258c0c.png)

## Requirements
- Anaconda 3.8
- Git bash

## Instalallation
```bash
pip install pandas
pip install numpy
pip install matplotlib
pip install seaborn
pip install hyperopt
```

## Starting up project locally
- Create a folder on your local machine where you want stash this project. Open this folder and right click in it. From scroll menu select Git Bash here. After application opens insert this line:
```git
git clone https://github.com/Maciasty15/Project_1_recommender.git
```
- Prepare your conda environment (instructions given for Windows, but it should be similar on other systems):

    Open Anaconda Prompt as administrator.

    Make sure you're in the repository main folder. Run the following command:
```bash
conda env create --name rs-proj-env -f environment.yml
```
- Activate just created environment with the following command:
```bash
 conda activate rs-proj-env	

```
- Then type:
```
 jupyter notebook
```
A new tab with Jupyter Notebook should open in your browser.

In Jupyter Notebook open projec1_data_preparation.ipynb.

In tab menu select "Cell" and hit "Run all". Wait for the process to finish and close project_data_preparation.ipynb

In Jupyter Notebook open project1_recommender_and_evaluation.ipynb

In tab menu select "Cell" and hit "Run all". Wait for the process to finish.

NOTE: project is not finished so some errors will be displayed
