# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/fairseq/data/huffman/huffman_coder.py

Prompts

```
['build a HuffmanCoder from a frequency file using HuffmanCoder.from_file with symbol and count pairs', 'encode a list of string tokens into compressed bytes using HuffmanCoder.encode with bitpadding', 'decode bitpadded bytes back into HuffmanNode leaves using HuffmanCoder.decode to recover symbols', 'merge two HuffmanCoder instances into one using HuffmanCoder.merge combining symbol frequencies', 'convert a HuffmanCoder to a fairseq Dictionary using HuffmanCoder.to_dictionary with symbol counts', 'build a HuffmanMMapIndexedDatasetBuilder to create a memory-mapped dataset with Huffman-compressed tokens', 'create a HuffmanMMapIndex to read offsets and sizes from a Huffman binary index file', 'load a HuffmanMMapIndexedDataset from a prefix path to access Huffman-compressed data via mmap', 'append an existing HuffmanMMapIndexedDataset to a HuffmanMMapIndexedDatasetBuilder using the same coder', 'decode a Huffman-compressed item from a HuffmanMMapIndexedDataset by index and return token IDs']
```

Usage

```
{'build_huffman_coder_from_file': 'build a HuffmanCoder from a frequency file using HuffmanCoder.from_file with symbol and count pairs', 'encode_tokens_to_bytes': 'encode a list of string tokens into compressed bytes using HuffmanCoder.encode with bitpadding', 'decode_bytes_to_nodes': 'decode bitpadded bytes back into HuffmanNode leaves using HuffmanCoder.decode to recover symbols', 'merge_two_huffman_coders': 'merge two HuffmanCoder instances into one using HuffmanCoder.merge combining symbol frequencies', 'convert_coder_to_dictionary': 'convert a HuffmanCoder to a fairseq Dictionary using HuffmanCoder.to_dictionary with symbol counts'}
```

## File: facebookresearch_fairseq/fairseq/data/huffman/huffman_mmap_indexed_dataset.py

Prompts

```
['build a HuffmanCoder from a frequency file using HuffmanCoder.from_file with symbol and count pairs', 'encode a list of string tokens into compressed bytes using HuffmanCoder.encode with bitpadding', 'decode bitpadded bytes back into HuffmanNode leaves using HuffmanCoder.decode to recover symbols', 'merge two HuffmanCoder instances into one using HuffmanCoder.merge combining symbol frequencies', 'convert a HuffmanCoder to a fairseq Dictionary using HuffmanCoder.to_dictionary with symbol counts', 'build a HuffmanMMapIndexedDatasetBuilder to create a memory-mapped dataset with Huffman-compressed tokens', 'create a HuffmanMMapIndex to read offsets and sizes from a Huffman binary index file', 'load a HuffmanMMapIndexedDataset from a prefix path to access Huffman-compressed data via mmap', 'append an existing HuffmanMMapIndexedDataset to a HuffmanMMapIndexedDatasetBuilder using the same coder', 'decode a Huffman-compressed item from a HuffmanMMapIndexedDataset by index and return token IDs']
```

Usage

```
{'build_huffman_mmap_dataset': 'build a HuffmanMMapIndexedDatasetBuilder to create a memory-mapped dataset with Huffman-compressed tokens', 'create_huffman_index': 'create a HuffmanMMapIndex to read offsets and sizes from a Huffman binary index file', 'load_huffman_dataset': 'load a HuffmanMMapIndexedDataset from a prefix path to access Huffman-compressed data via mmap', 'append_huffman_dataset': 'append an existing HuffmanMMapIndexedDataset to a HuffmanMMapIndexedDatasetBuilder using the same coder', 'decode_huffman_item': 'decode a Huffman-compressed item from a HuffmanMMapIndexedDataset by index and return token IDs'}
```

