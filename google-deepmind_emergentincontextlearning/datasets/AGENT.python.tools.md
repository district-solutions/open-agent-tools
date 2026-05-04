# Agent Python Tools

- repo: google-deepmind/emergentincontextlearning
- repo_uri: https://github.com/google-deepmind/emergent_in_context_learning

## File: google-deepmind_emergentincontextlearning/datasets/data_generators.py

Prompts

```
['create an OmniglotDatasetForSampling to load Omniglot data with single or separated exemplars', 'generate bursty few-shot sequences using SeqGenerator.get_bursty_seq with configurable shots and ways', 'generate k-shot n-way few-shot sequences using SeqGenerator.get_fewshot_seq for rare or common classes', 'generate random example sequences using SeqGenerator.get_random_seq with uniform or Zipfian class sampling', 'generate no-support sequences using SeqGenerator.get_no_support_seq where the query class has no support examples', 'prepare a tf.data.Dataset by converting example and label sequences into transformer-ready format with examples, labels, and target keys', 'create alternating label and zero target sequences from a tf.data.Dataset for transformer input', 'downsample image examples in a tf.data.Dataset to 28x28 resolution for transformer processing', 'replace true labels with constant ones in a tf.data.Dataset for ablation or baseline experiments', 'convert a dataset dictionary with example and label keys into examples, labels, and target keys for transformer models']
```

Usage

```
{'create_omniglot_dataset': 'create an OmniglotDatasetForSampling to load Omniglot data with single or separated exemplars', 'generate_bursty_sequence': 'generate bursty few-shot sequences using SeqGenerator.get_bursty_seq with configurable shots and ways', 'generate_fewshot_sequence': 'generate k-shot n-way few-shot sequences using SeqGenerator.get_fewshot_seq for rare or common classes', 'generate_random_sequence': 'generate random example sequences using SeqGenerator.get_random_seq with uniform or Zipfian class sampling', 'generate_no_support_sequence': 'generate no-support sequences using SeqGenerator.get_no_support_seq where the query class has no support examples'}
```

## File: google-deepmind_emergentincontextlearning/datasets/utils.py

Prompts

```
['create an OmniglotDatasetForSampling to load Omniglot data with single or separated exemplars', 'generate bursty few-shot sequences using SeqGenerator.get_bursty_seq with configurable shots and ways', 'generate k-shot n-way few-shot sequences using SeqGenerator.get_fewshot_seq for rare or common classes', 'generate random example sequences using SeqGenerator.get_random_seq with uniform or Zipfian class sampling', 'generate no-support sequences using SeqGenerator.get_no_support_seq where the query class has no support examples', 'prepare a tf.data.Dataset by converting example and label sequences into transformer-ready format with examples, labels, and target keys', 'create alternating label and zero target sequences from a tf.data.Dataset for transformer input', 'downsample image examples in a tf.data.Dataset to 28x28 resolution for transformer processing', 'replace true labels with constant ones in a tf.data.Dataset for ablation or baseline experiments', 'convert a dataset dictionary with example and label keys into examples, labels, and target keys for transformer models']
```

Usage

```
{'prepare_seqs_for_transformer': 'prepare a tf.data.Dataset by converting example and label sequences into transformer-ready format with examples, labels, and target keys', 'interleave_targets_in_dataset': 'create alternating label and zero target sequences from a tf.data.Dataset for transformer input', 'downsample_images_in_dataset': 'downsample image examples in a tf.data.Dataset to 28x28 resolution for transformer processing', 'use_constant_labels_in_dataset': 'replace true labels with constant ones in a tf.data.Dataset for ablation or baseline experiments', 'convert_dict_for_transformer': 'convert a dataset dictionary with example and label keys into examples, labels, and target keys for transformer models'}
```

