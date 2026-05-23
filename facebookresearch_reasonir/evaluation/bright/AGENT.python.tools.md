# Agent Python Tools

- repo: facebookresearch/reasonir
- repo_uri: https://github.com/facebookresearch/reasonir

## File: facebookresearch_reasonir/evaluation/bright/reranker.py

Prompts

```
['run the reranker on the BRIGHT dataset for a specified task using Qwen2.5-32B-Instruct', 'rerank retrieved documents by scoring relevance with an LLM and returning top-k results', 'calculate retrieval metrics comparing reranker scores against ground truth relevance labels', 'interpolate reranker scores with retriever scores to break ties and recalculate metrics', 'combine reranker scores with BM25 scores to break ties and evaluate retrieval performance', 'run BM25 retrieval on queries against a document corpus using gensim LuceneBM25Model', 'run dense retrieval using BGE or SBERT sentence transformer models with cosine similarity', 'run retrieval using OpenAI text-embedding-3-large embeddings with automatic text truncation', 'run retrieval using Salesforce SFR, Qwen, or E5 Mistral 7B embedding models']
```

Usage

```
{'run_reranker_evaluation': 'run the reranker on the BRIGHT dataset for a specified task using Qwen2.5-32B-Instruct', 'rerank_documents_with_llm': 'rerank retrieved documents by scoring relevance with an LLM and returning top-k results', 'calculate_retrieval_metrics': 'calculate retrieval metrics comparing reranker scores against ground truth relevance labels', 'interpolate_reranker_retriever_scores': 'interpolate reranker scores with retriever scores to break ties and recalculate metrics', 'combine_reranker_bm25_scores': 'combine reranker scores with BM25 scores to break ties and evaluate retrieval performance'}
```

## File: facebookresearch_reasonir/evaluation/bright/retrievers.py

Prompts

```
['run the reranker on the BRIGHT dataset for a specified task using Qwen2.5-32B-Instruct', 'rerank retrieved documents by scoring relevance with an LLM and returning top-k results', 'calculate retrieval metrics comparing reranker scores against ground truth relevance labels', 'interpolate reranker scores with retriever scores to break ties and recalculate metrics', 'combine reranker scores with BM25 scores to break ties and evaluate retrieval performance', 'run BM25 retrieval on queries against a document corpus using gensim LuceneBM25Model', 'run dense retrieval using BGE or SBERT sentence transformer models with cosine similarity', 'run retrieval using OpenAI text-embedding-3-large embeddings with automatic text truncation', 'run retrieval using Salesforce SFR, Qwen, or E5 Mistral 7B embedding models']
```

Usage

```
{'run_retrieval_bm25': 'run BM25 retrieval on queries against a document corpus using gensim LuceneBM25Model', 'run_retrieval_sbert_bge': 'run dense retrieval using BGE or SBERT sentence transformer models with cosine similarity', 'run_retrieval_openai': 'run retrieval using OpenAI text-embedding-3-large embeddings with automatic text truncation', 'run_retrieval_sf_qwen_e5': 'run retrieval using Salesforce SFR, Qwen, or E5 Mistral 7B embedding models', 'calculate_retrieval_metrics': 'calculate NDCG, MAP, Recall, Precision, and MRR metrics using pytrec_eval'}
```

