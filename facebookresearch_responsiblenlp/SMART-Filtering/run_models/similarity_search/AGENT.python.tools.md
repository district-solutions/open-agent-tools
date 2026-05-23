# Agent Python Tools

- repo: facebookresearch/responsiblenlp
- repo_uri: https://github.com/facebookresearch/responsiblenlp

## File: facebookresearch_responsiblenlp/SMART-Filtering/run_models/similarity_search/extract_embedding_bert.py

Prompts

```
['run the script to extract sentence embeddings for multiple choice questions using sentence-t5-xxl model', 'run the eval function to encode test questions into embeddings using a SentenceTransformer model', 'create a prompt string from training DataFrame rows for a given subject with k-shot examples', 'create a formatted multiple choice question string from a DataFrame row with optional answer', 'create a human-readable subject name by replacing underscores with spaces in the subject string', 'run the script to extract text embeddings from CSV test datasets using an LLM2Vec model', 'extract embeddings for all test subjects in a dataset directory and save as numpy arrays', 'format a DataFrame row into a multiple-choice prompt string with optional answer inclusion', 'encode a list of prompt strings into vector embeddings using the LLM2Vec encoder', 'load a pretrained LLM2Vec model with PEFT adapters and configure mean pooling for encoding', 'run the script to extract last-token embeddings from a causal LLM for all test subjects in a dataset', 'run format_example to format a DataFrame row as a multiple-choice prompt with optional answer', 'run main to load a causal LLM, iterate over test CSV subjects, extract embeddings, and save as numpy files', 'review the eval function that extracts last-token hidden state embeddings from a causal LLM for similarity search', 'compute pairwise cosine distances between two sets of feature vectors using sklearn', 'get the kth smallest value along a specified axis of a numpy array', 'compute distances to the k nearest neighbours for a set of input features', 'review the compute_pairwise_distance function to understand its cosine distance calculation logic', 'refactor the get_kth_value function to remove the pdb.set_trace debug call']
```

Usage

```
{'run_embedding_extraction': 'run the script to extract sentence embeddings for multiple choice questions using sentence-t5-xxl model', 'run_eval_embeddings': 'run the eval function to encode test questions into embeddings using a SentenceTransformer model', 'create_gen_prompt': 'create a prompt string from training DataFrame rows for a given subject with k-shot examples', 'create_format_example': 'create a formatted multiple choice question string from a DataFrame row with optional answer', 'create_format_subject': 'create a human-readable subject name by replacing underscores with spaces in the subject string'}
```

## File: facebookresearch_responsiblenlp/SMART-Filtering/run_models/similarity_search/extract_embedding_llm2vec.py

Prompts

```
['run the script to extract sentence embeddings for multiple choice questions using sentence-t5-xxl model', 'run the eval function to encode test questions into embeddings using a SentenceTransformer model', 'create a prompt string from training DataFrame rows for a given subject with k-shot examples', 'create a formatted multiple choice question string from a DataFrame row with optional answer', 'create a human-readable subject name by replacing underscores with spaces in the subject string', 'run the script to extract text embeddings from CSV test datasets using an LLM2Vec model', 'extract embeddings for all test subjects in a dataset directory and save as numpy arrays', 'format a DataFrame row into a multiple-choice prompt string with optional answer inclusion', 'encode a list of prompt strings into vector embeddings using the LLM2Vec encoder', 'load a pretrained LLM2Vec model with PEFT adapters and configure mean pooling for encoding', 'run the script to extract last-token embeddings from a causal LLM for all test subjects in a dataset', 'run format_example to format a DataFrame row as a multiple-choice prompt with optional answer', 'run main to load a causal LLM, iterate over test CSV subjects, extract embeddings, and save as numpy files', 'review the eval function that extracts last-token hidden state embeddings from a causal LLM for similarity search', 'compute pairwise cosine distances between two sets of feature vectors using sklearn', 'get the kth smallest value along a specified axis of a numpy array', 'compute distances to the k nearest neighbours for a set of input features', 'review the compute_pairwise_distance function to understand its cosine distance calculation logic', 'refactor the get_kth_value function to remove the pdb.set_trace debug call']
```

Usage

```
{'run_llm2vec_embedding_extraction': 'run the script to extract text embeddings from CSV test datasets using an LLM2Vec model', 'extract_embeddings_for_subjects': 'extract embeddings for all test subjects in a dataset directory and save as numpy arrays', 'format_example_for_prompting': 'format a DataFrame row into a multiple-choice prompt string with optional answer inclusion', 'encode_text_with_llm2vec': 'encode a list of prompt strings into vector embeddings using the LLM2Vec encoder', 'load_llm2vec_model': 'load a pretrained LLM2Vec model with PEFT adapters and configure mean pooling for encoding'}
```

## File: facebookresearch_responsiblenlp/SMART-Filtering/run_models/similarity_search/extract_embedding_llms.py

Prompts

```
['run the script to extract sentence embeddings for multiple choice questions using sentence-t5-xxl model', 'run the eval function to encode test questions into embeddings using a SentenceTransformer model', 'create a prompt string from training DataFrame rows for a given subject with k-shot examples', 'create a formatted multiple choice question string from a DataFrame row with optional answer', 'create a human-readable subject name by replacing underscores with spaces in the subject string', 'run the script to extract text embeddings from CSV test datasets using an LLM2Vec model', 'extract embeddings for all test subjects in a dataset directory and save as numpy arrays', 'format a DataFrame row into a multiple-choice prompt string with optional answer inclusion', 'encode a list of prompt strings into vector embeddings using the LLM2Vec encoder', 'load a pretrained LLM2Vec model with PEFT adapters and configure mean pooling for encoding', 'run the script to extract last-token embeddings from a causal LLM for all test subjects in a dataset', 'run format_example to format a DataFrame row as a multiple-choice prompt with optional answer', 'run main to load a causal LLM, iterate over test CSV subjects, extract embeddings, and save as numpy files', 'review the eval function that extracts last-token hidden state embeddings from a causal LLM for similarity search', 'compute pairwise cosine distances between two sets of feature vectors using sklearn', 'get the kth smallest value along a specified axis of a numpy array', 'compute distances to the k nearest neighbours for a set of input features', 'review the compute_pairwise_distance function to understand its cosine distance calculation logic', 'refactor the get_kth_value function to remove the pdb.set_trace debug call']
```

Usage

```
{'run_extract_embedding_llms': 'run the script to extract last-token embeddings from a causal LLM for all test subjects in a dataset', 'run_format_example': 'run format_example to format a DataFrame row as a multiple-choice prompt with optional answer', 'run_eval_embeddings': 'run eval to extract hidden state embeddings from a causal LLM for each row in a test DataFrame', 'run_main_pipeline': 'run main to load a causal LLM, iterate over test CSV subjects, extract embeddings, and save as numpy files', 'review_eval_function': 'review the eval function that extracts last-token hidden state embeddings from a causal LLM for similarity search'}
```

## File: facebookresearch_responsiblenlp/SMART-Filtering/run_models/similarity_search/manifold_metrics.py

Prompts

```
['run the script to extract sentence embeddings for multiple choice questions using sentence-t5-xxl model', 'run the eval function to encode test questions into embeddings using a SentenceTransformer model', 'create a prompt string from training DataFrame rows for a given subject with k-shot examples', 'create a formatted multiple choice question string from a DataFrame row with optional answer', 'create a human-readable subject name by replacing underscores with spaces in the subject string', 'run the script to extract text embeddings from CSV test datasets using an LLM2Vec model', 'extract embeddings for all test subjects in a dataset directory and save as numpy arrays', 'format a DataFrame row into a multiple-choice prompt string with optional answer inclusion', 'encode a list of prompt strings into vector embeddings using the LLM2Vec encoder', 'load a pretrained LLM2Vec model with PEFT adapters and configure mean pooling for encoding', 'run the script to extract last-token embeddings from a causal LLM for all test subjects in a dataset', 'run format_example to format a DataFrame row as a multiple-choice prompt with optional answer', 'run main to load a causal LLM, iterate over test CSV subjects, extract embeddings, and save as numpy files', 'review the eval function that extracts last-token hidden state embeddings from a causal LLM for similarity search', 'compute pairwise cosine distances between two sets of feature vectors using sklearn', 'get the kth smallest value along a specified axis of a numpy array', 'compute distances to the k nearest neighbours for a set of input features', 'review the compute_pairwise_distance function to understand its cosine distance calculation logic', 'refactor the get_kth_value function to remove the pdb.set_trace debug call']
```

Usage

```
{'compute_pairwise_cosine_distance': 'compute pairwise cosine distances between two sets of feature vectors using sklearn', 'get_kth_smallest_value': 'get the kth smallest value along a specified axis of a numpy array', 'compute_nearest_neighbour_distances': 'compute distances to the k nearest neighbours for a set of input features', 'review_compute_pairwise_distance': 'review the compute_pairwise_distance function to understand its cosine distance calculation logic', 'refactor_get_kth_value': 'refactor the get_kth_value function to remove the pdb.set_trace debug call'}
```

