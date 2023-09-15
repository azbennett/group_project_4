# group_project_4
* Alexander Charbonneau
* Cassie Graf
* Steve Bennett

# Goal: Train an algorithm to analyze conventional home loan applications to predict approved or denied outcomes.
- This repository contains a Python script that implements, trains, and evaluates a machine learning model. The script also includes optimization steps and documentation of the process. Below, we provide a breakdown of how the project fulfills the specified requirements.

# Data: FDIC Home Loan Data from 2018 to 2022 Chase Bank
* https://catalog.data.gov/dataset/home-mortgage-disclosure-act-hmda-public-data-from-2007-2017
* https://ffiec.cfpb.gov/data-publication/modified-lar/2022 

# Additional Resources:
* https://ffiec.cfpb.gov/documentation/publications/modified-lar/resources/supporting-resources
* https://s3.amazonaws.com/cfpb-hmda-public/prod/help/2018-public-LAR-code-sheet.pdf

# Data Files used:
* 2018_Chase_Loans.csv
* 2019_Chase_Loans.csv
* 2020_Chase_Loans.csv
* 2021_Chase_Loans.csv
* 2022_Chase_Loans.csv

# Notebooks Used
* import_home_loans_machine_learning_export.ipynb
- Takes the import files and prepares them to be ready for use in our machine_learning.ipynb 

* import_home_loans_named_export.ipynb
- Takes the import files and prepares them to be ready for use in Tableau

* machine_learning.ipynb
- Runs our machine learning python script

# Tableau Public Workbook
- https://public.tableau.com/app/profile/alexander.charbonneau/viz/Project_4_Chase/DensityofLoanApplications?publish=yes

# Breakdown of what we did:
- This repository contains a Python script that implements, trains, and evaluates a machine learning model. The script also includes optimization steps and documentation of the process. Below, we provide a breakdown of how the project fulfills the specified requirements.
- The machine learning model is implemented in the machine_learning.ipynb notebook.
- Data preprocessing steps, including cleaning, normalization, and standardization, are performed in two Jupyter notebook files.
- The model demonstrates meaningful predictive power, achieving at least 85% accuracy or higher on all five years of data.
- The optimization and evaluation process are thoroughly documented in cell #2 of the machine_learning.ipynb file. This documentation includes iterative changes made to the model and the resulting changes in model performance. It is documented through commented code, making it easy to follow.
- The overall model performance is displayed at the end of the script. This includes accuracy scores, a confusion matrix, and a classification report for the machine learning results.
Additionally, there are screenshots of all five years of data within a Google Slides presentation, enhancing the visualization of model performance.

# This repository showcases a well-implemented and optimized machine learning model, with a strong emphasis on documentation and performance evaluation.  The end result we achieved high classification accuracy and providing clear insights into the optimization process.