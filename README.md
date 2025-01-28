# House Prices Prediction

## Project Overview
This project aims to develop a predictive model for house prices using machine learning techniques. The dataset contains housing-related variables, and the goal is to build a reliable model that can accurately predict house prices based on these features. This project involves data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and interpretation.

## Key Features
- Data Cleaning: Handling missing values, outliers, and inconsistent data.
- Exploratory Data Analysis: Visualizing trends and relationships among features.
- Feature Engineering: Transforming raw data into meaningful features for modeling.
- Model Building: Training and evaluating multiple machine learning models.
- Model Tuning: Hyperparameter optimization using techniques like `RandomizedSearchCV`.
- Results Interpretation: Using visualizations and metrics to explain model performance.

## Dataset
The dataset used in this project includes variables such as:
- `Median House Value`: Median house value for households within a block (measured in US Dollars) (target variable)
- `Median Income`: Median income for households within a block of houses (measured in tens of thousands of US Dollars) [10k$]
- `Median Age`: Median age of a house within a block; a lower number is a newer building [years]
- `Total Rooms`: Total number of rooms within a block
- `Total Bedrooms`: Total number of bedrooms within a block
- `Population`: Total number of people residing within a block

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/RidhooCodes/House-Price-Prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd house-prices-prediction
   ```
3. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
4. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Prepare the data by placing the dataset in the `data` directory (if not already included).
2. Run the EDA notebook or script to explore the dataset:
   ```bash
   python src/eda.py
   ```
3. Train the predictive model:
   ```bash
   python src/train_model.py
   ```
4. Evaluate the model:
   ```bash
   python src/evaluate_model.py
   ```
5. View the results and visualizations in the `outputs` directory.

Detailed results and plots are available in the `outputs` folder.

## Technologies Used
- Python
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
- Jupyter Notebook for exploratory data analysis

## Project Structure
```
house-prices-prediction/
├── data/                   # Raw and processed data
├── notebooks/              # Jupyter notebooks for EDA and analysis
├── src/                    # Python scripts for processing and modeling
├── outputs/                # Results, metrics, and visualizations
├── requirements.txt        # List of required Python libraries
├── README.md               # Project documentation
```

## Contributions
Contributions are welcome! Feel free to open an issue or submit a pull request.

## Acknowledgments
- [Kaggle](https://www.kaggle.com/) for providing datasets.
- Open-source libraries and tools used in this project.

---
Feel free to reach out if you have questions or suggestions!
