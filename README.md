STUDENT MARKS PREDICTION USING MULTIPLE LINEAR REGRESSION

PROJECT OVERVIEW
This mini machine-learning project predicts a student's final exam mark
using multiple linear regression. It shows how several factors can be
used together to estimate one numerical result.

OBJECTIVE
Predict the final exam mark from these five input features:
1. Study hours per week
2. Attendance percentage
3. Assignment average
4. Previous exam mark
5. Sleep hours per night

DATASET
The project creates a reproducible sample dataset of 200 students. It is
for learning and practice only, not real academic decisions. Final marks
are from 0 to 100.

MODEL
The project uses multiple linear regression:

Final Mark = w1x1 + w2x2 + w3x3 + w4x4 + w5x5 + b

Each weight shows the estimated effect of one feature while the other
features remain fixed.

FILES
- Student_Marks_Multiple_Regression.ipynb : Main notebook, structured step by step.
- main.py : Python-script version of the project.
- project_report.md : Short project report.
- requirements.txt : Required Python packages.

HOW TO RUN THE NOTEBOOK
Open PowerShell in this folder and run:

jupyter notebook Student_Marks_Multiple_Regression.ipynb

If Jupyter is not installed, install it once:

python -m pip install notebook

In the browser, choose Run All Cells.

HOW TO RUN THE PYTHON SCRIPT

python main.py

OUTPUT
The notebook and script provide:
- Model coefficients (weights) for every feature
- MAE, RMSE, and R-squared evaluation values
- Actual versus predicted marks chart
- Feature-influence chart
- Predictions for five students only
- Whole-number predicted marks, not decimals

The script saves charts and the five prediction values in the outputs folder.

LIBRARIES USED
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

CONCLUSION
Multiple linear regression is an easy-to-understand baseline model for
predicting student marks. It helps explain how study habits and academic
performance factors relate to final exam scores.
