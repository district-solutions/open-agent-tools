# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/agents/reranker/classifier_gpt2_reranker.py

Prompts

```
['review the ClassifierGpt2RerankerAgent class that extends AbstractGpt2RerankAgent for GPT-2-based re-ranking', 'review the ClassifierGpt2Reranker class that extends ClassifierReranker for classifier-based re-ranking', 'run the ClassifierGpt2RerankerAgent to re-rank candidate outputs using a GPT-2 model and classifier', 'test the ClassifierGpt2RerankerAgent get_reranker_class method to verify it returns ClassifierGpt2Reranker', 'summarize the ClassifierGpt2RerankerAgent class and its inheritance from AbstractGpt2RerankAgent and Gpt2Agent', 'create a ClassifierRerankerAgent that re-ranks candidate outputs using a classifier model file', 'use batch_classify to predict augmented context with response candidates through the predictor', 'configure the ClassifierReranker target label to maximize probability of a specific class', 'initialize a predictor agent from a model file with candidate scoring overrides', 'add command line arguments for include_label_cand_only and target_label to the parser', 'create a subclass of AbstractReranker to use a custom classifier model for reranking response candidates', 'rerank dialogue response candidates using a predictor model and a chosen reranking strategy', 'batch predict scores for multiple augmented dialogue contexts using the predictor model', 'build a generator rerank agent that combines beam search with a classifier reranker for dialogue responses', 'review the reranker strategies including sum_scores, hard_choice, reranker_score, and none for candidate reordering']
```

Usage

```
{'review_ClassifierGpt2RerankerAgent': 'review the ClassifierGpt2RerankerAgent class that extends AbstractGpt2RerankAgent for GPT-2-based re-ranking', 'review_ClassifierGpt2Reranker': 'review the ClassifierGpt2Reranker class that extends ClassifierReranker for classifier-based re-ranking', 'run_ClassifierGpt2RerankerAgent': 'run the ClassifierGpt2RerankerAgent to re-rank candidate outputs using a GPT-2 model and classifier', 'test_ClassifierGpt2RerankerAgent': 'test the ClassifierGpt2RerankerAgent get_reranker_class method to verify it returns ClassifierGpt2Reranker', 'summarize_ClassifierGpt2RerankerAgent': 'summarize the ClassifierGpt2RerankerAgent class and its inheritance from AbstractGpt2RerankAgent and Gpt2Agent'}
```

## File: facebookresearch_parlai/parlai/agents/reranker/classifier_reranker.py

Prompts

```
['review the ClassifierGpt2RerankerAgent class that extends AbstractGpt2RerankAgent for GPT-2-based re-ranking', 'review the ClassifierGpt2Reranker class that extends ClassifierReranker for classifier-based re-ranking', 'run the ClassifierGpt2RerankerAgent to re-rank candidate outputs using a GPT-2 model and classifier', 'test the ClassifierGpt2RerankerAgent get_reranker_class method to verify it returns ClassifierGpt2Reranker', 'summarize the ClassifierGpt2RerankerAgent class and its inheritance from AbstractGpt2RerankAgent and Gpt2Agent', 'create a ClassifierRerankerAgent that re-ranks candidate outputs using a classifier model file', 'use batch_classify to predict augmented context with response candidates through the predictor', 'configure the ClassifierReranker target label to maximize probability of a specific class', 'initialize a predictor agent from a model file with candidate scoring overrides', 'add command line arguments for include_label_cand_only and target_label to the parser', 'create a subclass of AbstractReranker to use a custom classifier model for reranking response candidates', 'rerank dialogue response candidates using a predictor model and a chosen reranking strategy', 'batch predict scores for multiple augmented dialogue contexts using the predictor model', 'build a generator rerank agent that combines beam search with a classifier reranker for dialogue responses', 'review the reranker strategies including sum_scores, hard_choice, reranker_score, and none for candidate reordering']
```

Usage

```
{'create_classifier_reranker_agent': 'create a ClassifierRerankerAgent that re-ranks candidate outputs using a classifier model file', 'batch_classify_candidates': 'use batch_classify to predict augmented context with response candidates through the predictor', 'configure_target_label': 'configure the ClassifierReranker target label to maximize probability of a specific class', 'init_predictor_from_model': 'initialize a predictor agent from a model file with candidate scoring overrides', 'add_classifier_reranker_args': 'add command line arguments for include_label_cand_only and target_label to the parser'}
```

## File: facebookresearch_parlai/parlai/agents/reranker/reranker.py

Prompts

```
['review the ClassifierGpt2RerankerAgent class that extends AbstractGpt2RerankAgent for GPT-2-based re-ranking', 'review the ClassifierGpt2Reranker class that extends ClassifierReranker for classifier-based re-ranking', 'run the ClassifierGpt2RerankerAgent to re-rank candidate outputs using a GPT-2 model and classifier', 'test the ClassifierGpt2RerankerAgent get_reranker_class method to verify it returns ClassifierGpt2Reranker', 'summarize the ClassifierGpt2RerankerAgent class and its inheritance from AbstractGpt2RerankAgent and Gpt2Agent', 'create a ClassifierRerankerAgent that re-ranks candidate outputs using a classifier model file', 'use batch_classify to predict augmented context with response candidates through the predictor', 'configure the ClassifierReranker target label to maximize probability of a specific class', 'initialize a predictor agent from a model file with candidate scoring overrides', 'add command line arguments for include_label_cand_only and target_label to the parser', 'create a subclass of AbstractReranker to use a custom classifier model for reranking response candidates', 'rerank dialogue response candidates using a predictor model and a chosen reranking strategy', 'batch predict scores for multiple augmented dialogue contexts using the predictor model', 'build a generator rerank agent that combines beam search with a classifier reranker for dialogue responses', 'review the reranker strategies including sum_scores, hard_choice, reranker_score, and none for candidate reordering']
```

Usage

```
{'create_reranker_subclass': 'create a subclass of AbstractReranker to use a custom classifier model for reranking response candidates', 'rerank_candidates': 'rerank dialogue response candidates using a predictor model and a chosen reranking strategy', 'batch_predict_contexts': 'batch predict scores for multiple augmented dialogue contexts using the predictor model', 'build_generator_rerank_agent': 'build a generator rerank agent that combines beam search with a classifier reranker for dialogue responses', 'review_reranker_strategies': 'review the reranker strategies including sum_scores, hard_choice, reranker_score, and none for candidate reordering'}
```

