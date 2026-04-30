# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/multimodal_gen/configs/sample/ltx_2.py

Prompts

```
['create LTX2SamplingParams with video dimensions, frame count, fps, and denoising parameters', 'create LTX23SamplingParams with video and audio modality scales, CFG, STG, and rescale parameters', 'build request extra dict from LTX23SamplingParams with ltx2_stage1_guider_params for video and audio', 'test LTX2SamplingParams default values for seed, height, width, num_frames, fps, and guidance_scale', 'review LTX23SamplingParams inheriting from LTX2SamplingParams and overriding generator_device, guidance_scale, and num_inference_steps', 'build sampling parameters from user CLI arguments and server args for multimodal generation', 'create sampling parameters from a pretrained model path with optional backend and model id', 'add sampling parameter CLI arguments to an argparse parser for multimodal generation', 'get sampling parameter values from a parsed argparse namespace matching SamplingParams fields', 'adjust sampling parameters against server args for GPU frame splitting and resolution validation', 'create a TeaCacheParams instance with custom teacache threshold and skipping boundaries', 'test the get_coefficients method returns polynomial coefficients or callback result', 'test the get_skip_boundaries method resolves start and end skipping boundaries with CFG scaling', 'build a TeaCacheParams instance with a coefficients_callback for dynamic coefficient selection', 'review the TeaCacheParams dataclass and its skip boundary resolution logic']
```

Usage

```
{'create_LTX2SamplingParams': 'create LTX2SamplingParams with video dimensions, frame count, fps, and denoising parameters', 'create_LTX23SamplingParams': 'create LTX23SamplingParams with video and audio modality scales, CFG, STG, and rescale parameters', 'build_request_extra': 'build request extra dict from LTX23SamplingParams with ltx2_stage1_guider_params for video and audio', 'test_LTX2SamplingParams_defaults': 'test LTX2SamplingParams default values for seed, height, width, num_frames, fps, and guidance_scale', 'review_LTX23SamplingParams_inheritance': 'review LTX23SamplingParams inheriting from LTX2SamplingParams and overriding generator_device, guidance_scale, and num_inference_steps'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/configs/sample/sampling_params.py

Prompts

```
['create LTX2SamplingParams with video dimensions, frame count, fps, and denoising parameters', 'create LTX23SamplingParams with video and audio modality scales, CFG, STG, and rescale parameters', 'build request extra dict from LTX23SamplingParams with ltx2_stage1_guider_params for video and audio', 'test LTX2SamplingParams default values for seed, height, width, num_frames, fps, and guidance_scale', 'review LTX23SamplingParams inheriting from LTX2SamplingParams and overriding generator_device, guidance_scale, and num_inference_steps', 'build sampling parameters from user CLI arguments and server args for multimodal generation', 'create sampling parameters from a pretrained model path with optional backend and model id', 'add sampling parameter CLI arguments to an argparse parser for multimodal generation', 'get sampling parameter values from a parsed argparse namespace matching SamplingParams fields', 'adjust sampling parameters against server args for GPU frame splitting and resolution validation', 'create a TeaCacheParams instance with custom teacache threshold and skipping boundaries', 'test the get_coefficients method returns polynomial coefficients or callback result', 'test the get_skip_boundaries method resolves start and end skipping boundaries with CFG scaling', 'build a TeaCacheParams instance with a coefficients_callback for dynamic coefficient selection', 'review the TeaCacheParams dataclass and its skip boundary resolution logic']
```

Usage

```
{'build_sampling_params_from_cli': 'build sampling parameters from user CLI arguments and server args for multimodal generation', 'create_sampling_params_from_pretrained': 'create sampling parameters from a pretrained model path with optional backend and model id', 'add_cli_args_to_parser': 'add sampling parameter CLI arguments to an argparse parser for multimodal generation', 'get_cli_args_from_namespace': 'get sampling parameter values from a parsed argparse namespace matching SamplingParams fields', 'adjust_sampling_params_for_server': 'adjust sampling parameters against server args for GPU frame splitting and resolution validation'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/configs/sample/teacache.py

Prompts

```
['create LTX2SamplingParams with video dimensions, frame count, fps, and denoising parameters', 'create LTX23SamplingParams with video and audio modality scales, CFG, STG, and rescale parameters', 'build request extra dict from LTX23SamplingParams with ltx2_stage1_guider_params for video and audio', 'test LTX2SamplingParams default values for seed, height, width, num_frames, fps, and guidance_scale', 'review LTX23SamplingParams inheriting from LTX2SamplingParams and overriding generator_device, guidance_scale, and num_inference_steps', 'build sampling parameters from user CLI arguments and server args for multimodal generation', 'create sampling parameters from a pretrained model path with optional backend and model id', 'add sampling parameter CLI arguments to an argparse parser for multimodal generation', 'get sampling parameter values from a parsed argparse namespace matching SamplingParams fields', 'adjust sampling parameters against server args for GPU frame splitting and resolution validation', 'create a TeaCacheParams instance with custom teacache threshold and skipping boundaries', 'test the get_coefficients method returns polynomial coefficients or callback result', 'test the get_skip_boundaries method resolves start and end skipping boundaries with CFG scaling', 'build a TeaCacheParams instance with a coefficients_callback for dynamic coefficient selection', 'review the TeaCacheParams dataclass and its skip boundary resolution logic']
```

Usage

```
{'create_TeaCacheParams': 'create a TeaCacheParams instance with custom teacache threshold and skipping boundaries', 'test_get_coefficients': 'test the get_coefficients method returns polynomial coefficients or callback result', 'test_get_skip_boundaries': 'test the get_skip_boundaries method resolves start and end skipping boundaries with CFG scaling', 'build_TeaCacheParams_with_callback': 'build a TeaCacheParams instance with a coefficients_callback for dynamic coefficient selection', 'review_TeaCacheParams': 'review the TeaCacheParams dataclass and its skip boundary resolution logic'}
```

