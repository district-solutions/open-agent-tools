# Agent Python Tools

- repo: huggingface/text-clustering
- repo_uri: https://github.com/huggingface/text-clustering

## File: huggingface_text-clustering/src/plot_utils.py

Prompts

```
['plot the distribution of educational scores from a HuggingFace dataset as a histogram', 'plot a bar chart showing the number of samples across categories in a dataset', "extract the category and educational score from a dataset example's summary field", 'get the total number of examples across all entries in a dataset', 'generate a CSV file with category names and their corresponding sample counts', 'create a ClusterClassifier with sentence transformer embeddings, UMAP projection, and DBSCAN clustering parameters', 'fit a ClusterClassifier on a list of texts to compute embeddings, clusters, and LLM summaries', 'infer cluster labels for new texts using a fitted ClusterClassifier and FAISS nearest neighbor search', 'save a fitted ClusterClassifier model including embeddings, projections, cluster labels, and summaries to a folder', 'load a previously saved ClusterClassifier model from a folder including embeddings, projections, and cluster labels']
```

Usage

```
{'plot_educational_score_distribution': 'plot the distribution of educational scores from a HuggingFace dataset as a histogram', 'plot_category_sample_distribution': 'plot a bar chart showing the number of samples across categories in a dataset', 'extract_category_and_score': "extract the category and educational score from a dataset example's summary field", 'get_dataset_size': 'get the total number of examples across all entries in a dataset', 'generate_category_count_csv': 'generate a CSV file with category names and their corresponding sample counts'}
```

## File: huggingface_text-clustering/src/text_clustering.py

Prompts

```
['plot the distribution of educational scores from a HuggingFace dataset as a histogram', 'plot a bar chart showing the number of samples across categories in a dataset', "extract the category and educational score from a dataset example's summary field", 'get the total number of examples across all entries in a dataset', 'generate a CSV file with category names and their corresponding sample counts', 'create a ClusterClassifier with sentence transformer embeddings, UMAP projection, and DBSCAN clustering parameters', 'fit a ClusterClassifier on a list of texts to compute embeddings, clusters, and LLM summaries', 'infer cluster labels for new texts using a fitted ClusterClassifier and FAISS nearest neighbor search', 'save a fitted ClusterClassifier model including embeddings, projections, cluster labels, and summaries to a folder', 'load a previously saved ClusterClassifier model from a folder including embeddings, projections, and cluster labels']
```

Usage

```
{'init_cluster_classifier': 'create a ClusterClassifier with sentence transformer embeddings, UMAP projection, and DBSCAN clustering parameters', 'fit_cluster_classifier': 'fit a ClusterClassifier on a list of texts to compute embeddings, clusters, and LLM summaries', 'infer_cluster_labels': 'infer cluster labels for new texts using a fitted ClusterClassifier and FAISS nearest neighbor search', 'save_cluster_classifier': 'save a fitted ClusterClassifier model including embeddings, projections, cluster labels, and summaries to a folder', 'load_cluster_classifier': 'load a previously saved ClusterClassifier model from a folder including embeddings, projections, and cluster labels'}
```

