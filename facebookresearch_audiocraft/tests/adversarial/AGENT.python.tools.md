# Agent Python Tools

- repo: facebookresearch/audiocraft
- repo_uri: https://github.com/facebookresearch/audiocraft.git

## File: facebookresearch_audiocraft/tests/adversarial/test_discriminators.py

Prompts

```
['test the MultiPeriodDiscriminator with random periods and verify logits and feature map shapes', 'test the MultiScaleDiscriminator with weight_norm scales and verify output tensor dimensions', 'test the MultiScaleSTFTDiscriminator with custom FFT sizes and verify logit and feature map shapes', 'run the MultiPeriodDiscriminator on a random tensor and return logits and feature maps', 'run the MultiScaleDiscriminator on a random tensor and return logits and feature maps', 'test AdversarialLoss with MultiScaleDiscriminator by training on random real and fake audio tensors', 'test FeatureMatchingLoss with and without layer normalization on matching and mismatching feature lists', 'test the hinge generator adversarial criterion by computing loss on random and constant tensors', 'test the MSE discriminator adversarial loss by combining real and fake criterion outputs', 'test AdversarialLoss combined with FeatureMatchingLoss to verify both adversarial and feature loss tensors are returned']
```

Usage

```
{'test_MultiPeriodDiscriminator': 'test the MultiPeriodDiscriminator with random periods and verify logits and feature map shapes', 'test_MultiScaleDiscriminator': 'test the MultiScaleDiscriminator with weight_norm scales and verify output tensor dimensions', 'test_MultiScaleSTFTDiscriminator': 'test the MultiScaleSTFTDiscriminator with custom FFT sizes and verify logit and feature map shapes', 'run_MultiPeriodDiscriminator_inference': 'run the MultiPeriodDiscriminator on a random tensor and return logits and feature maps', 'run_MultiScaleDiscriminator_inference': 'run the MultiScaleDiscriminator on a random tensor and return logits and feature maps'}
```

## File: facebookresearch_audiocraft/tests/adversarial/test_losses.py

Prompts

```
['test the MultiPeriodDiscriminator with random periods and verify logits and feature map shapes', 'test the MultiScaleDiscriminator with weight_norm scales and verify output tensor dimensions', 'test the MultiScaleSTFTDiscriminator with custom FFT sizes and verify logit and feature map shapes', 'run the MultiPeriodDiscriminator on a random tensor and return logits and feature maps', 'run the MultiScaleDiscriminator on a random tensor and return logits and feature maps', 'test AdversarialLoss with MultiScaleDiscriminator by training on random real and fake audio tensors', 'test FeatureMatchingLoss with and without layer normalization on matching and mismatching feature lists', 'test the hinge generator adversarial criterion by computing loss on random and constant tensors', 'test the MSE discriminator adversarial loss by combining real and fake criterion outputs', 'test AdversarialLoss combined with FeatureMatchingLoss to verify both adversarial and feature loss tensors are returned']
```

Usage

```
{'test_adversarial_loss_with_multiscale_discriminator': 'test AdversarialLoss with MultiScaleDiscriminator by training on random real and fake audio tensors', 'test_feature_matching_loss_with_normalization': 'test FeatureMatchingLoss with and without layer normalization on matching and mismatching feature lists', 'test_hinge_generator_adversarial_loss': 'test the hinge generator adversarial criterion by computing loss on random and constant tensors', 'test_mse_discriminator_adversarial_loss': 'test the MSE discriminator adversarial loss by combining real and fake criterion outputs', 'test_adversarial_loss_with_feature_matching': 'test AdversarialLoss combined with FeatureMatchingLoss to verify both adversarial and feature loss tensors are returned'}
```

