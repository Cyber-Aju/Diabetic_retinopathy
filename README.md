﻿# RETINA NET : WEB BASED DIABETIC RETINOPATHY DETECTION SYSTEM

## Project Overview

This project aims to develop an automated web-based platform for diabetic retinopathy detection using deep learning techniques. Users can upload retinal images to the platform, which will then analyze the images and provide instant diagnoses. The system leverages Convolutional Neural Networks (CNNs) to classify the images into different severity levels of diabetic retinopathy, enhancing accuracy and reliability compared to traditional methods.

## Features

- Automated image upload and preprocessing
- Deep learning-based image classification
- User-friendly web interface using Flask
- Real-time diagnosis and probability score display
- Visualizations to enhance user understanding

## Modules

### Image Upload

Handles the upload of retinal images from users.

### Preprocessing

Processes the uploaded images to ensure they are in the correct format and size for analysis.

### Convolutional Neural Network (CNN)

Trains and uses a deep learning model to analyze the preprocessed images.

### Prediction

Generates a diagnosis based on the CNN model's analysis.

### User Interface

Provides a web-based interface for users to interact with the system.

### Flask Integration

Integrates the backend processing with the web interface using Flask.

## System Requirements

### Software Environment

#### Python Libraries and Frameworks

- TensorFlow
- Keras
- Flask
- NumPy

#### Development Tools

- Jupyter Notebook
- Integrated Development Environment (IDE) such as PyCharm or VS Code

## Algorithms

1. **Image Preprocessing**: Converts images to a standard size and format, normalizes pixel values.
2. **Convolutional Neural Network**: Extracts features from images and classifies them into different categories of diabetic retinopathy.
3. **Prediction and Diagnosis**: Uses the trained model to predict the presence and severity of diabetic retinopathy from new images.

## Experimental Work

The experimental setup involves training the CNN model on a dataset of retinal images, validating its performance, and fine-tuning hyperparameters to improve accuracy. The model is then deployed using Flask to provide real-time predictions on new images uploaded by users.

## Results and Discussion

The model achieved high accuracy in classifying the severity levels of diabetic retinopathy Over 93%. The web-based system provided instant and reliable diagnoses, making it a valuable tool for early detection and treatment planning. The use of visualizations helped users understand the diagnosis process better.

## Conclusion

The proposed system successfully automates the detection of diabetic retinopathy using deep learning, offering a **user-friendly, accurate, and reliable** solution for early diagnosis. This approach has the potential to significantly improve the accessibility and efficiency of diabetic retinopathy screening, particularly in resource-constrained settings.

## Usage

To use this project:

1. Clone the repository.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the Flask application with `python app.py`.
4. Access the web interface at `http://localhost:5000`.
5. Upload a retinal image and receive an instant diagnosis.

## Live Demo

Check out the live demo [here](https://diabetic-retinopathy-a5k8.onrender.com/).

## Contributing

We welcome contributions! If you have suggestions or improvements, please feel free to submit a pull request or raise an issue.

## Contact

For any queries, please reach out via email: [ajmalakram152@gmail.com](mailto:ajmalakram152@gmail.com) or phone: +91-70946 53492.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

