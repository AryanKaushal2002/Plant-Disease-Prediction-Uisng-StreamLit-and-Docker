# Plant Disease Prediction using StreamLit and Docker

![License](https://img.shields.io/badge/License-MIT-blue.svg)

This project utilizes StreamLit and Docker to create an interactive web application for predicting plant diseases. With a user-friendly interface, users can easily upload images of plant leaves and receive predictions regarding potential diseases.

## Features

- Predict plant diseases using machine learning models.
- Interactive web interface powered by StreamLit.
- Dockerized for easy deployment and scalability.

## Requirements

- Python 3.10
- Docker

## Installation and Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/AryanKaushal2002/Plant-Disease-Prediction-Using-StreamLit-and-Docker.git
    ```

2. Navigate to the project directory:

    ```bash
    cd plant-disease-prediction
    ```

3. Create a virtual environment:

    ```bash
    python -m venv venv
    ```

4. Activate the virtual environment(You will have to create a virtual environment for the project):

    - On Windows:

        ```bash
        venv\Scripts\activate
        ```

5. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

6. Build the Docker image:

    ```bash
    docker build -t plant-disease-prediction-image:v1.0 .
    ```

7. Run the Docker container:

    ```bash
    docker run -p 80 plant-disease-prediction-image:v1.0
    ```

8. Access the application in your browser at [http://localhost:80](http://localhost:80).

## Usage

- Upload an image of a plant leaf.
- Click on the "Classify" button to generate predictions for potential diseases.
- Explore the results and take necessary actions for plant care.


