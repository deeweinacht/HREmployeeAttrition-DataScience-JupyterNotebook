# HREmployeeAttrition-DataScience-JupyterNotebook
### This notebook uses a human resources dataset to predict employee attrition with machine learning by using a random forest algorithm.

    Copyright (C) 2023  Dee Weinacht

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.

**Description**

This is a supervised machine learning data science project. It utilizes a synthetic human resources dataset created by IBM, and sourced from [kaggle.com](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset).

The notebook includes a full data science project including the following:

1. Data Preparation
    - Importing and checking dataset
    - Data cleaning
    - Exploratory Data Analysis
    - Data Wrangling
2. Machine Learning
    - Train-test split
    - Random forest model
    - Balanced random forest model
    - Hyperparameter tuning
3. Model Application
    - Feature importance evaluation
    - Interactive web application

**User's Guide**

The notebook file ("Predicting Employee Attrition With HR Data.ipynb") should be run using a locally installed version of JupyterLab or Jupyter Notebook. The "HR-Employee-Attrion.csv" file should be located in the same directory as the notebook file.

All code cells should already have their output available. If not, all cells can be run at once using the ‘Restart & Run All’ command under the Kernel menu bar option, or the button on the top toolbar in Jupyter.

The Jupyter Notebook is divided into several sections:
- Data Preparation 
    - This section includes importing, exploring, and preparing the data. Several tables of data and descriptive visuals are viewable in this section. There are no interactive elements in this section.
- Machine Learning
    - This section covers creating and testing the predictive models. Graphical representations of accuracy measures are viewable in this section. There are no interactive elements in this section.
- Application 
    - A table of feature importance and the interactive application comprise this section.
    - The interactive application is comprised of multiple widgets. To use the application to make a prediction:
        1. Enter values for each attribute of the employee using the sliders and dropdown boxes.
        2. Click the ‘Predict!’ button.
        3. Enter new values for the attributes and click the button again for a new prediction.
