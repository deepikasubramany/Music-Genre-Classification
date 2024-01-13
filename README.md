# Music-Genre-Classification

Music genre classification involves the automated categorization of music tracks into distinct genres based on inherent musical characteristics. This project, titled "Efficient Music Genre Recognition with Deep Learning," explores this field, leveraging the capabilities of deep neural networks. 
The key points include:
Significance: Music genre classification is crucial for personalized playlist generation, music recommendation systems, and organizing vast music libraries efficiently.
Approach: Using a combination of Convolutional Neural Networks (CNNs) and Long Short-Term Memory networks (LSTMs) to address challenges in accurate genre classification, especially with overlapping elements and varying song lengths.

## Problem Statement:

The problem of music genre classification is complex due to the subjective nature of genres and the diverse characteristics defining each. Challenges include overlapping features and variability in song lengths. Computational and data resource requirements can be substantial, limiting applicability. This project focuses on developing an efficient and adaptable music genre recognition system for resource-constrained environments.

## The Data

Our project relies on the GTZAN dataset, comprising 10 music genres, each represented by 100 audio files. The dataset link is [GTZAN Dataset](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification). Audio files are converted into Mel Spectrograms for neural network analysis. Two CSV files provide statistical data derived from audio files, enhancing the dataset's size and performance.

In EDA, we visualize audio signals' characteristics, including amplitude, structure, and temporal features. Model Development involves CNNs (CNN1, CNN2 with dropout) and an LSTM capturing temporal dependencies, achieving high accuracy in music genre classification.
