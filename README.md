# Dog-Emotion
## About
The Dog Emotion Detection project is an AI-based system that aims to recognize and classify the emotions expressed by dogs in images. It utilizes state-of-the-art deep learning techniques to identify emotions to see if the dog is happy, sad, angry or relaxed.
## Data
Source: https://www.kaggle.com/datasets/danielshanbalico/dog-emotion 
The dataset includes 4000 images of dogs in total, with 1000 images for each emotion category (angry, happy, relaxed, sad).
This dataset consists of images of dogs with labels indicating their emotional state: angry, happy, relaxed, or sad. The images were collected from various online sources and manually annotated by the author in the given link.
## Model
As the dataset size is considered to be small, I used pretrained ResNet18 model with Pytorch, added a layer to the fully connected (fc) layer of the pretrained model and trained the model for this specific problem.
## Usage
### 1. Clone this repository to your local computer
```shell
git clone https://github.com/MindVu/Dog-Emotion.git
```
### 2. Install the required dependencies
Please install all required dependencies (libraries) if you do not already have any in your local computer.
### 3. Download the dataset
Download the dataset from the given link (https://www.kaggle.com/datasets/danielshanbalico/dog-emotion) and add the dataset folder to the repository folder.
### 4. Train, test and infer models
Run the EmotionDetection.ipynb file and you will get the trained models in the 'model' folder. Finally, you can use these models to test or infer (already in the ipynb file).
