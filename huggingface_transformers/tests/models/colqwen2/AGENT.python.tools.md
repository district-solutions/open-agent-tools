# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/colqwen2/test_modeling_colqwen2.py

Prompts

```
['test the ColQwen2ForRetrievalModelTest class that validates model forward pass, embedding handling, and common modeling behaviors', 'create a ColQwen2Config via ColQwen2ForRetrievalModelTester.get_config with vlm_config, embedding_dim, and initializer_range parameters', 'test the ColQwen2ForRetrieval model forward pass with pixel_values, image_grid_thw, and input_ids returning ColQwen2ForRetrievalOutput', 'test the ColQwen2ForRetrieval integration with vidore/colqwen2-v1.0-hf using 8-bit quantization and document retrieval scoring', 'test the ColQwen2ForRetrieval integration with Sahil-Kabir/colqwen2.5-v0.2-hf using bfloat16 dtype and document retrieval scoring', 'test the ColQwen2Processor process_images method to verify pixel_values output shape', 'test the ColQwen2Processor process_queries method to verify input_ids tensor output', 'test the ColQwen2Processor _get_num_multimodal_tokens helper for image token counting', 'test the ColQwen2Processor with nested structured kwargs for text and image modalities', 'test the ColQwen2Processor model_input_names match the processor output keys']
```

Usage

```
{'test_modeling_colqwen2': 'test the ColQwen2ForRetrievalModelTest class that validates model forward pass, embedding handling, and common modeling behaviors', 'create_colqwen2_config': 'create a ColQwen2Config via ColQwen2ForRetrievalModelTester.get_config with vlm_config, embedding_dim, and initializer_range parameters', 'test_colqwen2_forward': 'test the ColQwen2ForRetrieval model forward pass with pixel_values, image_grid_thw, and input_ids returning ColQwen2ForRetrievalOutput', 'test_colqwen2_integration': 'test the ColQwen2ForRetrieval integration with vidore/colqwen2-v1.0-hf using 8-bit quantization and document retrieval scoring', 'test_colqwen2_2_integration': 'test the ColQwen2ForRetrieval integration with Sahil-Kabir/colqwen2.5-v0.2-hf using bfloat16 dtype and document retrieval scoring'}
```

## File: huggingface_transformers/tests/models/colqwen2/test_processing_colqwen2.py

Prompts

```
['test the ColQwen2ForRetrievalModelTest class that validates model forward pass, embedding handling, and common modeling behaviors', 'create a ColQwen2Config via ColQwen2ForRetrievalModelTester.get_config with vlm_config, embedding_dim, and initializer_range parameters', 'test the ColQwen2ForRetrieval model forward pass with pixel_values, image_grid_thw, and input_ids returning ColQwen2ForRetrievalOutput', 'test the ColQwen2ForRetrieval integration with vidore/colqwen2-v1.0-hf using 8-bit quantization and document retrieval scoring', 'test the ColQwen2ForRetrieval integration with Sahil-Kabir/colqwen2.5-v0.2-hf using bfloat16 dtype and document retrieval scoring', 'test the ColQwen2Processor process_images method to verify pixel_values output shape', 'test the ColQwen2Processor process_queries method to verify input_ids tensor output', 'test the ColQwen2Processor _get_num_multimodal_tokens helper for image token counting', 'test the ColQwen2Processor with nested structured kwargs for text and image modalities', 'test the ColQwen2Processor model_input_names match the processor output keys']
```

Usage

```
{'test_process_images': 'test the ColQwen2Processor process_images method to verify pixel_values output shape', 'test_process_queries': 'test the ColQwen2Processor process_queries method to verify input_ids tensor output', 'test_get_num_vision_tokens': 'test the ColQwen2Processor _get_num_multimodal_tokens helper for image token counting', 'test_structured_kwargs_nested': 'test the ColQwen2Processor with nested structured kwargs for text and image modalities', 'test_model_input_names': 'test the ColQwen2Processor model_input_names match the processor output keys'}
```

