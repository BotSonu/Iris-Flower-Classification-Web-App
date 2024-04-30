# Iris-Flower-Classification-Web-App

Welcome to the Iris Flower Classification Web App repository!

This project demonstrates a simple web application that utilizes machine learning to classify Iris flowers based on their sepal and petal measurements. The app allows users to input these measurements and receive a prediction of the Iris species.

Technologies--->
Frontend: HTML, CSS, JavaScript
Backend: Flask (Python web framework)
Machine Learning: scikit-learn (Python library)

Project Structure:
├── app.py                 # Flask application file
├── classifier.skops       # Trained machine learning model
├── templates              # HTML templates for the web interface
│   └── index.html         # Main page with input form and prediction display
└── static                 # Static files (CSS, JavaScript)
    └── style.css          # CSS styles for the web interface

Getting Started---->

1) Clone the repository:
git clone https://github.com/your-username/Iris-Flower-Classification-Web-App.git

2) Navigate to the project directory:
cd Iris-Flower-Classification-Web-App

3) Install the required dependencies:
pip install -r requirements.txt

4) Run the Flask application:
python app.py

Usage:
Open your web browser and visit http://localhost:5000/ (or the specified port if different).
Enter the sepal and petal measurements (in centimeters) for the Iris flower you want to classify.
Click the "Predict" button.
The predicted Iris species will be displayed on the screen.

Model Details:
The machine learning model used in this application is a Decision Tree Classifier trained on the Iris dataset from scikit-learn. The model has been pre-trained and saved as "classifier.skops".

Further Enhancements:
Implement user interface improvements: Enhance the visual design and user experience of the web app.
Add more flower species: Expand the application to classify a wider variety of flowers.
Deploy the app to a cloud platform: Make the application accessible online for wider use.
Integrate with a database: Store user inputs and predictions for future analysis.

Enjoy classifying Iris flowers with this web app!
