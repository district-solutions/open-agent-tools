# Agent Python Tools

- repo: facebookresearch/text-adversarial-attack
- repo_uri: https://github.com/facebookresearch/text-adversarial-attack

## File: facebookresearch_text-adversarial-attack/evaluate_adv_samples.py

Prompts

```
['run the CLI to evaluate adversarial samples on a target model using gumbel softmax sampling', 'run the evaluate function to compute model accuracy on a test set with batching', 'run evaluate_adv_samples to assess adversarial robustness using gumbel samples and cosine similarity', 'create a TokenDataset PyTorch Dataset wrapper from tokenized encodings with label support', 'run the main function to load models, compute clean accuracy, and evaluate adversarial transferability', 'run adversarial text attacks on a dataset using BAE, BERT-Attack, or custom attack methods', 'run the BAE adversarial attack on a text classification dataset with a configurable cosine threshold', 'run the BERT-Attack adversarial attack on a text classification dataset using masked language model swaps', 'run the CLARE adversarial attack on a text classification dataset using embedding-based word swaps', 'run a custom adversarial attack with targeted or untargeted classification goal functions on text data', 'run text classification training on dbpedia14, ag_news, imdb, yelp, or mnli datasets using a pretrained transformer model', 'run full finetuning of a transformer model for text classification by passing the --finetune flag', 'run a linear probe by training only the classification head with the transformer frozen as default', 'run natural language inference training on the mnli dataset using premise and hypothesis text pairs', 'run training and save the model state dict to the result folder as a .pth file', 'run a white-box adversarial attack on a text classification model using gumbel-softmax optimization', 'run the adversarial attack using the Carlini-Wagner loss to fool a BERT classifier', 'run the white-box attack with a bertscore_idf constraint to preserve semantic similarity', 'run the adversarial attack on the MNLI dataset targeting either premise or hypothesis', 'run the adversarial attack on dbpedia14, ag_news, imdb, or yelp classification datasets']
```

Usage

```
{'run_evaluate_adv_samples_cli': 'run the CLI to evaluate adversarial samples on a target model using gumbel softmax sampling', 'run_evaluate_model_accuracy': 'run the evaluate function to compute model accuracy on a test set with batching', 'run_evaluate_adv_samples_function': 'run evaluate_adv_samples to assess adversarial robustness using gumbel samples and cosine similarity', 'create_TokenDataset': 'create a TokenDataset PyTorch Dataset wrapper from tokenized encodings with label support', 'run_main_evaluation_pipeline': 'run the main function to load models, compute clean accuracy, and evaluate adversarial transferability'}
```

## File: facebookresearch_text-adversarial-attack/run_textattack.py

Prompts

```
['run the CLI to evaluate adversarial samples on a target model using gumbel softmax sampling', 'run the evaluate function to compute model accuracy on a test set with batching', 'run evaluate_adv_samples to assess adversarial robustness using gumbel samples and cosine similarity', 'create a TokenDataset PyTorch Dataset wrapper from tokenized encodings with label support', 'run the main function to load models, compute clean accuracy, and evaluate adversarial transferability', 'run adversarial text attacks on a dataset using BAE, BERT-Attack, or custom attack methods', 'run the BAE adversarial attack on a text classification dataset with a configurable cosine threshold', 'run the BERT-Attack adversarial attack on a text classification dataset using masked language model swaps', 'run the CLARE adversarial attack on a text classification dataset using embedding-based word swaps', 'run a custom adversarial attack with targeted or untargeted classification goal functions on text data', 'run text classification training on dbpedia14, ag_news, imdb, yelp, or mnli datasets using a pretrained transformer model', 'run full finetuning of a transformer model for text classification by passing the --finetune flag', 'run a linear probe by training only the classification head with the transformer frozen as default', 'run natural language inference training on the mnli dataset using premise and hypothesis text pairs', 'run training and save the model state dict to the result folder as a .pth file', 'run a white-box adversarial attack on a text classification model using gumbel-softmax optimization', 'run the adversarial attack using the Carlini-Wagner loss to fool a BERT classifier', 'run the white-box attack with a bertscore_idf constraint to preserve semantic similarity', 'run the adversarial attack on the MNLI dataset targeting either premise or hypothesis', 'run the adversarial attack on dbpedia14, ag_news, imdb, or yelp classification datasets']
```

Usage

```
{'run_adversarial_attack': 'run adversarial text attacks on a dataset using BAE, BERT-Attack, or custom attack methods', 'run_bae_attack': 'run the BAE adversarial attack on a text classification dataset with a configurable cosine threshold', 'run_bert_attack': 'run the BERT-Attack adversarial attack on a text classification dataset using masked language model swaps', 'run_clare_attack': 'run the CLARE adversarial attack on a text classification dataset using embedding-based word swaps', 'run_custom_attack': 'run a custom adversarial attack with targeted or untargeted classification goal functions on text data'}
```

## File: facebookresearch_text-adversarial-attack/text_classification.py

Prompts

```
['run the CLI to evaluate adversarial samples on a target model using gumbel softmax sampling', 'run the evaluate function to compute model accuracy on a test set with batching', 'run evaluate_adv_samples to assess adversarial robustness using gumbel samples and cosine similarity', 'create a TokenDataset PyTorch Dataset wrapper from tokenized encodings with label support', 'run the main function to load models, compute clean accuracy, and evaluate adversarial transferability', 'run adversarial text attacks on a dataset using BAE, BERT-Attack, or custom attack methods', 'run the BAE adversarial attack on a text classification dataset with a configurable cosine threshold', 'run the BERT-Attack adversarial attack on a text classification dataset using masked language model swaps', 'run the CLARE adversarial attack on a text classification dataset using embedding-based word swaps', 'run a custom adversarial attack with targeted or untargeted classification goal functions on text data', 'run text classification training on dbpedia14, ag_news, imdb, yelp, or mnli datasets using a pretrained transformer model', 'run full finetuning of a transformer model for text classification by passing the --finetune flag', 'run a linear probe by training only the classification head with the transformer frozen as default', 'run natural language inference training on the mnli dataset using premise and hypothesis text pairs', 'run training and save the model state dict to the result folder as a .pth file', 'run a white-box adversarial attack on a text classification model using gumbel-softmax optimization', 'run the adversarial attack using the Carlini-Wagner loss to fool a BERT classifier', 'run the white-box attack with a bertscore_idf constraint to preserve semantic similarity', 'run the adversarial attack on the MNLI dataset targeting either premise or hypothesis', 'run the adversarial attack on dbpedia14, ag_news, imdb, or yelp classification datasets']
```

Usage

```
{'run_text_classification_training': 'run text classification training on dbpedia14, ag_news, imdb, yelp, or mnli datasets using a pretrained transformer model', 'run_finetune_transformer': 'run full finetuning of a transformer model for text classification by passing the --finetune flag', 'run_linear_probe': 'run a linear probe by training only the classification head with the transformer frozen as default', 'run_mnli_evaluation': 'run natural language inference training on the mnli dataset using premise and hypothesis text pairs', 'run_save_model': 'run training and save the model state dict to the result folder as a .pth file'}
```

## File: facebookresearch_text-adversarial-attack/whitebox_attack.py

Prompts

```
['run the CLI to evaluate adversarial samples on a target model using gumbel softmax sampling', 'run the evaluate function to compute model accuracy on a test set with batching', 'run evaluate_adv_samples to assess adversarial robustness using gumbel samples and cosine similarity', 'create a TokenDataset PyTorch Dataset wrapper from tokenized encodings with label support', 'run the main function to load models, compute clean accuracy, and evaluate adversarial transferability', 'run adversarial text attacks on a dataset using BAE, BERT-Attack, or custom attack methods', 'run the BAE adversarial attack on a text classification dataset with a configurable cosine threshold', 'run the BERT-Attack adversarial attack on a text classification dataset using masked language model swaps', 'run the CLARE adversarial attack on a text classification dataset using embedding-based word swaps', 'run a custom adversarial attack with targeted or untargeted classification goal functions on text data', 'run text classification training on dbpedia14, ag_news, imdb, yelp, or mnli datasets using a pretrained transformer model', 'run full finetuning of a transformer model for text classification by passing the --finetune flag', 'run a linear probe by training only the classification head with the transformer frozen as default', 'run natural language inference training on the mnli dataset using premise and hypothesis text pairs', 'run training and save the model state dict to the result folder as a .pth file', 'run a white-box adversarial attack on a text classification model using gumbel-softmax optimization', 'run the adversarial attack using the Carlini-Wagner loss to fool a BERT classifier', 'run the white-box attack with a bertscore_idf constraint to preserve semantic similarity', 'run the adversarial attack on the MNLI dataset targeting either premise or hypothesis', 'run the adversarial attack on dbpedia14, ag_news, imdb, or yelp classification datasets']
```

Usage

```
{'run_whitebox_attack': 'run a white-box adversarial attack on a text classification model using gumbel-softmax optimization', 'run_attack_with_cw_loss': 'run the adversarial attack using the Carlini-Wagner loss to fool a BERT classifier', 'run_attack_with_bertscore_constraint': 'run the white-box attack with a bertscore_idf constraint to preserve semantic similarity', 'run_attack_on_mnli': 'run the adversarial attack on the MNLI dataset targeting either premise or hypothesis', 'run_attack_on_classification_dataset': 'run the adversarial attack on dbpedia14, ag_news, imdb, or yelp classification datasets'}
```

