# Agent Python Tools

- repo: facebookresearch/multihopdenseretrieval
- repo_uri: https://github.com/facebookresearch/multihop_dense_retrieval

## File: facebookresearch_multihopdenseretrieval/scripts/eval/eval_mhop_retrieval.py

Prompts

```
['run the multi-hop dense retrieval evaluation script with eval data, corpus vectors, and model checkpoint', 'run retrieval evaluation using HNSW index for approximate nearest neighbor search on corpus vectors', 'run answer recall evaluation by checking if retrieved passages contain the gold answers', 'run the retrieval evaluation with GPU acceleration for faster FAISS index search', 'run two-hop retrieval search encoding question-document pairs and aggregating path scores', 'run single-hop retrieval evaluation on a QA dataset using a trained BERT retriever model and FAISS index', 'run retrieval evaluation with GPU acceleration by passing the --gpu flag to use FAISS GPU resources', 'run evaluation with a unified retriever model trained on both HotpotQA and Natural Questions datasets', 'save top-K retrieved document predictions and coverage metrics to a JSON lines file for later analysis', 'evaluate top-K recall metrics across multiple K values (5, 10, 20, 50, 100) for a set of QA pairs']
```

Usage

```
{'run_multi_hop_retrieval_eval': 'run the multi-hop dense retrieval evaluation script with eval data, corpus vectors, and model checkpoint', 'run_hnsw_index_retrieval': 'run retrieval evaluation using HNSW index for approximate nearest neighbor search on corpus vectors', 'run_answer_recall_eval': 'run answer recall evaluation by checking if retrieved passages contain the gold answers', 'run_gpu_accelerated_retrieval': 'run the retrieval evaluation with GPU acceleration for faster FAISS index search', 'run_two_hop_path_search': 'run two-hop retrieval search encoding question-document pairs and aggregating path scores'}
```

## File: facebookresearch_multihopdenseretrieval/scripts/eval/eval_retrieval.py

Prompts

```
['run the multi-hop dense retrieval evaluation script with eval data, corpus vectors, and model checkpoint', 'run retrieval evaluation using HNSW index for approximate nearest neighbor search on corpus vectors', 'run answer recall evaluation by checking if retrieved passages contain the gold answers', 'run the retrieval evaluation with GPU acceleration for faster FAISS index search', 'run two-hop retrieval search encoding question-document pairs and aggregating path scores', 'run single-hop retrieval evaluation on a QA dataset using a trained BERT retriever model and FAISS index', 'run retrieval evaluation with GPU acceleration by passing the --gpu flag to use FAISS GPU resources', 'run evaluation with a unified retriever model trained on both HotpotQA and Natural Questions datasets', 'save top-K retrieved document predictions and coverage metrics to a JSON lines file for later analysis', 'evaluate top-K recall metrics across multiple K values (5, 10, 20, 50, 100) for a set of QA pairs']
```

Usage

```
{'run_retrieval_evaluation': 'run single-hop retrieval evaluation on a QA dataset using a trained BERT retriever model and FAISS index', 'run_gpu_retrieval': 'run retrieval evaluation with GPU acceleration by passing the --gpu flag to use FAISS GPU resources', 'run_unified_model_eval': 'run evaluation with a unified retriever model trained on both HotpotQA and Natural Questions datasets', 'save_retrieval_predictions': 'save top-K retrieved document predictions and coverage metrics to a JSON lines file for later analysis', 'evaluate_recall_at_k': 'evaluate top-K recall metrics across multiple K values (5, 10, 20, 50, 100) for a set of QA pairs'}
```

