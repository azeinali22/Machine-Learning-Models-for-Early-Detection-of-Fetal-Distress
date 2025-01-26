# Abstract
According to the World Health Organization, there are nearly 2 million stillbirths. The most
common methods of diagnosing perinatal death and taking early precaution for maternal and
fetal health is NST (nonstress test) which is a pregnancy screening that measures fetal heart rate
and reaction to movement. \
This project aims on implementing predictive models for the early
detection of fetal distress.

# Background
The NST measures the heart rate of the fetus in response to its own movements. The NST device is
typically connected to a pregnant woman for 20 min, with two separate probes recording data on fetal
heart rate (FHR) and uterine contractions (UCs).

# Objective
This project focuses on implementing predictive models for the early detection of fetal distress and
aims to classify fetal health categories.

# Scope
The dataset used in this project is a labeled data of fetal health obtained from the CTG 2 data of
2126 pregnant women. There are 21 independent variables and 1 dependent variable which is tagged
as 1 (Normal), 2 (Suspect) and 3 (Pathological). In this project, KNN, Decision Tree, and Random
Forest are implemented after identifying and extracting features using exploratory data analysis (EDA)
and principal component analysis (PCA). The models are evaluated with confusion matrix to assess
classification performance.


# Hypothesis
This project aims to use machine Learning Models for Early Detection of Fetal Distress. In order to
experiment different classifiers, we use RF, DT and KNN algorithms for predicting fetal health and
after that we evaluate the model’s performance providing the accuracy score and confusion matrix.
