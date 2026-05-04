# Agent Python Tools

- repo: facebookresearch/anli
- repo_uri: https://github.com/facebookresearch/anli

## File: facebookresearch_anli/src/dataset_tools/build_data.py

Prompts

```
['build all NLI datasets including SNLI, MNLI, FEVER-NLI, and ANLI rounds 1 through 3', 'build the SNLI dataset by converting train, dev, and test splits to standard format', 'build the MNLI dataset with matched and mismatched dev splits in standard format', 'build the FEVER-NLI dataset by converting train, dev, and test splits to standard format', 'build the ANLI dataset for a specific round and version in standard format', 'convert a list of SNLI dataset items to standard NLI format with uid, premise, hypothesis, and label', 'convert a list of FEVER dataset items to standard NLI format with uid, premise, hypothesis, and label', 'convert a list of ANLI dataset items to standard NLI format including reason field and label', 'filter out dataset items with invalid labels by setting filter_invalid to true in any format conversion function', 'map dataset-specific labels like SUPPORTS or entailment to standard labels e, n, c, h using label mapping dictionaries']
```

Usage

```
{'build_data_all_nli': 'build all NLI datasets including SNLI, MNLI, FEVER-NLI, and ANLI rounds 1 through 3', 'build_snli_dataset': 'build the SNLI dataset by converting train, dev, and test splits to standard format', 'build_mnli_dataset': 'build the MNLI dataset with matched and mismatched dev splits in standard format', 'build_fever_nli_dataset': 'build the FEVER-NLI dataset by converting train, dev, and test splits to standard format', 'build_anli_dataset': 'build the ANLI dataset for a specific round and version in standard format'}
```

## File: facebookresearch_anli/src/dataset_tools/format_convert.py

Prompts

```
['build all NLI datasets including SNLI, MNLI, FEVER-NLI, and ANLI rounds 1 through 3', 'build the SNLI dataset by converting train, dev, and test splits to standard format', 'build the MNLI dataset with matched and mismatched dev splits in standard format', 'build the FEVER-NLI dataset by converting train, dev, and test splits to standard format', 'build the ANLI dataset for a specific round and version in standard format', 'convert a list of SNLI dataset items to standard NLI format with uid, premise, hypothesis, and label', 'convert a list of FEVER dataset items to standard NLI format with uid, premise, hypothesis, and label', 'convert a list of ANLI dataset items to standard NLI format including reason field and label', 'filter out dataset items with invalid labels by setting filter_invalid to true in any format conversion function', 'map dataset-specific labels like SUPPORTS or entailment to standard labels e, n, c, h using label mapping dictionaries']
```

Usage

```
{'convert_snli_to_standard': 'convert a list of SNLI dataset items to standard NLI format with uid, premise, hypothesis, and label', 'convert_fever_to_standard': 'convert a list of FEVER dataset items to standard NLI format with uid, premise, hypothesis, and label', 'convert_anli_to_standard': 'convert a list of ANLI dataset items to standard NLI format including reason field and label', 'filter_invalid_labels': 'filter out dataset items with invalid labels by setting filter_invalid to true in any format conversion function', 'map_labels_to_standard': 'map dataset-specific labels like SUPPORTS or entailment to standard labels e, n, c, h using label mapping dictionaries'}
```

