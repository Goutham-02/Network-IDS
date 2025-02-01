# Intrusion Detection System Using Machine Learning

## Project Overview

This project focuses on developing an efficient Intrusion Detection System (IDS) by implementing and comparing two machine learning classifiers: Support Vector Machine (SVM) and K-Nearest Neighbors (KNN). Utilizing the NSL-KDD dataset, the study aims to enhance detection accuracy and reduce computational complexity through optimal feature selection using a suitable algorithm.

## Motivation

Traditional IDS methods often struggle to detect new and evolving cyber threats due to their reliance on predefined signatures. This project addresses these limitations by leveraging machine learning techniques to create a more adaptive and effective IDS, thereby improving network security in modern environments.

## Objectives

- **Develop an IDS**: Implement a machine learning-based system to classify network traffic as normal or malicious.
- **Compare Classifiers**: Evaluate the performance of SVM and KNN classifiers to determine the more effective model for intrusion detection.
- **Optimize Feature Selection**: Apply a feature selection algorithm to select relevant features, enhancing detection accuracy and reducing computational load.
- **Evaluate Performance**: Assess models using metrics such as accuracy, precision, recall, and F1-score.

## Dataset

The [NSL-KDD dataset](https://www.unb.ca/cic/datasets/nsl.html) is used for training and evaluating the classifiers. It is a refined version of the KDD'99 dataset, addressing some of its inherent issues and providing a more reliable benchmark for intrusion detection research.

## Methodology

1. **Data Preprocessing**: Clean and preprocess the NSL-KDD dataset to prepare it for model training.
2. **Feature Selection**: Employ feature selection to identify and select the most relevant features.
3. **Model Implementation**: Develop and train SVM and KNN classifiers using the selected features.
4. **Evaluation**: Test the models and evaluate their performance using the specified metrics.

## Results

The KNN classifier achieved an accuracy of 97%, outperforming the SVM classifier, which achieved an accuracy of 96%. Detailed performance metrics are as follows:

| Class     | Precision | Recall | F1-Score |
|-----------|-----------|--------|----------|
| Abnormal  | 0.97      | 0.98   | 0.97     |
| Normal    | 0.98      | 0.97   | 0.98     |

## Conclusion

This study demonstrates that the KNN classifier, combined with effective feature selection, provides a more accurate and efficient solution for intrusion detection compared to the SVM classifier. The findings highlight the importance of classifier selection and feature optimization in developing robust IDS solutions.

## Installation and Usage

To replicate this study:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/ids-ml-project.git
   cd ids-ml-project
