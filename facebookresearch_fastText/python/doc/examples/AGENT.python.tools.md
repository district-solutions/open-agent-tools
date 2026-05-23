# Agent Python Tools

- repo: facebookresearch/fastText
- repo_uri: https://github.com/facebookresearch/fastText.git

## File: facebookresearch_fastText/python/doc/examples/FastTextEmbeddingBag.py

Prompts

```
['build a FastTextEmbeddingBag from a fastText model file to use as a PyTorch EmbeddingBag module', 'create a FastTextEmbeddingBag instance by passing a path to a trained fastText model binary file', 'run the forward method on a list of words to get their fastText embeddings as a PyTorch tensor', 'test the random_word function to generate random alphanumeric strings of a specified length', 'review the FastTextEmbeddingBag forward method to understand how subword indices are extracted and aggregated', 'run the fastText word analogy accuracy evaluation on a model with question file and threshold', 'run process_question to evaluate word analogy accuracy for a set of analogy questions against a fastText model', 'run print_compute_accuracy_score to display accuracy metrics for semantic and syntactic analogy categories', 'review the process_question function that computes word analogy accuracy using cosine similarity and nearest neighbor search', 'review the print_compute_accuracy_score function that formats and prints accuracy metrics for word analogy evaluation', 'train a fastText supervised text classification model with custom epochs, learning rate, and word n-grams', 'test the trained fastText model against validation data and print precision and recall metrics', 'save the trained fastText supervised model to disk in binary or quantized format', 'quantize the trained fastText model with norm quantization and retraining to reduce file size', 'print the number of examples, precision at 1, and recall at 1 from model test results', 'train an unsupervised fastText skipgram model from a text corpus and save it to disk', 'save a trained fastText model to a binary file for later use', 'get the word vector embedding for a given word from a trained fastText model', 'compute Spearman correlation between word pair cosine similarities and gold standard similarity scores', 'compute the cosine similarity between two word vectors using numpy dot product and norms']
```

Usage

```
{'build_fasttext_embedding_bag': 'build a FastTextEmbeddingBag from a fastText model file to use as a PyTorch EmbeddingBag module', 'create_fasttext_embedding_init': 'create a FastTextEmbeddingBag instance by passing a path to a trained fastText model binary file', 'run_forward_embeddings': 'run the forward method on a list of words to get their fastText embeddings as a PyTorch tensor', 'test_random_word_generation': 'test the random_word function to generate random alphanumeric strings of a specified length', 'review_fasttext_subword_extraction': 'review the FastTextEmbeddingBag forward method to understand how subword indices are extracted and aggregated'}
```

## File: facebookresearch_fastText/python/doc/examples/compute_accuracy.py

Prompts

```
['build a FastTextEmbeddingBag from a fastText model file to use as a PyTorch EmbeddingBag module', 'create a FastTextEmbeddingBag instance by passing a path to a trained fastText model binary file', 'run the forward method on a list of words to get their fastText embeddings as a PyTorch tensor', 'test the random_word function to generate random alphanumeric strings of a specified length', 'review the FastTextEmbeddingBag forward method to understand how subword indices are extracted and aggregated', 'run the fastText word analogy accuracy evaluation on a model with question file and threshold', 'run process_question to evaluate word analogy accuracy for a set of analogy questions against a fastText model', 'run print_compute_accuracy_score to display accuracy metrics for semantic and syntactic analogy categories', 'review the process_question function that computes word analogy accuracy using cosine similarity and nearest neighbor search', 'review the print_compute_accuracy_score function that formats and prints accuracy metrics for word analogy evaluation', 'train a fastText supervised text classification model with custom epochs, learning rate, and word n-grams', 'test the trained fastText model against validation data and print precision and recall metrics', 'save the trained fastText supervised model to disk in binary or quantized format', 'quantize the trained fastText model with norm quantization and retraining to reduce file size', 'print the number of examples, precision at 1, and recall at 1 from model test results', 'train an unsupervised fastText skipgram model from a text corpus and save it to disk', 'save a trained fastText model to a binary file for later use', 'get the word vector embedding for a given word from a trained fastText model', 'compute Spearman correlation between word pair cosine similarities and gold standard similarity scores', 'compute the cosine similarity between two word vectors using numpy dot product and norms']
```

Usage

```
{'run_compute_accuracy': 'run the fastText word analogy accuracy evaluation on a model with question file and threshold', 'run_process_question': 'run process_question to evaluate word analogy accuracy for a set of analogy questions against a fastText model', 'run_print_compute_accuracy_score': 'run print_compute_accuracy_score to display accuracy metrics for semantic and syntactic analogy categories', 'review_process_question': 'review the process_question function that computes word analogy accuracy using cosine similarity and nearest neighbor search', 'review_print_compute_accuracy_score': 'review the print_compute_accuracy_score function that formats and prints accuracy metrics for word analogy evaluation'}
```

## File: facebookresearch_fastText/python/doc/examples/train_supervised.py

Prompts

```
['build a FastTextEmbeddingBag from a fastText model file to use as a PyTorch EmbeddingBag module', 'create a FastTextEmbeddingBag instance by passing a path to a trained fastText model binary file', 'run the forward method on a list of words to get their fastText embeddings as a PyTorch tensor', 'test the random_word function to generate random alphanumeric strings of a specified length', 'review the FastTextEmbeddingBag forward method to understand how subword indices are extracted and aggregated', 'run the fastText word analogy accuracy evaluation on a model with question file and threshold', 'run process_question to evaluate word analogy accuracy for a set of analogy questions against a fastText model', 'run print_compute_accuracy_score to display accuracy metrics for semantic and syntactic analogy categories', 'review the process_question function that computes word analogy accuracy using cosine similarity and nearest neighbor search', 'review the print_compute_accuracy_score function that formats and prints accuracy metrics for word analogy evaluation', 'train a fastText supervised text classification model with custom epochs, learning rate, and word n-grams', 'test the trained fastText model against validation data and print precision and recall metrics', 'save the trained fastText supervised model to disk in binary or quantized format', 'quantize the trained fastText model with norm quantization and retraining to reduce file size', 'print the number of examples, precision at 1, and recall at 1 from model test results', 'train an unsupervised fastText skipgram model from a text corpus and save it to disk', 'save a trained fastText model to a binary file for later use', 'get the word vector embedding for a given word from a trained fastText model', 'compute Spearman correlation between word pair cosine similarities and gold standard similarity scores', 'compute the cosine similarity between two word vectors using numpy dot product and norms']
```

Usage

```
{'train_supervised_model': 'train a fastText supervised text classification model with custom epochs, learning rate, and word n-grams', 'test_model_with_validation_data': 'test the trained fastText model against validation data and print precision and recall metrics', 'save_trained_model': 'save the trained fastText supervised model to disk in binary or quantized format', 'quantize_model': 'quantize the trained fastText model with norm quantization and retraining to reduce file size', 'print_evaluation_results': 'print the number of examples, precision at 1, and recall at 1 from model test results'}
```

## File: facebookresearch_fastText/python/doc/examples/train_unsupervised.py

Prompts

```
['build a FastTextEmbeddingBag from a fastText model file to use as a PyTorch EmbeddingBag module', 'create a FastTextEmbeddingBag instance by passing a path to a trained fastText model binary file', 'run the forward method on a list of words to get their fastText embeddings as a PyTorch tensor', 'test the random_word function to generate random alphanumeric strings of a specified length', 'review the FastTextEmbeddingBag forward method to understand how subword indices are extracted and aggregated', 'run the fastText word analogy accuracy evaluation on a model with question file and threshold', 'run process_question to evaluate word analogy accuracy for a set of analogy questions against a fastText model', 'run print_compute_accuracy_score to display accuracy metrics for semantic and syntactic analogy categories', 'review the process_question function that computes word analogy accuracy using cosine similarity and nearest neighbor search', 'review the print_compute_accuracy_score function that formats and prints accuracy metrics for word analogy evaluation', 'train a fastText supervised text classification model with custom epochs, learning rate, and word n-grams', 'test the trained fastText model against validation data and print precision and recall metrics', 'save the trained fastText supervised model to disk in binary or quantized format', 'quantize the trained fastText model with norm quantization and retraining to reduce file size', 'print the number of examples, precision at 1, and recall at 1 from model test results', 'train an unsupervised fastText skipgram model from a text corpus and save it to disk', 'save a trained fastText model to a binary file for later use', 'get the word vector embedding for a given word from a trained fastText model', 'compute Spearman correlation between word pair cosine similarities and gold standard similarity scores', 'compute the cosine similarity between two word vectors using numpy dot product and norms']
```

Usage

```
{'train_unsupervised_model': 'train an unsupervised fastText skipgram model from a text corpus and save it to disk', 'save_model': 'save a trained fastText model to a binary file for later use', 'get_word_vector': 'get the word vector embedding for a given word from a trained fastText model', 'compute_similarity': 'compute Spearman correlation between word pair cosine similarities and gold standard similarity scores', 'cosine_similarity': 'compute the cosine similarity between two word vectors using numpy dot product and norms'}
```

