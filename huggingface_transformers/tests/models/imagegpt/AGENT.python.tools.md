# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/imagegpt/test_image_processing_imagegpt.py

Prompts

```
['test the ImageGPTImageProcessor has clusters, do_resize, size, and do_normalize attributes', 'test creating an ImageGPTImageProcessor from a dict with overridden size parameter', 'test serializing an ImageGPTImageProcessor to a JSON string and verifying fields', 'test saving and loading an ImageGPTImageProcessor via save_pretrained and from_pretrained', 'test processing PIL images with ImageGPTImageProcessor and verifying input_ids output shape', 'test the ImageGPTModel class that verifies forward pass, hidden state shape, and past key values format', 'test the ImageGPTForCausalImageModeling class that verifies causal language modeling loss and logits shape', 'test the ImageGPTForImageClassification class that verifies image classification logits output shape', 'test the ImageGPTConfig class by creating and validating configuration parameters', 'run slow inference test on ImageGPTForCausalImageModeling with a sample image and verify logits shape and values']
```

Usage

```
{'test_image_processor_properties': 'test the ImageGPTImageProcessor has clusters, do_resize, size, and do_normalize attributes', 'test_image_processor_from_dict_with_kwargs': 'test creating an ImageGPTImageProcessor from a dict with overridden size parameter', 'test_image_processor_to_json_string': 'test serializing an ImageGPTImageProcessor to a JSON string and verifying fields', 'test_image_processor_from_and_save_pretrained': 'test saving and loading an ImageGPTImageProcessor via save_pretrained and from_pretrained', 'test_call_pil': 'test processing PIL images with ImageGPTImageProcessor and verifying input_ids output shape'}
```

## File: huggingface_transformers/tests/models/imagegpt/test_modeling_imagegpt.py

Prompts

```
['test the ImageGPTImageProcessor has clusters, do_resize, size, and do_normalize attributes', 'test creating an ImageGPTImageProcessor from a dict with overridden size parameter', 'test serializing an ImageGPTImageProcessor to a JSON string and verifying fields', 'test saving and loading an ImageGPTImageProcessor via save_pretrained and from_pretrained', 'test processing PIL images with ImageGPTImageProcessor and verifying input_ids output shape', 'test the ImageGPTModel class that verifies forward pass, hidden state shape, and past key values format', 'test the ImageGPTForCausalImageModeling class that verifies causal language modeling loss and logits shape', 'test the ImageGPTForImageClassification class that verifies image classification logits output shape', 'test the ImageGPTConfig class by creating and validating configuration parameters', 'run slow inference test on ImageGPTForCausalImageModeling with a sample image and verify logits shape and values']
```

Usage

```
{'test_ImageGPTModel': 'test the ImageGPTModel class that verifies forward pass, hidden state shape, and past key values format', 'test_ImageGPTForCausalImageModeling': 'test the ImageGPTForCausalImageModeling class that verifies causal language modeling loss and logits shape', 'test_ImageGPTForImageClassification': 'test the ImageGPTForImageClassification class that verifies image classification logits output shape', 'test_ImageGPTModel_config': 'test the ImageGPTConfig class by creating and validating configuration parameters', 'test_ImageGPT_inference_causal_lm_head': 'run slow inference test on ImageGPTForCausalImageModeling with a sample image and verify logits shape and values'}
```

