# Iris-Flower-Classification-Web-App

Welcome to the Iris Flower Classification Web App repository!

This project demonstrates a simple web application that utilizes machine learning to classify Iris flowers based on their sepal and petal measurements. The app allows users to input these measurements and receive a prediction of the Iris species.

## Features

- **Home Page:** A simple form where users can input sepal length, sepal width, petal length, and petal width.
- **Prediction:** Upon form submission, the app predicts the species of the iris flower based on the provided measurements.

## Technology Stack

- **Backend:** Flask
- **Machine Learning Model:** Skops (Serialized sklearn model)
- **Frontend:** HTML (via Flask templates)

## Running the App

```
python app.py
```

- Make sure you have the `classifier.skops` file in the root directory of the project.

## Model Details:

The machine learning model used in this application is a Decision Tree Classifier trained on the Iris dataset from scikit-learn. The model has been pre-trained and saved as "classifier.skops".

## Usage

1) On the home page, enter the sepal length, sepal width, petal length, and petal width of the iris flower.
2) Click on the "Predict" button.
3) The predicted species of the iris flower will be displayed on the page.


## Further Enhancements:

- Implement user interface improvements: Enhance the visual design and user experience of the web app.
- Deploy the app to a cloud platform: Make the application accessible online for wider use.
- Integrate with a database: Store user inputs and predictions for future analysis.

Enjoy classifying Iris flowers with this web app!

### **Contributions are welcome! Please fork the repository and create a pull request with your changes.**
