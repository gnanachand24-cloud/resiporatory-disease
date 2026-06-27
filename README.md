# Respiratory Disease Detection from Cough Sounds

## Overview

This project presents a deep learning approach for detecting COVID-19 from human cough recordings. The objective is to investigate whether cough sounds contain distinctive acoustic patterns that can be used for preliminary disease screening.

The project uses the **CoughVID public dataset**, where cough audio recordings are converted into **Mel-spectrograms** and classified using a **Convolutional Neural Network (CNN)**.

> **Note:** This project is intended for research and educational purposes only and should not be used as a medical diagnostic tool.

---

## Features

* Audio preprocessing using Librosa
* Mel-spectrogram generation
* Binary classification (Healthy vs COVID-19)
* Convolutional Neural Network (CNN) implementation
* Model evaluation using classification metrics
* Confusion matrix visualization
* Prediction analysis

---

## Technologies Used

* Python
* TensorFlow / Keras
* Librosa
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

## Dataset

**Dataset:** CoughVID Public Dataset

The dataset contains thousands of cough recordings together with metadata describing health status and recording quality.

Each cough recording is converted into a Mel-spectrogram before being used to train the deep learning model.

---

## Project Workflow

1. Load metadata and cough recordings
2. Filter COVID-19 and healthy samples
3. Preprocess audio files
4. Generate Mel-spectrograms
5. Split data into training and testing sets
6. Train a CNN model
7. Evaluate model performance
8. Visualize predictions and confusion matrix

---

## Project Structure

```text
Respiratory-Disease/
│
├── Dataset/
├── notebooks/
├── images/
├── models/
├── respiratory_disease_detection.ipynb
├── requirements.txt
└── README.md
```

---

## Installation

```bash
git clone https://github.com/gnanachand24-cloud/resiporatory-disease.git

cd resiporatory-disease

pip install -r requirements.txt
```

---

## Running the Project

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Run all notebook cells sequentially.

---

## Results

The CNN model learns discriminative cough sound patterns for binary classification.

Performance is evaluated using:

* Classification Accuracy
* Confusion Matrix
* Precision
* Recall
* F1-Score

---

## Screenshot

Add screenshots such as:

* Mel Spectrogram
* CNN Training Accuracy Graph
* Loss Curve
* Confusion Matrix
* Sample Predictions

Create an `images/` folder and include them like this:

```markdown
![Confusion Matrix](images/confusion_matrix.png)
```

---

## Future Improvements

* Improve class balancing
* Experiment with transfer learning
* Evaluate ResNet and EfficientNet architectures
* Deploy the model as a web application
* Extend to multi-class respiratory disease detection

---

## Acknowledgements

* CoughVID Dataset
* TensorFlow
* Librosa
* Scikit-learn

---

## Author

**Gnanachand**

GitHub: https://github.com/gnanachand24-cloud
