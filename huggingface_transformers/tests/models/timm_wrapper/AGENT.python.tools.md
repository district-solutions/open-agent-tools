# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/timm_wrapper/test_image_processing_timm_wrapper.py

Prompts

```
['create a TimmWrapperImageProcessor by loading it from the Hugging Face hub for timm/resnet18.a1_in1k', 'create a TimmWrapperImageProcessor by loading it from a local directory with a saved TimmWrapperConfig', 'test the TimmWrapperImageProcessor has data_config, val_transforms, and train_transforms attributes', 'test the TimmWrapperImageProcessor processes single and batch numpy images into pixel values with shape (1,3,224,224)', 'test the TimmWrapperImageProcessor processes single and batch PIL images into pixel values with shape (1,3,224,224)', 'run the TimmWrapperModelTest unittest suite to verify TimmWrapperModel and TimmWrapperForImageClassification behavior', 'test that TimmWrapperModel returns the expected number and shapes of hidden states', 'test TimmWrapperConfig label mapping including id2label and label2id for various checkpoints', 'test image classification inference using the transformers pipeline with a timm checkpoint', 'test saving a TimmWrapper model and reloading it back into a native timm model']
```

Usage

```
{'create_load_timm_image_processor_from_hub': 'create a TimmWrapperImageProcessor by loading it from the Hugging Face hub for timm/resnet18.a1_in1k', 'create_load_timm_image_processor_from_local': 'create a TimmWrapperImageProcessor by loading it from a local directory with a saved TimmWrapperConfig', 'test_image_processor_properties': 'test the TimmWrapperImageProcessor has data_config, val_transforms, and train_transforms attributes', 'test_image_processor_call_numpy': 'test the TimmWrapperImageProcessor processes single and batch numpy images into pixel values with shape (1,3,224,224)', 'test_image_processor_call_pil': 'test the TimmWrapperImageProcessor processes single and batch PIL images into pixel values with shape (1,3,224,224)'}
```

## File: huggingface_transformers/tests/models/timm_wrapper/test_modeling_timm_wrapper.py

Prompts

```
['create a TimmWrapperImageProcessor by loading it from the Hugging Face hub for timm/resnet18.a1_in1k', 'create a TimmWrapperImageProcessor by loading it from a local directory with a saved TimmWrapperConfig', 'test the TimmWrapperImageProcessor has data_config, val_transforms, and train_transforms attributes', 'test the TimmWrapperImageProcessor processes single and batch numpy images into pixel values with shape (1,3,224,224)', 'test the TimmWrapperImageProcessor processes single and batch PIL images into pixel values with shape (1,3,224,224)', 'run the TimmWrapperModelTest unittest suite to verify TimmWrapperModel and TimmWrapperForImageClassification behavior', 'test that TimmWrapperModel returns the expected number and shapes of hidden states', 'test TimmWrapperConfig label mapping including id2label and label2id for various checkpoints', 'test image classification inference using the transformers pipeline with a timm checkpoint', 'test saving a TimmWrapper model and reloading it back into a native timm model']
```

Usage

```
{'run_TimmWrapperModelTest': 'run the TimmWrapperModelTest unittest suite to verify TimmWrapperModel and TimmWrapperForImageClassification behavior', 'test_hidden_states_output': 'test that TimmWrapperModel returns the expected number and shapes of hidden states', 'test_timm_config_labels': 'test TimmWrapperConfig label mapping including id2label and label2id for various checkpoints', 'test_inference_with_pipeline': 'test image classification inference using the transformers pipeline with a timm checkpoint', 'test_save_load_to_timm': 'test saving a TimmWrapper model and reloading it back into a native timm model'}
```

