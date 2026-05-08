# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/projects/roscoe/roscoe_data/restore_annotated.py

Prompts

```
['run the restore_annotated script to parse datasets and merge GPT-3 reasoning chains into JSON output', 'parse a DROP dataset file and merge GPT-3 reasoning chains into structured JSON records', 'parse an E-SNLI CSV file and merge GPT-3 reasoning chains into structured JSON records', 'parse a COSMOS QA CSV file and merge GPT-3 reasoning chains into structured JSON records', 'parse a SEMEVAL commonsense XML file and merge GPT-3 reasoning chains into structured JSON records', 'restore a percentage of perturbed synthetic data back to original using random sampling', 'restore specific perturbed data samples back to original using a provided perturbation IDs file', 'read a JSONL file line by line and yield each parsed JSON object', 'write a list of dictionaries to a JSONL file with one JSON object per line', 'restore perturbed dialog samples to their original un-perturbed state by index']
```

Usage

```
{'run_restore_annotated_cli': 'run the restore_annotated script to parse datasets and merge GPT-3 reasoning chains into JSON output', 'parse_drop_dataset': 'parse a DROP dataset file and merge GPT-3 reasoning chains into structured JSON records', 'parse_esnli_dataset': 'parse an E-SNLI CSV file and merge GPT-3 reasoning chains into structured JSON records', 'parse_cosmos_dataset': 'parse a COSMOS QA CSV file and merge GPT-3 reasoning chains into structured JSON records', 'parse_semeval_dataset': 'parse a SEMEVAL commonsense XML file and merge GPT-3 reasoning chains into structured JSON records'}
```

## File: facebookresearch_parlai/projects/roscoe/roscoe_data/restore_data.py

Prompts

```
['run the restore_annotated script to parse datasets and merge GPT-3 reasoning chains into JSON output', 'parse a DROP dataset file and merge GPT-3 reasoning chains into structured JSON records', 'parse an E-SNLI CSV file and merge GPT-3 reasoning chains into structured JSON records', 'parse a COSMOS QA CSV file and merge GPT-3 reasoning chains into structured JSON records', 'parse a SEMEVAL commonsense XML file and merge GPT-3 reasoning chains into structured JSON records', 'restore a percentage of perturbed synthetic data back to original using random sampling', 'restore specific perturbed data samples back to original using a provided perturbation IDs file', 'read a JSONL file line by line and yield each parsed JSON object', 'write a list of dictionaries to a JSONL file with one JSON object per line', 'restore perturbed dialog samples to their original un-perturbed state by index']
```

Usage

```
{'restore_perturbed_data_random': 'restore a percentage of perturbed synthetic data back to original using random sampling', 'restore_perturbed_data_deterministic': 'restore specific perturbed data samples back to original using a provided perturbation IDs file', 'read_json_lines': 'read a JSONL file line by line and yield each parsed JSON object', 'write_json_lines': 'write a list of dictionaries to a JSONL file with one JSON object per line', 'restore_positives': 'restore perturbed dialog samples to their original un-perturbed state by index'}
```

