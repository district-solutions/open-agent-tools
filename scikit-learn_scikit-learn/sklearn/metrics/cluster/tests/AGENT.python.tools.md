# Agent Python Tools

- repo: scikit-learn/scikit-learn
- repo_uri: https://github.com/scikit-learn/scikit-learn

## File: scikit-learn_scikit-learn/sklearn/metrics/cluster/tests/test_bicluster.py

Prompts

```
['test the _jaccard function that computes Jaccard similarity between bicluster indicator arrays', 'test the consensus_score function that measures agreement between two biclustering results', 'test consensus_score with different numbers of biclusters in each result', 'refactor the consensus_score function to support custom similarity metrics', 'review the test_bicluster module for coverage of edge cases in bicluster agreement scoring', 'test supervised clustering metrics return the same score when y_true and y_pred are swapped', 'test homogeneity and completeness metrics return different scores when y_true and y_pred are swapped', 'test clustering metrics are invariant to label permutation for supervised and unsupervised metrics', 'test clustering metrics accept inputs as arrays lists strings negative or positive integers', 'test unsupervised metrics calinski_harabasz and davies_bouldin work with array API namespaces', 'test the adjusted_rand_score function to measure agreement between two clusterings adjusted for chance', 'test the adjusted_mutual_info_score function to compute mutual information between clusterings adjusted for chance', 'test the v_measure_score function to compute the harmonic mean of homogeneity and completeness', 'test the contingency_matrix function to build a contingency matrix from true and predicted cluster labels', 'test the fowlkes_mallows_score function to compute the geometric mean of precision and recall for pairs', 'test the silhouette_score function computes clustering quality with precomputed or euclidean metrics', 'test the silhouette_samples function returns per-sample silhouette scores for cluster evaluation', 'test the calinski_harabasz_score function computes the Calinski-Harabasz index for clustering validation', 'test the davies_bouldin_score function computes the Davies-Bouldin index for cluster separation assessment', 'test the _silhouette_reduce private method handles CSR sparse matrix input for silhouette computation']
```

Usage

```
{'test_jaccard': 'test the _jaccard function that computes Jaccard similarity between bicluster indicator arrays', 'test_consensus_score': 'test the consensus_score function that measures agreement between two biclustering results', 'test_consensus_score_issue2445': 'test consensus_score with different numbers of biclusters in each result', 'refactor_consensus_score': 'refactor the consensus_score function to support custom similarity metrics', 'review_test_bicluster': 'review the test_bicluster module for coverage of edge cases in bicluster agreement scoring'}
```

## File: scikit-learn_scikit-learn/sklearn/metrics/cluster/tests/test_common.py

Prompts

```
['test the _jaccard function that computes Jaccard similarity between bicluster indicator arrays', 'test the consensus_score function that measures agreement between two biclustering results', 'test consensus_score with different numbers of biclusters in each result', 'refactor the consensus_score function to support custom similarity metrics', 'review the test_bicluster module for coverage of edge cases in bicluster agreement scoring', 'test supervised clustering metrics return the same score when y_true and y_pred are swapped', 'test homogeneity and completeness metrics return different scores when y_true and y_pred are swapped', 'test clustering metrics are invariant to label permutation for supervised and unsupervised metrics', 'test clustering metrics accept inputs as arrays lists strings negative or positive integers', 'test unsupervised metrics calinski_harabasz and davies_bouldin work with array API namespaces', 'test the adjusted_rand_score function to measure agreement between two clusterings adjusted for chance', 'test the adjusted_mutual_info_score function to compute mutual information between clusterings adjusted for chance', 'test the v_measure_score function to compute the harmonic mean of homogeneity and completeness', 'test the contingency_matrix function to build a contingency matrix from true and predicted cluster labels', 'test the fowlkes_mallows_score function to compute the geometric mean of precision and recall for pairs', 'test the silhouette_score function computes clustering quality with precomputed or euclidean metrics', 'test the silhouette_samples function returns per-sample silhouette scores for cluster evaluation', 'test the calinski_harabasz_score function computes the Calinski-Harabasz index for clustering validation', 'test the davies_bouldin_score function computes the Davies-Bouldin index for cluster separation assessment', 'test the _silhouette_reduce private method handles CSR sparse matrix input for silhouette computation']
```

Usage

```
{'test_symmetry': 'test supervised clustering metrics return the same score when y_true and y_pred are swapped', 'test_non_symmetry': 'test homogeneity and completeness metrics return different scores when y_true and y_pred are swapped', 'test_permute_labels': 'test clustering metrics are invariant to label permutation for supervised and unsupervised metrics', 'test_format_invariance': 'test clustering metrics accept inputs as arrays lists strings negative or positive integers', 'test_array_api_compliance': 'test unsupervised metrics calinski_harabasz and davies_bouldin work with array API namespaces'}
```

## File: scikit-learn_scikit-learn/sklearn/metrics/cluster/tests/test_supervised.py

Prompts

```
['test the _jaccard function that computes Jaccard similarity between bicluster indicator arrays', 'test the consensus_score function that measures agreement between two biclustering results', 'test consensus_score with different numbers of biclusters in each result', 'refactor the consensus_score function to support custom similarity metrics', 'review the test_bicluster module for coverage of edge cases in bicluster agreement scoring', 'test supervised clustering metrics return the same score when y_true and y_pred are swapped', 'test homogeneity and completeness metrics return different scores when y_true and y_pred are swapped', 'test clustering metrics are invariant to label permutation for supervised and unsupervised metrics', 'test clustering metrics accept inputs as arrays lists strings negative or positive integers', 'test unsupervised metrics calinski_harabasz and davies_bouldin work with array API namespaces', 'test the adjusted_rand_score function to measure agreement between two clusterings adjusted for chance', 'test the adjusted_mutual_info_score function to compute mutual information between clusterings adjusted for chance', 'test the v_measure_score function to compute the harmonic mean of homogeneity and completeness', 'test the contingency_matrix function to build a contingency matrix from true and predicted cluster labels', 'test the fowlkes_mallows_score function to compute the geometric mean of precision and recall for pairs', 'test the silhouette_score function computes clustering quality with precomputed or euclidean metrics', 'test the silhouette_samples function returns per-sample silhouette scores for cluster evaluation', 'test the calinski_harabasz_score function computes the Calinski-Harabasz index for clustering validation', 'test the davies_bouldin_score function computes the Davies-Bouldin index for cluster separation assessment', 'test the _silhouette_reduce private method handles CSR sparse matrix input for silhouette computation']
```

Usage

```
{'test_adjusted_rand_score': 'test the adjusted_rand_score function to measure agreement between two clusterings adjusted for chance', 'test_adjusted_mutual_info_score': 'test the adjusted_mutual_info_score function to compute mutual information between clusterings adjusted for chance', 'test_v_measure_score': 'test the v_measure_score function to compute the harmonic mean of homogeneity and completeness', 'test_contingency_matrix': 'test the contingency_matrix function to build a contingency matrix from true and predicted cluster labels', 'test_fowlkes_mallows_score': 'test the fowlkes_mallows_score function to compute the geometric mean of precision and recall for pairs'}
```

## File: scikit-learn_scikit-learn/sklearn/metrics/cluster/tests/test_unsupervised.py

Prompts

```
['test the _jaccard function that computes Jaccard similarity between bicluster indicator arrays', 'test the consensus_score function that measures agreement between two biclustering results', 'test consensus_score with different numbers of biclusters in each result', 'refactor the consensus_score function to support custom similarity metrics', 'review the test_bicluster module for coverage of edge cases in bicluster agreement scoring', 'test supervised clustering metrics return the same score when y_true and y_pred are swapped', 'test homogeneity and completeness metrics return different scores when y_true and y_pred are swapped', 'test clustering metrics are invariant to label permutation for supervised and unsupervised metrics', 'test clustering metrics accept inputs as arrays lists strings negative or positive integers', 'test unsupervised metrics calinski_harabasz and davies_bouldin work with array API namespaces', 'test the adjusted_rand_score function to measure agreement between two clusterings adjusted for chance', 'test the adjusted_mutual_info_score function to compute mutual information between clusterings adjusted for chance', 'test the v_measure_score function to compute the harmonic mean of homogeneity and completeness', 'test the contingency_matrix function to build a contingency matrix from true and predicted cluster labels', 'test the fowlkes_mallows_score function to compute the geometric mean of precision and recall for pairs', 'test the silhouette_score function computes clustering quality with precomputed or euclidean metrics', 'test the silhouette_samples function returns per-sample silhouette scores for cluster evaluation', 'test the calinski_harabasz_score function computes the Calinski-Harabasz index for clustering validation', 'test the davies_bouldin_score function computes the Davies-Bouldin index for cluster separation assessment', 'test the _silhouette_reduce private method handles CSR sparse matrix input for silhouette computation']
```

Usage

```
{'test_silhouette_score': 'test the silhouette_score function computes clustering quality with precomputed or euclidean metrics', 'test_silhouette_samples': 'test the silhouette_samples function returns per-sample silhouette scores for cluster evaluation', 'test_calinski_harabasz_score': 'test the calinski_harabasz_score function computes the Calinski-Harabasz index for clustering validation', 'test_davies_bouldin_score': 'test the davies_bouldin_score function computes the Davies-Bouldin index for cluster separation assessment', 'test_silhouette_reduce': 'test the _silhouette_reduce private method handles CSR sparse matrix input for silhouette computation'}
```

