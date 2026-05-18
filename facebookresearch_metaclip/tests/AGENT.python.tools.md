# Agent Python Tools

- repo: facebookresearch/metaclip
- repo_uri: https://github.com/facebookresearch/metaclip

## File: facebookresearch_metaclip/tests/config_test.py

Prompts

```
['run the TestMetaCLIPConfig test_400m method to validate b32_400m, b16_400m, and l14_400m config lookups', 'run the TestMetaCLIPConfig test_2_5B method to validate b32_fullcc, b16_fullcc, l14_fullcc, and h14_fullcc config lookups', 'run python -m unittest tests.config_test to execute all MetaCLIP config validation tests', 'test the search_config function by looking up a config name and verifying its name and output_dir attributes', 'review the TestMetaCLIPConfig class and its test_400m and test_2_5B methods for config validation logic', 'run the unittest pipeline tests for MetaCLIP indexing via python -m unittest tests.pipeline_test', 'test the search_config function for metaclip_400m and metaclip_2_5b configuration names', 'test the build_shards_index function from metaclip.indexing.substr_indexing with sample text data', 'test the entry_count function from metaclip.indexing.entry_count using the metaclip_test args dataclass', 'test the build_subset_index function from metaclip.indexing.balance_sampling using the metaclip_test args', 'test inference across ViT-B-32, ViT-B-16, and ViT-L-14 models with metaclip400m and metaclip2_5b pretrained weights', 'create an OpenCLIP model and preprocessing transforms using create_model_and_transforms with a model name and pretrained checkpoint', 'encode an image into feature embeddings using the model encode_image method with a preprocessed PIL image tensor', 'encode tokenized text into feature embeddings using the model encode_text method with a list of text tokens', 'compute image-text similarity probabilities by multiplying image features with transposed text features and applying softmax', 'run the test_inference function to validate CLIP model image and text encoding with ViT-B-32-quickgelu', 'run the test_metaclip2_inference function to validate multiple WorldWideCLIP model variants against image-text matching', 'test the create_model_and_transforms factory function to load a pretrained CLIP model and image preprocessing pipeline', 'test the get_tokenizer function to load an XLM-R tokenizer for multilingual text encoding', 'test the model encode_image and encode_text methods to compute image and text feature embeddings']
```

Usage

```
{'run_test_400m': 'run the TestMetaCLIPConfig test_400m method to validate b32_400m, b16_400m, and l14_400m config lookups', 'run_test_2_5B': 'run the TestMetaCLIPConfig test_2_5B method to validate b32_fullcc, b16_fullcc, l14_fullcc, and h14_fullcc config lookups', 'run_unittest': 'run python -m unittest tests.config_test to execute all MetaCLIP config validation tests', 'test_search_config': 'test the search_config function by looking up a config name and verifying its name and output_dir attributes', 'review_TestMetaCLIPConfig': 'review the TestMetaCLIPConfig class and its test_400m and test_2_5B methods for config validation logic'}
```

## File: facebookresearch_metaclip/tests/pipeline_test.py

Prompts

```
['run the TestMetaCLIPConfig test_400m method to validate b32_400m, b16_400m, and l14_400m config lookups', 'run the TestMetaCLIPConfig test_2_5B method to validate b32_fullcc, b16_fullcc, l14_fullcc, and h14_fullcc config lookups', 'run python -m unittest tests.config_test to execute all MetaCLIP config validation tests', 'test the search_config function by looking up a config name and verifying its name and output_dir attributes', 'review the TestMetaCLIPConfig class and its test_400m and test_2_5B methods for config validation logic', 'run the unittest pipeline tests for MetaCLIP indexing via python -m unittest tests.pipeline_test', 'test the search_config function for metaclip_400m and metaclip_2_5b configuration names', 'test the build_shards_index function from metaclip.indexing.substr_indexing with sample text data', 'test the entry_count function from metaclip.indexing.entry_count using the metaclip_test args dataclass', 'test the build_subset_index function from metaclip.indexing.balance_sampling using the metaclip_test args', 'test inference across ViT-B-32, ViT-B-16, and ViT-L-14 models with metaclip400m and metaclip2_5b pretrained weights', 'create an OpenCLIP model and preprocessing transforms using create_model_and_transforms with a model name and pretrained checkpoint', 'encode an image into feature embeddings using the model encode_image method with a preprocessed PIL image tensor', 'encode tokenized text into feature embeddings using the model encode_text method with a list of text tokens', 'compute image-text similarity probabilities by multiplying image features with transposed text features and applying softmax', 'run the test_inference function to validate CLIP model image and text encoding with ViT-B-32-quickgelu', 'run the test_metaclip2_inference function to validate multiple WorldWideCLIP model variants against image-text matching', 'test the create_model_and_transforms factory function to load a pretrained CLIP model and image preprocessing pipeline', 'test the get_tokenizer function to load an XLM-R tokenizer for multilingual text encoding', 'test the model encode_image and encode_text methods to compute image and text feature embeddings']
```

Usage

```
{'run_pipeline_tests': 'run the unittest pipeline tests for MetaCLIP indexing via python -m unittest tests.pipeline_test', 'test_data_config': 'test the search_config function for metaclip_400m and metaclip_2_5b configuration names', 'test_substr_indexing': 'test the build_shards_index function from metaclip.indexing.substr_indexing with sample text data', 'test_entry_count': 'test the entry_count function from metaclip.indexing.entry_count using the metaclip_test args dataclass', 'test_balance_sampling': 'test the build_subset_index function from metaclip.indexing.balance_sampling using the metaclip_test args'}
```

## File: facebookresearch_metaclip/tests/pretrained_test.py

Prompts

```
['run the TestMetaCLIPConfig test_400m method to validate b32_400m, b16_400m, and l14_400m config lookups', 'run the TestMetaCLIPConfig test_2_5B method to validate b32_fullcc, b16_fullcc, l14_fullcc, and h14_fullcc config lookups', 'run python -m unittest tests.config_test to execute all MetaCLIP config validation tests', 'test the search_config function by looking up a config name and verifying its name and output_dir attributes', 'review the TestMetaCLIPConfig class and its test_400m and test_2_5B methods for config validation logic', 'run the unittest pipeline tests for MetaCLIP indexing via python -m unittest tests.pipeline_test', 'test the search_config function for metaclip_400m and metaclip_2_5b configuration names', 'test the build_shards_index function from metaclip.indexing.substr_indexing with sample text data', 'test the entry_count function from metaclip.indexing.entry_count using the metaclip_test args dataclass', 'test the build_subset_index function from metaclip.indexing.balance_sampling using the metaclip_test args', 'test inference across ViT-B-32, ViT-B-16, and ViT-L-14 models with metaclip400m and metaclip2_5b pretrained weights', 'create an OpenCLIP model and preprocessing transforms using create_model_and_transforms with a model name and pretrained checkpoint', 'encode an image into feature embeddings using the model encode_image method with a preprocessed PIL image tensor', 'encode tokenized text into feature embeddings using the model encode_text method with a list of text tokens', 'compute image-text similarity probabilities by multiplying image features with transposed text features and applying softmax', 'run the test_inference function to validate CLIP model image and text encoding with ViT-B-32-quickgelu', 'run the test_metaclip2_inference function to validate multiple WorldWideCLIP model variants against image-text matching', 'test the create_model_and_transforms factory function to load a pretrained CLIP model and image preprocessing pipeline', 'test the get_tokenizer function to load an XLM-R tokenizer for multilingual text encoding', 'test the model encode_image and encode_text methods to compute image and text feature embeddings']
```

Usage

```
{'test_inference_metaclip': 'test inference across ViT-B-32, ViT-B-16, and ViT-L-14 models with metaclip400m and metaclip2_5b pretrained weights', 'create_model_and_transforms': 'create an OpenCLIP model and preprocessing transforms using create_model_and_transforms with a model name and pretrained checkpoint', 'encode_image_features': 'encode an image into feature embeddings using the model encode_image method with a preprocessed PIL image tensor', 'encode_text_features': 'encode tokenized text into feature embeddings using the model encode_text method with a list of text tokens', 'compute_image_text_similarity': 'compute image-text similarity probabilities by multiplying image features with transposed text features and applying softmax'}
```

## File: facebookresearch_metaclip/tests/simple_test.py

Prompts

```
['run the TestMetaCLIPConfig test_400m method to validate b32_400m, b16_400m, and l14_400m config lookups', 'run the TestMetaCLIPConfig test_2_5B method to validate b32_fullcc, b16_fullcc, l14_fullcc, and h14_fullcc config lookups', 'run python -m unittest tests.config_test to execute all MetaCLIP config validation tests', 'test the search_config function by looking up a config name and verifying its name and output_dir attributes', 'review the TestMetaCLIPConfig class and its test_400m and test_2_5B methods for config validation logic', 'run the unittest pipeline tests for MetaCLIP indexing via python -m unittest tests.pipeline_test', 'test the search_config function for metaclip_400m and metaclip_2_5b configuration names', 'test the build_shards_index function from metaclip.indexing.substr_indexing with sample text data', 'test the entry_count function from metaclip.indexing.entry_count using the metaclip_test args dataclass', 'test the build_subset_index function from metaclip.indexing.balance_sampling using the metaclip_test args', 'test inference across ViT-B-32, ViT-B-16, and ViT-L-14 models with metaclip400m and metaclip2_5b pretrained weights', 'create an OpenCLIP model and preprocessing transforms using create_model_and_transforms with a model name and pretrained checkpoint', 'encode an image into feature embeddings using the model encode_image method with a preprocessed PIL image tensor', 'encode tokenized text into feature embeddings using the model encode_text method with a list of text tokens', 'compute image-text similarity probabilities by multiplying image features with transposed text features and applying softmax', 'run the test_inference function to validate CLIP model image and text encoding with ViT-B-32-quickgelu', 'run the test_metaclip2_inference function to validate multiple WorldWideCLIP model variants against image-text matching', 'test the create_model_and_transforms factory function to load a pretrained CLIP model and image preprocessing pipeline', 'test the get_tokenizer function to load an XLM-R tokenizer for multilingual text encoding', 'test the model encode_image and encode_text methods to compute image and text feature embeddings']
```

Usage

```
{'run_test_inference': 'run the test_inference function to validate CLIP model image and text encoding with ViT-B-32-quickgelu', 'run_test_metaclip2_inference': 'run the test_metaclip2_inference function to validate multiple WorldWideCLIP model variants against image-text matching', 'test_create_model_and_transforms': 'test the create_model_and_transforms factory function to load a pretrained CLIP model and image preprocessing pipeline', 'test_get_tokenizer': 'test the get_tokenizer function to load an XLM-R tokenizer for multilingual text encoding', 'test_encode_image_and_text': 'test the model encode_image and encode_text methods to compute image and text feature embeddings'}
```

