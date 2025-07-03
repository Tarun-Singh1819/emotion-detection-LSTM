# emotion-detection-LSTM
Emotion detection from text sentences using LSTM model


# Emotion Detection from Sentences using LSTM 

This project detects emotions in user sentences using a deep learning LSTM model.  
It classifies text into emotions like Joy, Anger, Sadness, etc.


## Objective

To develop an emotion classification system using RNNs (LSTM) that takes a sentence and predicts its emotional category.

---

## Model Details

- Text preprocessing: tokenization, padding
- Embedding Layer
- LSTM Layer
- Dense + Softmax Output Layer
- Best model selected based on validation accuracy

---

## Dataset

- Dataset used: Emotion Dataset from Kaggle  
- [Kaggle Link](https://www.kaggle.com/datasets/praveengovi/emotions-dataset-for-nlp)
- You can also find the dataset in this repo as a ZIP file.

## Results

- Achieved ~92% validation accuracy
- Trained multiple models and saved the best

👉 [Download my_model.h5 from Google Drive](https://drive.google.com/file/d/1gbgSh9uW0pXeRYP6lxwAhgGcoQbP9tgH/view?usp=drive_link)


## How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/Tarun-Singh1819/emotion-detection-lstm.git
   cd emotion-detection-lstm

   pip install -r requirements.txt
