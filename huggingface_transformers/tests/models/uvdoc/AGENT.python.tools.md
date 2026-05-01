# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/uvdoc/test_image_processing_uvdoc.py

Prompts

```
['test the UVDocImageProcessingTester class that prepares image processor configuration dicts and test inputs', 'test the UVDoc image processor post_process_document_rectification method with identity grid predictions and original images', 'test post_process_document_rectification with original images of different sizes to verify per-image shape handling', 'review the UVDocImageProcessingTester prepare_image_processor_dict method that returns do_normalize, do_resize, and size config', 'review the UVDocImageProcessingTester prepare_image_inputs method that delegates to prepare_image_inputs with batch and resolution params', 'test the UVDocModel forward pass with pixel values and verify output shape', 'test the UVDocBackbone feature extraction with configurable resnet stages', 'test UVDocConfig initialization with backbone and bridge connector parameters', 'test UVDocBackboneConfig initialization with resnet and stage configurations', 'test UVDocModel inference with float32, float16, and bfloat16 dtypes', 'run UVDocModel integration test with pretrained model and real document image', 'test UVDocImageProcessor post processing of document rectification outputs']
```

Usage

```
{'test_UVDocImageProcessingTester': 'test the UVDocImageProcessingTester class that prepares image processor configuration dicts and test inputs', 'test_UVDocImageProcessingTest_post_process_document_rectification': 'test the UVDoc image processor post_process_document_rectification method with identity grid predictions and original images', 'test_UVDocImageProcessingTest_different_sizes': 'test post_process_document_rectification with original images of different sizes to verify per-image shape handling', 'review_UVDocImageProcessingTester_prepare_image_processor_dict': 'review the UVDocImageProcessingTester prepare_image_processor_dict method that returns do_normalize, do_resize, and size config', 'review_UVDocImageProcessingTester_prepare_image_inputs': 'review the UVDocImageProcessingTester prepare_image_inputs method that delegates to prepare_image_inputs with batch and resolution params'}
```

## File: huggingface_transformers/tests/models/uvdoc/test_modeling_uvdoc.py

Prompts

```
['test the UVDocImageProcessingTester class that prepares image processor configuration dicts and test inputs', 'test the UVDoc image processor post_process_document_rectification method with identity grid predictions and original images', 'test post_process_document_rectification with original images of different sizes to verify per-image shape handling', 'review the UVDocImageProcessingTester prepare_image_processor_dict method that returns do_normalize, do_resize, and size config', 'review the UVDocImageProcessingTester prepare_image_inputs method that delegates to prepare_image_inputs with batch and resolution params', 'test the UVDocModel forward pass with pixel values and verify output shape', 'test the UVDocBackbone feature extraction with configurable resnet stages', 'test UVDocConfig initialization with backbone and bridge connector parameters', 'test UVDocBackboneConfig initialization with resnet and stage configurations', 'test UVDocModel inference with float32, float16, and bfloat16 dtypes', 'run UVDocModel integration test with pretrained model and real document image', 'test UVDocImageProcessor post processing of document rectification outputs']
```

Usage

```
{'test_UVDocModel_document_rectification': 'test the UVDocModel forward pass with pixel values and verify output shape', 'test_UVDocBackbone_feature_extraction': 'test the UVDocBackbone feature extraction with configurable resnet stages', 'test_UVDocConfig_initialization': 'test UVDocConfig initialization with backbone and bridge connector parameters', 'test_UVDocBackboneConfig_initialization': 'test UVDocBackboneConfig initialization with resnet and stage configurations', 'test_UVDocModel_inference_dtypes': 'test UVDocModel inference with float32, float16, and bfloat16 dtypes', 'run_UVDocModel_integration_inference': 'run UVDocModel integration test with pretrained model and real document image', 'test_UVDocImageProcessor_post_process': 'test UVDocImageProcessor post processing of document rectification outputs'}
```

