# Iris_Flower_Detection
# Iris Flower Detection Project

This project demonstrates the integration of machine learning with Flask for Iris flower detection. The application uses a Support Vector Machine (SVM) model trained on the Iris dataset to predict the species of an Iris flower based on its sepal and petal dimensions.

## Machine Learning Model

The machine learning model utilized in this project is a Support Vector Machine (SVM) implemented using scikit-learn. The model is trained on the Iris dataset, which includes features such as sepal length, sepal width, petal length, and petal width.

## Flask Integration

The Flask web application serves as the user interface for interacting with the Iris flower detection model. Users can input sepal and petal dimensions through a web form, and the application provides real-time predictions using the trained SVM model.

## Input Features

The input features for the Iris flower detection include:
- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)

Users can enter these values in the provided web form, and the application will return the predicted Iris flower species.

## Project Structure

- **app.py**: The main Flask application file containing routes and logic for web interaction.
- **templates**: Folder containing HTML templates for rendering web pages.
- **static**: Folder for storing static files such as images.

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/iris-flower-detection.git
    cd iris-flower-detection
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the Flask application:

    ```bash
    python app.py
    ```

4. Open your web browser and navigate to [http://127.0.0.1:5000](http://127.0.0.1:5000) to access the application.

Feel free to customize this README file further based on additional information or details specific to your project.
