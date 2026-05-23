# Agent Python Tools

- repo: facebookresearch/stopes
- repo_uri: https://github.com/facebookresearch/stopes

## File: facebookresearch_stopes/stopes/pipelines/distillation/distillation_bitext_processor.py

Prompts

```
['extract paragraph content and metadata fields from a distillation bitext line', 'create a BitextProcessResult dataclass to track paragraph and sentence counts during bitext processing', 'merge multiple BitextProcessResult splits into a single aggregated result with summed counters', 'process bitext lines by splitting sentences, filtering with LID, and writing kept or discarded output', 'merge split processing results into final compressed output files without deduplication', 'run the distillation pipeline to train a distilled student model from monolingual source data', 'create a DistillationConfig dataclass with launcher, mono_pipeline, shard, generate, binarize, and train_fairseq settings', 'run the bitext_clean_helper async function to clean and filter parallel bitext file pairs', 'review the DistillationPipeline run method that orchestrates monolingual cleaning, sharding, generation, bitext cleaning, binarization, and training', 'run the main entry point with Hydra config and optional WandB tracking for distillation']
```

Usage

```
{'extract_distillation_metadata': 'extract paragraph content and metadata fields from a distillation bitext line', 'create_BitextProcessResult': 'create a BitextProcessResult dataclass to track paragraph and sentence counts during bitext processing', 'merge_BitextProcessResult': 'merge multiple BitextProcessResult splits into a single aggregated result with summed counters', 'process_lines_BitextSplitNormalizeFilterLID': 'process bitext lines by splitting sentences, filtering with LID, and writing kept or discarded output', 'merge_results_BitextSplitNormalizeFilterLID': 'merge split processing results into final compressed output files without deduplication'}
```

## File: facebookresearch_stopes/stopes/pipelines/distillation/distillation_pipeline.py

Prompts

```
['extract paragraph content and metadata fields from a distillation bitext line', 'create a BitextProcessResult dataclass to track paragraph and sentence counts during bitext processing', 'merge multiple BitextProcessResult splits into a single aggregated result with summed counters', 'process bitext lines by splitting sentences, filtering with LID, and writing kept or discarded output', 'merge split processing results into final compressed output files without deduplication', 'run the distillation pipeline to train a distilled student model from monolingual source data', 'create a DistillationConfig dataclass with launcher, mono_pipeline, shard, generate, binarize, and train_fairseq settings', 'run the bitext_clean_helper async function to clean and filter parallel bitext file pairs', 'review the DistillationPipeline run method that orchestrates monolingual cleaning, sharding, generation, bitext cleaning, binarization, and training', 'run the main entry point with Hydra config and optional WandB tracking for distillation']
```

Usage

```
{'run_distillation_pipeline': 'run the distillation pipeline to train a distilled student model from monolingual source data', 'create_distillation_config': 'create a DistillationConfig dataclass with launcher, mono_pipeline, shard, generate, binarize, and train_fairseq settings', 'run_bitext_clean_helper': 'run the bitext_clean_helper async function to clean and filter parallel bitext file pairs', 'review_DistillationPipeline_run': 'review the DistillationPipeline run method that orchestrates monolingual cleaning, sharding, generation, bitext cleaning, binarization, and training', 'run_main_entry_point': 'run the main entry point with Hydra config and optional WandB tracking for distillation'}
```

