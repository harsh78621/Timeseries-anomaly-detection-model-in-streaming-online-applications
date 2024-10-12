# Anomaly Detection Project

This project utilizes a Keras Sequential autoencoder for detecting anomalies in time-series data.

## Data Processing

- **Processed and normalized:** 4,032 data points
- **Duration:** 14 days
- **Sampling frequency:** Every 5 minutes (288 timesteps per day)

## Model Architecture

- **Model type:** Keras Sequential Autoencoder
- **Layers:** Conv1D and Conv1DTranspose
- **Optimizer:** Adam
- **Loss function:** Mean Squared Error (MSE)

## Anomaly Detection

- **Reconstruction error threshold:** 0.1233
- Samples with reconstruction loss exceeding this threshold were classified as anomalies.
- **Total anomalies detected:** 394

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/anomaly-detection.git


 ![Anamoly Demo](https://github.com/harsh78621/Timeseries-anomaly-detection-model-in-streaming-online-applications/blob/main/Anamoly.gif?raw=true)
