# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/pi0/test_modeling_pi0.py

Prompts

```
['test the PI0ForConditionalGeneration model forward pass with pixel values, state, and actions inputs', 'test the PI0 model sample_actions method to generate robot actions from image and text inputs', 'test creating a PI0Config with nested vision, text, and diffusion transformer sub-configs', 'test the PI0Processor to tokenize text and encode images for the PI0 model', 'test fine-tuning the PI0 model using the HuggingFace Trainer on a robot dataset', 'test the PI0Processor class with image processor and tokenizer setup for multi-camera vision-language processing', 'test that PI0Processor image processor outputs match the raw image processor outputs pixel-wise', 'test that PI0Processor produces 5D pixel_values output for a single camera input', 'test that PI0Processor correctly pads multi-camera inputs and generates pixel_attention_mask', 'test that PI0Processor normalizes trailing newlines in text input consistently']
```

Usage

```
{'test_pi0_model_forward_pass': 'test the PI0ForConditionalGeneration model forward pass with pixel values, state, and actions inputs', 'test_pi0_sample_actions': 'test the PI0 model sample_actions method to generate robot actions from image and text inputs', 'test_pi0_config_creation': 'test creating a PI0Config with nested vision, text, and diffusion transformer sub-configs', 'test_pi0_processor_integration': 'test the PI0Processor to tokenize text and encode images for the PI0 model', 'test_pi0_training_with_trainer': 'test fine-tuning the PI0 model using the HuggingFace Trainer on a robot dataset'}
```

## File: huggingface_transformers/tests/models/pi0/test_processing_pi0.py

Prompts

```
['test the PI0ForConditionalGeneration model forward pass with pixel values, state, and actions inputs', 'test the PI0 model sample_actions method to generate robot actions from image and text inputs', 'test creating a PI0Config with nested vision, text, and diffusion transformer sub-configs', 'test the PI0Processor to tokenize text and encode images for the PI0 model', 'test fine-tuning the PI0 model using the HuggingFace Trainer on a robot dataset', 'test the PI0Processor class with image processor and tokenizer setup for multi-camera vision-language processing', 'test that PI0Processor image processor outputs match the raw image processor outputs pixel-wise', 'test that PI0Processor produces 5D pixel_values output for a single camera input', 'test that PI0Processor correctly pads multi-camera inputs and generates pixel_attention_mask', 'test that PI0Processor normalizes trailing newlines in text input consistently']
```

Usage

```
{'test_PI0Processor': 'test the PI0Processor class with image processor and tokenizer setup for multi-camera vision-language processing', 'test_image_processor_defaults': 'test that PI0Processor image processor outputs match the raw image processor outputs pixel-wise', 'test_single_camera_output_is_5d': 'test that PI0Processor produces 5D pixel_values output for a single camera input', 'test_multi_camera_padding_and_masks': 'test that PI0Processor correctly pads multi-camera inputs and generates pixel_attention_mask', 'test_newline_normalization': 'test that PI0Processor normalizes trailing newlines in text input consistently'}
```

