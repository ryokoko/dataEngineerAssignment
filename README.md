## Data Engineering Assignment

Tools used:

1. Data cleaning and transformation

- Jupyter Notebook

2. Data integration

- SQLite3 on Python

3. Database queries

- SQLite3 on Python

Assumptions:

- JSON file is to be flattened to structured tables - Relational db
- SQLite db has only 5 data types
- repository name is unique as per Git Hub -- can be used as a pk but better to generate sk due to the length of repo can be longer

Steps:

1. View the dataset using text editor to understand the dataset structure, and any potential issues related to data cleaning and transformation
2. Create a new Jupyter notebook and import the dataset file

- Issues identified:
  - the structure is nested and complicated
  - need to flatten json to tabular form
  - any duplicates?
  - parent column is none for all records; should be

3. define data types
   | Field | Data Type |
   |-------|-----------|
   | owner | TEXT |
   | name | TEXT |
   | stars | INTEGER |
   | forks | INTEGER |
   | watchers | INTEGER |
   | isFork | TEXT |
   | isArchived | TEXT |
   | languages (language) |
