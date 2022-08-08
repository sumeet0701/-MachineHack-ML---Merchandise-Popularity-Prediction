# -MachineHack-ML---Merchandise-Popularity-Prediction

Overview
Big Brands spend a significant amount on popularizing a product. Nevertheless, their efforts go in vain while establishing the merchandise in the hyperlocal market. Based on different geographical conditions same attributes can communicate a piece of much different information about the customer. Hence, insights this is a must for any brand owner.

In this competition, we have brought the data gathered from one of the top apparel brands in India. Provided the details concerning category, score, and presence in the store, participants are challenged to predict the popularity level of the merchandise.

The popularity class decides how popular the product is given the attributes which a store owner can control to make it happen.

Dataset Description:
Train.csv - 18208 rows x 12 columns (Includes popularity Column as Target variable)
Test.csv - 12140 rows x 11 columns
Sample Submission.csv - Please check the Evaluation section for more details on how to generate a valid submission

Attributes:
storeratio basketratio
category1 storescore
category2 storepresence
score1 score2
score3 score4
time
popularity - Class of popularity (Target Column)

Skills:
Multi-class Classification Modeling
Advance Feature engineering
Optimizing Multi-Class log loss score as a metric to generalize well on unseen data

Contest Link --> Link
Prize
Top-3 winners will get MLDS 2021 passes
MLDS (Machine Learning Developer's Summit) INDIA’S NO.1 CONFERENCE EXCLUSIVELY FOR MACHINE LEARNING PRACTITIONERS ECOSYSTEM
MLDS21 brings together India’s leading Machine Learning innovators and practitioners to share their ideas and experience about machine learning tools, advanced development in this sphere and gives the attendees a first look at new trends & developer products.

How to Generate a valid Submission File
Use ytrue as provided as class Labels(ytrue) as predicted probabilities per class (ypred) from the model using the predictproba() method

You should submit a .csv/.xlsx file with exactly 12140 rows with 5 columns (i.e. 0, 1, 2, 3, 4). Your submission will return an Invalid Score if you have extra columns or rows.

