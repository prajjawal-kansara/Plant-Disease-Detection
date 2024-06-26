# Plant-Disease-Prediction-CNN-Deep-Leanring-Project- 


<h2>Overview:</h2>

This project implements a Convolutional Neural Network (CNN) model for plant disease detection using machine learning and computer vision techniques. 
The model is trained to classify images of plant leaves into different disease categories, enabling users to diagnose plant diseases quickly 
and accurately by uploading pictures through a web interface.

## Features:

- Classification of plant diseases based on leaf images using a CNN model.
- Real-time prediction of disease using uploaded pictures through a Streamlit web interface.
- Utilization of Google Colab for model training and evaluation in a cloud-based Jupyter notebook environment.
- Docker containerization for easy deployment and scalability.
- Integration with Kaggle datasets for accessing a wide range of plant disease image datasets.

## Installation: 
   ### Prerequisites 

- **Python** 

- **TensorFlow**

- **Numpy** 

- **Streamlit**

- **Google Colab**

- **Docker**

- **Kaggle API**

- **Required Python packages (specified in requirements.txt)**

## Installation Steps:

Clone the repository: 

```bash
git clone https://github.com/prajjawal-kansara/Plant-Disease-Detection.git
```
Navigate to the project directory:

```bash
cd plant-disease-detection
```
Install dependencies: 

```bash
pip install -r requirements.txt
```
Set up Kaggle API credentials from `https://www.kaggle.com/`

## Usage:

### Data Collection:

- Gather a dataset of plant leaf images, including healthy and diseased samples.

- Access additional datasets from Kaggle using the Kaggle API.

### Model Training:

- Use Google Colab for training the CNN model using the labeled dataset.

- Follow the training script provided in the Colab notebook (Plant_Disease_Prediction_CNN_Image_Classifier.ipynb).

### Model Evaluation:

Evaluate the trained model's performance using the evaluation script provided in the Colab notebook.



## Web Interface:

Start the Streamlit web application:

```bash
streamlit run app.py
```

Upload plant leaf images to the web interface to get real-time predictions of diseases.

 
## Docker Deployment:
Build the Docker image:

```bash
docker build -t plant-disease-cnn .
```

Run the Docker container:

```bash
docker run -p 8501:8501 plant-disease-cnn
```
Access the Streamlit web application at `http://localhost:8501` in your web browser.


## Contributing: 
Contributions to improve this project are welcome! Feel free to submit bug reports, feature requests, or pull requests.

## Acknowledgments:

- **PlantVillage Dataset** - Dataset used for training and evaluation.
  
- **Streamlit** - An open-source app framework for machine learning and data science projects.
  
- **Google Colab** - A free cloud-based Jupyter notebook environment for machine learning education and research.
  
- **Docker** - A platform for developing, shipping, and running applications in containers.
  
- **Kaggle** - An online community for data science and machine learning enthusiasts, providing datasets, competitions, and notebooks.
