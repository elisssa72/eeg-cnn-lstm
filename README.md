# EEG Motor Imagery Classification – CNN-LSTM

This repository contains my contribution to a deep learning EEG project using the EEG Motor Movement/Imagery Dataset (PhysioNet).

## My Contribution
- Implemented the CNN feature extraction layers
- Built and trained the CNN–LSTM (CLSTM) model
- Evaluated performance using Accuracy, AUC, Confusion Matrix, ROC curve, and F1-score

## Model
Input: 64 EEG channels × 256 time samples  
Output: Binary classification (pre-movement vs baseline)

## Tools Used
- TensorFlow / Keras
- MNE
- Scikit-learn
- Matplotlib

## Notes
Dataset files (.edf) are not included in this repository.
