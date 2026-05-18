# Agent Python Tools

- repo: facebookresearch/mlgym
- repo_uri: https://github.com/facebookresearch/mlgym

## File: facebookresearch_mlgym/data/imageClassificationFMnist/baseline.py

Prompts

```
['train a CNN model on the Fashion MNIST dataset using Hugging Face Transformers Trainer', 'evaluate a trained Fashion MNIST model and return predictions and label IDs', 'create a CSV submission file from model predictions with predicted labels', 'load the Fashion MNIST dataset and preprocess images into normalized PyTorch tensors', 'set a random seed for reproducibility across Python, NumPy, and PyTorch', 'run the evaluate script with a submission CSV file to calculate accuracy against Fashion MNIST test data', 'run the load_test_data function to load the Fashion MNIST test split from Hugging Face datasets', 'run the load_submission function to read a predictions CSV file into a pandas DataFrame', 'run the evaluate_submission function to compare predicted labels against true labels and return accuracy', 'review the main function that orchestrates loading test data, submission, and computing accuracy via argparse']
```

Usage

```
{'train_fashion_mnist_cnn': 'train a CNN model on the Fashion MNIST dataset using Hugging Face Transformers Trainer', 'evaluate_trained_model': 'evaluate a trained Fashion MNIST model and return predictions and label IDs', 'create_submission_csv': 'create a CSV submission file from model predictions with predicted labels', 'load_and_preprocess_fashion_mnist': 'load the Fashion MNIST dataset and preprocess images into normalized PyTorch tensors', 'set_reproducible_seed': 'set a random seed for reproducibility across Python, NumPy, and PyTorch'}
```

## File: facebookresearch_mlgym/data/imageClassificationFMnist/evaluate.py

Prompts

```
['train a CNN model on the Fashion MNIST dataset using Hugging Face Transformers Trainer', 'evaluate a trained Fashion MNIST model and return predictions and label IDs', 'create a CSV submission file from model predictions with predicted labels', 'load the Fashion MNIST dataset and preprocess images into normalized PyTorch tensors', 'set a random seed for reproducibility across Python, NumPy, and PyTorch', 'run the evaluate script with a submission CSV file to calculate accuracy against Fashion MNIST test data', 'run the load_test_data function to load the Fashion MNIST test split from Hugging Face datasets', 'run the load_submission function to read a predictions CSV file into a pandas DataFrame', 'run the evaluate_submission function to compare predicted labels against true labels and return accuracy', 'review the main function that orchestrates loading test data, submission, and computing accuracy via argparse']
```

Usage

```
{'run_evaluate_submission': 'run the evaluate script with a submission CSV file to calculate accuracy against Fashion MNIST test data', 'run_load_test_data': 'run the load_test_data function to load the Fashion MNIST test split from Hugging Face datasets', 'run_load_submission': 'run the load_submission function to read a predictions CSV file into a pandas DataFrame', 'run_evaluate_accuracy': 'run the evaluate_submission function to compare predicted labels against true labels and return accuracy', 'review_evaluate_main': 'review the main function that orchestrates loading test data, submission, and computing accuracy via argparse'}
```

