# Amazon Product Review Sentiment Analysis

An end-to-end capstone project that analyzes customer sentiment expressed in Amazon product reviews in the e-commerce domain. The repository explores the dataset, handles class imbalance, trains sentiment models, and compares ensemble and deep-learning approaches.

## Project Overview

The goal of this project is to classify customer reviews and understand sentiment patterns across the dataset. The analysis includes:

- Exploratory data analysis (EDA)
- Sentiment and review-length visualization
- Data preprocessing and class imbalance analysis
- Traditional machine-learning experimentation
- XGBoost ensemble modeling
- LSTM-based sentiment modeling
- Model evaluation with confusion matrices and classification reports

## Repository Structure

| File | Description |
|---|---|
| `01_EDA_Imbalance.ipynb` | Main notebook for exploratory analysis and class imbalance handling |
| `E_Commerce.ipynb` | Initial e-commerce sentiment analysis notebook |
| `e_commerce_2.ipynb` | Follow-up e-commerce analysis notebook |
| `XGBoost_Ensemble_Notebook.ipynb` | XGBoost ensemble notebook |
| `LSTM_Notebook.ipynb` | LSTM deep-learning notebook |
| `train_data.csv` | Original training data |
| `test_data.csv` | Test data |
| `test_data_hidden.csv` | Additional hidden test dataset |
| `processed_train.csv` | Preprocessed training data |
| `sentiment_distribution.png` | Sentiment class distribution visualization |
| `review_length.png` | Review-length distribution visualization |
| `confusion_matrix.png` | Confusion matrix for model evaluation |
| `Final_Report.docx` | Final project report |
| `End to End Project[Digicrome].docx.pdf` | Project PDF report |

## Getting Started

### Prerequisites

- Python 3
- Jupyter Notebook or JupyterLab
- Common data science packages, such as:
  - pandas
  - NumPy
  - matplotlib
  - seaborn
  - scikit-learn
  - XGBoost
  - TensorFlow or Keras

### Installation

1. Clone the repository:

```bash
git clone https://github.com/prashantsingh08/capstone_project_6.git
cd capstone_project_6
```

2. Create and activate a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate
```

On Windows:

```bash
.venv\Scripts\activate
```

3. Install the required packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost tensorflow jupyter
```

4. Start Jupyter:

```bash
jupyter notebook
```

Open `01_EDA_Imbalance.ipynb` and run the cells in order.

## Suggested Workflow

1. Explore `train_data.csv` and `test_data.csv`.
2. Review the class distribution and review-length analysis.
3. Run `01_EDA_Imbalance.ipynb` for preprocessing and imbalance handling.
4. Experiment with the XGBoost notebook.
5. Train and evaluate the LSTM model.
6. Compare model performance using the confusion matrix and evaluation metrics.

## Data

The project uses Amazon product review data stored in CSV format. The repository includes original, processed, test, and hidden-test datasets. Review the preprocessing notebook before training models to understand the transformations applied.

## Outputs

The repository contains visualizations from the analysis:

- Sentiment distribution
- Review length
- Model confusion matrix

## Deliverables

A detailed written summary is available in:

- `Final_Report.docx`
- `End to End Project[Digicrome].docx.pdf`

## Author

[Prashant Singh](https://github.com/prashantsingh08)

## License

No license is currently specified for this repository. Please contact the repository owner before reuse or redistribution.
