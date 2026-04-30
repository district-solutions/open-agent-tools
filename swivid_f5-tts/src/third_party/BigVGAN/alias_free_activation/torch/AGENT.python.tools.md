# Agent Python Tools

- repo: swivid/f5-tts
- repo_uri: https://github.com/swivid/f5-tts

## File: swivid_f5-tts/src/third_party/BigVGAN/alias_free_activation/torch/act.py

Prompts

```
['create a 1D activation module that upsamples, applies an activation, and downsamples a tensor', 'build an Activation1d instance with custom up_ratio and up_kernel_size for alias-free activation', 'build an Activation1d instance with custom down_ratio and down_kernel_size for alias-free activation', 'test the Activation1d forward pass with a [B,C,T] input tensor through upsample-activate-downsample', 'review the Activation1d class that wraps an activation function with alias-free resampling', 'create a 1D Kaiser-windowed sinc low-pass filter tensor with given cutoff, half_width, and kernel_size', 'build a PyTorch nn.Module 1D low-pass filter that applies convolution with Kaiser-sinc filter and configurable stride and padding', 'test the sinc function that computes sin(pi*x)/(pi*x) with a fallback for PyTorch versions without torch.sinc', 'review the forward pass of LowPassFilter1d that pads input and runs grouped 1D convolution with the registered filter', 'summarize how cutoff, half_width, and kernel_size parameters shape the Kaiser-windowed sinc filter in kaiser_sinc_filter1d', 'create a 1D upsampling module that applies low-pass filtering and transposed convolution with configurable ratio and kernel size', 'build an UpSample1d instance and forward a [B,C,T] tensor through it to upsample by the configured ratio', 'create a 1D downsampling module that applies low-pass filtering before downsampling with configurable ratio and kernel size', 'build a DownSample1d instance and forward a [B,C,T] tensor through it to downsample by the configured ratio', 'review the UpSample1d and DownSample1d classes that perform alias-free 1D resampling for BigVGAN']
```

Usage

```
{'create_Activation1d': 'create a 1D activation module that upsamples, applies an activation, and downsamples a tensor', 'build_Activation1d_upsample': 'build an Activation1d instance with custom up_ratio and up_kernel_size for alias-free activation', 'build_Activation1d_downsample': 'build an Activation1d instance with custom down_ratio and down_kernel_size for alias-free activation', 'test_Activation1d_forward': 'test the Activation1d forward pass with a [B,C,T] input tensor through upsample-activate-downsample', 'review_Activation1d': 'review the Activation1d class that wraps an activation function with alias-free resampling'}
```

## File: swivid_f5-tts/src/third_party/BigVGAN/alias_free_activation/torch/filter.py

Prompts

```
['create a 1D activation module that upsamples, applies an activation, and downsamples a tensor', 'build an Activation1d instance with custom up_ratio and up_kernel_size for alias-free activation', 'build an Activation1d instance with custom down_ratio and down_kernel_size for alias-free activation', 'test the Activation1d forward pass with a [B,C,T] input tensor through upsample-activate-downsample', 'review the Activation1d class that wraps an activation function with alias-free resampling', 'create a 1D Kaiser-windowed sinc low-pass filter tensor with given cutoff, half_width, and kernel_size', 'build a PyTorch nn.Module 1D low-pass filter that applies convolution with Kaiser-sinc filter and configurable stride and padding', 'test the sinc function that computes sin(pi*x)/(pi*x) with a fallback for PyTorch versions without torch.sinc', 'review the forward pass of LowPassFilter1d that pads input and runs grouped 1D convolution with the registered filter', 'summarize how cutoff, half_width, and kernel_size parameters shape the Kaiser-windowed sinc filter in kaiser_sinc_filter1d', 'create a 1D upsampling module that applies low-pass filtering and transposed convolution with configurable ratio and kernel size', 'build an UpSample1d instance and forward a [B,C,T] tensor through it to upsample by the configured ratio', 'create a 1D downsampling module that applies low-pass filtering before downsampling with configurable ratio and kernel size', 'build a DownSample1d instance and forward a [B,C,T] tensor through it to downsample by the configured ratio', 'review the UpSample1d and DownSample1d classes that perform alias-free 1D resampling for BigVGAN']
```

Usage

```
{'create_filter_kaiser_sinc_1d': 'create a 1D Kaiser-windowed sinc low-pass filter tensor with given cutoff, half_width, and kernel_size', 'build_low_pass_filter_1d_module': 'build a PyTorch nn.Module 1D low-pass filter that applies convolution with Kaiser-sinc filter and configurable stride and padding', 'test_sinc_function': 'test the sinc function that computes sin(pi*x)/(pi*x) with a fallback for PyTorch versions without torch.sinc', 'review_low_pass_filter_1d_forward': 'review the forward pass of LowPassFilter1d that pads input and runs grouped 1D convolution with the registered filter', 'summarize_kaiser_sinc_filter_parameters': 'summarize how cutoff, half_width, and kernel_size parameters shape the Kaiser-windowed sinc filter in kaiser_sinc_filter1d'}
```

## File: swivid_f5-tts/src/third_party/BigVGAN/alias_free_activation/torch/resample.py

Prompts

```
['create a 1D activation module that upsamples, applies an activation, and downsamples a tensor', 'build an Activation1d instance with custom up_ratio and up_kernel_size for alias-free activation', 'build an Activation1d instance with custom down_ratio and down_kernel_size for alias-free activation', 'test the Activation1d forward pass with a [B,C,T] input tensor through upsample-activate-downsample', 'review the Activation1d class that wraps an activation function with alias-free resampling', 'create a 1D Kaiser-windowed sinc low-pass filter tensor with given cutoff, half_width, and kernel_size', 'build a PyTorch nn.Module 1D low-pass filter that applies convolution with Kaiser-sinc filter and configurable stride and padding', 'test the sinc function that computes sin(pi*x)/(pi*x) with a fallback for PyTorch versions without torch.sinc', 'review the forward pass of LowPassFilter1d that pads input and runs grouped 1D convolution with the registered filter', 'summarize how cutoff, half_width, and kernel_size parameters shape the Kaiser-windowed sinc filter in kaiser_sinc_filter1d', 'create a 1D upsampling module that applies low-pass filtering and transposed convolution with configurable ratio and kernel size', 'build an UpSample1d instance and forward a [B,C,T] tensor through it to upsample by the configured ratio', 'create a 1D downsampling module that applies low-pass filtering before downsampling with configurable ratio and kernel size', 'build a DownSample1d instance and forward a [B,C,T] tensor through it to downsample by the configured ratio', 'review the UpSample1d and DownSample1d classes that perform alias-free 1D resampling for BigVGAN']
```

Usage

```
{'create_UpSample1d': 'create a 1D upsampling module that applies low-pass filtering and transposed convolution with configurable ratio and kernel size', 'build_UpSample1d_forward': 'build an UpSample1d instance and forward a [B,C,T] tensor through it to upsample by the configured ratio', 'create_DownSample1d': 'create a 1D downsampling module that applies low-pass filtering before downsampling with configurable ratio and kernel size', 'build_DownSample1d_forward': 'build a DownSample1d instance and forward a [B,C,T] tensor through it to downsample by the configured ratio', 'review_UpSample1d_DownSample1d': 'review the UpSample1d and DownSample1d classes that perform alias-free 1D resampling for BigVGAN'}
```

