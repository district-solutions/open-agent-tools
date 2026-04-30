# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/src/diffusers/pipelines/audioldm2/modeling_audioldm2.py

Prompts

```
['build a conditional 2D UNet model for audio diffusion with dual cross-attention encoder hidden states', 'create a linear projection model that maps two text encoder embeddings into a shared latent space with SOS and EOS tokens', 'run a function that prepends SOS and appends EOS token embeddings to hidden state sequences and updates attention masks', 'review the cross-attention downsampling block that applies multiple Transformer2D attention layers with dual encoder hidden states', 'test the cross-attention upsampling block that concatenates skip connections and applies multiple Transformer2D attention layers', 'generate audio waveforms from a text prompt using the AudioLDM2Pipeline with classifier-free guidance', 'generate text-to-speech audio using AudioLDM2Pipeline with a transcription and prompt describing the speaker', 'encode a text prompt into text encoder hidden states using the CLAP and T5 encoders', 'score and rank generated audio waveforms against input text using the CLAP model similarity', 'offload all AudioLDM2 models to CPU using accelerate to reduce memory usage during inference']
```

Usage

```
{'build_AudioLDM2UNet2DConditionModel': 'build a conditional 2D UNet model for audio diffusion with dual cross-attention encoder hidden states', 'create_AudioLDM2ProjectionModel': 'create a linear projection model that maps two text encoder embeddings into a shared latent space with SOS and EOS tokens', 'run_add_special_tokens': 'run a function that prepends SOS and appends EOS token embeddings to hidden state sequences and updates attention masks', 'review_CrossAttnDownBlock2D': 'review the cross-attention downsampling block that applies multiple Transformer2D attention layers with dual encoder hidden states', 'test_CrossAttnUpBlock2D': 'test the cross-attention upsampling block that concatenates skip connections and applies multiple Transformer2D attention layers'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/audioldm2/pipeline_audioldm2.py

Prompts

```
['build a conditional 2D UNet model for audio diffusion with dual cross-attention encoder hidden states', 'create a linear projection model that maps two text encoder embeddings into a shared latent space with SOS and EOS tokens', 'run a function that prepends SOS and appends EOS token embeddings to hidden state sequences and updates attention masks', 'review the cross-attention downsampling block that applies multiple Transformer2D attention layers with dual encoder hidden states', 'test the cross-attention upsampling block that concatenates skip connections and applies multiple Transformer2D attention layers', 'generate audio waveforms from a text prompt using the AudioLDM2Pipeline with classifier-free guidance', 'generate text-to-speech audio using AudioLDM2Pipeline with a transcription and prompt describing the speaker', 'encode a text prompt into text encoder hidden states using the CLAP and T5 encoders', 'score and rank generated audio waveforms against input text using the CLAP model similarity', 'offload all AudioLDM2 models to CPU using accelerate to reduce memory usage during inference']
```

Usage

```
{'generate_audio_from_prompt': 'generate audio waveforms from a text prompt using the AudioLDM2Pipeline with classifier-free guidance', 'generate_tts_audio': 'generate text-to-speech audio using AudioLDM2Pipeline with a transcription and prompt describing the speaker', 'encode_prompt': 'encode a text prompt into text encoder hidden states using the CLAP and T5 encoders', 'score_waveforms': 'score and rank generated audio waveforms against input text using the CLAP model similarity', 'enable_model_cpu_offload': 'offload all AudioLDM2 models to CPU using accelerate to reduce memory usage during inference'}
```

