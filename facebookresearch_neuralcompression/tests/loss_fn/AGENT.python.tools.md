# Agent Python Tools

- repo: facebookresearch/neuralcompression
- repo_uri: https://github.com/facebookresearch/neuralcompression

## File: facebookresearch_neuralcompression/tests/loss_fn/test_binary_cross_entropy.py

Prompts

```
['test the BinaryCrossentropyDiscriminatorLoss class by running pytest on test_binary_cross_entropy_disc', 'test the BinaryCrossentropyGeneratorLoss class by running pytest on test_binary_cross_entropy_gen', 'run the binary_logits pytest fixture to generate random logit tensors for testing', 'review the BinaryCrossentropyDiscriminatorLoss implementation and its expected output formula', 'review the BinaryCrossentropyGeneratorLoss implementation and its expected output formula', 'test the MSELoss class with a scaling parameter against a 4D image tensor', 'test MSELoss with multiple mse_param values including 255 squared, 1.0, and 0.5', 'run MSELoss on a randomly generated tensor compared to an arange 4D image', 'review the test_mse_loss function that validates MSELoss output against manual MSE calculation', 'summarize how MSELoss is instantiated with a scaling parameter and called with two tensors', 'test the MSELPIPSLoss class with parametrized shape, backbone, mse_param, and lpips_param combinations', 'run MSELPIPSLoss with alex or vgg backbone to compute combined MSE and LPIPS loss on image tensors', 'run NormFixLPIPS with alex or vgg backbone to compute perceptual similarity between two image tensors', 'test NormFixLPIPS by freezing parameters and comparing estimated loss against MSELPIPSLoss output', 'review the MSELPIPSLoss class to understand how mse_param and lpips_param weight the combined loss', 'test the OASISDiscriminatorLoss class by computing discriminator loss from real and fake logits with a target map', 'test the OASISGeneratorLoss class by computing generator loss from logits and a spatially-varying target map', 'run the OASISDiscriminatorLoss call with 4-D real logits, 4-D fake logits, and a 3-D target tensor', 'run the OASISGeneratorLoss call with 4-D logits and a 3-D ground truth label tensor', 'review the pytest test suite that validates OASIS discriminator and generator loss against expected cross-entropy values']
```

Usage

```
{'test_binary_cross_entropy_disc': 'test the BinaryCrossentropyDiscriminatorLoss class by running pytest on test_binary_cross_entropy_disc', 'test_binary_cross_entropy_gen': 'test the BinaryCrossentropyGeneratorLoss class by running pytest on test_binary_cross_entropy_gen', 'run_binary_logits_fixture': 'run the binary_logits pytest fixture to generate random logit tensors for testing', 'review_discriminator_loss': 'review the BinaryCrossentropyDiscriminatorLoss implementation and its expected output formula', 'review_generator_loss': 'review the BinaryCrossentropyGeneratorLoss implementation and its expected output formula'}
```

## File: facebookresearch_neuralcompression/tests/loss_fn/test_mse_loss.py

Prompts

```
['test the BinaryCrossentropyDiscriminatorLoss class by running pytest on test_binary_cross_entropy_disc', 'test the BinaryCrossentropyGeneratorLoss class by running pytest on test_binary_cross_entropy_gen', 'run the binary_logits pytest fixture to generate random logit tensors for testing', 'review the BinaryCrossentropyDiscriminatorLoss implementation and its expected output formula', 'review the BinaryCrossentropyGeneratorLoss implementation and its expected output formula', 'test the MSELoss class with a scaling parameter against a 4D image tensor', 'test MSELoss with multiple mse_param values including 255 squared, 1.0, and 0.5', 'run MSELoss on a randomly generated tensor compared to an arange 4D image', 'review the test_mse_loss function that validates MSELoss output against manual MSE calculation', 'summarize how MSELoss is instantiated with a scaling parameter and called with two tensors', 'test the MSELPIPSLoss class with parametrized shape, backbone, mse_param, and lpips_param combinations', 'run MSELPIPSLoss with alex or vgg backbone to compute combined MSE and LPIPS loss on image tensors', 'run NormFixLPIPS with alex or vgg backbone to compute perceptual similarity between two image tensors', 'test NormFixLPIPS by freezing parameters and comparing estimated loss against MSELPIPSLoss output', 'review the MSELPIPSLoss class to understand how mse_param and lpips_param weight the combined loss', 'test the OASISDiscriminatorLoss class by computing discriminator loss from real and fake logits with a target map', 'test the OASISGeneratorLoss class by computing generator loss from logits and a spatially-varying target map', 'run the OASISDiscriminatorLoss call with 4-D real logits, 4-D fake logits, and a 3-D target tensor', 'run the OASISGeneratorLoss call with 4-D logits and a 3-D ground truth label tensor', 'review the pytest test suite that validates OASIS discriminator and generator loss against expected cross-entropy values']
```

Usage

```
{'test_MSELoss_with_param': 'test the MSELoss class with a scaling parameter against a 4D image tensor', 'test_MSELoss_parametrized': 'test MSELoss with multiple mse_param values including 255 squared, 1.0, and 0.5', 'run_MSELoss_on_random_tensor': 'run MSELoss on a randomly generated tensor compared to an arange 4D image', 'review_test_mse_loss': 'review the test_mse_loss function that validates MSELoss output against manual MSE calculation', 'summarize_MSELoss_usage': 'summarize how MSELoss is instantiated with a scaling parameter and called with two tensors'}
```

## File: facebookresearch_neuralcompression/tests/loss_fn/test_mse_lpips_loss.py

Prompts

```
['test the BinaryCrossentropyDiscriminatorLoss class by running pytest on test_binary_cross_entropy_disc', 'test the BinaryCrossentropyGeneratorLoss class by running pytest on test_binary_cross_entropy_gen', 'run the binary_logits pytest fixture to generate random logit tensors for testing', 'review the BinaryCrossentropyDiscriminatorLoss implementation and its expected output formula', 'review the BinaryCrossentropyGeneratorLoss implementation and its expected output formula', 'test the MSELoss class with a scaling parameter against a 4D image tensor', 'test MSELoss with multiple mse_param values including 255 squared, 1.0, and 0.5', 'run MSELoss on a randomly generated tensor compared to an arange 4D image', 'review the test_mse_loss function that validates MSELoss output against manual MSE calculation', 'summarize how MSELoss is instantiated with a scaling parameter and called with two tensors', 'test the MSELPIPSLoss class with parametrized shape, backbone, mse_param, and lpips_param combinations', 'run MSELPIPSLoss with alex or vgg backbone to compute combined MSE and LPIPS loss on image tensors', 'run NormFixLPIPS with alex or vgg backbone to compute perceptual similarity between two image tensors', 'test NormFixLPIPS by freezing parameters and comparing estimated loss against MSELPIPSLoss output', 'review the MSELPIPSLoss class to understand how mse_param and lpips_param weight the combined loss', 'test the OASISDiscriminatorLoss class by computing discriminator loss from real and fake logits with a target map', 'test the OASISGeneratorLoss class by computing generator loss from logits and a spatially-varying target map', 'run the OASISDiscriminatorLoss call with 4-D real logits, 4-D fake logits, and a 3-D target tensor', 'run the OASISGeneratorLoss call with 4-D logits and a 3-D ground truth label tensor', 'review the pytest test suite that validates OASIS discriminator and generator loss against expected cross-entropy values']
```

Usage

```
{'test_mse_lpips_loss': 'test the MSELPIPSLoss class with parametrized shape, backbone, mse_param, and lpips_param combinations', 'run_MSELPIPSLoss': 'run MSELPIPSLoss with alex or vgg backbone to compute combined MSE and LPIPS loss on image tensors', 'run_NormFixLPIPS': 'run NormFixLPIPS with alex or vgg backbone to compute perceptual similarity between two image tensors', 'test_NormFixLPIPS': 'test NormFixLPIPS by freezing parameters and comparing estimated loss against MSELPIPSLoss output', 'review_MSELPIPSLoss': 'review the MSELPIPSLoss class to understand how mse_param and lpips_param weight the combined loss'}
```

## File: facebookresearch_neuralcompression/tests/loss_fn/test_oasis_loss.py

Prompts

```
['test the BinaryCrossentropyDiscriminatorLoss class by running pytest on test_binary_cross_entropy_disc', 'test the BinaryCrossentropyGeneratorLoss class by running pytest on test_binary_cross_entropy_gen', 'run the binary_logits pytest fixture to generate random logit tensors for testing', 'review the BinaryCrossentropyDiscriminatorLoss implementation and its expected output formula', 'review the BinaryCrossentropyGeneratorLoss implementation and its expected output formula', 'test the MSELoss class with a scaling parameter against a 4D image tensor', 'test MSELoss with multiple mse_param values including 255 squared, 1.0, and 0.5', 'run MSELoss on a randomly generated tensor compared to an arange 4D image', 'review the test_mse_loss function that validates MSELoss output against manual MSE calculation', 'summarize how MSELoss is instantiated with a scaling parameter and called with two tensors', 'test the MSELPIPSLoss class with parametrized shape, backbone, mse_param, and lpips_param combinations', 'run MSELPIPSLoss with alex or vgg backbone to compute combined MSE and LPIPS loss on image tensors', 'run NormFixLPIPS with alex or vgg backbone to compute perceptual similarity between two image tensors', 'test NormFixLPIPS by freezing parameters and comparing estimated loss against MSELPIPSLoss output', 'review the MSELPIPSLoss class to understand how mse_param and lpips_param weight the combined loss', 'test the OASISDiscriminatorLoss class by computing discriminator loss from real and fake logits with a target map', 'test the OASISGeneratorLoss class by computing generator loss from logits and a spatially-varying target map', 'run the OASISDiscriminatorLoss call with 4-D real logits, 4-D fake logits, and a 3-D target tensor', 'run the OASISGeneratorLoss call with 4-D logits and a 3-D ground truth label tensor', 'review the pytest test suite that validates OASIS discriminator and generator loss against expected cross-entropy values']
```

Usage

```
{'test_OASISDiscriminatorLoss': 'test the OASISDiscriminatorLoss class by computing discriminator loss from real and fake logits with a target map', 'test_OASISGeneratorLoss': 'test the OASISGeneratorLoss class by computing generator loss from logits and a spatially-varying target map', 'run_OASISDiscriminatorLoss': 'run the OASISDiscriminatorLoss call with 4-D real logits, 4-D fake logits, and a 3-D target tensor', 'run_OASISGeneratorLoss': 'run the OASISGeneratorLoss call with 4-D logits and a 3-D ground truth label tensor', 'review_oasis_loss_tests': 'review the pytest test suite that validates OASIS discriminator and generator loss against expected cross-entropy values'}
```

