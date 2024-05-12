# Human Activity Recognition using LSTM on HARTH Dataset

This repository (https://github.com/1666sApple/Human-Activity-Recognition-LSTM) contains an implementation of a Long Short-Term Memory (LSTM) neural network for Human Activity Recognition (HAR) using the Human Activity Recognition Trondheim (HARTH) dataset.

## About the HARTH Dataset

The HARTH dataset is a professionally-annotated dataset containing recordings of 22 subjects wearing two 3-axial accelerometers (attached to the right thigh and lower back) for around 2 hours in a free-living setting. The dataset was created by NTNU Helse to train machine learning classifiers for human activity recognition based on professional annotations of activities in a free-living setting.

Each subject's recordings are provided in a separate CSV file, containing the following columns:

- `timestamp`: date and time of recorded sample
- `back_x`, `back_y`, `back_z`: acceleration of back sensor in x, y, and z directions (in units of g)
- `thigh_x`, `thigh_y`, `thigh_z`: acceleration of thigh sensor in x, y, and z directions (in units of g)
- `label`: annotated activity code

The dataset includes the following annotated activities and their corresponding codes:

- 1: walking
- 2: running
- 3: shuffling
- 4: stairs (ascending)
- 5: stairs (descending)
- 6: standing
- 7: sitting
- 8: lying
- 13: cycling (sit)
- 14: cycling (stand)
- 130: cycling (sit, inactive)
- 140: cycling (stand, inactive)

## Repository Contents

- `Data/`: Directory containing the HARTH dataset files.
- `HARTH70/`: Directory containing a subset of the HARTH dataset (70% of the original data).
- `harth.ipynb`: Jupyter Notebook containing the code for data preprocessing, LSTM model training, and evaluation.
- `requirements.txt`: File containing the list of required Python packages.

## Getting Started

1. Clone the repository: `git clone https://github.com/1666sApple/Human-Activity-Recognition-LSTM.git`
2. Install the required Python packages: `pip install -r requirements.txt`
3. Open the `harth.ipynb` Jupyter Notebook and follow the instructions to preprocess the data, train the LSTM model, and evaluate its performance.

Note: The dataset files are not included in this repository due to their large size. You will need to obtain the HARTH dataset separately and place the CSV files in the `Data/` directory.

## Contributing

Contributions to this repository are welcome. If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Acknowledgments

I would like to thank NTNU Helse for creating and providing the HARTH dataset, which made this research possible.
