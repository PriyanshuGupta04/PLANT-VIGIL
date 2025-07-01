# Plant Vigil – Plant Disease Detection using Deep Learning

Plant Vigil is a deep learning-based web application that detects plant diseases from leaf images using a Convolutional Neural Network (CNN) developed in PyTorch. The model classifies images into 39 plant disease categories and is trained on the PlantVillage dataset. This application is intended for use in agricultural diagnostics and educational or research purposes.

## Project Features

* Image classification using a CNN trained on the PlantVillage dataset
* 39 different plant disease categories
* Flask-based web application for real-time predictions
* Supplement and fertilizer suggestions based on prediction
* Easily testable with included leaf images
* Open-source and open to community contributions

## Running the Project Locally

Prerequisites:

* Python 3.8 installed on your system

Steps to set up:

1. Clone the Repository

bash
git clone https://github.com/your-username/plant-vigil.git
cd plant-vigil


2. Set Up Virtual Environment
   Refer to the official Python venv guide or use:

bash
python3 -m venv venv
source venv/bin/activate  # For Linux/Mac
venv\Scripts\activate     # For Windows


3. Install Dependencies

bash
pip install -r requirements.txt


4. Download the Pre-trained Model
   Download the model file from the link below and place it in the project root directory:
   [Download model file](https://drive.google.com/drive/folders/1ewJWAiduGuld_9oGSrTuLumg9y62qS6A?usp=share_link)

5. Run the Flask Application

bash
python app.py


Visit http://localhost:5000 in your browser.

## Testing the Model

A folder named test_images/ is included with the repository. You can use these images to test the functionality of the model. Each image corresponds to a specific disease category to help verify the accuracy of predictions.

## AI Involvement

This project leverages Artificial Intelligence, specifically Deep Learning, to automate the detection of plant diseases from leaf images. The core of the application is a Convolutional Neural Network (CNN) implemented using the PyTorch framework.

The CNN model has been trained on the publicly available PlantVillage dataset, which contains thousands of labeled images of healthy and diseased plant leaves. Using supervised learning, the model learns to identify complex patterns and visual cues associated with 39 different plant disease categories.

Once trained, the AI model is capable of performing real-time inference through the web application, classifying user-uploaded images and providing accurate disease predictions. This approach significantly reduces manual inspection effort and provides a scalable solution for early disease detection in agriculture.

## Contributing

This repository is open for contributions. Interested developers and researchers are encouraged to contribute in the following ways:

* Enhancing the user interface
* Improving the accuracy of the deep learning model
* Extending the dataset or number of disease categories
* Adding new features such as multilingual support
* Writing documentation or tutorials

Contribution Guidelines:

* Fork the repository
* Create a new feature branch
* Commit and test your changes
* Submit a pull request for review

Detailed guidance on creating pull requests is available here:
[https://opensource.com/article/19/7/create-pull-request-github](https://opensource.com/article/19/7/create-pull-request-github)

## Acknowledgments

* PlantVillage Dataset on Kaggle
* PyTorch Development Team
* Flask Open Source Community
