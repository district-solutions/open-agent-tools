# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/sam_hq/convert_samhq_to_hf.py

Prompts

```
['convert a SAM-HQ checkpoint from the original repository to Hugging Face Transformers format', 'get a SamHQConfig object for a specified model variant (sam_hq_vit_b, sam_hq_vit_l, or sam_hq_vit_h)', 'replace original SAM-HQ checkpoint keys with Hugging Face-compatible key names', 'run the SAM-HQ to Hugging Face conversion script via command line with model name and checkpoint path', 'push a converted SAM-HQ model and processor to a Hugging Face Hub repository', 'run SAM-HQ model to generate high-quality segmentation masks from an image and input points', 'get image embeddings from the SAM-HQ vision encoder for memory-efficient mask decoding', 'build a SamHQMaskDecoder module that produces high-quality masks using intermediate vision encoder embeddings', 'create a SamHQPromptEncoder to embed point, box, and mask prompts for the mask decoder', 'test SAM-HQ mask decoder with multimask_output to return multiple candidate masks sorted by IoU scores', 'create a SamHQConfig object to configure the SAM-HQ model architecture and hyperparameters', 'run the SamHQProcessor to process images with input points, labels, and bounding boxes for segmentation', 'create a SamHQProcessor instance with an image processor for prompt-based segmentation tasks', 'normalize input point, label, and bounding box coordinates to match the target image size', 'pad input points and labels to the maximum number of points in a batch for consistent tensor shapes', "post-process output masks from the SamHQ model using the image processor's post_process_masks method"]
```

Usage

```
{'convert_sam_hq_checkpoint': 'convert a SAM-HQ checkpoint from the original repository to Hugging Face Transformers format', 'get_sam_hq_config': 'get a SamHQConfig object for a specified model variant (sam_hq_vit_b, sam_hq_vit_l, or sam_hq_vit_h)', 'replace_checkpoint_keys': 'replace original SAM-HQ checkpoint keys with Hugging Face-compatible key names', 'run_sam_hq_conversion_cli': 'run the SAM-HQ to Hugging Face conversion script via command line with model name and checkpoint path', 'push_sam_hq_to_hub': 'push a converted SAM-HQ model and processor to a Hugging Face Hub repository'}
```

## File: huggingface_transformers/src/transformers/models/sam_hq/modeling_sam_hq.py

Prompts

```
['convert a SAM-HQ checkpoint from the original repository to Hugging Face Transformers format', 'get a SamHQConfig object for a specified model variant (sam_hq_vit_b, sam_hq_vit_l, or sam_hq_vit_h)', 'replace original SAM-HQ checkpoint keys with Hugging Face-compatible key names', 'run the SAM-HQ to Hugging Face conversion script via command line with model name and checkpoint path', 'push a converted SAM-HQ model and processor to a Hugging Face Hub repository', 'run SAM-HQ model to generate high-quality segmentation masks from an image and input points', 'get image embeddings from the SAM-HQ vision encoder for memory-efficient mask decoding', 'build a SamHQMaskDecoder module that produces high-quality masks using intermediate vision encoder embeddings', 'create a SamHQPromptEncoder to embed point, box, and mask prompts for the mask decoder', 'test SAM-HQ mask decoder with multimask_output to return multiple candidate masks sorted by IoU scores', 'create a SamHQConfig object to configure the SAM-HQ model architecture and hyperparameters', 'run the SamHQProcessor to process images with input points, labels, and bounding boxes for segmentation', 'create a SamHQProcessor instance with an image processor for prompt-based segmentation tasks', 'normalize input point, label, and bounding box coordinates to match the target image size', 'pad input points and labels to the maximum number of points in a batch for consistent tensor shapes', "post-process output masks from the SamHQ model using the image processor's post_process_masks method"]
```

Usage

```
{'run_sam_hq_segmentation': 'run SAM-HQ model to generate high-quality segmentation masks from an image and input points', 'get_image_embeddings_sam_hq': 'get image embeddings from the SAM-HQ vision encoder for memory-efficient mask decoding', 'build_sam_hq_mask_decoder': 'build a SamHQMaskDecoder module that produces high-quality masks using intermediate vision encoder embeddings', 'create_sam_hq_prompt_encoder': 'create a SamHQPromptEncoder to embed point, box, and mask prompts for the mask decoder', 'test_sam_hq_multimask_output': 'test SAM-HQ mask decoder with multimask_output to return multiple candidate masks sorted by IoU scores'}
```

## File: huggingface_transformers/src/transformers/models/sam_hq/modular_sam_hq.py

Prompts

```
['convert a SAM-HQ checkpoint from the original repository to Hugging Face Transformers format', 'get a SamHQConfig object for a specified model variant (sam_hq_vit_b, sam_hq_vit_l, or sam_hq_vit_h)', 'replace original SAM-HQ checkpoint keys with Hugging Face-compatible key names', 'run the SAM-HQ to Hugging Face conversion script via command line with model name and checkpoint path', 'push a converted SAM-HQ model and processor to a Hugging Face Hub repository', 'run SAM-HQ model to generate high-quality segmentation masks from an image and input points', 'get image embeddings from the SAM-HQ vision encoder for memory-efficient mask decoding', 'build a SamHQMaskDecoder module that produces high-quality masks using intermediate vision encoder embeddings', 'create a SamHQPromptEncoder to embed point, box, and mask prompts for the mask decoder', 'test SAM-HQ mask decoder with multimask_output to return multiple candidate masks sorted by IoU scores', 'create a SamHQConfig object to configure the SAM-HQ model architecture and hyperparameters', 'run the SamHQProcessor to process images with input points, labels, and bounding boxes for segmentation', 'create a SamHQProcessor instance with an image processor for prompt-based segmentation tasks', 'normalize input point, label, and bounding box coordinates to match the target image size', 'pad input points and labels to the maximum number of points in a batch for consistent tensor shapes', "post-process output masks from the SamHQ model using the image processor's post_process_masks method"]
```

Usage

```
{'run_sam_hq_segmentation': 'run SAM-HQ model to generate high-quality segmentation masks from an image and input points', 'create_sam_hq_config': 'create a SamHQConfig object to configure the SAM-HQ model architecture and hyperparameters', 'get_image_embeddings_sam_hq': 'get image embeddings from the SAM-HQ vision encoder for memory-efficient mask decoding', 'build_sam_hq_mask_decoder': 'build a SamHQMaskDecoder module that produces high-quality masks using intermediate vision encoder embeddings', 'test_sam_hq_multimask_output': 'test SAM-HQ mask decoder with multimask_output to return multiple candidate masks sorted by IoU scores'}
```

## File: huggingface_transformers/src/transformers/models/sam_hq/processing_sam_hq.py

Prompts

```
['convert a SAM-HQ checkpoint from the original repository to Hugging Face Transformers format', 'get a SamHQConfig object for a specified model variant (sam_hq_vit_b, sam_hq_vit_l, or sam_hq_vit_h)', 'replace original SAM-HQ checkpoint keys with Hugging Face-compatible key names', 'run the SAM-HQ to Hugging Face conversion script via command line with model name and checkpoint path', 'push a converted SAM-HQ model and processor to a Hugging Face Hub repository', 'run SAM-HQ model to generate high-quality segmentation masks from an image and input points', 'get image embeddings from the SAM-HQ vision encoder for memory-efficient mask decoding', 'build a SamHQMaskDecoder module that produces high-quality masks using intermediate vision encoder embeddings', 'create a SamHQPromptEncoder to embed point, box, and mask prompts for the mask decoder', 'test SAM-HQ mask decoder with multimask_output to return multiple candidate masks sorted by IoU scores', 'create a SamHQConfig object to configure the SAM-HQ model architecture and hyperparameters', 'run the SamHQProcessor to process images with input points, labels, and bounding boxes for segmentation', 'create a SamHQProcessor instance with an image processor for prompt-based segmentation tasks', 'normalize input point, label, and bounding box coordinates to match the target image size', 'pad input points and labels to the maximum number of points in a batch for consistent tensor shapes', "post-process output masks from the SamHQ model using the image processor's post_process_masks method"]
```

Usage

```
{'run_sam_hq_processor': 'run the SamHQProcessor to process images with input points, labels, and bounding boxes for segmentation', 'create_sam_hq_processor': 'create a SamHQProcessor instance with an image processor for prompt-based segmentation tasks', 'normalize_batch_coordinates': 'normalize input point, label, and bounding box coordinates to match the target image size', 'pad_points_and_labels': 'pad input points and labels to the maximum number of points in a batch for consistent tensor shapes', 'post_process_sam_hq_masks': "post-process output masks from the SamHQ model using the image processor's post_process_masks method"}
```

