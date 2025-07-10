
#  Music Genre Classification with GMMs

A small-scale music genre classifier implemented from scratch using **MFCCs**, **Gaussian Mixture Models**, and a custom **Expectation-Maximization (EM)** algorithm. This project was created as part of a university course to explore probabilistic models in audio classification.

---

##  Project Summary

This project implements a simple genre classification pipeline in three stages:

1. **Feature Extraction**  
   - Extract **Mel-Frequency Cepstral Coefficients (MFCCs)** from audio files using `librosa`.

2. **Model Training**  
   - Train a separate **Gaussian Mixture Model (GMM)** for each genre using a **custom Expectation-Maximization (EM)** implementation.

3. **Classification**  
   - Predict genre labels using **Maximum A Posteriori (MAP)** classification based on log-likelihood.

---

##  Dataset

The dataset consists of:

- **3 genres**: Blues, Classical, Reggae  
- **100 total audio files**, split into training and testing sets  

