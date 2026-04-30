# Agent Python Tools

- repo: swivid/f5-tts
- repo_uri: https://github.com/swivid/f5-tts

## File: swivid_f5-tts/src/third_party/BigVGAN/tests/test_activation.py

Prompts

```
['test the fused CUDA kernel loading for BigVGAN anti-activation modules', 'test the fused vs pure PyTorch anti-alias activation outputs for numerical equivalence', 'create an Activation1d wrapper with Snake activation using fused CUDA kernels', 'create an Activation1d wrapper with Snake activation using pure PyTorch implementation', 'run the BigVGAN activation test suite to verify fused kernel correctness', 'create an Activation1d wrapper with SnakeBeta activation using fused CUDA kernels', 'create an Activation1d wrapper with SnakeBeta activation using pure PyTorch implementation', 'load the fused CUDA kernels from alias_free_activation.cuda before running activation tests', 'test the CUDA fused BigVGAN kernel against plain PyTorch inference using a checkpoint file', 'benchmark BigVGAN inference speed and VRAM usage comparing CUDA kernel vs plain PyTorch', 'generate a synthetic chirp soundwave with modulated frequency sweep at a given sampling rate', 'compute mel spectrogram from audio tensor using BigVGAN config parameters', 'load a BigVGAN checkpoint file and return its state dictionary for a given device']
```

Usage

```
{'test_load_fused_kernels': 'test the fused CUDA kernel loading for BigVGAN anti-activation modules', 'test_anti_alias_activation': 'test the fused vs pure PyTorch anti-alias activation outputs for numerical equivalence', 'create_Activation1d_fused': 'create an Activation1d wrapper with Snake activation using fused CUDA kernels', 'create_Activation1d_torch': 'create an Activation1d wrapper with Snake activation using pure PyTorch implementation', 'run_test_activation': 'run the BigVGAN activation test suite to verify fused kernel correctness'}
```

## File: swivid_f5-tts/src/third_party/BigVGAN/tests/test_activation_snake_beta.py

Prompts

```
['test the fused CUDA kernel loading for BigVGAN anti-activation modules', 'test the fused vs pure PyTorch anti-alias activation outputs for numerical equivalence', 'create an Activation1d wrapper with Snake activation using fused CUDA kernels', 'create an Activation1d wrapper with Snake activation using pure PyTorch implementation', 'run the BigVGAN activation test suite to verify fused kernel correctness', 'create an Activation1d wrapper with SnakeBeta activation using fused CUDA kernels', 'create an Activation1d wrapper with SnakeBeta activation using pure PyTorch implementation', 'load the fused CUDA kernels from alias_free_activation.cuda before running activation tests', 'test the CUDA fused BigVGAN kernel against plain PyTorch inference using a checkpoint file', 'benchmark BigVGAN inference speed and VRAM usage comparing CUDA kernel vs plain PyTorch', 'generate a synthetic chirp soundwave with modulated frequency sweep at a given sampling rate', 'compute mel spectrogram from audio tensor using BigVGAN config parameters', 'load a BigVGAN checkpoint file and return its state dictionary for a given device']
```

Usage

```
{'test_load_fused_kernels': 'test the fused CUDA kernel loading for BigVGAN anti-alias activation', 'test_anti_alias_activation': 'test the fused vs. pure PyTorch SnakeBeta activation outputs for numerical equivalence', 'create_activation1d_fused': 'create an Activation1d wrapper with SnakeBeta activation using fused CUDA kernels', 'create_activation1d_torch': 'create an Activation1d wrapper with SnakeBeta activation using pure PyTorch implementation', 'load_cuda_kernels': 'load the fused CUDA kernels from alias_free_activation.cuda before running activation tests'}
```

## File: swivid_f5-tts/src/third_party/BigVGAN/tests/test_cuda_vs_torch_model.py

Prompts

```
['test the fused CUDA kernel loading for BigVGAN anti-activation modules', 'test the fused vs pure PyTorch anti-alias activation outputs for numerical equivalence', 'create an Activation1d wrapper with Snake activation using fused CUDA kernels', 'create an Activation1d wrapper with Snake activation using pure PyTorch implementation', 'run the BigVGAN activation test suite to verify fused kernel correctness', 'create an Activation1d wrapper with SnakeBeta activation using fused CUDA kernels', 'create an Activation1d wrapper with SnakeBeta activation using pure PyTorch implementation', 'load the fused CUDA kernels from alias_free_activation.cuda before running activation tests', 'test the CUDA fused BigVGAN kernel against plain PyTorch inference using a checkpoint file', 'benchmark BigVGAN inference speed and VRAM usage comparing CUDA kernel vs plain PyTorch', 'generate a synthetic chirp soundwave with modulated frequency sweep at a given sampling rate', 'compute mel spectrogram from audio tensor using BigVGAN config parameters', 'load a BigVGAN checkpoint file and return its state dictionary for a given device']
```

Usage

```
{'test_cuda_kernel_correctness': 'test the CUDA fused BigVGAN kernel against plain PyTorch inference using a checkpoint file', 'benchmark_bigvgan_performance': 'benchmark BigVGAN inference speed and VRAM usage comparing CUDA kernel vs plain PyTorch', 'generate_soundwave_example': 'generate a synthetic chirp soundwave with modulated frequency sweep at a given sampling rate', 'compute_mel_spectrogram': 'compute mel spectrogram from audio tensor using BigVGAN config parameters', 'load_bigvgan_checkpoint': 'load a BigVGAN checkpoint file and return its state dictionary for a given device'}
```

