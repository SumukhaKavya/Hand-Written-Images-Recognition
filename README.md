# Hand-Written-Images-Recognition
This project focuses on building an image classification system that can accurately identify handwritten alphabet characters. The project involves preprocessing the dataset, constructing machine learning models, and creating an interactive web application for real-time predictions.

Introduction

The goal of this project is to develop a robust image classification model that can correctly classify handwritten alphabet characters. The project is divided into three main phases: dataset preparation, model building, and web application development.

Dataset

Preprocess the MNIST image data and convert it into a pandas data frame. This step involves reading the image files, handling any missing or corrupted data, and transforming the images into numerical vectors suitable for machine learning.


Model Building

Four machine learning algorithms were used to construct the classification models:

K-Nearest Neighbors (KNN)

Logistic Regression

Decision Tree

Random Forest

Each model was trained and evaluated using accuracy as a primary metric. Model sizes were also considered to strike a balance between accuracy and efficiency. Based on the evaluation, the best-performing model was selected for integration into the web application.

Web Application

An interactive web application was developed using Streamlit, allowing users to upload handwritten alphabet images and obtain real-time predictions from the selected model. Users can choose their preferred model from the available options and visualize the model's prediction on the uploaded image.

[[Streamlit web application]](https://drive.google.com/file/d/1HQpVnfcve3MmK928N9u0qSo9jqRvLu9Q/view?usp=sharing)

Usage

Run the Streamlit app: streamlit run app.py

Upload a handwritten alphabet image via the web interface.

Select the desired model from the dropdown menu.

View the predicted alphabet character based on the selected model.

Contributions

Contributions are welcome! If you find any issues or have ideas for enhancements, feel free to submit a pull request. Please ensure to follow the existing coding style and guidelines.




