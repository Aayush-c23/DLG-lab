# 7-Class Classification using Neural Network

## Aim

To implement a feed-forward neural network from scratch using NumPy for multiclass classification and evaluate its performance using accuracy, precision, recall, and F1-score.

## Dataset Used

The **UCI dataset (ID 31)** was used. The dataset contains **54 input features and 7 target classes**. The data was divided into training, validation, and test sets and standardized using `StandardScaler`.

## Results

The neural network was trained for up to **50 epochs** with early stopping and class-weighted loss to handle class imbalance. The final model was evaluated on the test set using accuracy, macro precision, macro recall, macro F1-score, and a confusion matrix. Per-class performance was also analyzed using precision, recall, and F1-score.
