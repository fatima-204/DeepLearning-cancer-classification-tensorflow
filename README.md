# Cancer Classification using TensorFlow

This repository contains a deep learning project for cancer classification using TensorFlow. The model is trained on medical data to classify cancer types, incorporating techniques like **early stopping** and **dropout** to prevent overfitting and improve generalization.

## Features

- **Deep Learning Model**: Built using TensorFlow/Keras.
- **Early Stopping**: Prevents overfitting by stopping training when validation performance plateaus.
- **Dropout**: Regularization technique to improve model generalization.
- **Easy to Use**: Includes scripts for training, evaluation, and prediction.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/cancer-classification-tensorflow.git
   cd cancer-classification-tensorflow
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Train the model:
   ```bash
   python train.py
   ```

4. Evaluate the model:
   ```bash
   python evaluate.py
   ```

5. Make predictions:
   ```bash
   python predict.py --input path/to/data.csv
   ```

## Requirements

- Python 3.x
- TensorFlow 2.x
- NumPy
- Pandas
- Scikit-learn

Example `requirements.txt`:
```plaintext
tensorflow>=2.0.0
numpy>=1.19.0
pandas>=1.2.0
scikit-learn>=0.24.0
```

## Model Details

- **Early Stopping**: Monitors validation loss and stops training if no improvement is observed for a specified number of epochs.
- **Dropout**: Randomly drops units during training to prevent overfitting.

## Example

Input:
```bash
python predict.py --input data/test_sample.csv
```

Output:
```
Predicted Class: Malignant
```

