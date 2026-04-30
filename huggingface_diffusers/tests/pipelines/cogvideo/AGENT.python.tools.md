# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/tests/pipelines/cogvideo/test_cogvideox.py

Prompts

```
['run the CogVideoXPipelineFastTests unittest class to test CogVideoX pipeline inference and features', 'run the CogVideoXPipelineIntegrationTests to perform slow integration tests with the THUDM/CogVideoX-2b model', 'test creating dummy transformer, VAE, scheduler, text encoder, and tokenizer components for CogVideoX', 'test generating dummy input parameters for CogVideoX pipeline inference with prompt and generator', 'test fusing and unfusing QKV projections in the CogVideoX transformer without affecting outputs', 'test the CogVideoXFunControlPipeline inference with dummy components and control video input', 'test the callback on step end tensor inputs for CogVideoXFunControlPipeline', 'test attention slicing forward pass with different slice sizes for CogVideoXFunControlPipeline', 'test VAE tiling with tile sample dimensions for CogVideoXFunControlPipeline inference', 'test fused QKV projections for CogVideoXFunControlPipeline transformer attention processors', 'run the CogVideoXImageToVideoPipeline to generate a video from an input image and text prompt', 'test the CogVideoXImageToVideoPipeline with dummy components for fast unit testing on CPU', 'test the callback_on_step_end functionality to inspect and modify tensors during inference steps', 'test fused QKV projections in the CogVideoX transformer to verify output consistency', 'test VAE tiling on the CogVideoX pipeline to verify output consistency with tiled decoding', 'test CogVideoXVideoToVideoPipeline inference by running the pipeline with dummy components and video inputs', 'test callback inputs for CogVideoXVideoToVideoPipeline by verifying callback_on_step_end tensor handling', 'test attention slicing forward pass for CogVideoXVideoToVideoPipeline with different slice sizes', 'test VAE tiling for CogVideoXVideoToVideoPipeline by comparing outputs with and without tiling enabled', 'test fused QKV projections for CogVideoXVideoToVideoPipeline by verifying fusion and unfusion produce matching outputs']
```

Usage

```
{'run_CogVideoXPipelineFastTests': 'run the CogVideoXPipelineFastTests unittest class to test CogVideoX pipeline inference and features', 'run_CogVideoXPipelineIntegrationTests': 'run the CogVideoXPipelineIntegrationTests to perform slow integration tests with the THUDM/CogVideoX-2b model', 'test_get_dummy_components': 'test creating dummy transformer, VAE, scheduler, text encoder, and tokenizer components for CogVideoX', 'test_get_dummy_inputs': 'test generating dummy input parameters for CogVideoX pipeline inference with prompt and generator', 'test_fused_qkv_projections': 'test fusing and unfusing QKV projections in the CogVideoX transformer without affecting outputs'}
```

## File: huggingface_diffusers/tests/pipelines/cogvideo/test_cogvideox_fun_control.py

Prompts

```
['run the CogVideoXPipelineFastTests unittest class to test CogVideoX pipeline inference and features', 'run the CogVideoXPipelineIntegrationTests to perform slow integration tests with the THUDM/CogVideoX-2b model', 'test creating dummy transformer, VAE, scheduler, text encoder, and tokenizer components for CogVideoX', 'test generating dummy input parameters for CogVideoX pipeline inference with prompt and generator', 'test fusing and unfusing QKV projections in the CogVideoX transformer without affecting outputs', 'test the CogVideoXFunControlPipeline inference with dummy components and control video input', 'test the callback on step end tensor inputs for CogVideoXFunControlPipeline', 'test attention slicing forward pass with different slice sizes for CogVideoXFunControlPipeline', 'test VAE tiling with tile sample dimensions for CogVideoXFunControlPipeline inference', 'test fused QKV projections for CogVideoXFunControlPipeline transformer attention processors', 'run the CogVideoXImageToVideoPipeline to generate a video from an input image and text prompt', 'test the CogVideoXImageToVideoPipeline with dummy components for fast unit testing on CPU', 'test the callback_on_step_end functionality to inspect and modify tensors during inference steps', 'test fused QKV projections in the CogVideoX transformer to verify output consistency', 'test VAE tiling on the CogVideoX pipeline to verify output consistency with tiled decoding', 'test CogVideoXVideoToVideoPipeline inference by running the pipeline with dummy components and video inputs', 'test callback inputs for CogVideoXVideoToVideoPipeline by verifying callback_on_step_end tensor handling', 'test attention slicing forward pass for CogVideoXVideoToVideoPipeline with different slice sizes', 'test VAE tiling for CogVideoXVideoToVideoPipeline by comparing outputs with and without tiling enabled', 'test fused QKV projections for CogVideoXVideoToVideoPipeline by verifying fusion and unfusion produce matching outputs']
```

Usage

```
{'test_cogvideox_fun_control_inference': 'test the CogVideoXFunControlPipeline inference with dummy components and control video input', 'test_cogvideox_fun_control_callback_inputs': 'test the callback on step end tensor inputs for CogVideoXFunControlPipeline', 'test_cogvideox_fun_control_attention_slicing': 'test attention slicing forward pass with different slice sizes for CogVideoXFunControlPipeline', 'test_cogvideox_fun_control_vae_tiling': 'test VAE tiling with tile sample dimensions for CogVideoXFunControlPipeline inference', 'test_cogvideox_fun_control_fused_qkv': 'test fused QKV projections for CogVideoXFunControlPipeline transformer attention processors'}
```

## File: huggingface_diffusers/tests/pipelines/cogvideo/test_cogvideox_image2video.py

Prompts

```
['run the CogVideoXPipelineFastTests unittest class to test CogVideoX pipeline inference and features', 'run the CogVideoXPipelineIntegrationTests to perform slow integration tests with the THUDM/CogVideoX-2b model', 'test creating dummy transformer, VAE, scheduler, text encoder, and tokenizer components for CogVideoX', 'test generating dummy input parameters for CogVideoX pipeline inference with prompt and generator', 'test fusing and unfusing QKV projections in the CogVideoX transformer without affecting outputs', 'test the CogVideoXFunControlPipeline inference with dummy components and control video input', 'test the callback on step end tensor inputs for CogVideoXFunControlPipeline', 'test attention slicing forward pass with different slice sizes for CogVideoXFunControlPipeline', 'test VAE tiling with tile sample dimensions for CogVideoXFunControlPipeline inference', 'test fused QKV projections for CogVideoXFunControlPipeline transformer attention processors', 'run the CogVideoXImageToVideoPipeline to generate a video from an input image and text prompt', 'test the CogVideoXImageToVideoPipeline with dummy components for fast unit testing on CPU', 'test the callback_on_step_end functionality to inspect and modify tensors during inference steps', 'test fused QKV projections in the CogVideoX transformer to verify output consistency', 'test VAE tiling on the CogVideoX pipeline to verify output consistency with tiled decoding', 'test CogVideoXVideoToVideoPipeline inference by running the pipeline with dummy components and video inputs', 'test callback inputs for CogVideoXVideoToVideoPipeline by verifying callback_on_step_end tensor handling', 'test attention slicing forward pass for CogVideoXVideoToVideoPipeline with different slice sizes', 'test VAE tiling for CogVideoXVideoToVideoPipeline by comparing outputs with and without tiling enabled', 'test fused QKV projections for CogVideoXVideoToVideoPipeline by verifying fusion and unfusion produce matching outputs']
```

Usage

```
{'run_cogvideox_i2v_inference': 'run the CogVideoXImageToVideoPipeline to generate a video from an input image and text prompt', 'test_cogvideox_i2v_fast': 'test the CogVideoXImageToVideoPipeline with dummy components for fast unit testing on CPU', 'test_cogvideox_i2v_callback': 'test the callback_on_step_end functionality to inspect and modify tensors during inference steps', 'test_cogvideox_i2v_qkv_fusion': 'test fused QKV projections in the CogVideoX transformer to verify output consistency', 'test_cogvideox_i2v_vae_tiling': 'test VAE tiling on the CogVideoX pipeline to verify output consistency with tiled decoding'}
```

## File: huggingface_diffusers/tests/pipelines/cogvideo/test_cogvideox_video2video.py

Prompts

```
['run the CogVideoXPipelineFastTests unittest class to test CogVideoX pipeline inference and features', 'run the CogVideoXPipelineIntegrationTests to perform slow integration tests with the THUDM/CogVideoX-2b model', 'test creating dummy transformer, VAE, scheduler, text encoder, and tokenizer components for CogVideoX', 'test generating dummy input parameters for CogVideoX pipeline inference with prompt and generator', 'test fusing and unfusing QKV projections in the CogVideoX transformer without affecting outputs', 'test the CogVideoXFunControlPipeline inference with dummy components and control video input', 'test the callback on step end tensor inputs for CogVideoXFunControlPipeline', 'test attention slicing forward pass with different slice sizes for CogVideoXFunControlPipeline', 'test VAE tiling with tile sample dimensions for CogVideoXFunControlPipeline inference', 'test fused QKV projections for CogVideoXFunControlPipeline transformer attention processors', 'run the CogVideoXImageToVideoPipeline to generate a video from an input image and text prompt', 'test the CogVideoXImageToVideoPipeline with dummy components for fast unit testing on CPU', 'test the callback_on_step_end functionality to inspect and modify tensors during inference steps', 'test fused QKV projections in the CogVideoX transformer to verify output consistency', 'test VAE tiling on the CogVideoX pipeline to verify output consistency with tiled decoding', 'test CogVideoXVideoToVideoPipeline inference by running the pipeline with dummy components and video inputs', 'test callback inputs for CogVideoXVideoToVideoPipeline by verifying callback_on_step_end tensor handling', 'test attention slicing forward pass for CogVideoXVideoToVideoPipeline with different slice sizes', 'test VAE tiling for CogVideoXVideoToVideoPipeline by comparing outputs with and without tiling enabled', 'test fused QKV projections for CogVideoXVideoToVideoPipeline by verifying fusion and unfusion produce matching outputs']
```

Usage

```
{'test_CogVideoXVideoToVideoPipeline_inference': 'test CogVideoXVideoToVideoPipeline inference by running the pipeline with dummy components and video inputs', 'test_CogVideoXVideoToVideoPipeline_callback_inputs': 'test callback inputs for CogVideoXVideoToVideoPipeline by verifying callback_on_step_end tensor handling', 'test_CogVideoXVideoToVideoPipeline_attention_slicing': 'test attention slicing forward pass for CogVideoXVideoToVideoPipeline with different slice sizes', 'test_CogVideoXVideoToVideoPipeline_vae_tiling': 'test VAE tiling for CogVideoXVideoToVideoPipeline by comparing outputs with and without tiling enabled', 'test_CogVideoXVideoToVideoPipeline_fused_qkv': 'test fused QKV projections for CogVideoXVideoToVideoPipeline by verifying fusion and unfusion produce matching outputs'}
```

