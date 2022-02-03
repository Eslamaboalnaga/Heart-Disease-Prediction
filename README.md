# Heart-Disease-Prediction

## Project Overview
I use the data which comes from the University of California Irvine's Machine Learning Repository to predict which patients
are most likely to suffer from heart disease soon using the features given.
Models: [Random Forest Classifier– Logistic Regression– SVC].

## Install

This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

We recommend students install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

## Code

Template code is provided in the `Heart.ipynb` notebook file. You will also be required to use the `heart.csv` dataset file to complete your work.

## Run

In a terminal or command window, navigate to the top-level project directory `Heart/` (that contains this README) and run one of the following commands:

```bash
ipython notebook Heart.ipynb
```  
or
```bash
jupyter notebook Heart.ipynb
```

This will open the iPython Notebook software and project file in your browser.

## Data

### Data Set Information:

This database contains 76 attributes, but all published experiments refer to using a subset of 14 of them. In particular, the Cleveland database is the only one that has been used by ML researchers to
this date. The "goal" field refers to the presence of heart disease in the patient. It is integer valued from 0 (no presence) to 4. Experiments with the Cleveland database have concentrated on simply attempting to distinguish presence (values 1,2,3,4) from absence (value 0).


Attribute Information:

Only 14 attributes used:
1. #3 (age)
2. #4 (sex)
3. #9 (cp)
4. #10 (trestbps)
5. #12 (chol)
6. #16 (fbs)
7. #19 (restecg)
8. #32 (thalach)
9. #38 (exang)
10. #40 (oldpeak)
11. #41 (slope)
12. #44 (ca)
13. #51 (thal)
14. #58 (num) (the predicted attribute)
