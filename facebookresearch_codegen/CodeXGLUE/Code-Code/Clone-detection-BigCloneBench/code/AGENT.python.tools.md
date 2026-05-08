# Agent Python Tools

- repo: facebookresearch/codegen
- repo_uri: https://github.com/facebookresearch/codegen

## File: facebookresearch_codegen/CodeXGLUE/Code-Code/Clone-detection-BigCloneBench/code/model.py

Prompts

```
['build a PyTorch model using RoBERTa encoder and RobertaClassificationHead for code clone detection', 'create a RobertaClassificationHead module for binary sentence-level classification with dense and dropout layers', 'run the Model forward pass with input_ids and optional labels to get probabilities or loss', 'test the RobertaClassificationHead forward method by passing feature tensors and checking output logits', 'review the Model class that wraps a RoBERTa encoder with a classification head for clone detection', 'run code clone detection training on BigCloneBench data using a pretrained transformer model', 'evaluate a trained code clone detection model on the evaluation dataset and report f1 score', 'test a trained code clone detection model on the test dataset and write predictions to file', 'convert pairs of Java code snippets into tokenized input features with cls and sep tokens for model input', 'create a PyTorch dataset from an index file and data.jsonl for code clone detection training']
```

Usage

```
{'build_clone_detection_model': 'build a PyTorch model using RoBERTa encoder and RobertaClassificationHead for code clone detection', 'create_classification_head': 'create a RobertaClassificationHead module for binary sentence-level classification with dense and dropout layers', 'run_model_forward_pass': 'run the Model forward pass with input_ids and optional labels to get probabilities or loss', 'test_roberta_classification_head': 'test the RobertaClassificationHead forward method by passing feature tensors and checking output logits', 'review_model_architecture': 'review the Model class that wraps a RoBERTa encoder with a classification head for clone detection'}
```

## File: facebookresearch_codegen/CodeXGLUE/Code-Code/Clone-detection-BigCloneBench/code/run.py

Prompts

```
['build a PyTorch model using RoBERTa encoder and RobertaClassificationHead for code clone detection', 'create a RobertaClassificationHead module for binary sentence-level classification with dense and dropout layers', 'run the Model forward pass with input_ids and optional labels to get probabilities or loss', 'test the RobertaClassificationHead forward method by passing feature tensors and checking output logits', 'review the Model class that wraps a RoBERTa encoder with a classification head for clone detection', 'run code clone detection training on BigCloneBench data using a pretrained transformer model', 'evaluate a trained code clone detection model on the evaluation dataset and report f1 score', 'test a trained code clone detection model on the test dataset and write predictions to file', 'convert pairs of Java code snippets into tokenized input features with cls and sep tokens for model input', 'create a PyTorch dataset from an index file and data.jsonl for code clone detection training']
```

Usage

```
{'run_clone_detection_training': 'run code clone detection training on BigCloneBench data using a pretrained transformer model', 'run_clone_detection_evaluation': 'evaluate a trained code clone detection model on the evaluation dataset and report f1 score', 'run_clone_detection_test': 'test a trained code clone detection model on the test dataset and write predictions to file', 'convert_code_pairs_to_features': 'convert pairs of Java code snippets into tokenized input features with cls and sep tokens for model input', 'create_clone_detection_dataset': 'create a PyTorch dataset from an index file and data.jsonl for code clone detection training'}
```

