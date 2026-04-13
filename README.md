# Gaming Addiction Neural Network Model 🧠🎮

This project houses an Artificial Neural Network (ANN) built to predict gaming addiction risk levels based on various behavioral and mental health metrics. It includes a complete machine learning pipeline from data preprocessing to model evaluation.

## Project Structure 📁
- **`ANN.ipynb`:** The core Jupyter Notebook containing the data analysis, data scaling, categorical encoding, model architecture definition, and training loops using Deep Learning.
- **`Gaming and Mental Health.csv`:** The dataset containing metrics such as primary game played, gaming patterns, and related mental health outcomes.

## Key Features & Techniques ⚙️
- **Data Preprocessing:** Utilizes `StandardScaler` for continuous features and One-Hot Encoding (`get_dummies`) alongside `LabelEncoder` for categorical alignment.
- **Neural Network Architecture:** Uses `MLPClassifier` with customized hyperparameters (e.g., hidden layers, sigmoid or ReLU activations) designed to classify varying risk levels.
- **Performance Evaluation:** Validates the model utilizing hold-out test sets to generate robust accuracy, precision, recall, F1 scores, and Confusion Matrices.
- **Hyperparameter Tuning:** Involves strategies like `GridSearchCV` to locate optimal node sizes and learning paths.

## Getting Started 🚀
1. Clone this repository:
   ```bash
   git clone https://github.com/BassemRamdan/ANN.git
   cd ANN
   ```
2. Boot up Jupyter:
   ```bash
   jupyter notebook
   ```
3. Open `ANN.ipynb` and run all cells to evaluate the predictions against the bundled dataset.

## Requirements 🛠️
Ensure the following packages are installed:
- `python` 3.x
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib` / `seaborn` (for visualization of the confusion metrics)
