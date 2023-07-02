# Deep Learning Plant Disease Detection

This project implements a deep learning model for the detection of plant diseases. It uses a convolutional neural network (CNN) trained on a dataset consisting of various plant images labeled with their corresponding disease categories. The model can identify diseases in plants such as apple scab, black rot, powdery mildew, and many more.

## Setup

### Virtual Environment

It is recommended to set up the project inside a virtual environment to keep the dependencies separated. You can use Python's `venv` module or Conda to create a virtual environment. Activate your virtual environment before proceeding with the installation.

```shell
$ python -m venv myenv      # Create a virtual environment
$ source myenv/bin/activate   # Activate the virtual environment (Linux/macOS)
$ .\myenv\Scripts\activate    # Activate the virtual environment (Windows)
```
## Install Dependencies
Install the required dependencies by running the following command:
```
$ pip install -r requirements.txt
```
## Start the Server
Start up the server by running the following command:
```
$ python app/server.py serve
```
## Explore and Test
Visit http://localhost:8080/ in your web browser to explore and test the plant disease detection system.
## Docker
Alternatively, you can use Docker to run the project. Follow these steps:

1- Clone the repository:
```
$ git clone https://github.com/imskr/Plant_Disease_Detection.git
$ cd Plant_Disease_Detection
```
Build the Docker image:
```
$ docker build -t fastai-v3 .
```
Run the Docker container:
```
$ docker run --rm -it -p 8080:8080 fastai-v3
```
## Dataset Description
The dataset used for training and testing the model consists of various plant images labeled with their corresponding disease categories. Here is a description of the categories for some of the plants:

Apple: 'Apple___Apple_scab', 'Apple___Black_rot', 'Apple___Cedar_apple_rust', 'Apple___healthy'
Blueberry: 'Blueberry___healthy'
Cherry: 'Cherry_(including_sour)Powdery_mildew', 'Cherry(including_sour)_healthy'
Corn: 'Corn___Cercospora_leaf_spot', 'Corn___Common_rust', 'Corn___Northern_Leaf_Blight', 'Corn___healthy'
Grape: 'Grape___Black_rot', 'Grape___Esca_(Black_Measles)', 'Leaf_blight_(Isariopsis_Leaf_Spot)', 'Grape___healthy'
Orange: 'Orange___Haunglongbing_(Citrus_greening)'
Peach: 'Peach___Bacterial_spot', 'Peach___healthy'
Pepper: 'Pepper,_bell___Bacterial_spot', 'Pepper,_bell___healthy'
Potato: 'Potato___Early_blight', 'Potato___Late_blight', 'Potato___healthy'
Raspberry: 'Raspberry___healthy'
Soybean: 'Soybean___healthy'
Squash: 'Squash___Powdery_mildew'
Strawberry: 'Strawberry___Leaf_scorch', 'Strawberry___healthy'
Tomato: 'Bacterial_spot', 'Early_blight', 'Late_blight', 'Leaf_Mold', 'Septoria_leaf_spot', 'Spider_mites', 'Target_Spot', 'Yellow_Leaf_Curl_Virus
