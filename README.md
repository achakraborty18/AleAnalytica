# Overview

Welcome to the Customer Segmentation and Insights Project repository! This project is a strategic initiative for a thriving billion-dollar enterprise in beer brewing industry, to harness valuable insights from customer survey responses. Through meticulous preprocessing, feature selection, and clustering techniques, we've crafted personas for distinct customer segments. This not only aids in understanding customer behavior but also facilitates targeted marketing strategies. The repository also includes a visually appealing dashboard showcasing the key findings and actionable recommendations derived from our analysis.

# Results
Each cluster has been labeled to facilitate easy reference and communication. These labels serve as shorthand for the distinct customer personas, aiding in the implementation of targeted strategies.

# Course of Action

- Data Preprocessing: Raw customer survey data has been preprocessed to ensure accuracy and reliability in subsequent analyses. This involves handling missing values, standardizing formats, and cleaning the dataset for optimal results.

- Clustering: Utilizing advanced clustering algorithms, we segmented the customer base into distinct groups. These clusters form the foundation for our customer personas, enabling a nuanced understanding of diverse customer needs, preferences, and behaviors.

![image](https://github.com/achakraborty18/AleAnalytica/assets/150084176/85d6cfc9-d8b0-4b36-a8ec-b177f5d98958)


- Feature Selection: To focus on the most influential factors, we employed feature selection techniques to narrow down the dataset. This step ensures that our analysis is centered on the most pertinent variables for persona creation and strategy formulation.

- Persona Creation: Based on the clustered data, we've crafted personas for each identified segment. These personas provide detailed snapshots of customer characteristics, helping to humanize and understand the unique traits of each group.

- Dashboard: The project includes an interactive dashboard that visually represents key insights, cluster characteristics, and persona details. This dashboard is designed to be user-friendly, allowing stakeholders to intuitively grasp the findings and make informed decisions. HeatMap representing Attitudes of the Customers.

- Recommendations: To drive positive growth, we've derived actionable recommendations based on the insights gained from the personas and clusters. These recommendations serve as strategic guidelines for refining marketing approaches, product development, and overall customer engagement.
  
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
