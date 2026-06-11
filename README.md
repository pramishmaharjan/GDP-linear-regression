# French GDP Prediction with Linear Regression

A linear regression model trained on French GDP data (1960-2009) to predict GDP trends. Uses scikit-learn to model GDP as a function of year, achieving an R² of 0.92 on historical data.

## Results

| Metric | Value |
|--------|-------|
| Training R² | 0.92 |
| Coefficient | ~754 EUR/year |
| Test MAE | ~3,850 EUR |
| Improvement vs. naive baseline | ~84% |

## Usage

```bash
pip install -r requirements.txt
```

Then run the notebook.
