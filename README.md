# Supply Chain Analysis Project

This project focuses on analyzing supply chain data to identify patterns, assess delivery risks, and visualize geographic performance. The analysis aims to provide insights that can help improve supply chain efficiency and reduce delays.

## Project Structure

```
supply-chain-analysis
├── src
│   ├── analysis
│   │   ├── exploratory_analysis.py
│   │   ├── geographic_analysis.py
│   │   └── delivery_risk_analysis.py
│   ├── data
│   │   ├── preprocessing.py
│   │   └── data_loader.py
│   ├── models
│   │   ├── logistic_regression.py
│   │   └── model_evaluation.py
│   ├── visualization
│   │   ├── frequency_plots.py
│   │   └── geographic_plots.py
│   └── utils
│       └── helpers.py
├── notebooks
│   ├── exploratory_analysis.ipynb
│   ├── geographic_analysis.ipynb
│   └── model_training.ipynb
├── data
│   ├── raw
│   └── processed
├── results
│   ├── figures
│   └── reports
├── requirements.txt
└── .gitignore
```

## Installation

To set up the project, clone the repository and install the required dependencies:

```bash
git clone <repository-url>
cd supply-chain-analysis
pip install -r requirements.txt
```

## Usage

1. **Data Loading**: Use the `data_loader.py` module to load raw data from the `data/raw` directory.
2. **Data Preprocessing**: Clean and preprocess the data using functions in `preprocessing.py`.
3. **Exploratory Analysis**: Perform exploratory data analysis using the Jupyter notebooks located in the `notebooks` directory.
4. **Geographic Analysis**: Analyze geographic performance using the `geographic_analysis.py` module.
5. **Delivery Risk Analysis**: Assess delivery risks with the `delivery_risk_analysis.py` module.
6. **Model Training**: Train models using the `logistic_regression.py` module and evaluate them with `model_evaluation.py`.
7. **Visualization**: Generate visualizations using the `visualization` module.

## Results

Generated figures and reports will be stored in the `results` directory. Check the `results/figures` and `results/reports` folders for outputs.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.