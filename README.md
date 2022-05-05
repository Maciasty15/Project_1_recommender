# Project_1_recommender

Projekt realizowany w ramach przedmiotu Systemy Rekomendacyjne na Uniwersytecie Adama Mickiewicza w Poznaniu.
Bazujący na materiałach z repozytorium https://github.com/PiotrZiolo/recommender-systems-class 
Autor: Maciej Barabasz 

## Goal
Celem projektu było uzyskanie najlepszego HR@10 in the final evaluation.

## Scores

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
git clone https://github.com/ant3k96/recommender_class_project1.git
```
- Prepare your conda environment (instructions given for Windows, but it should be similar on other systems):

    Open Anaconda Prompt as administrator.

    Make sure you're in the repository main folder. Run the following command:
```bash
conda env create --name rs-proj-env -f environment.yml
```
Activate just created environment with the following command:
```bash
 conda activate rs-proj-env	

```
Then type:
```
 jupyter notebook
```
A new tab with Jupyter Notebook should open in your browser.

In Jupyter Notebook open projec1_data_preparation.ipynb.

In tab menu select "Cell" and hit "Run all". Wait for the process to finish and close project_data_preparation.ipynb

In Jupyter Notebook open project1_recommender_and_evaluation.ipynb

In tab menu select "Cell" and hit "Run all". Wait for the process to finish.

NOTE: project is not finished so some errors will be displayed
