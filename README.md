# BERT-Enhanced SMS Spam Classification

## Overview
A comparative analysis of machine learning and deep learning models for SMS spam detection using BERT embeddings to improve contextual understanding and classification performance.

## Block Diagram
![Block Diagram](docs/block_diagram.png)

The system follows a pipeline of data collection, preprocessing, BERT-based feature extraction, model training, and performance evaluation.

## Key Features
- Uses BERT embeddings for semantic feature extraction
- Implements Naive Bayes, LSTM, BiLSTM, and Transformer models
- Handles class imbalance using dataset balancing techniques
- Evaluates using Accuracy, Precision, Recall, F1-score, ROC-AUC, and Brier Score

## Results Visualization
![Performance Comparison](docs/performance_chart.png)
![ROC Curve](docs/roc_curve.png)

## Results Summary
- Best Model: LSTM
- Accuracy: 96.7%
- ROC-AUC: 0.991
- Brier Score: 0.028
- Deep learning models outperform traditional methods in overall performance

## Tech Stack
- Python 3.12
- Google Colab
- Natural Language Processing (BERT)
- Machine Learning and Deep Learning

## Dataset
- Source: UCI SMS Spam Dataset
- Total messages: 5,574
- Balanced dataset: 747 spam and 747 ham messages

## Models Used
- Naive Bayes
- LSTM
- BiLSTM
- Transformer

## Applications
- SMS spam detection
- Fraud and phishing prevention
- Text classification systems

## Future Scope
- Hybrid models combining LSTM and Transformer
- Integration of Explainable AI (XAI)
- Deployment in real-time systems
## 📜 License

This project is licensed under the **MIT License**.

---

## 🙌 Acknowledgment

Developed as part of **GEN-AI**  
KLE Technological University

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
