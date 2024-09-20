# NASA-RUL-Assignment

## Project Overview
This project is part of the predictive maintenance assignment focused on estimating the Remaining Useful Life (RUL) of aircraft engines using machine learning models, specifically LSTM (Long Short-Term Memory) and GRU (Gated Recurrent Unit) neural networks. The project uses NASA’s C-MAPSS dataset, which contains run-to-failure data for engines under various conditions.

The objective is to predict the RUL of engines to improve maintenance schedules and avoid unexpected failures.


## Repository Structure:
- **code/**
  - `Starter_Notebook_Predictive_Maintenance_using_LSTM-1 (3).ipynb`: The main Jupyter notebook containing the entire workflow including data preprocessing, model training, evaluation, and visualization.
  - `main_rul.py`: A Python script designed to load and evaluate the saved LSTM and GRU models on test data.
  - `best_gru_model.keras` & `best_lstm_model.keras`: These files contain the best versions of the GRU and LSTM models saved during training.

- **data/**: Contains raw datasets in txt format required for training and testing models.
  - `train_FD001.txt`, `test_FD001.txt`, and `RUL_FD001.txt` are sample files; make sure to adjust these based on the datasets you actually use.

- **models/**: Stores the finalized models after evaluation.
  - `final_lstm_model.keras` & `final_gru_model.keras`: Final versions of the models saved after the training and evaluation phase.

- **README.md**: Provides a detailed overview of the project, instructions for setup, and how to run the scripts.

- **requirements.txt**: Lists the Python libraries required to run the project.

Feel free to update file names, paths, or descriptions as needed based on your specific implementation! Let me know if you need further adjustments.


## test
NASA-RUL-Assignment/
│
├── code/                         # Source code files
│   ├── main_rul.py               # Main script for evaluating models on test data
│   ├── feature_engineering.py    # Script for feature engineering and data preprocessing
│   ├── hyperparameter_tuning.py  # Script for hyperparameter tuning of LSTM and GRU models
│   ├── train_lstm.py             # Script for training the LSTM model
│   ├── train_gru.py              # Script for training the GRU model
│   └── utils.py                  # Utility functions for data loading and processing
│
├── models/                       # Folder containing trained model files
│   ├── final_lstm_model.keras    # Saved LSTM model
│   ├── final_gru_model.keras     # Saved GRU model
│
├── data/                         # Folder for storing dataset files
│   ├── train/                    # Training data files
│   ├── test/                     # Test data files
│   └── processed/                # Processed data files ready for modeling
│
├── README.md                     # Project overview and instructions
└── requirements.txt              # Python dependencies

