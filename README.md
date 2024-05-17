### Overview

This project focuses on the analysis of air quality data obtained from Data.gov. The dataset includes various air quality indicators, and the goal is to predict the risk level based on different features.

### Dataset

- **Source**: [Air Quality Dataset](https://www.data.gov/)

### Project Structure

#### Notebooks

1. **Data_Preprocessing.ipynb**:
   - Covers data cleaning, normalization, and encoding.
   - Converts date strings to numeric format.
   - Encodes categorical variables.

2. **Exploratory_Data_Analysis.ipynb**:
   - Explores data distribution.
   - Visualizes key insights such as feature distributions and correlations.

3. **Model_Training_and_Evaluation.ipynb**:
   - Implements and evaluates classification models including K-Nearest Neighbors, Decision Tree, and Random Forest.
   - Includes cross-validation and hyperparameter tuning.
   - Visualizes confusion matrices and feature importance.

### Setup

Clone the repository:

```sh
git clone https://github.com/your-username/air-quality-analysis.git
```

### How to Run

1. Navigate to the cloned repository:

    ```sh
    cd air-quality-analysis
    ```

2. Open the notebooks in Jupyter:

    ```sh
    jupyter notebook
    ```

3. Execute the notebooks in the following order:
    - Data_Preprocessing.ipynb
    - Exploratory_Data_Analysis.ipynb
    - Model_Training_and_Evaluation.ipynb

### Requirements

Install the necessary Python packages:

```sh
pip install -r requirements.txt
```

Ensure the `requirements.txt` file includes the necessary dependencies:

```
pandas
numpy
matplotlib
seaborn
scikit-learn
```

### License

This project is licensed under the MIT License.
