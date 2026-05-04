# Agent Python Tools

- repo: facebookresearch/egoblur
- repo_uri: https://github.com/facebookresearch/egoblur

## File: facebookresearch_egoblur/gen2/script/detectron2/export/torchscript_patch.py

Prompts

```
['use patch_instances contextmanager to replace detectron2 Instances with a statically-typed scriptable class for TorchScript export', 'generate a TorchScript-compatible Instances class definition from a dict of field names and types', 'use freeze_training_mode contextmanager to annotate training as constant so the training codepath is meta-compiled away', 'use patch_builtin_len contextmanager to replace builtin len with __len__ for tracing-friendly behavior in detectron2 modules', 'add from_instances conversion method to a scripted Instances class to create scripted instances from original Instances']
```

Usage

```
{'patch_instances_contextmanager': 'use patch_instances contextmanager to replace detectron2 Instances with a statically-typed scriptable class for TorchScript export', 'gen_instance_class_code_gen': 'generate a TorchScript-compatible Instances class definition from a dict of field names and types', 'freeze_training_mode_contextmanager': 'use freeze_training_mode contextmanager to annotate training as constant so the training codepath is meta-compiled away', 'patch_builtin_len_contextmanager': 'use patch_builtin_len contextmanager to replace builtin len with __len__ for tracing-friendly behavior in detectron2 modules', 'add_instances_conversion_methods': 'add from_instances conversion method to a scripted Instances class to create scripted instances from original Instances'}
```

