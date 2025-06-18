# EY 2025 Open Science AI Challenge – Cooling Urban Heat Islands
This repository contains the code and model used for my participation in the 2025 EY Open Science AI and Data Challenge, focused on predicting Urban Heat Island (UHI) intensity using satellite-based geospatial data.

## Project Summary
Objective:
Develop a machine learning model to predict Urban Heat Island values for specific geographic coordinates, leveraging open-access satellite imagery and climate data provided through Microsoft's Planetary Computer.

My Contribution:

- Designed a custom Attention-based Convolutional Neural Network (CNN) to capture spatial patterns influencing UHI effects.

- Built an efficient data pipeline to preprocess raw geospatial data and extract meaningful features.

- Achieved an R² score of 95% on the final test set.

- Ranked 4th out of 8 in Greece and 98th out of 377 globally.

- Improved RMSE by 25% over the provided baseline model.

## Model Architecture
The model uses:

Convolutional layers to extract spatial features from satellite image tiles.

A self-attention mechanism to focus on the most influential regions within the image.

Fully connected layers to regress UHI values.

Frameworks used:

- TensorFlow + Keras for model implementation.

- NumPy, Pandas for data handling.

- Planetary Computer SDK to query and retrieve geospatial satellite imagery.
