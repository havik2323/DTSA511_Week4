# Disaster Tweets Classification

This repository contains the code and data for the Disaster Tweets Classification project. The goal of this project is to classify tweets related to disasters using various machine learning and deep learning models.

## Repository Structure

- **best_models/**: Contains the top-performing models saved during training.
- **kaggle_leaderboard/**: Directory for Kaggle leaderboard-related files.
- **nlp-getting-started/**: Contains initial setup files and notebooks for the NLP project.
- **predictions/**: Contains prediction outputs from the trained models.
- **Disaster_Tweets_Lab_Final.ipynb**: The main Jupyter notebook containing the full code for the project.

## Getting Started

To get started with this project, you need to follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/disaster-tweets-classification.git
    cd disaster-tweets-classification
    ```

2. **Install the necessary dependencies**:
    Make sure you have Python and pip installed. Then, run:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Jupyter notebook**:
    Open the `Disaster_Tweets_Lab_Final.ipynb` notebook in Jupyter and follow the instructions to train and evaluate the models.

## Contents

### best_models/
This directory contains the top 10 models saved during the training process. Each model is saved as a checkpoint file with its respective hyperparameters and performance metrics.

### kaggle_leaderboard/
Contains files related to Kaggle leaderboard submissions and performance tracking.

### nlp-getting-started/
This directory includes initial setup files, data exploration, and preprocessing notebooks. It serves as the starting point for the project.

### predictions/
Contains the prediction outputs from the trained models. These files can be used for evaluation and comparison against ground truth labels.

### Disaster_Tweets_Lab_Final.ipynb
The main notebook for this project. It includes the following:
- Data loading and preprocessing
- Word embeddings generation (TF-IDF, Word2Vec, GloVe, BERT)
- Model definitions (LSTM, GRU, Bidirectional LSTM)
- Training and evaluation loops
- Hyperparameter tuning
- Results and analysis


This project is licensed under the MIT License - see the LICENSE.md file for details.

