# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/bros/convert_bros_to_pytorch.py

Prompts

```
['convert a BROS original checkpoint to a PyTorch HuggingFace model and save or push to hub', 'convert a BROS original state dict by renaming keys and removing ignored embedding keys', 'run the BROS checkpoint conversion CLI with a model name, output path, and optional hub push', 'rename BROS state dict keys from original repo naming to HuggingFace naming convention', 'load a BROS config from a pretrained model name for checkpoint conversion', 'create a BrosModel that encodes text with bounding box coordinates for document layout understanding', 'build a BrosForTokenClassification model for named-entity recognition on document layouts', 'create a BrosSpadeEEForTokenClassification model for entity extraction with initial and subsequent token classification', 'build a BrosSpadeELForTokenClassification model for intra-entity linking prediction on document layouts', 'create BrosBboxEmbeddings that generates 2D sinusoidal positional embeddings from bounding box coordinates']
```

Usage

```
{'convert_bros_checkpoint': 'convert a BROS original checkpoint to a PyTorch HuggingFace model and save or push to hub', 'convert_state_dict': 'convert a BROS original state dict by renaming keys and removing ignored embedding keys', 'run_convert_bros_cli': 'run the BROS checkpoint conversion CLI with a model name, output path, and optional hub push', 'rename_key': 'rename BROS state dict keys from original repo naming to HuggingFace naming convention', 'get_configs': 'load a BROS config from a pretrained model name for checkpoint conversion'}
```

## File: huggingface_transformers/src/transformers/models/bros/modeling_bros.py

Prompts

```
['convert a BROS original checkpoint to a PyTorch HuggingFace model and save or push to hub', 'convert a BROS original state dict by renaming keys and removing ignored embedding keys', 'run the BROS checkpoint conversion CLI with a model name, output path, and optional hub push', 'rename BROS state dict keys from original repo naming to HuggingFace naming convention', 'load a BROS config from a pretrained model name for checkpoint conversion', 'create a BrosModel that encodes text with bounding box coordinates for document layout understanding', 'build a BrosForTokenClassification model for named-entity recognition on document layouts', 'create a BrosSpadeEEForTokenClassification model for entity extraction with initial and subsequent token classification', 'build a BrosSpadeELForTokenClassification model for intra-entity linking prediction on document layouts', 'create BrosBboxEmbeddings that generates 2D sinusoidal positional embeddings from bounding box coordinates']
```

Usage

```
{'create_bros_model': 'create a BrosModel that encodes text with bounding box coordinates for document layout understanding', 'build_bros_token_classifier': 'build a BrosForTokenClassification model for named-entity recognition on document layouts', 'create_bros_spade_ee': 'create a BrosSpadeEEForTokenClassification model for entity extraction with initial and subsequent token classification', 'build_bros_entity_linker': 'build a BrosSpadeELForTokenClassification model for intra-entity linking prediction on document layouts', 'create_bros_bbox_embeddings': 'create BrosBboxEmbeddings that generates 2D sinusoidal positional embeddings from bounding box coordinates'}
```

