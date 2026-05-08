# Agent Python Tools

- repo: facebookresearch/qinco
- repo_uri: https://github.com/facebookresearch/qinco

## File: facebookresearch_qinco/qinco/search/pairwise_decoder.py

Prompts

```
['build a PairwiseDecoderIVF instance from config and training codes to perform pairwise vector quantization decoding', 'run the forward pass on codes_MB with optional IVF codes to reconstruct quantized vectors', 'compute the mean squared error between a dataset and its quantized reconstruction using the decoder', 'train the PairwiseDecoderIVF by building IVF small codebooks and greedily selecting best pairwise codebook combinations', 'build a combined codebook from two codebook indices m1 and m2 and compute local reconstruction error', 'run the IVFTrainTask to train IVF centroids using faiss K-means on a training vector set', 'run the EncodeDBTask to encode a database of vectors using the QINCo model and save codes to npz', 'run the BuildIndexTask to build a faiss IVF+RQ index from encoded vectors and IVF centroids', 'run the SearchTask to perform approximate nearest neighbor search using an IVF index or full database', 'run the TrainPairwiseDecoderTask to train a PairwiseDecoderIVF reranker model on encoded training data', 'batch a numpy database array into fixed-size chunks yielding batch index and data', 'show current GPU memory usage in gigabytes using PyTorch CUDA memory info', 'iterate over partitioned encoded database NPZ files in configurable batch sizes', 'compute fixed additive quantization codebooks from training data and codes using least squares', 'reconstruct original vectors from quantization codes and fixed additive codebooks']
```

Usage

```
{'build_PairwiseDecoderIVF': 'build a PairwiseDecoderIVF instance from config and training codes to perform pairwise vector quantization decoding', 'run_forward_decoding': 'run the forward pass on codes_MB with optional IVF codes to reconstruct quantized vectors', 'compute_dataset_mse': 'compute the mean squared error between a dataset and its quantized reconstruction using the decoder', 'train_PairwiseDecoderIVF': 'train the PairwiseDecoderIVF by building IVF small codebooks and greedily selecting best pairwise codebook combinations', 'build_combined_codebook': 'build a combined codebook from two codebook indices m1 and m2 and compute local reconstruction error'}
```

## File: facebookresearch_qinco/qinco/search/search_tasks.py

Prompts

```
['build a PairwiseDecoderIVF instance from config and training codes to perform pairwise vector quantization decoding', 'run the forward pass on codes_MB with optional IVF codes to reconstruct quantized vectors', 'compute the mean squared error between a dataset and its quantized reconstruction using the decoder', 'train the PairwiseDecoderIVF by building IVF small codebooks and greedily selecting best pairwise codebook combinations', 'build a combined codebook from two codebook indices m1 and m2 and compute local reconstruction error', 'run the IVFTrainTask to train IVF centroids using faiss K-means on a training vector set', 'run the EncodeDBTask to encode a database of vectors using the QINCo model and save codes to npz', 'run the BuildIndexTask to build a faiss IVF+RQ index from encoded vectors and IVF centroids', 'run the SearchTask to perform approximate nearest neighbor search using an IVF index or full database', 'run the TrainPairwiseDecoderTask to train a PairwiseDecoderIVF reranker model on encoded training data', 'batch a numpy database array into fixed-size chunks yielding batch index and data', 'show current GPU memory usage in gigabytes using PyTorch CUDA memory info', 'iterate over partitioned encoded database NPZ files in configurable batch sizes', 'compute fixed additive quantization codebooks from training data and codes using least squares', 'reconstruct original vectors from quantization codes and fixed additive codebooks']
```

Usage

```
{'run_IVFTrainTask': 'run the IVFTrainTask to train IVF centroids using faiss K-means on a training vector set', 'run_EncodeDBTask': 'run the EncodeDBTask to encode a database of vectors using the QINCo model and save codes to npz', 'run_BuildIndexTask': 'run the BuildIndexTask to build a faiss IVF+RQ index from encoded vectors and IVF centroids', 'run_SearchTask': 'run the SearchTask to perform approximate nearest neighbor search using an IVF index or full database', 'run_TrainPairwiseDecoderTask': 'run the TrainPairwiseDecoderTask to train a PairwiseDecoderIVF reranker model on encoded training data'}
```

## File: facebookresearch_qinco/qinco/search/search_utils.py

Prompts

```
['build a PairwiseDecoderIVF instance from config and training codes to perform pairwise vector quantization decoding', 'run the forward pass on codes_MB with optional IVF codes to reconstruct quantized vectors', 'compute the mean squared error between a dataset and its quantized reconstruction using the decoder', 'train the PairwiseDecoderIVF by building IVF small codebooks and greedily selecting best pairwise codebook combinations', 'build a combined codebook from two codebook indices m1 and m2 and compute local reconstruction error', 'run the IVFTrainTask to train IVF centroids using faiss K-means on a training vector set', 'run the EncodeDBTask to encode a database of vectors using the QINCo model and save codes to npz', 'run the BuildIndexTask to build a faiss IVF+RQ index from encoded vectors and IVF centroids', 'run the SearchTask to perform approximate nearest neighbor search using an IVF index or full database', 'run the TrainPairwiseDecoderTask to train a PairwiseDecoderIVF reranker model on encoded training data', 'batch a numpy database array into fixed-size chunks yielding batch index and data', 'show current GPU memory usage in gigabytes using PyTorch CUDA memory info', 'iterate over partitioned encoded database NPZ files in configurable batch sizes', 'compute fixed additive quantization codebooks from training data and codes using least squares', 'reconstruct original vectors from quantization codes and fixed additive codebooks']
```

Usage

```
{'batch_db': 'batch a numpy database array into fixed-size chunks yielding batch index and data', 'show_gpu_memory': 'show current GPU memory usage in gigabytes using PyTorch CUDA memory info', 'iterate_encoded_db': 'iterate over partitioned encoded database NPZ files in configurable batch sizes', 'compute_aq_codebooks': 'compute fixed additive quantization codebooks from training data and codes using least squares', 'reconstruct_vectors': 'reconstruct original vectors from quantization codes and fixed additive codebooks'}
```

