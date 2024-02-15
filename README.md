# EEG Eye State Classification Project

## Abstract

This project is dedicated to the classification of EEG eye state data, aiming to develop an accurate model for predicting whether a person's eyes are open (labeled as 1) or closed (labeled as 0) based on recorded EEG measurements. The comprehensive approach involves preprocessing steps, feature extraction, and the application of Independent Component Analysis (ICA) for artifact removal, culminating in the implementation of a machine learning model.

## 1. Introduction

The understanding of the intricate relationship between EEG data and eye states holds significant potential across various domains, such as healthcare, neurology, and human-computer interaction. By leveraging advanced data processing techniques and machine learning methodologies, this project seeks to contribute to the nuanced understanding of EEG patterns associated with different eye states.

## 2. Data Description

The EEG eye state dataset originates from the 'EEG_Eye_State_Classification.csv' file. Comprising EEG measurements from distinct scalp locations, the dataset encapsulates the electrical activity in the brain during various eye states. The binary 'label' variable signifies whether the eyes are open (1) or closed (0) during each recorded instance.

## 3. Preprocessing Techniques

To ensure the reliability and quality of input data, the raw EEG data undergoes meticulous preprocessing steps. This includes creating MNE data structures for efficient handling of EEG data. Additionally, Independent Component Analysis (ICA) is applied to remove artifacts, such as eye blinks or muscle activity, ensuring that the subsequent analysis is based on a clean and representative dataset.

ICA is a powerful signal processing technique that decomposes the raw EEG data into statistically independent components. By identifying and excluding components associated with artifacts, the ICA process enhances the quality of the EEG signals, providing a more accurate representation of the underlying brain activity.

**ICA Visualization:**
 <p align="left">
    <img src="https://github.com/hazemzakariasaad/EEG_Eye_State_Prediction/blob/main/Screenshot.png" alt="ICA="200" height="300">
 </p>


## 4. Data Preparation

Datasets are meticulously prepared for different frequency bands (Delta, Theta, Alpha, Beta). This granular categorization allows for a nuanced exploration of specific brainwave activities associated with different eye states, providing deeper insights into the underlying neurophysiological processes.

## 5. Machine Learning Algorithm

The heart of the project lies in the implementation of a machine learning model using TensorFlow and Keras. This model is trained on the preprocessed and feature-enriched data, learning intricate relationships between EEG features and eye states. The choice of model architecture and hyperparameters is made with careful consideration to optimize predictive performance.

## 6. Results and Discussion

In this section, we present the results obtained from the machine learning model, including relevant visualizations and insights. Discussion points include the significance of specific features, model performance metrics, and potential areas for improvement. Any challenges encountered during the project are thoroughly addressed.

## 7. Conclusion

The project concludes by summarizing key findings, acknowledging limitations, and suggesting potential avenues for future research. Emphasis is placed on the broader implications of accurate EEG eye state classification and how it could impact diverse applications.


