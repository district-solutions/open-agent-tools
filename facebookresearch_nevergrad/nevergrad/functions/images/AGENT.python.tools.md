# Agent Python Tools

- repo: facebookresearch/nevergrad
- repo_uri: https://github.com/facebookresearch/nevergrad

## File: facebookresearch_nevergrad/nevergrad/functions/images/core.py

Prompts

```
['create an Image experiment function to recover a target image using nevergrad optimization', 'create an ImageAdversarial experiment to generate adversarial perturbations against a pretrained classifier', 'create an ImageFromPGAN experiment to optimize noise vectors and generate face images via a GAN', 'build a pretrained Resnet50 classifier with built-in ImageNet normalization for image classification', 'test the ImageAdversarial make_folder_functions classmethod to yield adversarial attack functions from an image folder', 'create a SumAbsoluteDifferences loss to compare two images by summing absolute pixel differences', 'create a SumSquareDifferences loss to compare two images by summing squared pixel differences', 'create a HistogramDifference loss to compare sorted channel-sum histograms of two images', 'create a Blur loss to estimate image blurriness using the Laplacian variance', 'create a Koncept512 loss to score image aesthetics using a neural network model', 'test ImageAdversarial evaluation_function by checking untargeted output equals 1 and targeted output equals 0', 'test ImageAdversarial copy method by chaining two copies and verifying identical function output', 'test Image class by instantiating it and calling it with random normalized input data', 'test Image copy method by creating a copy and verifying it returns the same value', 'test that imagelosses registry has 5 reference and 2 non-reference loss classes', 'test SumAbsoluteDifferences loss by computing L1 distance against a known reference image array', 'test all registered image loss classes for consistent float output on a resized PNG image', 'test that reference-based loss classes return zero when evaluated on their own reference image', 'test that reference-based losses score the reference image better than random noise data']
```

Usage

```
{'create_Image_experiment': 'create an Image experiment function to recover a target image using nevergrad optimization', 'create_ImageAdversarial_attack': 'create an ImageAdversarial experiment to generate adversarial perturbations against a pretrained classifier', 'create_ImageFromPGAN_faces': 'create an ImageFromPGAN experiment to optimize noise vectors and generate face images via a GAN', 'build_Resnet50_classifier': 'build a pretrained Resnet50 classifier with built-in ImageNet normalization for image classification', 'test_ImageAdversarial_make_folder_functions': 'test the ImageAdversarial make_folder_functions classmethod to yield adversarial attack functions from an image folder'}
```

## File: facebookresearch_nevergrad/nevergrad/functions/images/imagelosses.py

Prompts

```
['create an Image experiment function to recover a target image using nevergrad optimization', 'create an ImageAdversarial experiment to generate adversarial perturbations against a pretrained classifier', 'create an ImageFromPGAN experiment to optimize noise vectors and generate face images via a GAN', 'build a pretrained Resnet50 classifier with built-in ImageNet normalization for image classification', 'test the ImageAdversarial make_folder_functions classmethod to yield adversarial attack functions from an image folder', 'create a SumAbsoluteDifferences loss to compare two images by summing absolute pixel differences', 'create a SumSquareDifferences loss to compare two images by summing squared pixel differences', 'create a HistogramDifference loss to compare sorted channel-sum histograms of two images', 'create a Blur loss to estimate image blurriness using the Laplacian variance', 'create a Koncept512 loss to score image aesthetics using a neural network model', 'test ImageAdversarial evaluation_function by checking untargeted output equals 1 and targeted output equals 0', 'test ImageAdversarial copy method by chaining two copies and verifying identical function output', 'test Image class by instantiating it and calling it with random normalized input data', 'test Image copy method by creating a copy and verifying it returns the same value', 'test that imagelosses registry has 5 reference and 2 non-reference loss classes', 'test SumAbsoluteDifferences loss by computing L1 distance against a known reference image array', 'test all registered image loss classes for consistent float output on a resized PNG image', 'test that reference-based loss classes return zero when evaluated on their own reference image', 'test that reference-based losses score the reference image better than random noise data']
```

Usage

```
{'compute_sum_absolute_differences': 'create a SumAbsoluteDifferences loss to compare two images by summing absolute pixel differences', 'compute_sum_square_differences': 'create a SumSquareDifferences loss to compare two images by summing squared pixel differences', 'compute_histogram_difference': 'create a HistogramDifference loss to compare sorted channel-sum histograms of two images', 'estimate_image_blur': 'create a Blur loss to estimate image blurriness using the Laplacian variance', 'score_image_with_koncept512': 'create a Koncept512 loss to score image aesthetics using a neural network model'}
```

## File: facebookresearch_nevergrad/nevergrad/functions/images/test_core.py

Prompts

```
['create an Image experiment function to recover a target image using nevergrad optimization', 'create an ImageAdversarial experiment to generate adversarial perturbations against a pretrained classifier', 'create an ImageFromPGAN experiment to optimize noise vectors and generate face images via a GAN', 'build a pretrained Resnet50 classifier with built-in ImageNet normalization for image classification', 'test the ImageAdversarial make_folder_functions classmethod to yield adversarial attack functions from an image folder', 'create a SumAbsoluteDifferences loss to compare two images by summing absolute pixel differences', 'create a SumSquareDifferences loss to compare two images by summing squared pixel differences', 'create a HistogramDifference loss to compare sorted channel-sum histograms of two images', 'create a Blur loss to estimate image blurriness using the Laplacian variance', 'create a Koncept512 loss to score image aesthetics using a neural network model', 'test ImageAdversarial evaluation_function by checking untargeted output equals 1 and targeted output equals 0', 'test ImageAdversarial copy method by chaining two copies and verifying identical function output', 'test Image class by instantiating it and calling it with random normalized input data', 'test Image copy method by creating a copy and verifying it returns the same value', 'test that imagelosses registry has 5 reference and 2 non-reference loss classes', 'test SumAbsoluteDifferences loss by computing L1 distance against a known reference image array', 'test all registered image loss classes for consistent float output on a resized PNG image', 'test that reference-based loss classes return zero when evaluated on their own reference image', 'test that reference-based losses score the reference image better than random noise data']
```

Usage

```
{'test_ImageAdversarial_make_folder_functions': 'test ImageAdversarial.make_folder_functions by creating an instance with model test and calling it with zeros', 'test_ImageAdversarial_evaluation_function': 'test ImageAdversarial evaluation_function by checking untargeted output equals 1 and targeted output equals 0', 'test_ImageAdversarial_copy': 'test ImageAdversarial copy method by chaining two copies and verifying identical function output', 'test_Image_creation': 'test Image class by instantiating it and calling it with random normalized input data', 'test_Image_copy': 'test Image copy method by creating a copy and verifying it returns the same value'}
```

## File: facebookresearch_nevergrad/nevergrad/functions/images/test_imagelosses.py

Prompts

```
['create an Image experiment function to recover a target image using nevergrad optimization', 'create an ImageAdversarial experiment to generate adversarial perturbations against a pretrained classifier', 'create an ImageFromPGAN experiment to optimize noise vectors and generate face images via a GAN', 'build a pretrained Resnet50 classifier with built-in ImageNet normalization for image classification', 'test the ImageAdversarial make_folder_functions classmethod to yield adversarial attack functions from an image folder', 'create a SumAbsoluteDifferences loss to compare two images by summing absolute pixel differences', 'create a SumSquareDifferences loss to compare two images by summing squared pixel differences', 'create a HistogramDifference loss to compare sorted channel-sum histograms of two images', 'create a Blur loss to estimate image blurriness using the Laplacian variance', 'create a Koncept512 loss to score image aesthetics using a neural network model', 'test ImageAdversarial evaluation_function by checking untargeted output equals 1 and targeted output equals 0', 'test ImageAdversarial copy method by chaining two copies and verifying identical function output', 'test Image class by instantiating it and calling it with random normalized input data', 'test Image copy method by creating a copy and verifying it returns the same value', 'test that imagelosses registry has 5 reference and 2 non-reference loss classes', 'test SumAbsoluteDifferences loss by computing L1 distance against a known reference image array', 'test all registered image loss classes for consistent float output on a resized PNG image', 'test that reference-based loss classes return zero when evaluated on their own reference image', 'test that reference-based losses score the reference image better than random noise data']
```

Usage

```
{'test_image_loss_registry': 'test that imagelosses registry has 5 reference and 2 non-reference loss classes', 'test_l1_loss_calculation': 'test SumAbsoluteDifferences loss by computing L1 distance against a known reference image array', 'test_consistency_losses': 'test all registered image loss classes for consistent float output on a resized PNG image', 'test_reference_loss_zero': 'test that reference-based loss classes return zero when evaluated on their own reference image', 'test_loss_random_vs_reference': 'test that reference-based losses score the reference image better than random noise data'}
```

