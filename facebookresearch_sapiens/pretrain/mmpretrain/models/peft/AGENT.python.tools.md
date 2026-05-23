# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/pretrain/mmpretrain/models/peft/lora.py

Prompts

```
['build a LoRAModel wrapping a VisionTransformer with LoRA applied to qkv and proj target layers', 'create a LoRALinear layer wrapping an existing nn.Linear with configurable alpha rank and dropout', 'test the LoRAModel forward pass by passing input tensors through the wrapped module', 'review the LoRALinear forward method that computes original output plus scaled low-rank adaptation', 'refactor the LoRAModel targets list to match different layer names using regex or suffix patterns']
```

Usage

```
{'build_LoRAModel': 'build a LoRAModel wrapping a VisionTransformer with LoRA applied to qkv and proj target layers', 'create_LoRALinear': 'create a LoRALinear layer wrapping an existing nn.Linear with configurable alpha rank and dropout', 'test_LoRAModel_forward': 'test the LoRAModel forward pass by passing input tensors through the wrapped module', 'review_LoRALinear_forward': 'review the LoRALinear forward method that computes original output plus scaled low-rank adaptation', 'refactor_LoRAModel_targets': 'refactor the LoRAModel targets list to match different layer names using regex or suffix patterns'}
```

