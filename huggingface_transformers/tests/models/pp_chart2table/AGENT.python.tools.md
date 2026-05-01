# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/pp_chart2table/test_image_processing_pp_chart2table.py

Prompts

```
['test the PPChart2TableImageProcessingTest to verify image processor has do_resize, size, do_normalize, image_mean, and image_std properties', 'create a configuration dictionary with do_resize, size, do_normalize, image_mean, and image_std for the PPChart2Table image processor', 'create synthetic test image inputs with configurable batch size, channels, and resolution for PPChart2Table image processing tests', 'get the expected output image shape as a tuple of num_channels, height, and width from the PPChart2TableImageProcessingTester', 'run the PPChart2TableImageProcessingTest unittest suite to validate image processor initialization and property attributes', 'test the PPChart2TableIntegrationTest class loads the PaddlePaddle/PP-Chart2Table_safetensors model and verifies chart-to-table text generation', 'create an AutoModelForImageTextToText instance from the PaddlePaddle/PP-Chart2Table_safetensors pretrained checkpoint', 'create an AutoProcessor instance from the PaddlePaddle/PP-Chart2Table_safetensors checkpoint for image and text tokenization', 'run the model.generate method with apply_chat_template inputs to produce chart-to-table text output without sampling', 'test batched inference by passing two identical conversations and verifying matching decoded outputs from model.generate', 'test the PPChart2TableProcessor with OCR queries using chat template and image inputs', 'test batched processing with unstructured kwargs like rescale factor and padding on the processor', 'setup a tokenizer from the PaddlePaddle PP-Chart2Table pretrained safetensors model', 'apply a chat template to a conversation with the PPChart2TableProcessor for generation prompts', 'run the PPChart2TableProcessorTest suite to validate processor input shapes and batched kwargs']
```

Usage

```
{'test_image_processor_properties': 'test the PPChart2TableImageProcessingTest to verify image processor has do_resize, size, do_normalize, image_mean, and image_std properties', 'prepare_image_processor_dict': 'create a configuration dictionary with do_resize, size, do_normalize, image_mean, and image_std for the PPChart2Table image processor', 'prepare_image_inputs': 'create synthetic test image inputs with configurable batch size, channels, and resolution for PPChart2Table image processing tests', 'expected_output_image_shape': 'get the expected output image shape as a tuple of num_channels, height, and width from the PPChart2TableImageProcessingTester', 'run_image_processing_test': 'run the PPChart2TableImageProcessingTest unittest suite to validate image processor initialization and property attributes'}
```

## File: huggingface_transformers/tests/models/pp_chart2table/test_modeling_pp_chart2table.py

Prompts

```
['test the PPChart2TableImageProcessingTest to verify image processor has do_resize, size, do_normalize, image_mean, and image_std properties', 'create a configuration dictionary with do_resize, size, do_normalize, image_mean, and image_std for the PPChart2Table image processor', 'create synthetic test image inputs with configurable batch size, channels, and resolution for PPChart2Table image processing tests', 'get the expected output image shape as a tuple of num_channels, height, and width from the PPChart2TableImageProcessingTester', 'run the PPChart2TableImageProcessingTest unittest suite to validate image processor initialization and property attributes', 'test the PPChart2TableIntegrationTest class loads the PaddlePaddle/PP-Chart2Table_safetensors model and verifies chart-to-table text generation', 'create an AutoModelForImageTextToText instance from the PaddlePaddle/PP-Chart2Table_safetensors pretrained checkpoint', 'create an AutoProcessor instance from the PaddlePaddle/PP-Chart2Table_safetensors checkpoint for image and text tokenization', 'run the model.generate method with apply_chat_template inputs to produce chart-to-table text output without sampling', 'test batched inference by passing two identical conversations and verifying matching decoded outputs from model.generate', 'test the PPChart2TableProcessor with OCR queries using chat template and image inputs', 'test batched processing with unstructured kwargs like rescale factor and padding on the processor', 'setup a tokenizer from the PaddlePaddle PP-Chart2Table pretrained safetensors model', 'apply a chat template to a conversation with the PPChart2TableProcessor for generation prompts', 'run the PPChart2TableProcessorTest suite to validate processor input shapes and batched kwargs']
```

Usage

```
{'test_pp_chart2table_integration': 'test the PPChart2TableIntegrationTest class loads the PaddlePaddle/PP-Chart2Table_safetensors model and verifies chart-to-table text generation', 'create_model_from_pretrained': 'create an AutoModelForImageTextToText instance from the PaddlePaddle/PP-Chart2Table_safetensors pretrained checkpoint', 'create_processor_from_pretrained': 'create an AutoProcessor instance from the PaddlePaddle/PP-Chart2Table_safetensors checkpoint for image and text tokenization', 'run_model_generate': 'run the model.generate method with apply_chat_template inputs to produce chart-to-table text output without sampling', 'test_batched_inference': 'test batched inference by passing two identical conversations and verifying matching decoded outputs from model.generate'}
```

## File: huggingface_transformers/tests/models/pp_chart2table/test_processing_pp_chart2table.py

Prompts

```
['test the PPChart2TableImageProcessingTest to verify image processor has do_resize, size, do_normalize, image_mean, and image_std properties', 'create a configuration dictionary with do_resize, size, do_normalize, image_mean, and image_std for the PPChart2Table image processor', 'create synthetic test image inputs with configurable batch size, channels, and resolution for PPChart2Table image processing tests', 'get the expected output image shape as a tuple of num_channels, height, and width from the PPChart2TableImageProcessingTester', 'run the PPChart2TableImageProcessingTest unittest suite to validate image processor initialization and property attributes', 'test the PPChart2TableIntegrationTest class loads the PaddlePaddle/PP-Chart2Table_safetensors model and verifies chart-to-table text generation', 'create an AutoModelForImageTextToText instance from the PaddlePaddle/PP-Chart2Table_safetensors pretrained checkpoint', 'create an AutoProcessor instance from the PaddlePaddle/PP-Chart2Table_safetensors checkpoint for image and text tokenization', 'run the model.generate method with apply_chat_template inputs to produce chart-to-table text output without sampling', 'test batched inference by passing two identical conversations and verifying matching decoded outputs from model.generate', 'test the PPChart2TableProcessor with OCR queries using chat template and image inputs', 'test batched processing with unstructured kwargs like rescale factor and padding on the processor', 'setup a tokenizer from the PaddlePaddle PP-Chart2Table pretrained safetensors model', 'apply a chat template to a conversation with the PPChart2TableProcessor for generation prompts', 'run the PPChart2TableProcessorTest suite to validate processor input shapes and batched kwargs']
```

Usage

```
{'test_ocr_queries': 'test the PPChart2TableProcessor with OCR queries using chat template and image inputs', 'test_unstructured_kwargs_batched': 'test batched processing with unstructured kwargs like rescale factor and padding on the processor', 'setup_tokenizer': 'setup a tokenizer from the PaddlePaddle PP-Chart2Table pretrained safetensors model', 'apply_chat_template': 'apply a chat template to a conversation with the PPChart2TableProcessor for generation prompts', 'run_processor_tests': 'run the PPChart2TableProcessorTest suite to validate processor input shapes and batched kwargs'}
```

