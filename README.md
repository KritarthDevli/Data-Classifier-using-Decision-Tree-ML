# Fruit Classifier using Decision Tree

This project demonstrates a basic fruit classification model using a Decision Tree Classifier from `scikit-learn`. The model classifies fruits into two categories (Apple or Orange) based on their size and color shade.

## Dataset:
The dataset used for training consists of two features:
1. **Fruit size** (in centimeters)
2. **Color shade** (from 1 to 10, where 1 is light and 10 is dark)

The target variable `y` consists of:
- `0` for Apple
- `1` for Orange

The model is trained on a very small dataset for demonstration purposes.

## How It Works:
1. The user is prompted to input the size and color shade of a fruit.
2. Based on the input, the trained Decision Tree model predicts whether the fruit is likely to be an **Apple (0)** or an **Orange (1)**.
3. The prediction is printed as output.

## Requirements:
- Python 3.x
- scikit-learn library

To install the necessary dependencies, run:
```bash
pip install scikit-learn
