# QR Code Authentication

## Overview  
This project classifies QR codes as **original (First Print)** or **counterfeit (Second Print)** using **machine learning (ML) and deep learning (DL) approaches**.

## Approaches Tested  
- **Support Vector Machine (SVM)** (Best ML Model) → **86.67% Accuracy**  
- **EfficientNetB0** (Best DL Model) → **58.33% Accuracy**  
- **Artificial Neural Network (ANN)** with extracted features → **50% Accuracy**  
- **Simple CNN with Data Augmentation** → Poor performance due to small dataset  
- **Decision Tree Classifier** → Overfitting issues  

## Dataset  
- **First Print (Original QR Codes):** 100 images  
- **Second Print (Counterfeit QR Codes):** 100 images  
- **Train/Test Split:** 70% training, 30% testing for both classes  

## Key Findings  
- **Feature-based ML models (SVM) performed best.**  
- **Deep learning models struggled due to dataset size.**  
- **Hybrid models combining features with deep learning could improve accuracy.**  

## How to Run  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/QR_Code_Authentication.git
   cd QR_Code_Authentication
