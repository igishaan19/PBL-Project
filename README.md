# Signature Verification on Bank Cheques to Reduce Fraud

# Overview
This project presents an automated signature verification system designed to detect fraudulent signatures on bank cheques. The system leverages image processing techniques and machine learning models to improve the efficiency and reliability of signature authentication in financial institutions.

Manual signature verification is time-consuming and subjective. This project aims to reduce fraud by implementing a robust automated verification mechanism.

# Problem Statement
Manual signature verification on bank cheques is inefficient and prone to human error. There is a need for an automated system that can accurately verify signatures and reduce financial fraud.

# Objectives
- To automatically detect signatures from cheque images
- To extract geometric and structural features of signatures
- To classify signatures as genuine or forged using ML models
- To improve fraud detection accuracy in financial institutions

# System Workflow
1. Capture cheque image
2. Localize signature using OCR
3. Extract signature using detection algorithms
4. Perform feature extraction
5. Classify using Machine Learning model
6. Verify authenticity

# Signature Detection Approaches

# 1️. OCR + Connected Components
- OCR is used to localize signature regions.
- Connected Components Labelling extracts the signature.
- Assumption: Signature strokes are connected.

# 2️. OCR + Line Sweep Algorithm
- OCR identifies signature region.
- Line Sweep algorithm fits rectangles across signature.
- More efficient and accurate than Connected Components.

# Signature Verification Models
# 🔹 Support Vector Machine (SVM)
Supervised machine learning model used for classification.
# 🔹 Artificial Neural Network (ANN)
Deep learning approach used for improved classification performance.

# Results
The proposed system achieved approximately 91% accuracy in distinguishing genuine and forged signatures.
