# machine-learning-module3lab
ML Module 3 Lab
Melissa Stone Rogers, July 9, 2024

## Introduction
Professional project to use Jupyter Lab, python, and needed frameworks to prepare Howell dataset for machine learning.
Commands were used on a Mac machine running zsh.  

## How to Install and Run the Project
Create project repository in Github and clone to your machine.

```
git clone project.url
```
Verify Python version of Python 3
```
python3 --version

```
```
python3 -m venv .venv 
source .venv/bin/activate  
```

Install required packages 
```
pip install jupyterlab pandas matplotlib scikit-learn
python3 -m pip install -U scikit-learn
```

Create requirements.txt in the root project folder. 
```
touch requirements.txt
```
Add the following requirements into requirements.txt:
- jupyterlab
- pandas
- matplotlib
- sklearn

## Freeze Requirements

```
python3 -m pip freeze > requirements.txt
```

## Add .gitignore File
Add .gitignore file to the root project folder. 
```
touch .gitignore
```
Add the following to your .gitignore file: 
- .venv/
- .vscode/
- .ipynb_checkpoints/

## Initial Project Save
```
git add .
git commit -m "initial"                         
git push origin main
```
### Start and Complete Project 
Copy your personalized lab2_starter.ipynb into this workspace. Rename it to be "lab3_starter." Copy lab3_utility.ipynb into workspace. Rename it to personalize to your work. Open the lab3_starter and begin your project. 

Copy Howell.csv dataset into your project workspace. 

Follow project steps as found in [this PDF](https://github.com/meldstonerogers/machine-learning-module3lab/blob/main/lab3_utility.ipynb).

## Complete Your Project
Save your project and push back to your repository. 
```
git add .
git commit -m "final"                         
git push origin main
```