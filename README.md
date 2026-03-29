legal-clause-classifier
Pairwise legal clause classification using BiLSTM and Attention-based encoders with custom FastText embeddings, built in PyTorch.
Overview
This project trains deep learning models to classify whether two legal clauses are related or similar. It was developed as part of a Deep Learning course assignment.
Features

Custom FastText embeddings (100-dim) trained on the legal clause corpus
Two model architectures:

BiLSTM Classifier — shared BiLSTM encoder with max+avg pooling
Attention Encoder — attention-based clause pair encoder


Full training loop with checkpointing
Evaluation metrics: Accuracy, Precision, Recall, F1, ROC-AUC
Runtime inference for testing custom clause pairs

Tech Stack

Python, PyTorch, Gensim, NLTK, scikit-learn
Google Colab (T4 GPU)

Usage

Open the notebook in Google Colab
Mount your Google Drive and place kaggle.json at /MyDrive/kaggle/kaggle.json
Run all cells in order — data download, preprocessing, training, and evaluation are all included