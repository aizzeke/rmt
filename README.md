# RMT: Bus Arrival Time Prediction Framework

This repository contains the code, models, and data associated with the final research project on multi-step bus arrival time prediction using advanced deep learning techniques.

## Overview

The project focuses on developing a robust framework to predict bus arrival times by integrating real-time GPS data, traffic conditions, and weather information. Two main deep learning architectures are employed:
- **Enhanced WaveNet** – a convolutional neural network that captures temporal dependencies via causal convolutions.
- **Temporal Fusion Transformer (TFT)** – a hybrid model combining LSTM layers with multi-head attention to dynamically weight feature importance.

This approach is aimed at addressing the challenges of urban transit systems, enhancing passenger experience, and providing insights for transit operators.

## Repository Structure

- **models/**  
  Contains the trained deep learning model files (e.g., Enhanced WaveNet and TFT) and their configuration scripts.

- **notebooks/**  
  Includes Jupyter notebooks that document data preprocessing, model training, evaluation, and visualization of results.

- **line_30.csv**  
  The dataset used in this project, which includes both static (route numbers, driver IDs, scheduled times) and dynamic features (inter-stop time differences, distances, weather conditions).

## How to Use

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/aizzeke/rmt.git
   ```

2. **Explore the Notebooks:**  
   The notebooks in the `notebooks/` folder detail the data preprocessing steps, model training procedures, and evaluation metrics. They serve as a guide to reproduce the experiments.

3. **Review the Models:**  
   The `models/` folder contains the source code for the deep learning architectures used in the project. These scripts outline the implementation details for the Enhanced WaveNet and TFT models.

4. **Run the Project:**  
   Use the provided notebooks and model scripts to run training and inference on the dataset (`data.csv`). Detailed instructions are provided within the notebooks.

## Project Highlights

- **Multi-Step Prediction:**  
  Our framework predicts bus arrival times for multiple upcoming stops rather than just the next stop.

- **Performance Evaluation:**  
  Models are evaluated using RMSE, MAE, and R² scores. The experimental results demonstrate competitive performance compared to traditional methods.

## Contact

@aizzeke on telegram
