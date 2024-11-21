# TFM_Covid19

## Data Analysis Project

This is a data analysis project that uses Machine Learning techniques to predict outcomes based on a provided dataset. The main goal of this project is to create a predictive model using various algorithms and evaluate its performance.

## Technologies Used

- **Python**: The main language used for analysis and model development.
- **Pandas**: A library for data manipulation and analysis.
- **NumPy**: A library for numerical computations.
- **Scikit-Learn**: A library for implementing Machine Learning models.
- **Matplotlib** and **Seaborn**: Libraries for data visualization.

## Installation

Follow these steps to set up the project in your local environment:

1. Clone the repository:
    ```bash
    git clone https://github.com/username/project.git
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv env
    ```

3. Activate the virtual environment:
    - On **Windows**:
      ```bash
      .\env\Scripts\activate
      ```
    - On **macOS/Linux**:
      ```bash
      source env/bin/activate
      ```

4. Install the necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the analysis, execute the notebooks in the following order:

1. **TFM_Preprocessing.ipynb**: Preprocess the data.
2. **Modelos_TFM.ipynb**: Train the machine learning models.
3. **GRAFICOS.ipynb**: Generate the visualizations.

Simply open each notebook and run the cells in order to perform the analysis.

## Model Performance

Below is a summary of the performance of the best machine learning models for each category, including their training, validation, and test accuracies:

| Category               | Best ML Model | Training Accuracy  | Validation Accuracy | Test Accuracy  |
|------------------------|---------------|--------------------|---------------------|----------------|
| **Demographic characteristics** |               |                    |                     |                |
| Hostility              | DT            | 91.15% ± 2.50      | 85.16% ± 1.48       | 81.36%         |
| Somatization           | SVM           | 81.70% ± 5.86      | 76.36% ± 3.09       | 87.50%         |
| Depression             | SVM           | 85.09% ± 4.47      | 80.27% ± 2.85       | 87.50%         |
| Obsession-Compulsion   | RF            | 90.96% ± 2.40      | 82.40% ± 1.50       | 89.55%         |
| Anxiety                | SVM           | 81.89% ± 5.42      | 77.81% ± 3.47       | 89.71%         |
| Interpersonal Sensitivity | DT         | 89.60% ± 2.42      | 87.59% ± 1.01       | 85.29%         |
| Agoraphobia            | RF            | 92.76% ± 1.25      | 85.89% ± 0.53       | 90.00%         |
| Paranoid Ideation      | DT            | 92.23% ± 1.69      | 84.52% ± 1.1        | 92.31%         |
| Psychoticism           | MLP           | 86.83% ± 7.37      | 79.95% ± 3.07       | 87.50%         |
| **Living environment** |               |                    |                     |                |
| Hostility              | SVM           | 83.94% ± 10.16     | 76.75% ± 6.93       | 88.14%         |
| Somatization           | SVM           | 84.14% ± 9.7       | 76.85% ± 7.98       | 87.50%         |
| Depression             | MLP           | 73.34% ± 3.67      | 71.04% ± 3.46       | 84.38%         |
| Obsession-Compulsion   | RF            | 95.35% ± 2.12      | 88.36% ± 0.78       | 89.55%         |
| Anxiety                | SVM           | 82.20% ± 10.67     | 75.35% ± 7.49       | 94.12%         |
| Interpersonal Sensitivity | GB         | 94.44% ± 5.40      | 80.75% ± 1.74       | 83.82%         |
| Agoraphobia            | MLP           | 90.60% ± 7.83      | 81.22% ± 3.77       | 90.00%         |
| Paranoid Ideation      | RF            | 96.09% ± 1.98      | 85.63% ± 0.67       | 90.38%         |
| Psychoticism           | RF            | 96.50% ± 1.63      | 79.53% ± 1.35       | 92.86%         |
| **Economic status**     |               |                    |                     |                |
| Hostility              | SVM           | 89.22% ± 7.89      | 83.76% ± 5.56       | 91.52%         |
| Somatization           | RF            | 96.3% ± 1.3        | 87.86% ± 0.91       | 87.50%         |
| Depression             | DT            | 93.12% ± 2.29      | 78.73% ± 1.25       | 85.29%         |
| Obsession-Compulsion   | RF            | 97.64% ± 0.98      | 88.20% ± 0.71       | 88.06%         |
| Anxiety                | RF            | 97.17% ± 1.12      | 85.75% ± 0.51       | 85.29%         |
| Interpersonal Sensitivity | DT         | 91.98% ± 3.01      | 81.55% ± 1.48       | 91.18%         |
| Agoraphobia            | SVM           | 87.94% ± 9.88      | 80.12% ± 6.78       | 94.00%         |
| Paranoid Ideation      | RF            | 95.66% ± 1.56      | 85.40% ± 1.37       | 96.15%         |
| Psychoticism           | NB            | 83.92% ± 4.15      | 82.60% ± 3.74       | 87.50%         |
| **Health impacts**      |               |                    |                     |                |
| Hostility              | DT            | 95.74% ± 1.15      | 93.12% ± 0.35       | 96.61%         |
| Somatization           | RF            | 96.7% ± 0.15       | 96.15% ± 0.68       | 92.19%         |
| Depression             | GB            | 96.84% ± 0.79      | 95.37% ± 0.78       | 95.31%         |
| Obsession-Compulsion   | DT            | 94.01% ± 0.61      | 93.51% ± 0.7        | 98.51%         |
| Anxiety                | RF            | 95.4% ± 0.16       | 95.31% ± 0.41       | 92.65%         |
| Interpersonal Sensitivity | DT         | 95.68% ± 0.63      | 94.69% ± 0.7        | 92.65%         |
| Agoraphobia            | NB            | 92.79% ± 8.67      | 92.61% ± 8.91       | 98.00%         |
| Paranoid Ideation      | DT            | 92.3% ± 0.68       | 92.00% ± 1.13       | 100%           |
| Psychoticism           | SVM           | 87.33% ± 7.45      | 85.89% ± 7.39       | 91.07%         |
