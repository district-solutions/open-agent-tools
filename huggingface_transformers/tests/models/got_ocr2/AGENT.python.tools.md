# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/got_ocr2/test_image_processing_got_ocr2.py

Prompts

```
['test the GotOcr2ImageProcessingTester class that configures image processor parameters and generates dummy image inputs', 'test the GotOcr2ProcessingTest class that validates GOT-OCR2 image processing behavior across backends', 'test the crop_image_to_patches method that splits images into configurable patches using PIL or torchvision backend', 'test the get_number_of_image_patches method that computes patch counts from image dimensions and crop settings', 'test backend equivalence by comparing PIL and torchvision crop-to-patches outputs for consistency', 'test the GotOcr2VisionText2TextModelTester class to prepare config and inputs for GOT-OCR-2 model testing', 'run the GotOcr2ModelTest suite to verify GOT-OCR-2 model and generation mixin behavior', 'test GOT-OCR-2 model generation with stop strings to control output termination', 'test GOT-OCR-2 model with format mode to generate structured LaTeX-style output', 'test GOT-OCR-2 model batched inference to process multiple images in a single forward pass', 'test the GotOcr2Processor with basic image input returning tensors', 'test the GotOcr2Processor with format=True query parameter', "test the GotOcr2Processor with color='red' query parameter", 'test the GotOcr2Processor with box=[0,0,100,100] query parameter', 'test the GotOcr2Processor with multi_page=True and multiple images']
```

Usage

```
{'test_GotOcr2ImageProcessingTester': 'test the GotOcr2ImageProcessingTester class that configures image processor parameters and generates dummy image inputs', 'test_GotOcr2ProcessingTest': 'test the GotOcr2ProcessingTest class that validates GOT-OCR2 image processing behavior across backends', 'test_crop_image_to_patches': 'test the crop_image_to_patches method that splits images into configurable patches using PIL or torchvision backend', 'test_get_number_of_image_patches': 'test the get_number_of_image_patches method that computes patch counts from image dimensions and crop settings', 'test_backends_equivalence': 'test backend equivalence by comparing PIL and torchvision crop-to-patches outputs for consistency'}
```

## File: huggingface_transformers/tests/models/got_ocr2/test_modeling_got_ocr2.py

Prompts

```
['test the GotOcr2ImageProcessingTester class that configures image processor parameters and generates dummy image inputs', 'test the GotOcr2ProcessingTest class that validates GOT-OCR2 image processing behavior across backends', 'test the crop_image_to_patches method that splits images into configurable patches using PIL or torchvision backend', 'test the get_number_of_image_patches method that computes patch counts from image dimensions and crop settings', 'test backend equivalence by comparing PIL and torchvision crop-to-patches outputs for consistency', 'test the GotOcr2VisionText2TextModelTester class to prepare config and inputs for GOT-OCR-2 model testing', 'run the GotOcr2ModelTest suite to verify GOT-OCR-2 model and generation mixin behavior', 'test GOT-OCR-2 model generation with stop strings to control output termination', 'test GOT-OCR-2 model with format mode to generate structured LaTeX-style output', 'test GOT-OCR-2 model batched inference to process multiple images in a single forward pass', 'test the GotOcr2Processor with basic image input returning tensors', 'test the GotOcr2Processor with format=True query parameter', "test the GotOcr2Processor with color='red' query parameter", 'test the GotOcr2Processor with box=[0,0,100,100] query parameter', 'test the GotOcr2Processor with multi_page=True and multiple images']
```

Usage

```
{'test_GotOcr2VisionText2TextModelTester': 'test the GotOcr2VisionText2TextModelTester class to prepare config and inputs for GOT-OCR-2 model testing', 'run_GotOcr2ModelTest': 'run the GotOcr2ModelTest suite to verify GOT-OCR-2 model and generation mixin behavior', 'test_GotOcr2_stop_strings': 'test GOT-OCR-2 model generation with stop strings to control output termination', 'test_GotOcr2_format_mode': 'test GOT-OCR-2 model with format mode to generate structured LaTeX-style output', 'test_GotOcr2_batched_inference': 'test GOT-OCR-2 model batched inference to process multiple images in a single forward pass'}
```

## File: huggingface_transformers/tests/models/got_ocr2/test_processing_got_ocr2.py

Prompts

```
['test the GotOcr2ImageProcessingTester class that configures image processor parameters and generates dummy image inputs', 'test the GotOcr2ProcessingTest class that validates GOT-OCR2 image processing behavior across backends', 'test the crop_image_to_patches method that splits images into configurable patches using PIL or torchvision backend', 'test the get_number_of_image_patches method that computes patch counts from image dimensions and crop settings', 'test backend equivalence by comparing PIL and torchvision crop-to-patches outputs for consistency', 'test the GotOcr2VisionText2TextModelTester class to prepare config and inputs for GOT-OCR-2 model testing', 'run the GotOcr2ModelTest suite to verify GOT-OCR-2 model and generation mixin behavior', 'test GOT-OCR-2 model generation with stop strings to control output termination', 'test GOT-OCR-2 model with format mode to generate structured LaTeX-style output', 'test GOT-OCR-2 model batched inference to process multiple images in a single forward pass', 'test the GotOcr2Processor with basic image input returning tensors', 'test the GotOcr2Processor with format=True query parameter', "test the GotOcr2Processor with color='red' query parameter", 'test the GotOcr2Processor with box=[0,0,100,100] query parameter', 'test the GotOcr2Processor with multi_page=True and multiple images']
```

Usage

```
{'test_GotOcr2Processor_ocr_queries': 'test the GotOcr2Processor with basic image input returning tensors', 'test_GotOcr2Processor_format_query': 'test the GotOcr2Processor with format=True query parameter', 'test_GotOcr2Processor_color_query': "test the GotOcr2Processor with color='red' query parameter", 'test_GotOcr2Processor_box_query': 'test the GotOcr2Processor with box=[0,0,100,100] query parameter', 'test_GotOcr2Processor_multi_page': 'test the GotOcr2Processor with multi_page=True and multiple images'}
```

