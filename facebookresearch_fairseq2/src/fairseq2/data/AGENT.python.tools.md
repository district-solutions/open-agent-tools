# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/src/fairseq2/data/data_pipeline.py

Prompts

```
['build a python module that creates a DataPipeline from a sequence and iterates over examples', 'build a python module that creates a DataPipeline and applies a map function to transform each example', 'create a python module that calls create_bucket_sizes to compute optimal bucket sizes for bucket_by_length', 'build a python module that creates a DataPipeline with collate to batch examples into padded tensors', 'create a python module that uses FileMapper to read file contents as bytes from a given path', 'create an IteratorPickleWrapper to make a non-pickleable iterator safe for pickling and state restoration', 'use read_pickle_wrapped_iterator to read elements from an iterator factory into a DataPipelineBuilder', 'review the IteratorPickleWrapper class and its __getstate__ and __setstate__ pickle methods', 'test read_pickle_wrapped_iterator to verify it falls back to IteratorPickleWrapper when the iterator is not pickleable', 'build a DataPipelineBuilder from an iterator factory using read_pickle_wrapped_iterator for safe pickling']
```

Usage

```
{'create_data_pipeline': 'build a python module that creates a DataPipeline from a sequence and iterates over examples', 'build_pipeline_with_map': 'build a python module that creates a DataPipeline and applies a map function to transform each example', 'create_bucket_sizes': 'create a python module that calls create_bucket_sizes to compute optimal bucket sizes for bucket_by_length', 'build_collated_pipeline': 'build a python module that creates a DataPipeline with collate to batch examples into padded tensors', 'create_file_mapper': 'create a python module that uses FileMapper to read file contents as bytes from a given path'}
```

## File: facebookresearch_fairseq2/src/fairseq2/data/utils.py

Prompts

```
['build a python module that creates a DataPipeline from a sequence and iterates over examples', 'build a python module that creates a DataPipeline and applies a map function to transform each example', 'create a python module that calls create_bucket_sizes to compute optimal bucket sizes for bucket_by_length', 'build a python module that creates a DataPipeline with collate to batch examples into padded tensors', 'create a python module that uses FileMapper to read file contents as bytes from a given path', 'create an IteratorPickleWrapper to make a non-pickleable iterator safe for pickling and state restoration', 'use read_pickle_wrapped_iterator to read elements from an iterator factory into a DataPipelineBuilder', 'review the IteratorPickleWrapper class and its __getstate__ and __setstate__ pickle methods', 'test read_pickle_wrapped_iterator to verify it falls back to IteratorPickleWrapper when the iterator is not pickleable', 'build a DataPipelineBuilder from an iterator factory using read_pickle_wrapped_iterator for safe pickling']
```

Usage

```
{'create_iterator_pickle_wrapper': 'create an IteratorPickleWrapper to make a non-pickleable iterator safe for pickling and state restoration', 'use_read_pickle_wrapped_iterator': 'use read_pickle_wrapped_iterator to read elements from an iterator factory into a DataPipelineBuilder', 'review_iterator_pickle_wrapper_class': 'review the IteratorPickleWrapper class and its __getstate__ and __setstate__ pickle methods', 'test_read_pickle_wrapped_iterator_fallback': 'test read_pickle_wrapped_iterator to verify it falls back to IteratorPickleWrapper when the iterator is not pickleable', 'build_data_pipeline_from_iterator_factory': 'build a DataPipelineBuilder from an iterator factory using read_pickle_wrapped_iterator for safe pickling'}
```

