# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/sam3/test_modeling_sam3.py

Prompts

```
['test the Sam3VisionModelTest class that validates the ViT backbone with FPN neck for SAM3', 'test the Sam3ModelTest class that validates the full SAM3 model with vision, text, and mask decoder components', 'test the Sam3ModelIntegrationTest class that validates SAM3 inference with pretrained weights on real images', 'test the Sam3ModelTest.test_attention_outputs method that verifies component-specific attention outputs across all sub-models', 'test the Sam3ModelTest.test_forward_with_text_embeds and test_forward_with_vision_embeds methods that validate precomputed embedding inputs', 'test the Sam3Processor with mixed None and real input boxes to verify default label assignment (-10 for None, 1 for real)', 'test the Sam3Processor with all real input boxes to verify default labels are set to 1', 'test the Sam3Processor without input boxes to verify input_boxes and input_boxes_labels keys are omitted', 'test the Sam3Processor with user-provided input_boxes_labels to verify custom labels are preserved', 'test the Sam3Processor custom __call__ interface with images, text, and input_boxes returning torch tensors']
```

Usage

```
{'test_Sam3VisionModel': 'test the Sam3VisionModelTest class that validates the ViT backbone with FPN neck for SAM3', 'test_Sam3Model': 'test the Sam3ModelTest class that validates the full SAM3 model with vision, text, and mask decoder components', 'test_Sam3Model_integration': 'test the Sam3ModelIntegrationTest class that validates SAM3 inference with pretrained weights on real images', 'test_Sam3Model_attention_outputs': 'test the Sam3ModelTest.test_attention_outputs method that verifies component-specific attention outputs across all sub-models', 'test_Sam3Model_embeddings': 'test the Sam3ModelTest.test_forward_with_text_embeds and test_forward_with_vision_embeds methods that validate precomputed embedding inputs'}
```

## File: huggingface_transformers/tests/models/sam3/test_processing_sam3.py

Prompts

```
['test the Sam3VisionModelTest class that validates the ViT backbone with FPN neck for SAM3', 'test the Sam3ModelTest class that validates the full SAM3 model with vision, text, and mask decoder components', 'test the Sam3ModelIntegrationTest class that validates SAM3 inference with pretrained weights on real images', 'test the Sam3ModelTest.test_attention_outputs method that verifies component-specific attention outputs across all sub-models', 'test the Sam3ModelTest.test_forward_with_text_embeds and test_forward_with_vision_embeds methods that validate precomputed embedding inputs', 'test the Sam3Processor with mixed None and real input boxes to verify default label assignment (-10 for None, 1 for real)', 'test the Sam3Processor with all real input boxes to verify default labels are set to 1', 'test the Sam3Processor without input boxes to verify input_boxes and input_boxes_labels keys are omitted', 'test the Sam3Processor with user-provided input_boxes_labels to verify custom labels are preserved', 'test the Sam3Processor custom __call__ interface with images, text, and input_boxes returning torch tensors']
```

Usage

```
{'test_Sam3Processor_input_boxes_default_labels_mixed_batch': 'test the Sam3Processor with mixed None and real input boxes to verify default label assignment (-10 for None, 1 for real)', 'test_Sam3Processor_input_boxes_default_labels_all_real': 'test the Sam3Processor with all real input boxes to verify default labels are set to 1', 'test_Sam3Processor_no_input_boxes_omits_labels': 'test the Sam3Processor without input boxes to verify input_boxes and input_boxes_labels keys are omitted', 'test_Sam3Processor_user_provided_labels_preserved': 'test the Sam3Processor with user-provided input_boxes_labels to verify custom labels are preserved', 'test_Sam3Processor_custom_interface': 'test the Sam3Processor custom __call__ interface with images, text, and input_boxes returning torch tensors'}
```

