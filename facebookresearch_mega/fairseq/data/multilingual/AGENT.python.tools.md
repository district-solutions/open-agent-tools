# Agent Python Tools

- repo: facebookresearch/mega
- repo_uri: https://github.com/facebookresearch/mega

## File: facebookresearch_mega/fairseq/data/multilingual/multilingual_data_manager.py

Prompts

```
['setup a MultilingualDatasetManager instance with args, lang pairs, langs, dicts, and a sampling method', 'load a sampled multi epoch dataset for a given split with configurable epoch and shard epoch', 'load a language pair dataset from a data path with source and target dictionaries and padding options', 'create a language dictionary from a list of language codes for multilingual token management', 'load sampling weights from a JSON file as a dictionary mapping dataset keys to float weights', 'create a SampledMultiDataset from multiple sub-datasets with configurable sampling ratios and seed', 'build a collater that outputs batches in single or ordered_dict format from sub-datasets', 'test the get_virtual_indices method to verify weighted sampling produces correct virtual dataset sizes', 'refactor the default_virtual_size_func to compute virtual dataset size relative to the largest dataset', 'review the set_epoch method that resamples virtual datasets with a new epoch-based random seed', 'create a SampledMultiEpochDataset instance with multiple sub-datasets and sampling ratios for multilingual training', 'build a dataset that loads data in virtual epoch chunks to speed up dataloading', 'test the ordered_indices method to sort samples by source and target sequence length', 'review the set_epoch method that establishes new global virtual indices for each training epoch', 'summarize the prefetch method that maps local indices to sub-dataset indices for data preloading', 'build a SamplingMethod sampler from args and task using the build_sampler static method', 'run uniform sampling on dataset sizes to return equal weights of 1.0 for each dataset', 'run temperature sampling on dataset sizes with a given temperature to compute weighted sampling ratios', 'create a temperature sampling function with a fixed temperature using make_temperature_sampling', 'create a ratio sampling function with fixed ratios using make_ratio_sampling']
```

Usage

```
{'setup_multilingual_data_manager': 'setup a MultilingualDatasetManager instance with args, lang pairs, langs, dicts, and a sampling method', 'load_sampled_multi_epoch_dataset': 'load a sampled multi epoch dataset for a given split with configurable epoch and shard epoch', 'load_langpair_dataset': 'load a language pair dataset from a data path with source and target dictionaries and padding options', 'create_lang_dictionary': 'create a language dictionary from a list of language codes for multilingual token management', 'load_sampling_weights': 'load sampling weights from a JSON file as a dictionary mapping dataset keys to float weights'}
```

## File: facebookresearch_mega/fairseq/data/multilingual/sampled_multi_dataset.py

Prompts

```
['setup a MultilingualDatasetManager instance with args, lang pairs, langs, dicts, and a sampling method', 'load a sampled multi epoch dataset for a given split with configurable epoch and shard epoch', 'load a language pair dataset from a data path with source and target dictionaries and padding options', 'create a language dictionary from a list of language codes for multilingual token management', 'load sampling weights from a JSON file as a dictionary mapping dataset keys to float weights', 'create a SampledMultiDataset from multiple sub-datasets with configurable sampling ratios and seed', 'build a collater that outputs batches in single or ordered_dict format from sub-datasets', 'test the get_virtual_indices method to verify weighted sampling produces correct virtual dataset sizes', 'refactor the default_virtual_size_func to compute virtual dataset size relative to the largest dataset', 'review the set_epoch method that resamples virtual datasets with a new epoch-based random seed', 'create a SampledMultiEpochDataset instance with multiple sub-datasets and sampling ratios for multilingual training', 'build a dataset that loads data in virtual epoch chunks to speed up dataloading', 'test the ordered_indices method to sort samples by source and target sequence length', 'review the set_epoch method that establishes new global virtual indices for each training epoch', 'summarize the prefetch method that maps local indices to sub-dataset indices for data preloading', 'build a SamplingMethod sampler from args and task using the build_sampler static method', 'run uniform sampling on dataset sizes to return equal weights of 1.0 for each dataset', 'run temperature sampling on dataset sizes with a given temperature to compute weighted sampling ratios', 'create a temperature sampling function with a fixed temperature using make_temperature_sampling', 'create a ratio sampling function with fixed ratios using make_ratio_sampling']
```

Usage

```
{'create_sampled_multidataset': 'create a SampledMultiDataset from multiple sub-datasets with configurable sampling ratios and seed', 'build_collate_format': 'build a collater that outputs batches in single or ordered_dict format from sub-datasets', 'test_get_virtual_indices': 'test the get_virtual_indices method to verify weighted sampling produces correct virtual dataset sizes', 'refactor_default_virtual_size_func': 'refactor the default_virtual_size_func to compute virtual dataset size relative to the largest dataset', 'review_set_epoch': 'review the set_epoch method that resamples virtual datasets with a new epoch-based random seed'}
```

## File: facebookresearch_mega/fairseq/data/multilingual/sampled_multi_epoch_dataset.py

Prompts

```
['setup a MultilingualDatasetManager instance with args, lang pairs, langs, dicts, and a sampling method', 'load a sampled multi epoch dataset for a given split with configurable epoch and shard epoch', 'load a language pair dataset from a data path with source and target dictionaries and padding options', 'create a language dictionary from a list of language codes for multilingual token management', 'load sampling weights from a JSON file as a dictionary mapping dataset keys to float weights', 'create a SampledMultiDataset from multiple sub-datasets with configurable sampling ratios and seed', 'build a collater that outputs batches in single or ordered_dict format from sub-datasets', 'test the get_virtual_indices method to verify weighted sampling produces correct virtual dataset sizes', 'refactor the default_virtual_size_func to compute virtual dataset size relative to the largest dataset', 'review the set_epoch method that resamples virtual datasets with a new epoch-based random seed', 'create a SampledMultiEpochDataset instance with multiple sub-datasets and sampling ratios for multilingual training', 'build a dataset that loads data in virtual epoch chunks to speed up dataloading', 'test the ordered_indices method to sort samples by source and target sequence length', 'review the set_epoch method that establishes new global virtual indices for each training epoch', 'summarize the prefetch method that maps local indices to sub-dataset indices for data preloading', 'build a SamplingMethod sampler from args and task using the build_sampler static method', 'run uniform sampling on dataset sizes to return equal weights of 1.0 for each dataset', 'run temperature sampling on dataset sizes with a given temperature to compute weighted sampling ratios', 'create a temperature sampling function with a fixed temperature using make_temperature_sampling', 'create a ratio sampling function with fixed ratios using make_ratio_sampling']
```

Usage

```
{'create_sampled_multi_epoch_dataset': 'create a SampledMultiEpochDataset instance with multiple sub-datasets and sampling ratios for multilingual training', 'build_virtual_epoch_sized_dataset': 'build a dataset that loads data in virtual epoch chunks to speed up dataloading', 'test_ordered_indices_batch_by_size': 'test the ordered_indices method to sort samples by source and target sequence length', 'review_set_epoch_virtual_indices': 'review the set_epoch method that establishes new global virtual indices for each training epoch', 'summarize_prefetch_indices': 'summarize the prefetch method that maps local indices to sub-dataset indices for data preloading'}
```

## File: facebookresearch_mega/fairseq/data/multilingual/sampling_method.py

Prompts

```
['setup a MultilingualDatasetManager instance with args, lang pairs, langs, dicts, and a sampling method', 'load a sampled multi epoch dataset for a given split with configurable epoch and shard epoch', 'load a language pair dataset from a data path with source and target dictionaries and padding options', 'create a language dictionary from a list of language codes for multilingual token management', 'load sampling weights from a JSON file as a dictionary mapping dataset keys to float weights', 'create a SampledMultiDataset from multiple sub-datasets with configurable sampling ratios and seed', 'build a collater that outputs batches in single or ordered_dict format from sub-datasets', 'test the get_virtual_indices method to verify weighted sampling produces correct virtual dataset sizes', 'refactor the default_virtual_size_func to compute virtual dataset size relative to the largest dataset', 'review the set_epoch method that resamples virtual datasets with a new epoch-based random seed', 'create a SampledMultiEpochDataset instance with multiple sub-datasets and sampling ratios for multilingual training', 'build a dataset that loads data in virtual epoch chunks to speed up dataloading', 'test the ordered_indices method to sort samples by source and target sequence length', 'review the set_epoch method that establishes new global virtual indices for each training epoch', 'summarize the prefetch method that maps local indices to sub-dataset indices for data preloading', 'build a SamplingMethod sampler from args and task using the build_sampler static method', 'run uniform sampling on dataset sizes to return equal weights of 1.0 for each dataset', 'run temperature sampling on dataset sizes with a given temperature to compute weighted sampling ratios', 'create a temperature sampling function with a fixed temperature using make_temperature_sampling', 'create a ratio sampling function with fixed ratios using make_ratio_sampling']
```

Usage

```
{'build_sampler': 'build a SamplingMethod sampler from args and task using the build_sampler static method', 'run_uniform_sampling': 'run uniform sampling on dataset sizes to return equal weights of 1.0 for each dataset', 'run_temperature_sampling': 'run temperature sampling on dataset sizes with a given temperature to compute weighted sampling ratios', 'create_temperature_sampling_func': 'create a temperature sampling function with a fixed temperature using make_temperature_sampling', 'create_ratio_sampling_func': 'create a ratio sampling function with fixed ratios using make_ratio_sampling'}
```

