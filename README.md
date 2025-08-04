# Data Engineering Part-1 Studio

## Studio instructions

For this studio, pair up with another student.

We want you to create a [dbdiagram.io](https://dbdiagram.io/home) Entity Relationship Diagram (ERD) for this [formula one dataset](https://www.kaggle.com/datasets/melissamonfared/formula-1?select=constructor_results.csv) on Kaggle. 

We have included the .csv files for this dataset in the folder 'formula-one-dataset', for your convenience.

### Before creating your ERD for the dataset, we recommend you investigate the data using the following steps:
1. Explore the data: 
    - Create a single Excel file to hold all .csv files for the dataset. 
        - Certain .csv files in this dataset may be too large to import into Excel. For those, you can either import a small amount of the .csv data into Excel to review it, or you can use Python and the `pandas` library to investigate that specific .csv dataset 
    - Import the data from each .csv file into its own sheet tab
    - Review the overall data in this format, looking for relationships and inconsistencies in the data
    - Highlight fields with mixed types or inconsistent formats, and add comments in Excel.
2. Profile and Normalize the data: 
    - Decide appropriate data types and constraints for the data in each tab 
    - Decide on the relationships to define between fields in different tabs

### When creating your dbdiagram.io ERD we want you to:
- Identify entities, primary keys, and foreign keys.
- Draw relationships (cardinalities) and note optional vs. required links.
- Add brief comments on columns that require cleaning or should remain TEXT/VARCHAR due to variability in the field's data.

## Deliverable:

- When you are done, create a .txt file named `formula-one-dataset-solution.txt` and paste in your final dbdiagram.io ERD code into the file
- Push your changes to the Github repo you created for this studio, and submit a link to your repo in Canvas
