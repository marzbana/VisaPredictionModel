# Work Visa Prediction Project

## Team Members
- **Alex Marzban** - [marzban3@illinois.edu](mailto:marzban3@illinois.edu)
- **Bo Wang** - [bo11@illinois.edu](mailto:bo11@illinois.edu)
- **Fang Li** - [fangli3@illinois.edu](mailto:fangli3@illinois.edu)
- **Michal Juscinski** - [michalj2@illinois.edu](mailto:michalj2@illinois.edu)

## Objectives
Develop a deep learning model to predict the amount of work visas that will be awarded next year(s) versus those that will be denied. 

Key tasks include:
- Utilizing 8 features mapped to 2 labels provided in the dataset.
- Assessing each feature's contribution to the model by freezing other parameters and observing changes in results when the specific feature updates.

## Dataset
The project uses data provided by the Department of Labor:
- [PERM Disclosure Data FY2022 Q4](https://www.dol.gov/sites/dolgov/files/ETA/oflc/pdfs/PERM_Disclosure_Data_FY2022_Q4.xlsx)

## Code Files
- "Data Extraction.ipynb"
    - Notebook containing initial data extraction and formatting. 
    - We removed features with high levels of missing data.
    - Pickled our resulting datasets for further use.
- "Data Exploration.ipynb"
    - Explored over 100 features in the pickled datasets to find the 8 features used in our models.
- "Baseline learning.ipynb"
    - Created baseline linear regression and logistic regression models.
- "DeepLearning.ipynb"
    - Used hyperperameter tuning to tune number of layers, hidden units, activation function and optimizer. 
    - Created final deep model with 5 layers and 128 hidden units in each.
- "Feature Importance.ipynb"
    - Analyzed our final 8 features using SHAP values.
    - Finding temporal features were the most important. 

## License
This project is licensed under the MIT License.
