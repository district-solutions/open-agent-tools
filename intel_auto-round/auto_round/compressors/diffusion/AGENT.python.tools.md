# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/auto_round/compressors/diffusion/compressor.py

Prompts

```
['build a DiffusionCompressor instance to quantize a diffusion model with W4A16 scheme on coco2014 dataset', 'run the calib method to cache block inputs by executing the diffusion pipeline on calibration prompts', 'save the quantized diffusion model and pipeline components to an output directory in auto_round format', 'run the diffusion pipeline forward pass with custom prompts, guidance scale, and inference steps for calibration', 'get the output tensors of a transformer block by forwarding sampled inputs through the block', 'build a pytorch dataloader for the coco2014 text to image caption dataset with a custom batch size', 'build a pytorch dataloader from a local tsv file containing image id and caption columns', 'create a torch dataset subclass that loads captions from a tsv file and register it with the decorator', 'register a custom dataset class to the diffusion dataset registry using the register_dataset decorator', 'summarize the Text2ImgDataset class that loads caption id and caption text pairs from a tsv file', 'run diffusion_eval to generate images from prompts and compute CLIP, CLIP-IQA, or ImageReward metrics', 'compute the CLIP score between text prompts and generated images using the CLIPScore model', 'compute the CLIP-IQA image quality assessment score for generated images', 'compute the ImageReward score between text prompts and generated images using ImageReward-v1.0', 'review the metric_map dictionary that maps clip, clip-iqa, and imagereward to their compute functions', 'build a HybridCompressor to quantize both AR and DiT components of a hybrid diffusion model', 'quantize a hybrid AR+Diffusion model using HybridCompressor with W4A16 scheme and custom calibration datasets', 'save a quantized hybrid model pipeline to an output directory with both AR and DiT components', 'quantize and save a hybrid diffusion model in one step using quantize_and_save with auto_round format', 'check if a model path or pipeline object is a hybrid AR+Diffusion model using is_hybrid_diffusion_model']
```

Usage

```
{'build_diffusion_compressor': 'build a DiffusionCompressor instance to quantize a diffusion model with W4A16 scheme on coco2014 dataset', 'run_calibration': 'run the calib method to cache block inputs by executing the diffusion pipeline on calibration prompts', 'save_quantized_model': 'save the quantized diffusion model and pipeline components to an output directory in auto_round format', 'run_pipeline_forward': 'run the diffusion pipeline forward pass with custom prompts, guidance scale, and inference steps for calibration', 'get_block_outputs': 'get the output tensors of a transformer block by forwarding sampled inputs through the block'}
```

## File: intel_auto-round/auto_round/compressors/diffusion/dataset.py

Prompts

```
['build a DiffusionCompressor instance to quantize a diffusion model with W4A16 scheme on coco2014 dataset', 'run the calib method to cache block inputs by executing the diffusion pipeline on calibration prompts', 'save the quantized diffusion model and pipeline components to an output directory in auto_round format', 'run the diffusion pipeline forward pass with custom prompts, guidance scale, and inference steps for calibration', 'get the output tensors of a transformer block by forwarding sampled inputs through the block', 'build a pytorch dataloader for the coco2014 text to image caption dataset with a custom batch size', 'build a pytorch dataloader from a local tsv file containing image id and caption columns', 'create a torch dataset subclass that loads captions from a tsv file and register it with the decorator', 'register a custom dataset class to the diffusion dataset registry using the register_dataset decorator', 'summarize the Text2ImgDataset class that loads caption id and caption text pairs from a tsv file', 'run diffusion_eval to generate images from prompts and compute CLIP, CLIP-IQA, or ImageReward metrics', 'compute the CLIP score between text prompts and generated images using the CLIPScore model', 'compute the CLIP-IQA image quality assessment score for generated images', 'compute the ImageReward score between text prompts and generated images using ImageReward-v1.0', 'review the metric_map dictionary that maps clip, clip-iqa, and imagereward to their compute functions', 'build a HybridCompressor to quantize both AR and DiT components of a hybrid diffusion model', 'quantize a hybrid AR+Diffusion model using HybridCompressor with W4A16 scheme and custom calibration datasets', 'save a quantized hybrid model pipeline to an output directory with both AR and DiT components', 'quantize and save a hybrid diffusion model in one step using quantize_and_save with auto_round format', 'check if a model path or pipeline object is a hybrid AR+Diffusion model using is_hybrid_diffusion_model']
```

Usage

```
{'build_dataloader_coco2014': 'build a pytorch dataloader for the coco2014 text to image caption dataset with a custom batch size', 'build_dataloader_local_tsv': 'build a pytorch dataloader from a local tsv file containing image id and caption columns', 'create_dataset_class': 'create a torch dataset subclass that loads captions from a tsv file and register it with the decorator', 'register_custom_dataset': 'register a custom dataset class to the diffusion dataset registry using the register_dataset decorator', 'summarize_text2imgdataset': 'summarize the Text2ImgDataset class that loads caption id and caption text pairs from a tsv file'}
```

## File: intel_auto-round/auto_round/compressors/diffusion/eval.py

Prompts

```
['build a DiffusionCompressor instance to quantize a diffusion model with W4A16 scheme on coco2014 dataset', 'run the calib method to cache block inputs by executing the diffusion pipeline on calibration prompts', 'save the quantized diffusion model and pipeline components to an output directory in auto_round format', 'run the diffusion pipeline forward pass with custom prompts, guidance scale, and inference steps for calibration', 'get the output tensors of a transformer block by forwarding sampled inputs through the block', 'build a pytorch dataloader for the coco2014 text to image caption dataset with a custom batch size', 'build a pytorch dataloader from a local tsv file containing image id and caption columns', 'create a torch dataset subclass that loads captions from a tsv file and register it with the decorator', 'register a custom dataset class to the diffusion dataset registry using the register_dataset decorator', 'summarize the Text2ImgDataset class that loads caption id and caption text pairs from a tsv file', 'run diffusion_eval to generate images from prompts and compute CLIP, CLIP-IQA, or ImageReward metrics', 'compute the CLIP score between text prompts and generated images using the CLIPScore model', 'compute the CLIP-IQA image quality assessment score for generated images', 'compute the ImageReward score between text prompts and generated images using ImageReward-v1.0', 'review the metric_map dictionary that maps clip, clip-iqa, and imagereward to their compute functions', 'build a HybridCompressor to quantize both AR and DiT components of a hybrid diffusion model', 'quantize a hybrid AR+Diffusion model using HybridCompressor with W4A16 scheme and custom calibration datasets', 'save a quantized hybrid model pipeline to an output directory with both AR and DiT components', 'quantize and save a hybrid diffusion model in one step using quantize_and_save with auto_round format', 'check if a model path or pipeline object is a hybrid AR+Diffusion model using is_hybrid_diffusion_model']
```

Usage

```
{'run_diffusion_eval': 'run diffusion_eval to generate images from prompts and compute CLIP, CLIP-IQA, or ImageReward metrics', 'compute_clip_score': 'compute the CLIP score between text prompts and generated images using the CLIPScore model', 'compute_clip_iqa_score': 'compute the CLIP-IQA image quality assessment score for generated images', 'compute_imagereward_score': 'compute the ImageReward score between text prompts and generated images using ImageReward-v1.0', 'review_metric_map': 'review the metric_map dictionary that maps clip, clip-iqa, and imagereward to their compute functions'}
```

## File: intel_auto-round/auto_round/compressors/diffusion/hybrid.py

Prompts

```
['build a DiffusionCompressor instance to quantize a diffusion model with W4A16 scheme on coco2014 dataset', 'run the calib method to cache block inputs by executing the diffusion pipeline on calibration prompts', 'save the quantized diffusion model and pipeline components to an output directory in auto_round format', 'run the diffusion pipeline forward pass with custom prompts, guidance scale, and inference steps for calibration', 'get the output tensors of a transformer block by forwarding sampled inputs through the block', 'build a pytorch dataloader for the coco2014 text to image caption dataset with a custom batch size', 'build a pytorch dataloader from a local tsv file containing image id and caption columns', 'create a torch dataset subclass that loads captions from a tsv file and register it with the decorator', 'register a custom dataset class to the diffusion dataset registry using the register_dataset decorator', 'summarize the Text2ImgDataset class that loads caption id and caption text pairs from a tsv file', 'run diffusion_eval to generate images from prompts and compute CLIP, CLIP-IQA, or ImageReward metrics', 'compute the CLIP score between text prompts and generated images using the CLIPScore model', 'compute the CLIP-IQA image quality assessment score for generated images', 'compute the ImageReward score between text prompts and generated images using ImageReward-v1.0', 'review the metric_map dictionary that maps clip, clip-iqa, and imagereward to their compute functions', 'build a HybridCompressor to quantize both AR and DiT components of a hybrid diffusion model', 'quantize a hybrid AR+Diffusion model using HybridCompressor with W4A16 scheme and custom calibration datasets', 'save a quantized hybrid model pipeline to an output directory with both AR and DiT components', 'quantize and save a hybrid diffusion model in one step using quantize_and_save with auto_round format', 'check if a model path or pipeline object is a hybrid AR+Diffusion model using is_hybrid_diffusion_model']
```

Usage

```
{'build_hybrid_compressor': 'build a HybridCompressor to quantize both AR and DiT components of a hybrid diffusion model', 'quantize_hybrid_model': 'quantize a hybrid AR+Diffusion model using HybridCompressor with W4A16 scheme and custom calibration datasets', 'save_quantized_hybrid': 'save a quantized hybrid model pipeline to an output directory with both AR and DiT components', 'quantize_and_save_hybrid': 'quantize and save a hybrid diffusion model in one step using quantize_and_save with auto_round format', 'check_is_hybrid_diffusion_model': 'check if a model path or pipeline object is a hybrid AR+Diffusion model using is_hybrid_diffusion_model'}
```

