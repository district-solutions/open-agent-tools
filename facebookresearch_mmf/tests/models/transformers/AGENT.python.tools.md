# Agent Python Tools

- repo: facebookresearch/mmf
- repo_uri: https://github.com/facebookresearch/mmf

## File: facebookresearch_mmf/tests/models/transformers/test_heads.py

Prompts

```
['test the MLM head forward pass with masked language model labels and verify logits output', 'test the MLP head forward pass and verify classification scores output shape', 'test the ITM head forward pass with image-text matching labels and verify itm_loss', 'test the Refiner head forward pass with text and image masks and verify fused embedding output', 'test the MRC head forward pass with KL divergence and cross entropy loss options', 'build a HeadsDict from a dictionary of head configurations with task names and loss mappings', 'build a HeadsDict from a list of head configurations without explicit task names', 'test the HeadsDict forward pass with a task name, model output tensor, and sample list', 'test the HeadsDict forward pass with multiple loss types configured per task', 'test the HeadsDict forward pass selecting a specific task from multiple configured tasks']
```

Usage

```
{'test_MLM_head_forward': 'test the MLM head forward pass with masked language model labels and verify logits output', 'test_MLP_head_forward': 'test the MLP head forward pass and verify classification scores output shape', 'test_ITM_head_forward': 'test the ITM head forward pass with image-text matching labels and verify itm_loss', 'test_Refiner_head_forward': 'test the Refiner head forward pass with text and image masks and verify fused embedding output', 'test_MRC_head_forward': 'test the MRC head forward pass with KL divergence and cross entropy loss options'}
```

## File: facebookresearch_mmf/tests/models/transformers/test_heads_dict.py

Prompts

```
['test the MLM head forward pass with masked language model labels and verify logits output', 'test the MLP head forward pass and verify classification scores output shape', 'test the ITM head forward pass with image-text matching labels and verify itm_loss', 'test the Refiner head forward pass with text and image masks and verify fused embedding output', 'test the MRC head forward pass with KL divergence and cross entropy loss options', 'build a HeadsDict from a dictionary of head configurations with task names and loss mappings', 'build a HeadsDict from a list of head configurations without explicit task names', 'test the HeadsDict forward pass with a task name, model output tensor, and sample list', 'test the HeadsDict forward pass with multiple loss types configured per task', 'test the HeadsDict forward pass selecting a specific task from multiple configured tasks']
```

Usage

```
{'build_heads_dict_from_dict_conf': 'build a HeadsDict from a dictionary of head configurations with task names and loss mappings', 'build_heads_dict_from_list_conf': 'build a HeadsDict from a list of head configurations without explicit task names', 'test_heads_dict_forward': 'test the HeadsDict forward pass with a task name, model output tensor, and sample list', 'test_heads_dict_multiple_losses': 'test the HeadsDict forward pass with multiple loss types configured per task', 'test_heads_dict_multiple_tasks': 'test the HeadsDict forward pass selecting a specific task from multiple configured tasks'}
```

