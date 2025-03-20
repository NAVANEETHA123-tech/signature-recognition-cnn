# Signature Recognition using CNN & Feature Engineering  

## Overview  
This project implements **Signature Recognition** using **Convolutional Neural Networks (CNNs)** and **manual feature extraction techniques (HOG, SIFT)**. The goal is to **classify signatures** based on different individuals and compare **CNN-based feature extraction vs. traditional techniques**.  

## Key Objectives  
- **Segment signatures** into separate folders per individual  
- **Perform train-test split** for model evaluation  
- **Train CNNs for signature classification**  
- **Compare CNN features with manual feature extraction (HOG, SIFT, etc.)**  
- **Evaluate models using Precision, Recall, F1-score, and Accuracy**  
- **Analyze performance through error plots & visualizations**  

## Repository Contents  
- `code/` → Python scripts for segmentation, feature extraction, model training  
- `report.pdf` → Detailed analysis, methodology, and results  
- `README.md` → Project documentation (to be expanded)  

## 🚀 Future Enhancements  
✅ Add dataset details & preprocessing steps  
✅ Upload sample outputs & model performance comparisons  
✅ Expand CNN hyperparameter tuning & architecture variations  
✅ Implement additional feature extraction techniques  

## 📜 How to Run  
```bash
# Example: Running CNN model
python train_cnn.py

# Running feature extraction
python feature_extraction.py --method HOG
