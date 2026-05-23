# Agent Python Tools

- repo: facebookresearch/faiss
- repo_uri: https://github.com/facebookresearch/faiss.git

## File: facebookresearch_faiss/contrib/torch/clustering.py

Prompts

```
['create a DatasetAssign wrapper for a PyTorch tensor to assign vectors to centroids using FAISS k-NN search', 'run assign_to on a DatasetAssign instance to get cluster assignments, distances, and centroid sums', 'create a DatasetAssignGPU wrapper that performs GPU-accelerated k-NN search for assigning vectors to centroids', 'run the kmeans function imported from faiss.contrib.clustering to compute centroids for a dataset', 'review the DatasetAssign perform_search method to understand how FAISS k-NN is used for nearest centroid lookup', 'create a ProductQuantizer instance with dimension d, M subvectors, and 8 nbits for vector quantization', 'train a ProductQuantizer on a PyTorch tensor to build the codebook using kmeans clustering per subvector', 'encode float vectors into compact uint8 codes using a trained ProductQuantizer codebook and faiss knn search', 'decode uint8 codes back into reconstructed float vectors using a ProductQuantizer codebook lookup', 'create a VectorQuantizer instance with dimension d and k centroids for vector quantization training']
```

Usage

```
{'create_DatasetAssign': 'create a DatasetAssign wrapper for a PyTorch tensor to assign vectors to centroids using FAISS k-NN search', 'run_DatasetAssign_assign_to': 'run assign_to on a DatasetAssign instance to get cluster assignments, distances, and centroid sums', 'create_DatasetAssignGPU': 'create a DatasetAssignGPU wrapper that performs GPU-accelerated k-NN search for assigning vectors to centroids', 'run_kmeans': 'run the kmeans function imported from faiss.contrib.clustering to compute centroids for a dataset', 'review_DatasetAssign_perform_search': 'review the DatasetAssign perform_search method to understand how FAISS k-NN is used for nearest centroid lookup'}
```

## File: facebookresearch_faiss/contrib/torch/quantization.py

Prompts

```
['create a DatasetAssign wrapper for a PyTorch tensor to assign vectors to centroids using FAISS k-NN search', 'run assign_to on a DatasetAssign instance to get cluster assignments, distances, and centroid sums', 'create a DatasetAssignGPU wrapper that performs GPU-accelerated k-NN search for assigning vectors to centroids', 'run the kmeans function imported from faiss.contrib.clustering to compute centroids for a dataset', 'review the DatasetAssign perform_search method to understand how FAISS k-NN is used for nearest centroid lookup', 'create a ProductQuantizer instance with dimension d, M subvectors, and 8 nbits for vector quantization', 'train a ProductQuantizer on a PyTorch tensor to build the codebook using kmeans clustering per subvector', 'encode float vectors into compact uint8 codes using a trained ProductQuantizer codebook and faiss knn search', 'decode uint8 codes back into reconstructed float vectors using a ProductQuantizer codebook lookup', 'create a VectorQuantizer instance with dimension d and k centroids for vector quantization training']
```

Usage

```
{'create_ProductQuantizer': 'create a ProductQuantizer instance with dimension d, M subvectors, and 8 nbits for vector quantization', 'train_ProductQuantizer': 'train a ProductQuantizer on a PyTorch tensor to build the codebook using kmeans clustering per subvector', 'encode_ProductQuantizer': 'encode float vectors into compact uint8 codes using a trained ProductQuantizer codebook and faiss knn search', 'decode_ProductQuantizer': 'decode uint8 codes back into reconstructed float vectors using a ProductQuantizer codebook lookup', 'create_VectorQuantizer': 'create a VectorQuantizer instance with dimension d and k centroids for vector quantization training'}
```

