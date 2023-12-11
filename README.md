# Overview

Welcome to the Customer Segmentation and Insight Project repository! This project is a strategic initiative for a thriving billion-dollar enterprise in beer brewing industry, to harness valuable insights from customer survey responses. Through meticulous preprocessing, feature selection, and clustering techniques, we've crafted personas for distinct customer segments. This not only aids in understanding customer behavior but also facilitates targeted marketing strategies. The repository also includes a visually appealing dashboard showcasing the key findings and actionable recommendations derived from our analysis.

## Steps to run and install the Project:

Prerequisites: [Poetry](https://python-poetry.org/docs/)
1. From the cmd run ```poetry shell``` to activate the virtual environment.
2. Use ```poetry install``` to install all the dependencies.
3. Run ```poetry run flask run``` to start the project.

## Steps to generate the preprocessed file:
Run the [preprocessing.py](./app/src/preprocessing.py) file to generate the preprocessed file used to clustering.
```
python ./app/src/preprocessing.py
```
