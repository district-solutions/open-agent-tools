# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/tests/pipelines/ltx2/test_ltx2.py

Prompts

```
['test the LTX2Pipeline inference to generate video and audio from a text prompt', 'test the LTX2Pipeline two-stage inference using latent outputs as inputs for the second stage', 'test the LTX2Pipeline batch inference with identical prompts to verify consistent output', 'review the LTX2PipelineFastTests get_dummy_components method that creates transformer, VAE, audio VAE, vocoder, and connectors', 'review the LTX2PipelineFastTests get_dummy_inputs method that creates prompt, generator, and inference parameters', 'test the LTX2ImageToVideoPipeline by running single stage image to video inference with dummy components', 'test the LTX2ImageToVideoPipeline two stage inference by generating latents then decoding to video and audio', 'test the LTX2ImageToVideoPipeline two stage inference with latent upsampling to produce higher resolution video', 'create dummy components for LTX2ImageToVideoPipeline including transformer, VAE, audio VAE, vocoder, connectors and scheduler', 'create dummy input tensors and parameters for running the LTX2ImageToVideoPipeline on a given device']
```

Usage

```
{'test_LTX2Pipeline_inference': 'test the LTX2Pipeline inference to generate video and audio from a text prompt', 'test_LTX2Pipeline_two_stages': 'test the LTX2Pipeline two-stage inference using latent outputs as inputs for the second stage', 'test_LTX2Pipeline_batch_inference': 'test the LTX2Pipeline batch inference with identical prompts to verify consistent output', 'review_LTX2PipelineFastTests_get_dummy_components': 'review the LTX2PipelineFastTests get_dummy_components method that creates transformer, VAE, audio VAE, vocoder, and connectors', 'review_LTX2PipelineFastTests_get_dummy_inputs': 'review the LTX2PipelineFastTests get_dummy_inputs method that creates prompt, generator, and inference parameters'}
```

## File: huggingface_diffusers/tests/pipelines/ltx2/test_ltx2_image2video.py

Prompts

```
['test the LTX2Pipeline inference to generate video and audio from a text prompt', 'test the LTX2Pipeline two-stage inference using latent outputs as inputs for the second stage', 'test the LTX2Pipeline batch inference with identical prompts to verify consistent output', 'review the LTX2PipelineFastTests get_dummy_components method that creates transformer, VAE, audio VAE, vocoder, and connectors', 'review the LTX2PipelineFastTests get_dummy_inputs method that creates prompt, generator, and inference parameters', 'test the LTX2ImageToVideoPipeline by running single stage image to video inference with dummy components', 'test the LTX2ImageToVideoPipeline two stage inference by generating latents then decoding to video and audio', 'test the LTX2ImageToVideoPipeline two stage inference with latent upsampling to produce higher resolution video', 'create dummy components for LTX2ImageToVideoPipeline including transformer, VAE, audio VAE, vocoder, connectors and scheduler', 'create dummy input tensors and parameters for running the LTX2ImageToVideoPipeline on a given device']
```

Usage

```
{'test_LTX2ImageToVideoPipeline_inference': 'test the LTX2ImageToVideoPipeline by running single stage image to video inference with dummy components', 'test_LTX2ImageToVideoPipeline_two_stages': 'test the LTX2ImageToVideoPipeline two stage inference by generating latents then decoding to video and audio', 'test_LTX2ImageToVideoPipeline_upsampler': 'test the LTX2ImageToVideoPipeline two stage inference with latent upsampling to produce higher resolution video', 'create_get_dummy_components': 'create dummy components for LTX2ImageToVideoPipeline including transformer, VAE, audio VAE, vocoder, connectors and scheduler', 'create_get_dummy_inputs': 'create dummy input tensors and parameters for running the LTX2ImageToVideoPipeline on a given device'}
```

