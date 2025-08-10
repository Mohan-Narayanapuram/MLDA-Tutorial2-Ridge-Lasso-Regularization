# Tutorial 2: Ridge and Lasso Regularization

## Overview
In this tutorial, we apply Ridge and Lasso regression to the *Medical Insurance Charges* dataset to understand how regularization helps improve model generalization.

### Why Regularization?
Regularization helps prevent overfitting by penalizing large coefficients.
- Ridge Regression (L2 penalty): Shrinks all coefficients towards zero but does not eliminate features completely.
- Lasso Regression (L1 penalty): Can shrink some coefficients to exactly zero, effectively performing feature selection.

## Dataset
- **Name**: Medical Cost Personal Dataset
- **Source**: [GitHub – stedy/Machine-Learning-with-R-datasets](https://github.com/stedy/Machine-Learning-with-R-datasets/blob/master/insurance.csv)  
- **Description**: Same dataset as Tutorial 1. We reuse the preprocessed data from Tutorial 1.

## Steps Performed
1. Load preprocessed training/testing data from Tutorial 1
2. Fit Ridge Regression model and print coefficients
3. Fit Lasso Regression model and print coefficients
4. Compare and interpret results

## Results
- Ridge Coefficients: `[ 3603.27, 2051.94, 513.15, -10.64, 23514.63, -366.15, -643.01, -802.91 ]`
- Lasso Coefficients: `[ 3608.22, 2052.69, 511.52, -14.05, 23644.65, -354.19, -640.19, -793.01 ]`

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook Tutorial-2.ipynb
```

## Credits
Dataset sourced from: [GitHub – stedy/Machine-Learning-with-R-datasets](https://github.com/stedy/Machine-Learning-with-R-datasets)  
Original dataset creator: *Stedy* (Machine Learning with R book resources)
