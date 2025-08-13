# Distinguishing Real and AI-Generated Images Using Classification Models

## Project Overview
This project focuses on differentiating between real and AI-generated images by employing advanced classification models. A balanced dataset containing both image types was collected and preprocessed to train and evaluate three distinct models.

## Methodology
- **Data Collection:** Compiled a balanced dataset categorized into "REAL" and "FAKE" images.
- **Data Preprocessing:** Uniform resizing (32x32 and 128x128), normalization, and dataset splitting into training, validation, and testing sets.
- **Exploratory Data Analysis (EDA):** Identified distinguishing features such as edge sharpness, texture details, and color distribution.
- **Model Development:**  
  - Model 1: Pre-trained Vision Transformer (ViT) as a baseline.  
  - Model 2: Custom lightweight CNN for 32x32 images.  
  - Model 3: Deeper CNN with Dropout for 128x128 images.
- **Training and Evaluation:** Trained Models 2 and 3, evaluated using accuracy, precision, recall, F1-score, confusion matrices, and learning curves.
- **Performance Comparison:** Analyzed strengths and limitations of each model.
- **Challenges and Solutions:** Addressed issues like unstructured image data, resource limitations, dataset bias, and model overfitting.
- **Future Work:** Suggested improvements including diverse AI-generated image sources, higher-resolution inputs, advanced architectures, and explainability techniques.

## Technologies Used
- Python  
- TensorFlow / PyTorch (mention whichever you used)  
- OpenCV  
- Jupyter Notebook  

## Project Presentation  
You can view/download the project presentation here: [Presentation PDF]([https://drive.google.com/your-shared-link](https://drive.google.com/file/d/1s-jCafpj0SztWsTMGRLsjMtT2ENVP_TG/view?usp=sharing))

