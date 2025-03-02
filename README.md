# Exoplanet Classification using Kepler Dataset

This repository contains machine learning algorithms for classifying exoplanets using data from the Kepler Space Telescope. The goal is to identify and categorize exoplanet candidates based on various observational parameters.

## Dataset

The dataset used in this project comes from NASA's Kepler mission, which aimed to discover Earth-sized exoplanets orbiting other stars. The dataset includes features such as:

- Transit Depth
- Orbital Period
- Stellar Flux
- Signal-to-Noise Ratio
- Other relevant astrophysical parameters

## Algorithms Implemented

The repository includes implementations of various ensemble classification algorithms, such as:

- Random Forest
- Adaboost
- Stacking
- Random Subspace Methods
- Extremely Randomized Trees (Extra Trees)

These algorithms were used in the article: ["Assessment of Ensemble-Based Machine Learning Algorithms for Exoplanet Identification"](https://www.mdpi.com/2079-9292/13/19/3950).

## Installation

To run the models locally, clone this repository and install the required dependencies:

```bash
 git clone https://github.com/your-username/your-repository.git
 cd your-repository
 pip install -r requirements.txt
```

## Usage

1. Load and preprocess the dataset.
2. Run each model script separately to train and evaluate.
3. Evaluate the classification performance using standard metrics such as accuracy, precision, recall, and F1-score.

To run a specific model script, use:

```bash
python script_name.py
```

## Results

The trained models are evaluated based on their ability to accurately classify exoplanets. The results are visualized through confusion matrices and classification reports.

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests to improve the repository.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

