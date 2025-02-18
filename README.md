# TIR Predictor for E.Coli (Work in Progress)

## Overview
- TIR Predictor is a machine learning-based project aimed at predicting translational initiation rates (TIR) using gene sequence data. The project is currently under development, with ongoing improvements in feature selection and model performance.

## Dataset
- The dataset(final_data.csv) is **really small**, containing only **331 different ecoli gene sequences**.
- Each sequence has **26 parameters** out of which 4 are gene_length,shine-dalgarno score,position of A and C nucleotide (T and G are irrelevant) and rest of them being Gibbs-Free energy for various parts of the sequence.

## Current Approach
- **Dimensionality Reduction:** We applied **Principal Component Analysis (PCA)** and selected **12 dimensions** for optimal performance.
- **Model Used:** after thorough testing,**XGBoost** has provided best results for prediction.
- **Performance:**
  - **Train Pearson Score:** 78%
  - **Test Pearson Score:** 75%

## Next Steps
- Exploring feature engineering techniques to enhance prediction accuracy.
- Calculating sd_score using some better way that have a positive effect on pearson score
- Trying different models and hyperparameter tuning.
- Increasing dataset size for better generalization.

## Acknowledgment
- Currently working on it under the guidance of [Dr. Ajeet Kumar Sharma (Department of Physics, IIT Jammu)](https://scholar.google.com/citations?user=EiyNQG8AAAAJ&hl=en).

Stay tuned for further updates!

