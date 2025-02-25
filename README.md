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

The repository includes implementations of various classification algorithms, such as:
- Logistic Regression
- Random Forest
- Support Vector Machines (SVM)
- Neural Networks

## Installation

To run the models locally, clone this repository and install the required dependencies:

```bash
 git clone https://github.com/your-username/your-repository.git
 cd your-repository
 pip install -r requirements.txt
```

## Usage

1. Load and preprocess the dataset.
2. Train the models using the provided scripts.
3. Evaluate the classification performance using standard metrics such as accuracy, precision, recall, and F1-score.

To run the main script:
```bash
python main.py
```

## Results

The trained models are evaluated based on their ability to accurately classify exoplanets. The results are visualized through confusion matrices and classification reports.

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests to improve the repository.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

