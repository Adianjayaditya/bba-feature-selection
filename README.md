# Parkinson's Disease Classification using SVM

This project aims to classify individuals with Parkinson's disease using a Support Vector Machine (SVM) model. The classification is based on biomedical voice measurements, helping in early diagnosis and analysis of the disease. The features used in this dataset are various speech signal processing algorithms including Time Frequency Features, Mel Frequency Cepstral Coefficients (MFCCs), Wavelet Transform based Features, Vocal Fold Features and TWQT features of parkinson's disease patients.

## Dataset

- **Source**: [Kaggle](https://www.kaggle.com/datasets/dipayanbiswas/parkinsons-disease-speech-signal-features)
- **Target Variable**: `status`  
  - `1` = Parkinson’s  
  - `0` = Healthy

## Technologies Used
- Pandas
- NumPy
- Scikit-learn

## Methods Used

- Data Cleaning & Preprocessing
- Feature scaling (MinMaxScaler)
- Feature selection using Binary Bat Algorithm
- Model Evaluation using accuracy

## Results

- **Best Accuracy**: 92.5%  
- **Model**: SVM with Linear kernel

## Installation and Setup
### Prerequisites

Before setting up this project, ensure that you have the following installed:

- Python 3.8+
- Pip package manager
- Git

### Clone the Repository

```bash
git clone https://github.com/your-username/KTP-Data-Extractor.git
cd KTP-Data-Extractor
```

### Install Dependencies

You can install the required dependencies using the following command:

```bash
pip install -r requirements.txt
```

Once everything is set up, you can run the code in Jupiter Notebook.