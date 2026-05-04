# Agent Python Tools

- repo: facebookresearch/dpr-scale
- repo_uri: https://github.com/facebookresearch/dpr-scale

## File: facebookresearch_dpr-scale/dpr_scale/datamodule/citadel.py

Prompts

```
['create a memory-mapped dataset from a file path with optional header and ID indexing support', 'create a memory-mapped CSV dataset with tab-separated columns and optional ID-based row lookup', 'create a memory-mapped TREC query dataset for parsing test set files with question IDs', 'create a TREC dataset that joins query, question, and passage CSV files for dense retrieval reranking', 'create a PyTorch data module for batched query embedding creation from CSV or TREC files', 'create a CrossEncoderRerankDataModule instance with a text transform and TREC dataset paths for reranking', 'build a collate function that extracts questions and contexts from a batch and transforms them into tensors', 'test the dataloader with a ContiguousDistributedSamplerForTest for multi-GPU cross-encoder reranking evaluation', 'review the collate_eval, collate_test, and collate_train methods that delegate to the shared collate function', 'refactor the _transform method to apply a custom text transform on question and context pairs', 'create a memory mapped dataset from a file path for efficient random access to large text files', 'create a multi-source dataset that randomly samples from multiple memory mapped datasets by index', 'create a memory mapped CSV dataset that parses tab-separated files with header rows into dictionaries', 'create a PyTorch Lightning data module for DPR training with positive and negative context sampling']
```

Usage

```
{'create_IDMemoryMappedDataset': 'create a memory-mapped dataset from a file path with optional header and ID indexing support', 'create_IDCSVDataset': 'create a memory-mapped CSV dataset with tab-separated columns and optional ID-based row lookup', 'create_QueryTRECDataset': 'create a memory-mapped TREC query dataset for parsing test set files with question IDs', 'create_TRECDataset': 'create a TREC dataset that joins query, question, and passage CSV files for dense retrieval reranking', 'create_DenseRetrieverQueriesDataModule': 'create a PyTorch data module for batched query embedding creation from CSV or TREC files'}
```

## File: facebookresearch_dpr-scale/dpr_scale/datamodule/cross_encoder.py

Prompts

```
['create a memory-mapped dataset from a file path with optional header and ID indexing support', 'create a memory-mapped CSV dataset with tab-separated columns and optional ID-based row lookup', 'create a memory-mapped TREC query dataset for parsing test set files with question IDs', 'create a TREC dataset that joins query, question, and passage CSV files for dense retrieval reranking', 'create a PyTorch data module for batched query embedding creation from CSV or TREC files', 'create a CrossEncoderRerankDataModule instance with a text transform and TREC dataset paths for reranking', 'build a collate function that extracts questions and contexts from a batch and transforms them into tensors', 'test the dataloader with a ContiguousDistributedSamplerForTest for multi-GPU cross-encoder reranking evaluation', 'review the collate_eval, collate_test, and collate_train methods that delegate to the shared collate function', 'refactor the _transform method to apply a custom text transform on question and context pairs', 'create a memory mapped dataset from a file path for efficient random access to large text files', 'create a multi-source dataset that randomly samples from multiple memory mapped datasets by index', 'create a memory mapped CSV dataset that parses tab-separated files with header rows into dictionaries', 'create a PyTorch Lightning data module for DPR training with positive and negative context sampling']
```

Usage

```
{'create_cross_encoder_data_module': 'create a CrossEncoderRerankDataModule instance with a text transform and TREC dataset paths for reranking', 'build_collate_fn': 'build a collate function that extracts questions and contexts from a batch and transforms them into tensors', 'test_dataloader_distributed': 'test the dataloader with a ContiguousDistributedSamplerForTest for multi-GPU cross-encoder reranking evaluation', 'review_collate_methods': 'review the collate_eval, collate_test, and collate_train methods that delegate to the shared collate function', 'refactor_transform_pipeline': 'refactor the _transform method to apply a custom text transform on question and context pairs'}
```

## File: facebookresearch_dpr-scale/dpr_scale/datamodule/dpr.py

Prompts

```
['create a memory-mapped dataset from a file path with optional header and ID indexing support', 'create a memory-mapped CSV dataset with tab-separated columns and optional ID-based row lookup', 'create a memory-mapped TREC query dataset for parsing test set files with question IDs', 'create a TREC dataset that joins query, question, and passage CSV files for dense retrieval reranking', 'create a PyTorch data module for batched query embedding creation from CSV or TREC files', 'create a CrossEncoderRerankDataModule instance with a text transform and TREC dataset paths for reranking', 'build a collate function that extracts questions and contexts from a batch and transforms them into tensors', 'test the dataloader with a ContiguousDistributedSamplerForTest for multi-GPU cross-encoder reranking evaluation', 'review the collate_eval, collate_test, and collate_train methods that delegate to the shared collate function', 'refactor the _transform method to apply a custom text transform on question and context pairs', 'create a memory mapped dataset from a file path for efficient random access to large text files', 'create a multi-source dataset that randomly samples from multiple memory mapped datasets by index', 'create a memory mapped CSV dataset that parses tab-separated files with header rows into dictionaries', 'create a PyTorch Lightning data module for DPR training with positive and negative context sampling']
```

Usage

```
{'create_MemoryMappedDataset': 'create a memory mapped dataset from a file path for efficient random access to large text files', 'create_MultiSourceDataset': 'create a multi-source dataset that randomly samples from multiple memory mapped datasets by index', 'create_CSVDataset': 'create a memory mapped CSV dataset that parses tab-separated files with header rows into dictionaries', 'create_DenseRetrieverJsonlDataModule': 'create a PyTorch Lightning data module for DPR training with positive and negative context sampling', 'create_DenseRetrieverQueriesDataModule': 'create a PyTorch Lightning data module for query embedding creation from TSV or CSV query files'}
```

