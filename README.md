# Housing Price Prediction using Yggdrasil Decision Forests

This project focuses on predicting housing prices using the Yggdrasil Decision Forests (YDF) framework. It demonstrates a well-structured data pipeline, from wrangling to training and evaluation using Gradient Boosted Trees.

## Project Structure

- `house-price-prediction.ipynb` – Main notebook containing data preparation, modeling, and evaluation.
- `models/house_price_model/` – Optional directory to save the trained model.

## Key Concepts

- Semantic-aware preprocessing that retains meaningful missing values.
- Feature engineering, such as calculating `YearsUntilRemodel`.
- Model training using Gradient Boosted Trees with the `better_defaultv1` template.
- Evaluation based on RMSE and R² metrics.

## Requirements

- Python 3.8 or above
- Pandas
- Yggdrasil Decision Forests (`pip install ydf`)
- Jupyter, Kaggle, or Google Colab

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/housing-price-prediction-ydf.git
   cd housing-price-prediction-ydf

2. **Run the notebook**

    Open the `house-price-prediction.ipynb` file in your preferred environment:

    - **Jupyter Notebook** (locally or via Anaconda)
    - **Kaggle Notebooks** (recommended for this project)
    - **Google Colab**

    Make sure the required libraries (`pandas`, `ydf`) are installed, and then run all cells sequentially to execute the full pipeline: from data wrangling to model evaluation and saving.


## Data Source

The dataset is from the Kaggle competition:  
**[House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)**

> **Note:** Data files are not included in this repository due to licensing restrictions.  
> Please download them directly from the Kaggle competition page.

---

## 🔧 Future Enhancements

- Add hyperparameter tuning for model optimization.
- Extend model selection with stacking and ensemble techniques.
- Improve data visualization and exploratory data analysis (EDA) coverage.

---

This notebook serves as a starting point for more advanced modeling efforts.