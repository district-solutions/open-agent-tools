# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/tests/pipelines/ltx/test_ltx.py

Prompts

```
['test the LTXPipeline inference by generating a video from a text prompt with dummy components', 'test the LTXPipeline callback inputs to verify callback_on_step_end tensor handling during inference', 'test the LTXPipeline attention slicing forward pass to verify slicing does not affect inference results', 'test the LTXPipeline VAE tiling to verify tiling does not significantly affect inference output', 'test the LTXPipeline batch inference to verify single and batch outputs are identical', 'test the LTXConditionPipeline inference with and without LTXVideoCondition conditions', 'test the LTXConditionPipeline callback_on_step_end tensor inputs handling', 'test the LTXConditionPipeline batch single identical inference with batch size 3', 'test the LTXConditionPipeline attention slicing forward pass with different slice sizes', 'test the LTXConditionPipeline VAE tiling with tile sample height and width', 'run the LTXImageToVideoPipeline inference test to generate a video from a dummy image and prompt', 'test the LTXImageToVideoPipeline callback inputs to verify step-end callbacks receive correct tensor arguments', 'test the LTXImageToVideoPipeline attention slicing forward pass to ensure slicing does not affect inference results', 'test the LTXImageToVideoPipeline VAE tiling to verify tiling does not affect inference results', 'test the LTXImageToVideoPipeline batch inference to verify single and batch outputs are identical', 'test the LTXLatentUpsamplePipeline inference by running dummy video through the pipeline and verifying output shape', 'test VAE tiling on LTXLatentUpsamplePipeline by comparing outputs with and without tiling enabled', 'create an AutoencoderKLLTXVideo component with configurable channels, blocks, and spatio-temporal scaling for LTX video', 'create an LTXLatentUpsamplerModel with configurable channels, blocks, and spatial or temporal upsampling', 'run the LTXLatentUpsamplePipelineFastTests suite to validate pipeline inference and VAE tiling behavior']
```

Usage

```
{'test_LTXPipeline_inference': 'test the LTXPipeline inference by generating a video from a text prompt with dummy components', 'test_LTXPipeline_callback_inputs': 'test the LTXPipeline callback inputs to verify callback_on_step_end tensor handling during inference', 'test_LTXPipeline_attention_slicing': 'test the LTXPipeline attention slicing forward pass to verify slicing does not affect inference results', 'test_LTXPipeline_vae_tiling': 'test the LTXPipeline VAE tiling to verify tiling does not significantly affect inference output', 'test_LTXPipeline_batch_inference': 'test the LTXPipeline batch inference to verify single and batch outputs are identical'}
```

## File: huggingface_diffusers/tests/pipelines/ltx/test_ltx_condition.py

Prompts

```
['test the LTXPipeline inference by generating a video from a text prompt with dummy components', 'test the LTXPipeline callback inputs to verify callback_on_step_end tensor handling during inference', 'test the LTXPipeline attention slicing forward pass to verify slicing does not affect inference results', 'test the LTXPipeline VAE tiling to verify tiling does not significantly affect inference output', 'test the LTXPipeline batch inference to verify single and batch outputs are identical', 'test the LTXConditionPipeline inference with and without LTXVideoCondition conditions', 'test the LTXConditionPipeline callback_on_step_end tensor inputs handling', 'test the LTXConditionPipeline batch single identical inference with batch size 3', 'test the LTXConditionPipeline attention slicing forward pass with different slice sizes', 'test the LTXConditionPipeline VAE tiling with tile sample height and width', 'run the LTXImageToVideoPipeline inference test to generate a video from a dummy image and prompt', 'test the LTXImageToVideoPipeline callback inputs to verify step-end callbacks receive correct tensor arguments', 'test the LTXImageToVideoPipeline attention slicing forward pass to ensure slicing does not affect inference results', 'test the LTXImageToVideoPipeline VAE tiling to verify tiling does not affect inference results', 'test the LTXImageToVideoPipeline batch inference to verify single and batch outputs are identical', 'test the LTXLatentUpsamplePipeline inference by running dummy video through the pipeline and verifying output shape', 'test VAE tiling on LTXLatentUpsamplePipeline by comparing outputs with and without tiling enabled', 'create an AutoencoderKLLTXVideo component with configurable channels, blocks, and spatio-temporal scaling for LTX video', 'create an LTXLatentUpsamplerModel with configurable channels, blocks, and spatial or temporal upsampling', 'run the LTXLatentUpsamplePipelineFastTests suite to validate pipeline inference and VAE tiling behavior']
```

Usage

```
{'test_LTXConditionPipeline_inference': 'test the LTXConditionPipeline inference with and without LTXVideoCondition conditions', 'test_LTXConditionPipeline_callback_inputs': 'test the LTXConditionPipeline callback_on_step_end tensor inputs handling', 'test_LTXConditionPipeline_batch_single_identical': 'test the LTXConditionPipeline batch single identical inference with batch size 3', 'test_LTXConditionPipeline_attention_slicing': 'test the LTXConditionPipeline attention slicing forward pass with different slice sizes', 'test_LTXConditionPipeline_vae_tiling': 'test the LTXConditionPipeline VAE tiling with tile sample height and width'}
```

## File: huggingface_diffusers/tests/pipelines/ltx/test_ltx_image2video.py

Prompts

```
['test the LTXPipeline inference by generating a video from a text prompt with dummy components', 'test the LTXPipeline callback inputs to verify callback_on_step_end tensor handling during inference', 'test the LTXPipeline attention slicing forward pass to verify slicing does not affect inference results', 'test the LTXPipeline VAE tiling to verify tiling does not significantly affect inference output', 'test the LTXPipeline batch inference to verify single and batch outputs are identical', 'test the LTXConditionPipeline inference with and without LTXVideoCondition conditions', 'test the LTXConditionPipeline callback_on_step_end tensor inputs handling', 'test the LTXConditionPipeline batch single identical inference with batch size 3', 'test the LTXConditionPipeline attention slicing forward pass with different slice sizes', 'test the LTXConditionPipeline VAE tiling with tile sample height and width', 'run the LTXImageToVideoPipeline inference test to generate a video from a dummy image and prompt', 'test the LTXImageToVideoPipeline callback inputs to verify step-end callbacks receive correct tensor arguments', 'test the LTXImageToVideoPipeline attention slicing forward pass to ensure slicing does not affect inference results', 'test the LTXImageToVideoPipeline VAE tiling to verify tiling does not affect inference results', 'test the LTXImageToVideoPipeline batch inference to verify single and batch outputs are identical', 'test the LTXLatentUpsamplePipeline inference by running dummy video through the pipeline and verifying output shape', 'test VAE tiling on LTXLatentUpsamplePipeline by comparing outputs with and without tiling enabled', 'create an AutoencoderKLLTXVideo component with configurable channels, blocks, and spatio-temporal scaling for LTX video', 'create an LTXLatentUpsamplerModel with configurable channels, blocks, and spatial or temporal upsampling', 'run the LTXLatentUpsamplePipelineFastTests suite to validate pipeline inference and VAE tiling behavior']
```

Usage

```
{'run_LTXImageToVideoPipeline_inference': 'run the LTXImageToVideoPipeline inference test to generate a video from a dummy image and prompt', 'test_LTXImageToVideoPipeline_callback_inputs': 'test the LTXImageToVideoPipeline callback inputs to verify step-end callbacks receive correct tensor arguments', 'test_LTXImageToVideoPipeline_attention_slicing': 'test the LTXImageToVideoPipeline attention slicing forward pass to ensure slicing does not affect inference results', 'test_LTXImageToVideoPipeline_vae_tiling': 'test the LTXImageToVideoPipeline VAE tiling to verify tiling does not affect inference results', 'test_LTXImageToVideoPipeline_batch_identical': 'test the LTXImageToVideoPipeline batch inference to verify single and batch outputs are identical'}
```

## File: huggingface_diffusers/tests/pipelines/ltx/test_ltx_latent_upsample.py

Prompts

```
['test the LTXPipeline inference by generating a video from a text prompt with dummy components', 'test the LTXPipeline callback inputs to verify callback_on_step_end tensor handling during inference', 'test the LTXPipeline attention slicing forward pass to verify slicing does not affect inference results', 'test the LTXPipeline VAE tiling to verify tiling does not significantly affect inference output', 'test the LTXPipeline batch inference to verify single and batch outputs are identical', 'test the LTXConditionPipeline inference with and without LTXVideoCondition conditions', 'test the LTXConditionPipeline callback_on_step_end tensor inputs handling', 'test the LTXConditionPipeline batch single identical inference with batch size 3', 'test the LTXConditionPipeline attention slicing forward pass with different slice sizes', 'test the LTXConditionPipeline VAE tiling with tile sample height and width', 'run the LTXImageToVideoPipeline inference test to generate a video from a dummy image and prompt', 'test the LTXImageToVideoPipeline callback inputs to verify step-end callbacks receive correct tensor arguments', 'test the LTXImageToVideoPipeline attention slicing forward pass to ensure slicing does not affect inference results', 'test the LTXImageToVideoPipeline VAE tiling to verify tiling does not affect inference results', 'test the LTXImageToVideoPipeline batch inference to verify single and batch outputs are identical', 'test the LTXLatentUpsamplePipeline inference by running dummy video through the pipeline and verifying output shape', 'test VAE tiling on LTXLatentUpsamplePipeline by comparing outputs with and without tiling enabled', 'create an AutoencoderKLLTXVideo component with configurable channels, blocks, and spatio-temporal scaling for LTX video', 'create an LTXLatentUpsamplerModel with configurable channels, blocks, and spatial or temporal upsampling', 'run the LTXLatentUpsamplePipelineFastTests suite to validate pipeline inference and VAE tiling behavior']
```

Usage

```
{'test_LTXLatentUpsamplePipeline_inference': 'test the LTXLatentUpsamplePipeline inference by running dummy video through the pipeline and verifying output shape', 'test_LTXLatentUpsamplePipeline_vae_tiling': 'test VAE tiling on LTXLatentUpsamplePipeline by comparing outputs with and without tiling enabled', 'create_AutoencoderKLLTXVideo_component': 'create an AutoencoderKLLTXVideo component with configurable channels, blocks, and spatio-temporal scaling for LTX video', 'create_LTXLatentUpsamplerModel_component': 'create an LTXLatentUpsamplerModel with configurable channels, blocks, and spatial or temporal upsampling', 'run_LTXLatentUpsamplePipeline_fast_tests': 'run the LTXLatentUpsamplePipelineFastTests suite to validate pipeline inference and VAE tiling behavior'}
```

