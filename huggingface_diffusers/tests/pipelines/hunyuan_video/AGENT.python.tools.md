# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/tests/pipelines/hunyuan_video/test_hunyuan_image2video.py

Prompts

```
['run the HunyuanVideoImageToVideoPipeline inference test with dummy components and verify output shape and values', 'test the callback_on_step_end mechanism to verify tensor inputs are passed correctly during inference', 'test attention slicing forward pass to verify slicing does not affect inference results', 'test VAE tiling to verify tiled decoding produces results close to non-tiled decoding', 'create dummy transformer, VAE, scheduler, text encoders, tokenizers, and image processor for testing the pipeline', 'test the HunyuanSkyreelsImageToVideoPipeline inference by generating a video from a prompt and image', 'test the callback on step end functionality for the HunyuanSkyreels image to video pipeline', 'test attention slicing forward pass for the HunyuanSkyreels image to video pipeline', 'create dummy components including transformer, VAE, scheduler, and text encoders for HunyuanSkyreels pipeline testing', 'test the HunyuanVideoPipeline inference by generating a video from a text prompt and verifying output shape and values', 'run the HunyuanVideoFramepackPipeline inference test with dummy components and a prompt', 'test float16 inference with higher tolerance for numerical differences']
```

Usage

```
{'run_pipeline_inference_test': 'run the HunyuanVideoImageToVideoPipeline inference test with dummy components and verify output shape and values', 'test_callback_inputs': 'test the callback_on_step_end mechanism to verify tensor inputs are passed correctly during inference', 'test_attention_slicing': 'test attention slicing forward pass to verify slicing does not affect inference results', 'test_vae_tiling': 'test VAE tiling to verify tiled decoding produces results close to non-tiled decoding', 'get_dummy_components': 'create dummy transformer, VAE, scheduler, text encoders, tokenizers, and image processor for testing the pipeline'}
```

## File: huggingface_diffusers/tests/pipelines/hunyuan_video/test_hunyuan_skyreels_image2video.py

Prompts

```
['run the HunyuanVideoImageToVideoPipeline inference test with dummy components and verify output shape and values', 'test the callback_on_step_end mechanism to verify tensor inputs are passed correctly during inference', 'test attention slicing forward pass to verify slicing does not affect inference results', 'test VAE tiling to verify tiled decoding produces results close to non-tiled decoding', 'create dummy transformer, VAE, scheduler, text encoders, tokenizers, and image processor for testing the pipeline', 'test the HunyuanSkyreelsImageToVideoPipeline inference by generating a video from a prompt and image', 'test the callback on step end functionality for the HunyuanSkyreels image to video pipeline', 'test attention slicing forward pass for the HunyuanSkyreels image to video pipeline', 'create dummy components including transformer, VAE, scheduler, and text encoders for HunyuanSkyreels pipeline testing', 'test the HunyuanVideoPipeline inference by generating a video from a text prompt and verifying output shape and values', 'run the HunyuanVideoFramepackPipeline inference test with dummy components and a prompt', 'test float16 inference with higher tolerance for numerical differences']
```

Usage

```
{'test_hunyuan_skyreels_image2video_inference': 'test the HunyuanSkyreelsImageToVideoPipeline inference by generating a video from a prompt and image', 'test_callback_on_step_end': 'test the callback on step end functionality for the HunyuanSkyreels image to video pipeline', 'test_attention_slicing_forward_pass': 'test attention slicing forward pass for the HunyuanSkyreels image to video pipeline', 'test_vae_tiling': 'test VAE tiling for the HunyuanSkyreels image to video pipeline with custom tile sizes', 'get_dummy_components_hunyuan_skyreels': 'create dummy components including transformer, VAE, scheduler, and text encoders for HunyuanSkyreels pipeline testing'}
```

## File: huggingface_diffusers/tests/pipelines/hunyuan_video/test_hunyuan_video.py

Prompts

```
['run the HunyuanVideoImageToVideoPipeline inference test with dummy components and verify output shape and values', 'test the callback_on_step_end mechanism to verify tensor inputs are passed correctly during inference', 'test attention slicing forward pass to verify slicing does not affect inference results', 'test VAE tiling to verify tiled decoding produces results close to non-tiled decoding', 'create dummy transformer, VAE, scheduler, text encoders, tokenizers, and image processor for testing the pipeline', 'test the HunyuanSkyreelsImageToVideoPipeline inference by generating a video from a prompt and image', 'test the callback on step end functionality for the HunyuanSkyreels image to video pipeline', 'test attention slicing forward pass for the HunyuanSkyreels image to video pipeline', 'create dummy components including transformer, VAE, scheduler, and text encoders for HunyuanSkyreels pipeline testing', 'test the HunyuanVideoPipeline inference by generating a video from a text prompt and verifying output shape and values', 'run the HunyuanVideoFramepackPipeline inference test with dummy components and a prompt', 'test float16 inference with higher tolerance for numerical differences']
```

Usage

```
{'test_hunyuan_video_pipeline_inference': 'test the HunyuanVideoPipeline inference by generating a video from a text prompt and verifying output shape and values', 'test_callback_inputs': 'test the callback_on_step_end functionality to verify tensor inputs are passed correctly during pipeline inference steps', 'test_attention_slicing': 'test attention slicing forward pass to verify slicing does not significantly affect inference results', 'test_vae_tiling': 'test VAE tiling to verify tiled decoding produces results close to non-tiled decoding', 'get_dummy_components': 'create dummy HunyuanVideo pipeline components including transformer, VAE, scheduler, and text encoders for testing'}
```

## File: huggingface_diffusers/tests/pipelines/hunyuan_video/test_hunyuan_video_framepack.py

Prompts

```
['run the HunyuanVideoImageToVideoPipeline inference test with dummy components and verify output shape and values', 'test the callback_on_step_end mechanism to verify tensor inputs are passed correctly during inference', 'test attention slicing forward pass to verify slicing does not affect inference results', 'test VAE tiling to verify tiled decoding produces results close to non-tiled decoding', 'create dummy transformer, VAE, scheduler, text encoders, tokenizers, and image processor for testing the pipeline', 'test the HunyuanSkyreelsImageToVideoPipeline inference by generating a video from a prompt and image', 'test the callback on step end functionality for the HunyuanSkyreels image to video pipeline', 'test attention slicing forward pass for the HunyuanSkyreels image to video pipeline', 'create dummy components including transformer, VAE, scheduler, and text encoders for HunyuanSkyreels pipeline testing', 'test the HunyuanVideoPipeline inference by generating a video from a text prompt and verifying output shape and values', 'run the HunyuanVideoFramepackPipeline inference test with dummy components and a prompt', 'test float16 inference with higher tolerance for numerical differences']
```

Usage

```
{'run_pipeline_inference': 'run the HunyuanVideoFramepackPipeline inference test with dummy components and a prompt', 'test_callback_inputs': 'test the callback on step end functionality for tensor inputs during pipeline execution', 'test_attention_slicing': 'test attention slicing forward pass with different slice sizes for memory optimization', 'test_vae_tiling': 'test VAE tiling to verify it does not significantly affect inference results', 'test_float16_inference': 'test float16 inference with higher tolerance for numerical differences'}
```

