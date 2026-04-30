# Agent Python Tools

- repo: huggingface/optimum-habana
- repo_uri: https://github.com/huggingface/optimum-habana

## File: huggingface_optimum-habana/optimum/habana/diffusers/pipelines/text_to_video_synthesis/pipeline_text_to_video_synth.py

Prompts

```
['run the GaudiTextToVideoSDPipeline to generate a video from a text prompt on HPU', 'prepare initial noise latents for video synthesis with a given batch size and frame count', 'split latents and prompt embeddings into batches for HPU batched inference processing', 'capture and replay an HPU graph for cached UNet forward passes to accelerate inference', 'run the UNet3DConditionModel forward pass on HPU with optional HPU graph capture and replay']
```

Usage

```
{'run_text_to_video_generation': 'run the GaudiTextToVideoSDPipeline to generate a video from a text prompt on HPU', 'prepare_latents_for_video': 'prepare initial noise latents for video synthesis with a given batch size and frame count', 'split_inputs_into_batches': 'split latents and prompt embeddings into batches for HPU batched inference processing', 'capture_replay_hpu_graph': 'capture and replay an HPU graph for cached UNet forward passes to accelerate inference', 'run_unet_on_hpu': 'run the UNet3DConditionModel forward pass on HPU with optional HPU graph capture and replay'}
```

