# Agent Python Tools

- repo: facebookresearch/text-adversarial-attack
- repo_uri: https://github.com/facebookresearch/text-adversarial-attack

## File: facebookresearch_text-adversarial-attack/src/attacks.py

Prompts

```
['build a BAE adversarial attack using WordSwapMaskedLM with part-of-speech and USE constraints for untargeted classification', 'build a BERT-style adversarial attack with BAE transformation supporting both targeted and untargeted classification goals', 'compute the mean cosine similarity between clean and adversarial text embeddings using Universal Sentence Encoder', 'initialize a Universal Sentence Encoder model loaded from TensorFlow Hub for semantic similarity computation', 'review the build_attack function to understand how targeted vs untargeted classification attacks are configured', 'load the dbpedia14 dataset from CSV files with label, title, and sentence columns', 'load the ag_news dataset for news classification with 4 classes', 'load the imdb dataset for movie review sentiment analysis with 2 classes', 'load the yelp_polarity dataset for review sentiment classification with 2 classes', 'load the mnli dataset from GLUE for natural language inference with 3 classes', 'load a GPT-2 language model from a saved state dictionary file with configurable hidden states', 'parse a command line string argument into a boolean value accepting on off true false 0 1', 'offset all label values in an examples dictionary by subtracting one from each', 'generate a checkpoint output file path based on model dataset attack and hyperparameter arguments', 'load and aggregate adversarial attack checkpoint files from a folder returning logits texts and labels']
```

Usage

```
{'build_baegarg2019': 'build a BAE adversarial attack using WordSwapMaskedLM with part-of-speech and USE constraints for untargeted classification', 'build_attack': 'build a BERT-style adversarial attack with BAE transformation supporting both targeted and untargeted classification goals', 'USE_compute_sim': 'compute the mean cosine similarity between clean and adversarial text embeddings using Universal Sentence Encoder', 'USE_init': 'initialize a Universal Sentence Encoder model loaded from TensorFlow Hub for semantic similarity computation', 'review_build_attack': 'review the build_attack function to understand how targeted vs untargeted classification attacks are configured'}
```

## File: facebookresearch_text-adversarial-attack/src/dataset.py

Prompts

```
['build a BAE adversarial attack using WordSwapMaskedLM with part-of-speech and USE constraints for untargeted classification', 'build a BERT-style adversarial attack with BAE transformation supporting both targeted and untargeted classification goals', 'compute the mean cosine similarity between clean and adversarial text embeddings using Universal Sentence Encoder', 'initialize a Universal Sentence Encoder model loaded from TensorFlow Hub for semantic similarity computation', 'review the build_attack function to understand how targeted vs untargeted classification attacks are configured', 'load the dbpedia14 dataset from CSV files with label, title, and sentence columns', 'load the ag_news dataset for news classification with 4 classes', 'load the imdb dataset for movie review sentiment analysis with 2 classes', 'load the yelp_polarity dataset for review sentiment classification with 2 classes', 'load the mnli dataset from GLUE for natural language inference with 3 classes', 'load a GPT-2 language model from a saved state dictionary file with configurable hidden states', 'parse a command line string argument into a boolean value accepting on off true false 0 1', 'offset all label values in an examples dictionary by subtracting one from each', 'generate a checkpoint output file path based on model dataset attack and hyperparameter arguments', 'load and aggregate adversarial attack checkpoint files from a folder returning logits texts and labels']
```

Usage

```
{'load_data_dbpedia14': 'load the dbpedia14 dataset from CSV files with label, title, and sentence columns', 'load_data_ag_news': 'load the ag_news dataset for news classification with 4 classes', 'load_data_imdb': 'load the imdb dataset for movie review sentiment analysis with 2 classes', 'load_data_yelp': 'load the yelp_polarity dataset for review sentiment classification with 2 classes', 'load_data_mnli': 'load the mnli dataset from GLUE for natural language inference with 3 classes'}
```

## File: facebookresearch_text-adversarial-attack/src/utils.py

Prompts

```
['build a BAE adversarial attack using WordSwapMaskedLM with part-of-speech and USE constraints for untargeted classification', 'build a BERT-style adversarial attack with BAE transformation supporting both targeted and untargeted classification goals', 'compute the mean cosine similarity between clean and adversarial text embeddings using Universal Sentence Encoder', 'initialize a Universal Sentence Encoder model loaded from TensorFlow Hub for semantic similarity computation', 'review the build_attack function to understand how targeted vs untargeted classification attacks are configured', 'load the dbpedia14 dataset from CSV files with label, title, and sentence columns', 'load the ag_news dataset for news classification with 4 classes', 'load the imdb dataset for movie review sentiment analysis with 2 classes', 'load the yelp_polarity dataset for review sentiment classification with 2 classes', 'load the mnli dataset from GLUE for natural language inference with 3 classes', 'load a GPT-2 language model from a saved state dictionary file with configurable hidden states', 'parse a command line string argument into a boolean value accepting on off true false 0 1', 'offset all label values in an examples dictionary by subtracting one from each', 'generate a checkpoint output file path based on model dataset attack and hyperparameter arguments', 'load and aggregate adversarial attack checkpoint files from a folder returning logits texts and labels']
```

Usage

```
{'load_gpt2_from_dict': 'load a GPT-2 language model from a saved state dictionary file with configurable hidden states', 'bool_flag': 'parse a command line string argument into a boolean value accepting on off true false 0 1', 'target_offset': 'offset all label values in an examples dictionary by subtracting one from each', 'get_output_file': 'generate a checkpoint output file path based on model dataset attack and hyperparameter arguments', 'load_checkpoints': 'load and aggregate adversarial attack checkpoint files from a folder returning logits texts and labels'}
```

