# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/paint_by_example/image_encoder.py

Prompts

```
['build a PaintByExampleImageEncoder using a CLIP config and optional projection size', 'run the PaintByExampleImageEncoder forward pass on pixel values to get latent states', 'build a PaintByExampleMapper with transformer blocks derived from a CLIP config', 'run the PaintByExampleMapper forward pass on hidden states through transformer blocks', 'review the PaintByExampleImageEncoder uncond_vector parameter used for unconditional scaling', 'run the PaintByExamplePipeline to generate images guided by example images using inpainting', 'prepare a mask and masked image tensor pair for the Paint by Example pipeline', 'encode an example image using the PaintByExampleImageEncoder to get image embeddings', 'prepare mask latents by resizing and encoding masked images for the UNet input', 'run the safety checker on generated images to detect NSFW content']
```

Usage

```
{'build_PaintByExampleImageEncoder': 'build a PaintByExampleImageEncoder using a CLIP config and optional projection size', 'run_PaintByExampleImageEncoder_forward': 'run the PaintByExampleImageEncoder forward pass on pixel values to get latent states', 'build_PaintByExampleMapper': 'build a PaintByExampleMapper with transformer blocks derived from a CLIP config', 'run_PaintByExampleMapper_forward': 'run the PaintByExampleMapper forward pass on hidden states through transformer blocks', 'review_PaintByExampleImageEncoder_uncond_vector': 'review the PaintByExampleImageEncoder uncond_vector parameter used for unconditional scaling'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/paint_by_example/pipeline_paint_by_example.py

Prompts

```
['build a PaintByExampleImageEncoder using a CLIP config and optional projection size', 'run the PaintByExampleImageEncoder forward pass on pixel values to get latent states', 'build a PaintByExampleMapper with transformer blocks derived from a CLIP config', 'run the PaintByExampleMapper forward pass on hidden states through transformer blocks', 'review the PaintByExampleImageEncoder uncond_vector parameter used for unconditional scaling', 'run the PaintByExamplePipeline to generate images guided by example images using inpainting', 'prepare a mask and masked image tensor pair for the Paint by Example pipeline', 'encode an example image using the PaintByExampleImageEncoder to get image embeddings', 'prepare mask latents by resizing and encoding masked images for the UNet input', 'run the safety checker on generated images to detect NSFW content']
```

Usage

```
{'run_paint_by_example_pipeline': 'run the PaintByExamplePipeline to generate images guided by example images using inpainting', 'prepare_mask_and_masked_image': 'prepare a mask and masked image tensor pair for the Paint by Example pipeline', 'encode_example_image': 'encode an example image using the PaintByExampleImageEncoder to get image embeddings', 'prepare_mask_latents': 'prepare mask latents by resizing and encoding masked images for the UNet input', 'run_safety_checker': 'run the safety checker on generated images to detect NSFW content'}
```

