# Iris Flower Classification

## What is this?
This project is about teaching a model to recognize three different types of Iris flowers: Setosa, Versicolor, and Virginica. Instead of guessing, the model uses measurements of the petals and sepals to identify the flower correctly.

## The Model
I used the **K-Nearest Neighbors (KNN)** algorithm for this. It works by finding the most similar data points (neighbors) to a new flower and classifying it based on them. I also used a **StandardScaler** to adjust the measurements so they are all on the same scale, which helps the model be more accurate.

## The Code
The code is broken down into simple steps:
1. **Input:** It takes four numbers: sepal length, sepal width, petal length, and petal width.
2. **Process:** It scales these numbers and feeds them into the KNN model.
3. **Output:** I created a function called `predict_species` that gives you the name of the flower immediately.
