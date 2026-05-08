# Agent Python Tools

- repo: facebookresearch/covidprognosis
- repo_uri: https://github.com/facebookresearch/covidprognosis

## File: facebookresearch_covidprognosis/tests/conftest.py

Prompts

```
['create a synthetic chest X-ray input sample with a PIL image and random labels for testing', 'fetch a chest X-ray dataset like NIH, CheXpert, or MIMIC by name and split from config', 'test the create_input function to verify it returns a dict with image, labels, and metadata keys', 'review the fetch_dataset function to understand how it loads NIH, CheXpert, MIMIC, or combined datasets', 'summarize the dataset_length_dict pytest fixture that returns expected dataset lengths per split', 'test the Compose transform that chains RandomHorizontalFlip, ToTensor, and RandomGaussianBlur together', 'test the NanToInt transform that replaces NaN label values with a specified integer', 'test the RemapLabel transform that remaps a start label value to an end label value', 'test the HistogramNormalize transform that applies histogram equalization to image tensors', 'test the RandomGaussianBlur transform that applies configurable Gaussian blur with probability and sigma range', 'test that X-ray datasets like nih_train and chexpert_all return the expected number of samples', 'test that fetching the first and last item from each X-ray dataset returns valid data', 'test that the combined_all dataset interleaves CheXpert, NIH, and MIMIC-CXR samples correctly', 'run the pytest suite to validate all X-ray dataset loaders return correct lengths and items', 'review the test_xray_datasets module to understand which datasets are tested and how samples are validated']
```

Usage

```
{'create_input_synthetic_sample': 'create a synthetic chest X-ray input sample with a PIL image and random labels for testing', 'fetch_dataset_by_name': 'fetch a chest X-ray dataset like NIH, CheXpert, or MIMIC by name and split from config', 'test_create_input_function': 'test the create_input function to verify it returns a dict with image, labels, and metadata keys', 'review_fetch_dataset_function': 'review the fetch_dataset function to understand how it loads NIH, CheXpert, MIMIC, or combined datasets', 'summarize_dataset_length_dict_fixture': 'summarize the dataset_length_dict pytest fixture that returns expected dataset lengths per split'}
```

## File: facebookresearch_covidprognosis/tests/test_transforms.py

Prompts

```
['create a synthetic chest X-ray input sample with a PIL image and random labels for testing', 'fetch a chest X-ray dataset like NIH, CheXpert, or MIMIC by name and split from config', 'test the create_input function to verify it returns a dict with image, labels, and metadata keys', 'review the fetch_dataset function to understand how it loads NIH, CheXpert, MIMIC, or combined datasets', 'summarize the dataset_length_dict pytest fixture that returns expected dataset lengths per split', 'test the Compose transform that chains RandomHorizontalFlip, ToTensor, and RandomGaussianBlur together', 'test the NanToInt transform that replaces NaN label values with a specified integer', 'test the RemapLabel transform that remaps a start label value to an end label value', 'test the HistogramNormalize transform that applies histogram equalization to image tensors', 'test the RandomGaussianBlur transform that applies configurable Gaussian blur with probability and sigma range', 'test that X-ray datasets like nih_train and chexpert_all return the expected number of samples', 'test that fetching the first and last item from each X-ray dataset returns valid data', 'test that the combined_all dataset interleaves CheXpert, NIH, and MIMIC-CXR samples correctly', 'run the pytest suite to validate all X-ray dataset loaders return correct lengths and items', 'review the test_xray_datasets module to understand which datasets are tested and how samples are validated']
```

Usage

```
{'test_compose_transforms': 'test the Compose transform that chains RandomHorizontalFlip, ToTensor, and RandomGaussianBlur together', 'test_nan_to_int': 'test the NanToInt transform that replaces NaN label values with a specified integer', 'test_remap_label': 'test the RemapLabel transform that remaps a start label value to an end label value', 'test_histogram_normalize': 'test the HistogramNormalize transform that applies histogram equalization to image tensors', 'test_random_gaussian_blur': 'test the RandomGaussianBlur transform that applies configurable Gaussian blur with probability and sigma range'}
```

## File: facebookresearch_covidprognosis/tests/test_xray_datasets.py

Prompts

```
['create a synthetic chest X-ray input sample with a PIL image and random labels for testing', 'fetch a chest X-ray dataset like NIH, CheXpert, or MIMIC by name and split from config', 'test the create_input function to verify it returns a dict with image, labels, and metadata keys', 'review the fetch_dataset function to understand how it loads NIH, CheXpert, MIMIC, or combined datasets', 'summarize the dataset_length_dict pytest fixture that returns expected dataset lengths per split', 'test the Compose transform that chains RandomHorizontalFlip, ToTensor, and RandomGaussianBlur together', 'test the NanToInt transform that replaces NaN label values with a specified integer', 'test the RemapLabel transform that remaps a start label value to an end label value', 'test the HistogramNormalize transform that applies histogram equalization to image tensors', 'test the RandomGaussianBlur transform that applies configurable Gaussian blur with probability and sigma range', 'test that X-ray datasets like nih_train and chexpert_all return the expected number of samples', 'test that fetching the first and last item from each X-ray dataset returns valid data', 'test that the combined_all dataset interleaves CheXpert, NIH, and MIMIC-CXR samples correctly', 'run the pytest suite to validate all X-ray dataset loaders return correct lengths and items', 'review the test_xray_datasets module to understand which datasets are tested and how samples are validated']
```

Usage

```
{'test_dataset_lengths': 'test that X-ray datasets like nih_train and chexpert_all return the expected number of samples', 'test_dataset_getitem': 'test that fetching the first and last item from each X-ray dataset returns valid data', 'test_combined_loader': 'test that the combined_all dataset interleaves CheXpert, NIH, and MIMIC-CXR samples correctly', 'run_xray_dataset_tests': 'run the pytest suite to validate all X-ray dataset loaders return correct lengths and items', 'review_xray_dataset_tests': 'review the test_xray_datasets module to understand which datasets are tested and how samples are validated'}
```

