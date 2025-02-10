

# Final Project: Voice Authentication and Gender Classification using Machine Learning

## Overview

This project focuses on utilizing machine learning algorithms to perform **voice authentication** and **gender classification** using audio features. The aim is to design a model capable of distinguishing between male and female speakers and authenticating the identity of the speaker using their voice, based on various audio features.

## Objectives

1. **Voice Authentication** : The model will authenticate a speaker's identity based on their voice using closed-set and open-set authentication techniques.
2. **Gender Classification** : The model will classify the gender of the speaker from audio features.
3. **Feature Extraction** : Extract relevant features from audio signals, such as  **Mel-frequency cepstral coefficients (MFCC)** ,  **spectral centroid** ,  **log Mel spectrogram** , and more.
4. **Data Preprocessing** : Implement noise reduction, normalization, and windowing techniques to enhance the quality of the input data.

## Project Structure

The project is divided into several phases:

### Phase 1: Introduction to Audio Signal Processing

* **Data Preprocessing** : Learn and implement the basic signal processing techniques, such as:
* **Noise reduction** (e.g., using spectral subtraction or bandpass filtering).
* **Normalization** and **windowing** techniques.
* **Feature Extraction** : Apply various algorithms to extract features from audio signals. Focus will be on:
* **MFCC (Mel Frequency Cepstral Coefficients)**
* **Spectral Centroid**
* **Log Mel Spectrogram**
* **Zero-Crossing Rate**
* **Chroma Features**
* **Spectral Contrast**

### Phase 2: Practical Implementation with Dataset

* **Dataset** : The dataset consists of audio files in MP3 format, named with the pattern `HWx_Qy_Student-ID_gender.mp3`.
* **Tasks** :
* **Gender Classification** : Use machine learning models to classify the gender of the speaker.
* **Voice Authentication** : Use models to authenticate the voice based on prior recordings from the same individual.
* **Steps** :

1. **Data Loading** : Load the raw audio files.
2. **Data Preprocessing** : Clean and prepare the data by removing noise and resampling.
3. **Feature Extraction** : Apply feature extraction techniques.
4. **Model Training** : Train models using extracted features for both tasks (gender classification and voice authentication).
5. **Model Evaluation** : Evaluate the models using appropriate metrics (e.g., accuracy, precision, recall, F1-score, confusion matrix).

### Phase 3: Report Writing and Analysis

* **Initial Report** : Prepare a group report covering:
* Voice authentication methods (closed-set and open-set).
* Data preprocessing challenges and solutions.
* Comparison of feature extraction techniques.
* **Final Report** : The final report will include:
* A detailed explanation of the models used, the results, and the challenges faced.
* A comparative analysis of different classification techniques such as Logistic Regression, KNN, SVM, MLP, and XGBoost.
* Evaluation using performance metrics and visualizations (e.g., ROC Curve, confusion matrix).
* **Clustering Analysis** : Apply clustering algorithms to identify patterns within the audio data and visualize the results.

### Phase 4: Grading Criteria

The grading will be based on the following:

* **Initial Report (20%)**
* **Preprocessing and Feature Extraction (30%)**
* **Classification (30%)**
* **Clustering (20%)**

### Phase 5: Final Considerations

* **Plagiarism Policy** : Any form of plagiarism or copying from other students will result in severe penalties.
* **Collaboration** : The project can be done individually or in a group of up to 4 people.

## Required Libraries and Tools

* **Python** : Programming language used for model development.
* **Librosa** : Library for audio processing.
* **Scikit-learn** : For machine learning models.
* **TensorFlow / Keras** : For deep learning models (if applicable).
* **Matplotlib** : For visualization.

## How to Run the Project

1. **Clone the Repository** :

```bash
   git clone https://github.com/your-repository/voice-authentication-project.git
```

1. **Install Dependencies** :

```bash
   pip install -r requirements.txt
```

1. **Data Preparation** : Download the dataset from [Google Drive](https://drive.google.com/drive/folders/1pq_jGqdBda_QjNnK2yAzD4N2grbPF8Rs?usp=sharing) and place it in the appropriate folder.
2. **Run the Code** : Execute the scripts for data preprocessing, feature extraction, and model training.

---
