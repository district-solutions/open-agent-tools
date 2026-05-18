# Agent Python Tools

- repo: facebookresearch/mlgym
- repo_uri: https://github.com/facebookresearch/mlgym

## File: facebookresearch_mlgym/data/bertMNLI/baseline.py

Prompts

```
['run the train_model function to train a BERT classifier on the MNLI dataset with mixed precision', 'create an MNLIDataset instance to load and tokenize MNLI premise-hypothesis pairs for a given split', 'review the MNLIDataset __getitem__ method that tokenizes text pairs and returns input IDs, attention masks, and labels', 'refactor the train_model function to adjust hyperparameters like learning rate, batch size, or number of epochs', 'summarize the MNLIDataset class that wraps the HuggingFace MNLI dataset with BERT tokenization', 'run the evaluate_model function to evaluate a BERT model on the MNLI validation_matched dataset', 'test the evaluate_model function to compute validation accuracy on the MNLI dataset', 'refactor the MNLIDataset class to support configurable dataset splits beyond train and validation_matched']
```

Usage

```
{'run_train_model': 'run the train_model function to train a BERT classifier on the MNLI dataset with mixed precision', 'create_MNLIDataset': 'create an MNLIDataset instance to load and tokenize MNLI premise-hypothesis pairs for a given split', 'review_MNLIDataset_getitem': 'review the MNLIDataset __getitem__ method that tokenizes text pairs and returns input IDs, attention masks, and labels', 'refactor_train_model': 'refactor the train_model function to adjust hyperparameters like learning rate, batch size, or number of epochs', 'summarize_MNLIDataset': 'summarize the MNLIDataset class that wraps the HuggingFace MNLI dataset with BERT tokenization'}
```

## File: facebookresearch_mlgym/data/bertMNLI/evaluate.py

Prompts

```
['run the train_model function to train a BERT classifier on the MNLI dataset with mixed precision', 'create an MNLIDataset instance to load and tokenize MNLI premise-hypothesis pairs for a given split', 'review the MNLIDataset __getitem__ method that tokenizes text pairs and returns input IDs, attention masks, and labels', 'refactor the train_model function to adjust hyperparameters like learning rate, batch size, or number of epochs', 'summarize the MNLIDataset class that wraps the HuggingFace MNLI dataset with BERT tokenization', 'run the evaluate_model function to evaluate a BERT model on the MNLI validation_matched dataset', 'test the evaluate_model function to compute validation accuracy on the MNLI dataset', 'refactor the MNLIDataset class to support configurable dataset splits beyond train and validation_matched']
```

Usage

```
{'run_evaluate_model': 'run the evaluate_model function to evaluate a BERT model on the MNLI validation_matched dataset', 'create_MNLIDataset': 'create an MNLIDataset instance to load and tokenize MNLI premise-hypothesis pairs with BERT tokenizer', 'review_MNLIDataset_getitem': 'review the MNLIDataset __getitem__ method that tokenizes premise and hypothesis with max length 128', 'test_evaluate_model_accuracy': 'test the evaluate_model function to compute validation accuracy on the MNLI dataset', 'refactor_MNLIDataset_split': 'refactor the MNLIDataset class to support configurable dataset splits beyond train and validation_matched'}
```

