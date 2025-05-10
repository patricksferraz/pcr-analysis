# PCR Analysis - Machine Learning for PCR Data Analysis

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.2.0-orange)](https://www.tensorflow.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/)

A comprehensive machine learning project for PCR (Polymerase Chain Reaction) data analysis, featuring transfer learning, time series forecasting, and advanced data processing capabilities.

## 🚀 Features

- **Transfer Learning Implementation**: Leverages pre-trained models for improved PCR data analysis
- **Time Series Forecasting**: Advanced prediction models for PCR data trends
- **Data Processing Pipeline**: Comprehensive data preprocessing and feature engineering
- **Interactive Visualization**: Rich data visualization using Plotly and Seaborn
- **Model Evaluation**: Comprehensive metrics and performance analysis
- **SHAP Analysis**: Explainable AI for model interpretability

## 📋 Prerequisites

- Python 3.8 or higher
- Node.js 10 or higher (for JupyterLab extensions)
- pip (Python package manager)

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/patricksferraz/pcr-analysis.git
cd pcr-analysis
```

2. Create and activate a virtual environment:
```bash
python3 -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Install JupyterLab extensions (for enhanced visualization):
```bash
# Basic JupyterLab renderer support
jupyter labextension install jupyterlab-plotly@4.12.0

# Jupyter widgets extension for FigureWidget support
jupyter labextension install @jupyter-widgets/jupyterlab-manager plotlywidget@4.12.0
```

## 🎮 Usage

1. Start JupyterLab:
```bash
jupyter-lab
```

2. Open the notebooks in the following order:
   - `processing-ods.ipynb`: Data preprocessing
   - `transfer-learning-isi.ipynb`: Transfer learning implementation
   - `predict-isi.ipynb`: Prediction models
   - `forecast.ipynb`: Time series forecasting

## 📊 Project Structure

```
pcr-analysis/
├── models/           # Trained model files
├── scalers/          # Data scaling models
├── without_isi/      # Analysis without ISI
├── notebooks/        # Jupyter notebooks
│   ├── processing-ods.ipynb
│   ├── transfer-learning-isi.ipynb
│   ├── predict-isi.ipynb
│   └── forecast.ipynb
├── requirements.txt  # Project dependencies
└── README.md        # Project documentation
```

## 🛠️ Technologies

- **Machine Learning**: TensorFlow, scikit-learn
- **Data Processing**: Pandas, NumPy
- **Visualization**: Plotly, Seaborn, Matplotlib
- **Development**: JupyterLab, Python
- **Model Interpretation**: SHAP

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Author

- **Patrick Sferraz** - [GitHub Profile](https://github.com/patricksferraz)

## 🙏 Acknowledgments

- Thanks to all contributors and the open-source community
- Special thanks to the scientific community for their valuable research in PCR analysis
