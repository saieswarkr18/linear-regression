# Iris Dataset Classification with Logistic Regression

This project demonstrates a basic multi-class classification using the Iris dataset and a Logistic Regression model.

## Project Goal

The goal of this project is to:

1. Load the Iris dataset.
2. Split the data into training and testing sets.
3. Train a Logistic Regression model.
4. Evaluate the model's accuracy.
5. Visualize the decision boundaries of the trained model.

## Dataset

The dataset used is the classic [Iris dataset](https://en.wikipedia.org/wiki/Iris_flower_data_set), which contains measurements of sepal length, sepal width, petal length, and petal width for three species of iris flowers: Setosa, Versicolor, and Virginica.

## Project Structure

The project is implemented in a Jupyter Notebook (or Google Colab notebook) and includes the following steps:

1. **Loading the dataset**: The Iris dataset is loaded from a CSV file.
2. **Splitting the data**: The dataset is split into 80% for training and 20% for testing.
3. **Training the model**: A `LogisticRegression` model is trained on the training data.
4. **Evaluating the model**: The accuracy of the trained model is calculated and printed.
5. **Visualizing decision boundaries**: The decision boundaries of the model are plotted using two features (petal length and petal width) for visualization purposes.

## Dependencies

The following libraries are required to run this notebook:

- pandas
- numpy
- scikit-learn
- matplotlib
