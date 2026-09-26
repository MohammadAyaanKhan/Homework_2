# DSCI 552 — Homework 2

Name : Mohammad Ayaan Khan

USC ID: 4147952900

Email ID : mkhan736@usc.edu

Combined Cycle Power Plant regression analysis, plus ISLR exercises 2.4.1 and 2.4.7.

## Contents
`HW2.ipynb` — The solution covers every aspect, ranging from data loading, exploratory data analysis, single and multiple regression as well as non-linearity and interaction tests, .An improved the model using a 70/30 split, applying KNN regression, and successfully answering every query including those in ISLR 2.4.1 and 2.4.7.
 `requirements.txt` — Python packages needed to run the notebook.

## How to run
1. Install the dependencies:
pip install -r requirements.txt
2. Open the notebook and run cells:
jupyter notebook HW2.ipynb

The notebook downloads the Combined Cycle Power Plant data from the UCI repository straight away. Hence it is not necessary to download any data files. However, an Internet connection is required while running the program for the first time.

## Notes
- Sheet 1 of the dataset is used, as specified in the assignment.
- The 70/30 train/test split uses `random_state=42` for reproducibility.
