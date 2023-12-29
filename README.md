# UAV_RF_predictor

This repository contains the implementation of various models and **Random Forest (RF) model** for predicting the **type** of **Unmanned Aerial Vehicles (UAVs)**. The model is trained on a dataset of **UAV signal strength measurements** from https://www.kaggle.com/datasets/xcz74741/rf-signals-of-uavs.

## Requirements

- Python 3.6 or higher
- scikit-learn
- pandas
- numpy
- scipy.io
- csv
- random


## Usage

1. Clone the repository:

git clone https://github.com/AghababyanSG/UAV_RF_predictor.git

2. Install the required packages:

pip install -r requirements.txt


## Dataset

The dataset used for training the RF model is available in the `data` directory. It contains the following columns:

- `Latitude`: The latitude of the location where the signal strength was measured.
- `Longitude`: The longitude of the location where the signal strength was measured.
- `Altitude`: The altitude of the location where the signal strength was measured.
- `Signal Strength`: The signal strength measured at the location.

The dataset was obtained from Kaggle [^1^][1].

## Results

The RF model achieved an **F1 score of 0.97** on the test set, indicating a good fit to the data.

## License

This project is licensed under the MIT License - see the LICENSE file for details.