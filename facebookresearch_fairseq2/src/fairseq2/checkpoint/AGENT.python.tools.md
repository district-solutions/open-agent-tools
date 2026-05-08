# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/src/fairseq2/checkpoint/hg.py

Prompts

```
['create an OutOfProcHuggingFaceExporter instance with output_dir, gangs, file_system, process_runner, and thread_pool', 'call export on OutOfProcHuggingFaceExporter to export a checkpoint step to Hugging Face format', 'call maybe_complete_operation on OutOfProcHuggingFaceExporter to finalize a pending Hugging Face export', 'check the is_exporting property on OutOfProcHuggingFaceExporter to see if an export is in progress', 'use the NOOP_HG_EXPORTER singleton as a no-op HuggingFaceExporter when export is not needed', 'build a StandardCheckpointManager to save and load training checkpoints on a file system', 'save a full training checkpoint including trainer, model, optimizer, and data reader state', 'save a model-only checkpoint without trainer, optimizer, or data reader state', 'load and restore model state from a checkpoint at a given step number', 'get stale checkpoint step numbers based on keep_last_n, keep_best_n, and keep_every_n_steps policies', 'create a StandardModelMetadataDumper to dump model config as model.yaml into a checkpoint directory', 'use StandardModelMetadataDumper.dump to write checkpoint metadata with family name and config to disk', 'create a StandardModelMetadataLoader to load checkpoint metadata from a directory and resolve step scores', 'use StandardModelMetadataLoader.load to read model.yaml and discover step directories with best and last checkpoints', 'create a ModelMetadataSource to wrap a checkpoint directory and metadata loader for asset metadata iteration']
```

Usage

```
{'create_OutOfProcHuggingFaceExporter': 'create an OutOfProcHuggingFaceExporter instance with output_dir, gangs, file_system, process_runner, and thread_pool', 'export_checkpoint_to_hg': 'call export on OutOfProcHuggingFaceExporter to export a checkpoint step to Hugging Face format', 'complete_export_operation': 'call maybe_complete_operation on OutOfProcHuggingFaceExporter to finalize a pending Hugging Face export', 'check_exporting_status': 'check the is_exporting property on OutOfProcHuggingFaceExporter to see if an export is in progress', 'use_noop_hg_exporter': 'use the NOOP_HG_EXPORTER singleton as a no-op HuggingFaceExporter when export is not needed'}
```

## File: facebookresearch_fairseq2/src/fairseq2/checkpoint/manager.py

Prompts

```
['create an OutOfProcHuggingFaceExporter instance with output_dir, gangs, file_system, process_runner, and thread_pool', 'call export on OutOfProcHuggingFaceExporter to export a checkpoint step to Hugging Face format', 'call maybe_complete_operation on OutOfProcHuggingFaceExporter to finalize a pending Hugging Face export', 'check the is_exporting property on OutOfProcHuggingFaceExporter to see if an export is in progress', 'use the NOOP_HG_EXPORTER singleton as a no-op HuggingFaceExporter when export is not needed', 'build a StandardCheckpointManager to save and load training checkpoints on a file system', 'save a full training checkpoint including trainer, model, optimizer, and data reader state', 'save a model-only checkpoint without trainer, optimizer, or data reader state', 'load and restore model state from a checkpoint at a given step number', 'get stale checkpoint step numbers based on keep_last_n, keep_best_n, and keep_every_n_steps policies', 'create a StandardModelMetadataDumper to dump model config as model.yaml into a checkpoint directory', 'use StandardModelMetadataDumper.dump to write checkpoint metadata with family name and config to disk', 'create a StandardModelMetadataLoader to load checkpoint metadata from a directory and resolve step scores', 'use StandardModelMetadataLoader.load to read model.yaml and discover step directories with best and last checkpoints', 'create a ModelMetadataSource to wrap a checkpoint directory and metadata loader for asset metadata iteration']
```

Usage

```
{'build_standard_checkpoint_manager': 'build a StandardCheckpointManager to save and load training checkpoints on a file system', 'save_checkpoint': 'save a full training checkpoint including trainer, model, optimizer, and data reader state', 'save_model_only': 'save a model-only checkpoint without trainer, optimizer, or data reader state', 'load_model_state': 'load and restore model state from a checkpoint at a given step number', 'get_stale_step_numbers': 'get stale checkpoint step numbers based on keep_last_n, keep_best_n, and keep_every_n_steps policies'}
```

## File: facebookresearch_fairseq2/src/fairseq2/checkpoint/model_metadata.py

Prompts

```
['create an OutOfProcHuggingFaceExporter instance with output_dir, gangs, file_system, process_runner, and thread_pool', 'call export on OutOfProcHuggingFaceExporter to export a checkpoint step to Hugging Face format', 'call maybe_complete_operation on OutOfProcHuggingFaceExporter to finalize a pending Hugging Face export', 'check the is_exporting property on OutOfProcHuggingFaceExporter to see if an export is in progress', 'use the NOOP_HG_EXPORTER singleton as a no-op HuggingFaceExporter when export is not needed', 'build a StandardCheckpointManager to save and load training checkpoints on a file system', 'save a full training checkpoint including trainer, model, optimizer, and data reader state', 'save a model-only checkpoint without trainer, optimizer, or data reader state', 'load and restore model state from a checkpoint at a given step number', 'get stale checkpoint step numbers based on keep_last_n, keep_best_n, and keep_every_n_steps policies', 'create a StandardModelMetadataDumper to dump model config as model.yaml into a checkpoint directory', 'use StandardModelMetadataDumper.dump to write checkpoint metadata with family name and config to disk', 'create a StandardModelMetadataLoader to load checkpoint metadata from a directory and resolve step scores', 'use StandardModelMetadataLoader.load to read model.yaml and discover step directories with best and last checkpoints', 'create a ModelMetadataSource to wrap a checkpoint directory and metadata loader for asset metadata iteration']
```

Usage

```
{'create_standard_model_metadata_dumper': 'create a StandardModelMetadataDumper to dump model config as model.yaml into a checkpoint directory', 'dump_model_metadata': 'use StandardModelMetadataDumper.dump to write checkpoint metadata with family name and config to disk', 'create_standard_model_metadata_loader': 'create a StandardModelMetadataLoader to load checkpoint metadata from a directory and resolve step scores', 'load_checkpoint_metadata': 'use StandardModelMetadataLoader.load to read model.yaml and discover step directories with best and last checkpoints', 'create_model_metadata_source': 'create a ModelMetadataSource to wrap a checkpoint directory and metadata loader for asset metadata iteration'}
```

