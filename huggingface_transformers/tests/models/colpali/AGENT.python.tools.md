# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/colpali/test_modeling_colpali.py

Prompts

```
['test the ColPaliForRetrieval model forward pass with pixel values and input ids', 'create a ColPaliConfig with vision, text, and projection dimensions for retrieval', 'run ColPaliForRetrieval inference to compute image and query embeddings for retrieval', 'score ColPali query and passage embeddings using processor.score_retrieval', 'test ColPali model integration on a document retrieval dataset with expected diagonal scores', 'test the ColPaliProcessor to process images and verify pixel_values output shape', 'test the ColPaliProcessor to process text queries and verify input_ids tensor output', 'test the ColPaliProcessor helper method to count multimodal tokens for given image sizes', 'test the ColPaliProcessor with nested structured kwargs for text and image modalities', 'test the ColPaliProcessor model input names match the processor output keys']
```

Usage

```
{'test_colpali_model_forward': 'test the ColPaliForRetrieval model forward pass with pixel values and input ids', 'create_colpali_config': 'create a ColPaliConfig with vision, text, and projection dimensions for retrieval', 'run_colpali_retrieval_inference': 'run ColPaliForRetrieval inference to compute image and query embeddings for retrieval', 'score_colpali_retrieval_results': 'score ColPali query and passage embeddings using processor.score_retrieval', 'test_colpali_model_integration': 'test ColPali model integration on a document retrieval dataset with expected diagonal scores'}
```

## File: huggingface_transformers/tests/models/colpali/test_processing_colpali.py

Prompts

```
['test the ColPaliForRetrieval model forward pass with pixel values and input ids', 'create a ColPaliConfig with vision, text, and projection dimensions for retrieval', 'run ColPaliForRetrieval inference to compute image and query embeddings for retrieval', 'score ColPali query and passage embeddings using processor.score_retrieval', 'test ColPali model integration on a document retrieval dataset with expected diagonal scores', 'test the ColPaliProcessor to process images and verify pixel_values output shape', 'test the ColPaliProcessor to process text queries and verify input_ids tensor output', 'test the ColPaliProcessor helper method to count multimodal tokens for given image sizes', 'test the ColPaliProcessor with nested structured kwargs for text and image modalities', 'test the ColPaliProcessor model input names match the processor output keys']
```

Usage

```
{'test_process_images': 'test the ColPaliProcessor to process images and verify pixel_values output shape', 'test_process_queries': 'test the ColPaliProcessor to process text queries and verify input_ids tensor output', 'test_get_num_vision_tokens': 'test the ColPaliProcessor helper method to count multimodal tokens for given image sizes', 'test_structured_kwargs_nested': 'test the ColPaliProcessor with nested structured kwargs for text and image modalities', 'test_model_input_names': 'test the ColPaliProcessor model input names match the processor output keys'}
```

