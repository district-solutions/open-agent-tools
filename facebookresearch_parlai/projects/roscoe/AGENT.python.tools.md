# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/projects/roscoe/roscoe.py

Prompts

```
['run the roscoe CLI to evaluate generated chains-of-reasoning across datasets like drop, esnli, cosmos, gsm8k, and semeval', 'run roscoe evaluation with a custom transformer model name and perplexity model for scoring', 'create a ReasoningSteps object to parse a reasoning chain into individual steps using sent_tokenize or GSM8K splitting', 'create a ReasoningEvaluator with a specified embedding model type, transformer model, and batch sizes for discourse and coherence', 'run update_evaluator on a ReasoningEvaluator to load JSONL hypothesis, context, and reference chains from a file', 'create an Evaluator to score reasoning chains against context and reference chains using embedding, NLI, perplexity, and grammar metrics', 'compute embedding-based scores like faithfulness, informativeness, and reasoning alignment between hypothesis and context chains', 'compute NLI-based discourse representation and coherence scores by measuring contradiction probability between chain steps', 'compute perplexity scores for each step and the whole chain using a GPT-2 language model with strided cross-entropy', 'compute grammatical correctness scores for each step in a reasoning chain using a pre-trained RoBERTa COLA classifier', 'create a function that saves a dictionary of scores to a formatted text file at a given path', 'compute the normalized cosine similarity between two numpy embedding vectors and return a scaled score', 'calculate embedding alignment scores between reference and hypothesis embeddings using cosine similarity', 'split a GSM8K reasoning string into individual steps using sentence tokenization and newline splitting', 'split a list of strings into two lists based on a boolean condition applied to each element']
```

Usage

```
{'run_roscoe_evaluation': 'run the roscoe CLI to evaluate generated chains-of-reasoning across datasets like drop, esnli, cosmos, gsm8k, and semeval', 'run_roscoe_with_custom_model': 'run roscoe evaluation with a custom transformer model name and perplexity model for scoring', 'create_ReasoningSteps': 'create a ReasoningSteps object to parse a reasoning chain into individual steps using sent_tokenize or GSM8K splitting', 'create_ReasoningEvaluator': 'create a ReasoningEvaluator with a specified embedding model type, transformer model, and batch sizes for discourse and coherence', 'run_ReasoningEvaluator_update_evaluator': 'run update_evaluator on a ReasoningEvaluator to load JSONL hypothesis, context, and reference chains from a file'}
```

## File: facebookresearch_parlai/projects/roscoe/score.py

Prompts

```
['run the roscoe CLI to evaluate generated chains-of-reasoning across datasets like drop, esnli, cosmos, gsm8k, and semeval', 'run roscoe evaluation with a custom transformer model name and perplexity model for scoring', 'create a ReasoningSteps object to parse a reasoning chain into individual steps using sent_tokenize or GSM8K splitting', 'create a ReasoningEvaluator with a specified embedding model type, transformer model, and batch sizes for discourse and coherence', 'run update_evaluator on a ReasoningEvaluator to load JSONL hypothesis, context, and reference chains from a file', 'create an Evaluator to score reasoning chains against context and reference chains using embedding, NLI, perplexity, and grammar metrics', 'compute embedding-based scores like faithfulness, informativeness, and reasoning alignment between hypothesis and context chains', 'compute NLI-based discourse representation and coherence scores by measuring contradiction probability between chain steps', 'compute perplexity scores for each step and the whole chain using a GPT-2 language model with strided cross-entropy', 'compute grammatical correctness scores for each step in a reasoning chain using a pre-trained RoBERTa COLA classifier', 'create a function that saves a dictionary of scores to a formatted text file at a given path', 'compute the normalized cosine similarity between two numpy embedding vectors and return a scaled score', 'calculate embedding alignment scores between reference and hypothesis embeddings using cosine similarity', 'split a GSM8K reasoning string into individual steps using sentence tokenization and newline splitting', 'split a list of strings into two lists based on a boolean condition applied to each element']
```

Usage

```
{'create_evaluator_for_reasoning_chains': 'create an Evaluator to score reasoning chains against context and reference chains using embedding, NLI, perplexity, and grammar metrics', 'compute_embedding_scores_faithfulness_alignment': 'compute embedding-based scores like faithfulness, informativeness, and reasoning alignment between hypothesis and context chains', 'compute_nli_scores_contradiction': 'compute NLI-based discourse representation and coherence scores by measuring contradiction probability between chain steps', 'compute_perplexity_scores': 'compute perplexity scores for each step and the whole chain using a GPT-2 language model with strided cross-entropy', 'compute_grammar_scores': 'compute grammatical correctness scores for each step in a reasoning chain using a pre-trained RoBERTa COLA classifier'}
```

## File: facebookresearch_parlai/projects/roscoe/utils.py

Prompts

```
['run the roscoe CLI to evaluate generated chains-of-reasoning across datasets like drop, esnli, cosmos, gsm8k, and semeval', 'run roscoe evaluation with a custom transformer model name and perplexity model for scoring', 'create a ReasoningSteps object to parse a reasoning chain into individual steps using sent_tokenize or GSM8K splitting', 'create a ReasoningEvaluator with a specified embedding model type, transformer model, and batch sizes for discourse and coherence', 'run update_evaluator on a ReasoningEvaluator to load JSONL hypothesis, context, and reference chains from a file', 'create an Evaluator to score reasoning chains against context and reference chains using embedding, NLI, perplexity, and grammar metrics', 'compute embedding-based scores like faithfulness, informativeness, and reasoning alignment between hypothesis and context chains', 'compute NLI-based discourse representation and coherence scores by measuring contradiction probability between chain steps', 'compute perplexity scores for each step and the whole chain using a GPT-2 language model with strided cross-entropy', 'compute grammatical correctness scores for each step in a reasoning chain using a pre-trained RoBERTa COLA classifier', 'create a function that saves a dictionary of scores to a formatted text file at a given path', 'compute the normalized cosine similarity between two numpy embedding vectors and return a scaled score', 'calculate embedding alignment scores between reference and hypothesis embeddings using cosine similarity', 'split a GSM8K reasoning string into individual steps using sentence tokenization and newline splitting', 'split a list of strings into two lists based on a boolean condition applied to each element']
```

Usage

```
{'save_scores_to_file': 'create a function that saves a dictionary of scores to a formatted text file at a given path', 'compute_cosine_similarity': 'compute the normalized cosine similarity between two numpy embedding vectors and return a scaled score', 'calculate_embedding_alignment': 'calculate embedding alignment scores between reference and hypothesis embeddings using cosine similarity', 'split_reasoning_to_steps': 'split a GSM8K reasoning string into individual steps using sentence tokenization and newline splitting', 'split_list_by_condition': 'split a list of strings into two lists based on a boolean condition applied to each element'}
```

