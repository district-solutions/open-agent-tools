# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/habitat-lab/habitat/datasets/vln/r2r_vln_dataset.py

Prompts

```
['create a VLNDatasetV1 instance from a Habitat config to load R2R vision-language navigation episodes from a gzipped JSON dataset file', 'call from_json on VLNDatasetV1 to parse a JSON string into VLNEpisode objects with instructions and navigation goals', 'call check_config_paths_exist on VLNDatasetV1 to verify the dataset file and scenes directory exist before loading', 'access the instruction_vocab attribute on VLNDatasetV1 to get a VocabDict of words from the R2R dataset instructions', 'use the episodes list on VLNDatasetV1 after initialization to get navigation episodes filtered by the config scenes list']
```

Usage

```
{'load_vln_dataset_from_config': 'create a VLNDatasetV1 instance from a Habitat config to load R2R vision-language navigation episodes from a gzipped JSON dataset file', 'parse_vln_episodes_from_json': 'call from_json on VLNDatasetV1 to parse a JSON string into VLNEpisode objects with instructions and navigation goals', 'check_vln_dataset_config_paths': 'call check_config_paths_exist on VLNDatasetV1 to verify the dataset file and scenes directory exist before loading', 'build_vln_instruction_vocab': 'access the instruction_vocab attribute on VLNDatasetV1 to get a VocabDict of words from the R2R dataset instructions', 'filter_vln_episodes_by_scenes': 'use the episodes list on VLNDatasetV1 after initialization to get navigation episodes filtered by the config scenes list'}
```

