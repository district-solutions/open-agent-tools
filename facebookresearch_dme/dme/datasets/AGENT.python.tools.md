# Agent Python Tools

- repo: facebookresearch/dme
- repo_uri: https://github.com/facebookresearch/dme

## File: facebookresearch_dme/dme/datasets/img_cap_retrieval.py

Prompts

```
['create an ImageCaptionDataset from a pickle file with image features and captions for training', 'build train, validation, and test splits of ImageCaptionDataset using the splits class method', 'run get_dataloader on an ImageCaptionDataset instance to get a PyTorch DataLoader with batching', 'review the collate_fn method that sorts captions by length and pads them for batching', 'test the __getitem__ method to retrieve image features, raw images, and captions by index', 'create SNLI dataset splits using SNLIDataset.splits with text and label fields', 'create MultiNLI dataset splits using MultiNLIDataset.splits with text and label fields', 'create combined SNLI and MultiNLI dataset splits using AllNLIDataset.splits', 'get NLI dataset field definitions using NLIDataset.get_fields with text and label fields', 'sort NLI dataset examples by premise and hypothesis length using NLIDataset.sort_key', 'create SST2Dataset splits for train, validation, and test using torchtext TabularDataset', 'use the SST2Dataset sort_key method to sort examples by text length', 'load SST-2 sentiment dataset from JSONL files using the splits class method', 'configure text and label fields for the SST2Dataset splits method', 'review the SST2Dataset class extending torchtext TabularDataset for sentiment classification']
```

Usage

```
{'create_ImageCaptionDataset': 'create an ImageCaptionDataset from a pickle file with image features and captions for training', 'build_ImageCaptionDataset_splits': 'build train, validation, and test splits of ImageCaptionDataset using the splits class method', 'run_ImageCaptionDataset_get_dataloader': 'run get_dataloader on an ImageCaptionDataset instance to get a PyTorch DataLoader with batching', 'review_ImageCaptionDataset_collate_fn': 'review the collate_fn method that sorts captions by length and pads them for batching', 'test_ImageCaptionDataset_getitem': 'test the __getitem__ method to retrieve image features, raw images, and captions by index'}
```

## File: facebookresearch_dme/dme/datasets/nli.py

Prompts

```
['create an ImageCaptionDataset from a pickle file with image features and captions for training', 'build train, validation, and test splits of ImageCaptionDataset using the splits class method', 'run get_dataloader on an ImageCaptionDataset instance to get a PyTorch DataLoader with batching', 'review the collate_fn method that sorts captions by length and pads them for batching', 'test the __getitem__ method to retrieve image features, raw images, and captions by index', 'create SNLI dataset splits using SNLIDataset.splits with text and label fields', 'create MultiNLI dataset splits using MultiNLIDataset.splits with text and label fields', 'create combined SNLI and MultiNLI dataset splits using AllNLIDataset.splits', 'get NLI dataset field definitions using NLIDataset.get_fields with text and label fields', 'sort NLI dataset examples by premise and hypothesis length using NLIDataset.sort_key', 'create SST2Dataset splits for train, validation, and test using torchtext TabularDataset', 'use the SST2Dataset sort_key method to sort examples by text length', 'load SST-2 sentiment dataset from JSONL files using the splits class method', 'configure text and label fields for the SST2Dataset splits method', 'review the SST2Dataset class extending torchtext TabularDataset for sentiment classification']
```

Usage

```
{'create_SNLI_splits': 'create SNLI dataset splits using SNLIDataset.splits with text and label fields', 'create_MultiNLI_splits': 'create MultiNLI dataset splits using MultiNLIDataset.splits with text and label fields', 'create_AllNLI_combined_splits': 'create combined SNLI and MultiNLI dataset splits using AllNLIDataset.splits', 'get_NLI_fields': 'get NLI dataset field definitions using NLIDataset.get_fields with text and label fields', 'sort_NLI_examples': 'sort NLI dataset examples by premise and hypothesis length using NLIDataset.sort_key'}
```

## File: facebookresearch_dme/dme/datasets/sst.py

Prompts

```
['create an ImageCaptionDataset from a pickle file with image features and captions for training', 'build train, validation, and test splits of ImageCaptionDataset using the splits class method', 'run get_dataloader on an ImageCaptionDataset instance to get a PyTorch DataLoader with batching', 'review the collate_fn method that sorts captions by length and pads them for batching', 'test the __getitem__ method to retrieve image features, raw images, and captions by index', 'create SNLI dataset splits using SNLIDataset.splits with text and label fields', 'create MultiNLI dataset splits using MultiNLIDataset.splits with text and label fields', 'create combined SNLI and MultiNLI dataset splits using AllNLIDataset.splits', 'get NLI dataset field definitions using NLIDataset.get_fields with text and label fields', 'sort NLI dataset examples by premise and hypothesis length using NLIDataset.sort_key', 'create SST2Dataset splits for train, validation, and test using torchtext TabularDataset', 'use the SST2Dataset sort_key method to sort examples by text length', 'load SST-2 sentiment dataset from JSONL files using the splits class method', 'configure text and label fields for the SST2Dataset splits method', 'review the SST2Dataset class extending torchtext TabularDataset for sentiment classification']
```

Usage

```
{'create_sst2_dataset_splits': 'create SST2Dataset splits for train, validation, and test using torchtext TabularDataset', 'use_sst2_sort_key': 'use the SST2Dataset sort_key method to sort examples by text length', 'load_sst2_jsonl': 'load SST-2 sentiment dataset from JSONL files using the splits class method', 'configure_sst2_fields': 'configure text and label fields for the SST2Dataset splits method', 'review_sst2dataset_class': 'review the SST2Dataset class extending torchtext TabularDataset for sentiment classification'}
```

