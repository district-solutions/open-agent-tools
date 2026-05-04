# Agent Python Tools

- repo: facebookresearch/audiocraft
- repo_uri: https://github.com/facebookresearch/audiocraft.git

## File: facebookresearch_audiocraft/audiocraft/adversarial/discriminators/base.py

Prompts

```
['review the python MultiDiscriminator abstract base class for multi-scale discriminator implementations', 'implement the abstract forward method of MultiDiscriminator to return logits and feature maps', 'implement the abstract num_discriminators property to return the count of sub-discriminators', 'use the FeatureMapType type alias to annotate a list of torch tensors for feature maps', 'use the MultiDiscriminatorOutputType type alias to annotate the tuple of logits and feature maps', 'build a PeriodDiscriminator with a custom period to discriminate audio signals at that period', 'build a MultiPeriodDiscriminator with periods [2,3,5,7,11] for multi-scale audio discrimination', 'run the PeriodDiscriminator forward pass on a 1D audio tensor to get logits and feature maps', 'run the MultiPeriodDiscriminator forward pass on audio to get logits and feature maps from all sub-discriminators', 'review the MultiPeriodDiscriminator num_discriminators property to check how many sub-discriminators are configured', 'build a MultiScaleDiscriminator with weight_norm for audio GAN adversarial training', 'build a ScaleDiscriminator waveform sub-discriminator with custom kernel sizes and filters', 'run the MultiScaleDiscriminator forward pass on a waveform tensor to get logits and feature maps', 'run the ScaleDiscriminator forward pass on a waveform tensor to get logits and feature maps', 'review the MultiScaleDiscriminator architecture with multiple ScaleDiscriminator sub-discriminators and AvgPool1d downsampling', 'build a MultiScaleSTFTDiscriminator with custom FFT sizes and hop lengths for audio GAN training', 'create a DiscriminatorSTFT module with configurable filters, kernel size, and dilation for spectrogram discrimination', 'run forward pass of DiscriminatorSTFT on audio tensor to get logits and feature maps', 'review the MultiScaleSTFTDiscriminator class to understand how multiple STFT scales are combined', 'refactor the get_2d_padding function to compute convolution padding for arbitrary kernel and dilation tuples']
```

Usage

```
{'review_MultiDiscriminator_base_class': 'review the python MultiDiscriminator abstract base class for multi-scale discriminator implementations', 'implement_MultiDiscriminator_forward': 'implement the abstract forward method of MultiDiscriminator to return logits and feature maps', 'implement_MultiDiscriminator_num_discriminators': 'implement the abstract num_discriminators property to return the count of sub-discriminators', 'use_FeatureMapType_alias': 'use the FeatureMapType type alias to annotate a list of torch tensors for feature maps', 'use_MultiDiscriminatorOutputType_alias': 'use the MultiDiscriminatorOutputType type alias to annotate the tuple of logits and feature maps'}
```

## File: facebookresearch_audiocraft/audiocraft/adversarial/discriminators/mpd.py

Prompts

```
['review the python MultiDiscriminator abstract base class for multi-scale discriminator implementations', 'implement the abstract forward method of MultiDiscriminator to return logits and feature maps', 'implement the abstract num_discriminators property to return the count of sub-discriminators', 'use the FeatureMapType type alias to annotate a list of torch tensors for feature maps', 'use the MultiDiscriminatorOutputType type alias to annotate the tuple of logits and feature maps', 'build a PeriodDiscriminator with a custom period to discriminate audio signals at that period', 'build a MultiPeriodDiscriminator with periods [2,3,5,7,11] for multi-scale audio discrimination', 'run the PeriodDiscriminator forward pass on a 1D audio tensor to get logits and feature maps', 'run the MultiPeriodDiscriminator forward pass on audio to get logits and feature maps from all sub-discriminators', 'review the MultiPeriodDiscriminator num_discriminators property to check how many sub-discriminators are configured', 'build a MultiScaleDiscriminator with weight_norm for audio GAN adversarial training', 'build a ScaleDiscriminator waveform sub-discriminator with custom kernel sizes and filters', 'run the MultiScaleDiscriminator forward pass on a waveform tensor to get logits and feature maps', 'run the ScaleDiscriminator forward pass on a waveform tensor to get logits and feature maps', 'review the MultiScaleDiscriminator architecture with multiple ScaleDiscriminator sub-discriminators and AvgPool1d downsampling', 'build a MultiScaleSTFTDiscriminator with custom FFT sizes and hop lengths for audio GAN training', 'create a DiscriminatorSTFT module with configurable filters, kernel size, and dilation for spectrogram discrimination', 'run forward pass of DiscriminatorSTFT on audio tensor to get logits and feature maps', 'review the MultiScaleSTFTDiscriminator class to understand how multiple STFT scales are combined', 'refactor the get_2d_padding function to compute convolution padding for arbitrary kernel and dilation tuples']
```

Usage

```
{'build_period_discriminator': 'build a PeriodDiscriminator with a custom period to discriminate audio signals at that period', 'build_multiperiod_discriminator': 'build a MultiPeriodDiscriminator with periods [2,3,5,7,11] for multi-scale audio discrimination', 'run_period_discriminator_forward': 'run the PeriodDiscriminator forward pass on a 1D audio tensor to get logits and feature maps', 'run_multiperiod_discriminator_forward': 'run the MultiPeriodDiscriminator forward pass on audio to get logits and feature maps from all sub-discriminators', 'review_multiperiod_discriminator_num_discriminators': 'review the MultiPeriodDiscriminator num_discriminators property to check how many sub-discriminators are configured'}
```

## File: facebookresearch_audiocraft/audiocraft/adversarial/discriminators/msd.py

Prompts

```
['review the python MultiDiscriminator abstract base class for multi-scale discriminator implementations', 'implement the abstract forward method of MultiDiscriminator to return logits and feature maps', 'implement the abstract num_discriminators property to return the count of sub-discriminators', 'use the FeatureMapType type alias to annotate a list of torch tensors for feature maps', 'use the MultiDiscriminatorOutputType type alias to annotate the tuple of logits and feature maps', 'build a PeriodDiscriminator with a custom period to discriminate audio signals at that period', 'build a MultiPeriodDiscriminator with periods [2,3,5,7,11] for multi-scale audio discrimination', 'run the PeriodDiscriminator forward pass on a 1D audio tensor to get logits and feature maps', 'run the MultiPeriodDiscriminator forward pass on audio to get logits and feature maps from all sub-discriminators', 'review the MultiPeriodDiscriminator num_discriminators property to check how many sub-discriminators are configured', 'build a MultiScaleDiscriminator with weight_norm for audio GAN adversarial training', 'build a ScaleDiscriminator waveform sub-discriminator with custom kernel sizes and filters', 'run the MultiScaleDiscriminator forward pass on a waveform tensor to get logits and feature maps', 'run the ScaleDiscriminator forward pass on a waveform tensor to get logits and feature maps', 'review the MultiScaleDiscriminator architecture with multiple ScaleDiscriminator sub-discriminators and AvgPool1d downsampling', 'build a MultiScaleSTFTDiscriminator with custom FFT sizes and hop lengths for audio GAN training', 'create a DiscriminatorSTFT module with configurable filters, kernel size, and dilation for spectrogram discrimination', 'run forward pass of DiscriminatorSTFT on audio tensor to get logits and feature maps', 'review the MultiScaleSTFTDiscriminator class to understand how multiple STFT scales are combined', 'refactor the get_2d_padding function to compute convolution padding for arbitrary kernel and dilation tuples']
```

Usage

```
{'build_multiscale_discriminator': 'build a MultiScaleDiscriminator with weight_norm for audio GAN adversarial training', 'build_scale_discriminator': 'build a ScaleDiscriminator waveform sub-discriminator with custom kernel sizes and filters', 'run_multiscale_discriminator_forward': 'run the MultiScaleDiscriminator forward pass on a waveform tensor to get logits and feature maps', 'run_scale_discriminator_forward': 'run the ScaleDiscriminator forward pass on a waveform tensor to get logits and feature maps', 'review_multiscale_discriminator_architecture': 'review the MultiScaleDiscriminator architecture with multiple ScaleDiscriminator sub-discriminators and AvgPool1d downsampling'}
```

## File: facebookresearch_audiocraft/audiocraft/adversarial/discriminators/msstftd.py

Prompts

```
['review the python MultiDiscriminator abstract base class for multi-scale discriminator implementations', 'implement the abstract forward method of MultiDiscriminator to return logits and feature maps', 'implement the abstract num_discriminators property to return the count of sub-discriminators', 'use the FeatureMapType type alias to annotate a list of torch tensors for feature maps', 'use the MultiDiscriminatorOutputType type alias to annotate the tuple of logits and feature maps', 'build a PeriodDiscriminator with a custom period to discriminate audio signals at that period', 'build a MultiPeriodDiscriminator with periods [2,3,5,7,11] for multi-scale audio discrimination', 'run the PeriodDiscriminator forward pass on a 1D audio tensor to get logits and feature maps', 'run the MultiPeriodDiscriminator forward pass on audio to get logits and feature maps from all sub-discriminators', 'review the MultiPeriodDiscriminator num_discriminators property to check how many sub-discriminators are configured', 'build a MultiScaleDiscriminator with weight_norm for audio GAN adversarial training', 'build a ScaleDiscriminator waveform sub-discriminator with custom kernel sizes and filters', 'run the MultiScaleDiscriminator forward pass on a waveform tensor to get logits and feature maps', 'run the ScaleDiscriminator forward pass on a waveform tensor to get logits and feature maps', 'review the MultiScaleDiscriminator architecture with multiple ScaleDiscriminator sub-discriminators and AvgPool1d downsampling', 'build a MultiScaleSTFTDiscriminator with custom FFT sizes and hop lengths for audio GAN training', 'create a DiscriminatorSTFT module with configurable filters, kernel size, and dilation for spectrogram discrimination', 'run forward pass of DiscriminatorSTFT on audio tensor to get logits and feature maps', 'review the MultiScaleSTFTDiscriminator class to understand how multiple STFT scales are combined', 'refactor the get_2d_padding function to compute convolution padding for arbitrary kernel and dilation tuples']
```

Usage

```
{'build_multiscale_stft_discriminator': 'build a MultiScaleSTFTDiscriminator with custom FFT sizes and hop lengths for audio GAN training', 'create_stft_discriminator': 'create a DiscriminatorSTFT module with configurable filters, kernel size, and dilation for spectrogram discrimination', 'run_discriminator_forward': 'run forward pass of DiscriminatorSTFT on audio tensor to get logits and feature maps', 'review_multiscale_discriminators': 'review the MultiScaleSTFTDiscriminator class to understand how multiple STFT scales are combined', 'refactor_get_2d_padding': 'refactor the get_2d_padding function to compute convolution padding for arbitrary kernel and dilation tuples'}
```

