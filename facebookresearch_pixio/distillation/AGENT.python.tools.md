# Agent Python Tools

- repo: facebookresearch/pixio
- repo_uri: https://github.com/facebookresearch/pixio

## File: facebookresearch_pixio/distillation/engine_distill.py

Prompts

```
['run one epoch of teacher-student distillation training with multiple student models and gradient accumulation', 'build a training loop that computes teacher features once and aligns multiple student models via feature loss', 'refactor train_one_epoch to support additional loss types beyond classification and patch alignment losses', 'review how feat_align_loss is computed between student and teacher features with masking and ids_keep', 'summarize the metric logging and wandb tracking for per-student loss_cls, loss_patch, and learning rate', 'run Pixio knowledge distillation training with a teacher model and one or more student models', 'run distillation training with multiple student models learning from a single teacher model simultaneously', 'run distillation training using a webdataset instead of ImageNet as the data source', 'run distillation training with configurable patch masking ratio and grid size for student models', 'resume a distillation training run from a saved checkpoint at a specific epoch', 'build a PixioViT transformer model with configurable patch size, depth, and embedding dimensions', 'create a PixioViT-B/16 model with 768 embedding dim and 12 transformer blocks', 'create a PixioViT-L/16 model with 1024 embedding dim and 24 transformer blocks', 'create a PixioViT-H/16 model with 1280 embedding dim and 32 transformer blocks', 'create a PixioViT-1B/16 model with 1536 embedding dim and 48 transformer blocks', 'run multinode Pixio distillation training via submitit on a Slurm cluster with configurable GPUs and nodes', 'submit a Slurm job for Pixio distillation training with custom partition, account, and QoS settings', 'configure a submitit AutoExecutor with GPU, memory, and node parameters for distributed training jobs', 'create a Trainer checkpoint that requeues the job with a fresh init file and delayed submission', 'setup GPU arguments from the submitit JobEnvironment including rank, world size, and output directory']
```

Usage

```
{'run_train_one_epoch': 'run one epoch of teacher-student distillation training with multiple student models and gradient accumulation', 'build_distillation_training_loop': 'build a training loop that computes teacher features once and aligns multiple student models via feature loss', 'refactor_train_one_epoch': 'refactor train_one_epoch to support additional loss types beyond classification and patch alignment losses', 'review_feat_align_loss_integration': 'review how feat_align_loss is computed between student and teacher features with masking and ids_keep', 'summarize_metric_logging': 'summarize the metric logging and wandb tracking for per-student loss_cls, loss_patch, and learning rate'}
```

## File: facebookresearch_pixio/distillation/main_distill.py

Prompts

```
['run one epoch of teacher-student distillation training with multiple student models and gradient accumulation', 'build a training loop that computes teacher features once and aligns multiple student models via feature loss', 'refactor train_one_epoch to support additional loss types beyond classification and patch alignment losses', 'review how feat_align_loss is computed between student and teacher features with masking and ids_keep', 'summarize the metric logging and wandb tracking for per-student loss_cls, loss_patch, and learning rate', 'run Pixio knowledge distillation training with a teacher model and one or more student models', 'run distillation training with multiple student models learning from a single teacher model simultaneously', 'run distillation training using a webdataset instead of ImageNet as the data source', 'run distillation training with configurable patch masking ratio and grid size for student models', 'resume a distillation training run from a saved checkpoint at a specific epoch', 'build a PixioViT transformer model with configurable patch size, depth, and embedding dimensions', 'create a PixioViT-B/16 model with 768 embedding dim and 12 transformer blocks', 'create a PixioViT-L/16 model with 1024 embedding dim and 24 transformer blocks', 'create a PixioViT-H/16 model with 1280 embedding dim and 32 transformer blocks', 'create a PixioViT-1B/16 model with 1536 embedding dim and 48 transformer blocks', 'run multinode Pixio distillation training via submitit on a Slurm cluster with configurable GPUs and nodes', 'submit a Slurm job for Pixio distillation training with custom partition, account, and QoS settings', 'configure a submitit AutoExecutor with GPU, memory, and node parameters for distributed training jobs', 'create a Trainer checkpoint that requeues the job with a fresh init file and delayed submission', 'setup GPU arguments from the submitit JobEnvironment including rank, world size, and output directory']
```

Usage

```
{'run_distillation_training': 'run Pixio knowledge distillation training with a teacher model and one or more student models', 'run_multi_student_distillation': 'run distillation training with multiple student models learning from a single teacher model simultaneously', 'run_distillation_with_webdataset': 'run distillation training using a webdataset instead of ImageNet as the data source', 'run_distillation_with_masking': 'run distillation training with configurable patch masking ratio and grid size for student models', 'run_distillation_resume': 'resume a distillation training run from a saved checkpoint at a specific epoch'}
```

## File: facebookresearch_pixio/distillation/models_distill.py

Prompts

```
['run one epoch of teacher-student distillation training with multiple student models and gradient accumulation', 'build a training loop that computes teacher features once and aligns multiple student models via feature loss', 'refactor train_one_epoch to support additional loss types beyond classification and patch alignment losses', 'review how feat_align_loss is computed between student and teacher features with masking and ids_keep', 'summarize the metric logging and wandb tracking for per-student loss_cls, loss_patch, and learning rate', 'run Pixio knowledge distillation training with a teacher model and one or more student models', 'run distillation training with multiple student models learning from a single teacher model simultaneously', 'run distillation training using a webdataset instead of ImageNet as the data source', 'run distillation training with configurable patch masking ratio and grid size for student models', 'resume a distillation training run from a saved checkpoint at a specific epoch', 'build a PixioViT transformer model with configurable patch size, depth, and embedding dimensions', 'create a PixioViT-B/16 model with 768 embedding dim and 12 transformer blocks', 'create a PixioViT-L/16 model with 1024 embedding dim and 24 transformer blocks', 'create a PixioViT-H/16 model with 1280 embedding dim and 32 transformer blocks', 'create a PixioViT-1B/16 model with 1536 embedding dim and 48 transformer blocks', 'run multinode Pixio distillation training via submitit on a Slurm cluster with configurable GPUs and nodes', 'submit a Slurm job for Pixio distillation training with custom partition, account, and QoS settings', 'configure a submitit AutoExecutor with GPU, memory, and node parameters for distributed training jobs', 'create a Trainer checkpoint that requeues the job with a fresh init file and delayed submission', 'setup GPU arguments from the submitit JobEnvironment including rank, world size, and output directory']
```

Usage

```
{'build_pixio_vit_model': 'build a PixioViT transformer model with configurable patch size, depth, and embedding dimensions', 'create_pixio_vitb16': 'create a PixioViT-B/16 model with 768 embedding dim and 12 transformer blocks', 'create_pixio_vitl16': 'create a PixioViT-L/16 model with 1024 embedding dim and 24 transformer blocks', 'create_pixio_vith16': 'create a PixioViT-H/16 model with 1280 embedding dim and 32 transformer blocks', 'create_pixio_vit1b16': 'create a PixioViT-1B/16 model with 1536 embedding dim and 48 transformer blocks'}
```

## File: facebookresearch_pixio/distillation/submitit_distill.py

Prompts

```
['run one epoch of teacher-student distillation training with multiple student models and gradient accumulation', 'build a training loop that computes teacher features once and aligns multiple student models via feature loss', 'refactor train_one_epoch to support additional loss types beyond classification and patch alignment losses', 'review how feat_align_loss is computed between student and teacher features with masking and ids_keep', 'summarize the metric logging and wandb tracking for per-student loss_cls, loss_patch, and learning rate', 'run Pixio knowledge distillation training with a teacher model and one or more student models', 'run distillation training with multiple student models learning from a single teacher model simultaneously', 'run distillation training using a webdataset instead of ImageNet as the data source', 'run distillation training with configurable patch masking ratio and grid size for student models', 'resume a distillation training run from a saved checkpoint at a specific epoch', 'build a PixioViT transformer model with configurable patch size, depth, and embedding dimensions', 'create a PixioViT-B/16 model with 768 embedding dim and 12 transformer blocks', 'create a PixioViT-L/16 model with 1024 embedding dim and 24 transformer blocks', 'create a PixioViT-H/16 model with 1280 embedding dim and 32 transformer blocks', 'create a PixioViT-1B/16 model with 1536 embedding dim and 48 transformer blocks', 'run multinode Pixio distillation training via submitit on a Slurm cluster with configurable GPUs and nodes', 'submit a Slurm job for Pixio distillation training with custom partition, account, and QoS settings', 'configure a submitit AutoExecutor with GPU, memory, and node parameters for distributed training jobs', 'create a Trainer checkpoint that requeues the job with a fresh init file and delayed submission', 'setup GPU arguments from the submitit JobEnvironment including rank, world size, and output directory']
```

Usage

```
{'run_multinode_distillation': 'run multinode Pixio distillation training via submitit on a Slurm cluster with configurable GPUs and nodes', 'submit_slurm_job': 'submit a Slurm job for Pixio distillation training with custom partition, account, and QoS settings', 'configure_trainer_executor': 'configure a submitit AutoExecutor with GPU, memory, and node parameters for distributed training jobs', 'create_trainer_checkpoint': 'create a Trainer checkpoint that requeues the job with a fresh init file and delayed submission', 'setup_gpu_args': 'setup GPU arguments from the submitit JobEnvironment including rank, world size, and output directory'}
```

