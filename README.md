
# Climate AI Forest Monitoring

This project uses machine learning and deep learning to analyze, predict, and monitor climate and forest health in India, leveraging satellite and government datasets. It includes two main notebooks:

## Notebooks

### 1. ClimateChange Model.ipynb
- **Purpose:** Assesses climate and forest health using tree cover loss and carbon emissions data.
- **Data:** Processes multiple Excel/CSV files (tree cover loss, carbon data, combined health).
- **Methods:**
  - Random Forest models (and XGBoost imports)
  - Predicts tree loss, climate health, carbon health, and overall forest health
  - Classification reports and model evaluation
- **Outputs:**
  - Saves predictions and trained models
  - CSV files with health status per region
  - Visualizations of results

### 2. ClimateMitigation ML Model.ipynb
- **Purpose:** Advanced ML for forest health and carbon emission prediction, with feature engineering and time-series modeling.
- **Data:** Uses `IND.xlsx` (subnational tree cover loss, country carbon data).
- **Methods:**
  - Feature engineering and statewise aggregation
  - Forest health categorization
  - Random Forest with hyperparameter tuning
  - LSTM neural networks for time-series prediction and forecasting
- **Outputs:**
  - Forest health category predictions
  - Model evaluation metrics
  - Feature importance analysis
  - Visualizations of trends and metrics

## Data Sources
- Tree cover loss and carbon emission data (Excel/CSV)
- Subnational and country-level datasets

## Requirements
- Python 3.8+
- Jupyter Notebook
- pandas, numpy, scikit-learn, matplotlib, seaborn, xgboost, tensorflow

## How to Run
1. Clone the repository and open in VS Code or Jupyter.
2. Place the required datasets in the `Dataset/` folder.
3. Open either notebook and run cells sequentially.
4. Review outputs, saved models, and generated CSVs for results.

## Project Structure
- `ClimateChange Model.ipynb`: Climate and forest health analysis
- `ClimateMitigation ML Model.ipynb`: Mitigation modeling and forecasting
- `Dataset/`: Contains all required data files

## License
MIT
