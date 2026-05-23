# Agent Python Tools

- repo: facebookresearch/responsiblenlp
- repo_uri: https://github.com/facebookresearch/responsiblenlp

## File: facebookresearch_responsiblenlp/holistic_bias/src/bias_measurements.py

Prompts

```
['run the BiasMeasurementCompiler to compile perplexity measurements on HolisticBias sentences and calculate bias per demographic axis', 'compile perplexity measurements from world logs and calculate Mann-Whitney U statistical significance across descriptor pairs', 'add command line arguments for BiasMeasurementCompiler including the world-logs path for reading perplexities', 'calculate median perplexity per descriptor and template across all demographic axes and save to CSV', 'measure statistical significance of perplexity differences between descriptor pairs using Mann-Whitney U test with p-value threshold', 'create a HolisticBiasSentenceGenerator to generate templated sentences with metadata from the HolisticBias dataset', 'build a dataframe of all noun phrases by combining descriptors and nouns from the dataset', 'retrieve a randomly selected sentence with stylistic variations like lowercase and hyphen removal', 'load all descriptors from the HolisticBias dataset JSON file for a given dataset version', 'load all sentence templates from the HolisticBias dataset JSON file for a given dataset version']
```

Usage

```
{'run_bias_measurement_compiler': 'run the BiasMeasurementCompiler to compile perplexity measurements on HolisticBias sentences and calculate bias per demographic axis', 'compile_bias_measurements': 'compile perplexity measurements from world logs and calculate Mann-Whitney U statistical significance across descriptor pairs', 'add_cmdline_args': 'add command line arguments for BiasMeasurementCompiler including the world-logs path for reading perplexities', 'calculate_median_perplexities': 'calculate median perplexity per descriptor and template across all demographic axes and save to CSV', 'measure_statistical_significance': 'measure statistical significance of perplexity differences between descriptor pairs using Mann-Whitney U test with p-value threshold'}
```

## File: facebookresearch_responsiblenlp/holistic_bias/src/sentences.py

Prompts

```
['run the BiasMeasurementCompiler to compile perplexity measurements on HolisticBias sentences and calculate bias per demographic axis', 'compile perplexity measurements from world logs and calculate Mann-Whitney U statistical significance across descriptor pairs', 'add command line arguments for BiasMeasurementCompiler including the world-logs path for reading perplexities', 'calculate median perplexity per descriptor and template across all demographic axes and save to CSV', 'measure statistical significance of perplexity differences between descriptor pairs using Mann-Whitney U test with p-value threshold', 'create a HolisticBiasSentenceGenerator to generate templated sentences with metadata from the HolisticBias dataset', 'build a dataframe of all noun phrases by combining descriptors and nouns from the dataset', 'retrieve a randomly selected sentence with stylistic variations like lowercase and hyphen removal', 'load all descriptors from the HolisticBias dataset JSON file for a given dataset version', 'load all sentence templates from the HolisticBias dataset JSON file for a given dataset version']
```

Usage

```
{'generate_sentences': 'create a HolisticBiasSentenceGenerator to generate templated sentences with metadata from the HolisticBias dataset', 'get_compiled_noun_phrases': 'build a dataframe of all noun phrases by combining descriptors and nouns from the dataset', 'get_sentence': 'retrieve a randomly selected sentence with stylistic variations like lowercase and hyphen removal', 'get_descriptors': 'load all descriptors from the HolisticBias dataset JSON file for a given dataset version', 'get_sentence_templates': 'load all sentence templates from the HolisticBias dataset JSON file for a given dataset version'}
```

