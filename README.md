# NASA-RUL-Assignment

## Project Overview
This project is part of the predictive maintenance assignment focused on estimating the Remaining Useful Life (RUL) of aircraft engines using machine learning models, specifically LSTM (Long Short-Term Memory) and GRU (Gated Recurrent Unit) neural networks. The project uses NASA’s C-MAPSS dataset, which contains run-to-failure data for engines under various conditions.

The objective is to predict the RUL of engines to improve maintenance schedules and avoid unexpected failures.


## Repository Structure
- **code/**
  - `Starter_Notebook_Predictive_Maintenance_using_LSTM-1 (3).ipynb`: The main Jupyter notebook containing the entire workflow including data preprocessing, model training, evaluation, and visualization.
  - `main_rul.py`: A Python script designed to load and evaluate the saved LSTM and GRU models on test data.
  - `best_gru_model.keras` & `best_lstm_model.keras`: These files contain the best versions of the GRU and LSTM models saved during training.

- **data/**: Contains raw datasets in txt format required for training and testing models.
  - `train_FD001.txt`, `test_FD001.txt`, and `RUL_FD001.txt` are sample files; make sure to adjust these based on the datasets you actually use.

- **visualizations/**: This folder contains all the visuals I produced in my notebook. I have a total of 12 images. Each image that has an _n at the end represents the order of image creation.
  - `CM_1.png` - Is the first image created
  - ....
  - `Bonus_Attempt_12.png` - Is the last image created


- **README.md**: Provides a detailed overview of the project, instructions for setup, and how to run the scripts.


## Getting Started
If you download the jupyter notebook and run it in google colab, all will run accordingly.

## Running the Jupyter Notebook
To run the entire workflow, open Starter_Notebook_Predictive_Maintenance_using_LSTM-1 (3).ipynb in Google Colab or any Jupyter Notebook environment. This notebook includes:

Data Preprocessing and Feature Engineering
Hyperparameter Tuning for LSTM and GRU models
Model Training and Evaluation
Visualization of Results
