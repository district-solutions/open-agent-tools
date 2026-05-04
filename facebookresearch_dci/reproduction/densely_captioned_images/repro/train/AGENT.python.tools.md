# Agent Python Tools

- repo: facebookresearch/dci
- repo_uri: https://github.com/facebookresearch/dci

## File: facebookresearch_dci/reproduction/densely_captioned_images/repro/train/coco_wrap.py

Prompts

```
['get the COCO train 2017 dataset source with captions and Spacy negatives for a given split', 'get the COCO valid 2017 dataset source with captions and Spacy negatives for validation', 'get the COCO dataset source with Spacy antonym negatives enabled for contrastive learning', 'create a PyTorch COCO dataset wrapper that processes images and captions with a CLIP processor', 'review the COCODataset getitem method that returns tokenized captions, negatives, and pixel values', 'create a PyTorch dataset from a localized narratives source list with CLIP processing', 'review the COCOLocalizedNarrativesDataset getitem method that processes images and captions with CLIP', 'summarize the get_dataset_source function that loads annotations and filters by token length', 'run a CLIP model training job with LoRA adapters on densely captioned image datasets', 'create a training configuration dataclass with LoRA, dataset, loss, and sampling hyperparameters', 'build a descriptive output directory name string from a CLIPAndNegConfig object', 'create a submitit job wrapper to queue and checkpoint CLIP training runs', 'register the CLIPAndNegConfig dataclass with Hydra for CLI-based training execution', 'create a ClipAndNegTrainer instance with custom loss_alpha, loss_beta, and sampler settings', 'run compute_loss on a model with positive and negative bag inputs to get joint loss', 'get the training DataLoader with a configurable sampler choice like rand, seq, or rand_batch', 'compute clip-loss and neg-loss metrics from evaluation predictions returned by the model', 'configure the training sampler to use RandomSampler, SequentialSampler, or DenseCaptionBatchSampler']
```

Usage

```
{'get_dataset_source_train': 'get the COCO train 2017 dataset source with captions and Spacy negatives for a given split', 'get_dataset_source_valid': 'get the COCO valid 2017 dataset source with captions and Spacy negatives for validation', 'get_dataset_source_antonyms': 'get the COCO dataset source with Spacy antonym negatives enabled for contrastive learning', 'create_COCODataset': 'create a PyTorch COCO dataset wrapper that processes images and captions with a CLIP processor', 'review_COCODataset_getitem': 'review the COCODataset getitem method that returns tokenized captions, negatives, and pixel values'}
```

## File: facebookresearch_dci/reproduction/densely_captioned_images/repro/train/localized_narratives_wrap.py

Prompts

```
['get the COCO train 2017 dataset source with captions and Spacy negatives for a given split', 'get the COCO valid 2017 dataset source with captions and Spacy negatives for validation', 'get the COCO dataset source with Spacy antonym negatives enabled for contrastive learning', 'create a PyTorch COCO dataset wrapper that processes images and captions with a CLIP processor', 'review the COCODataset getitem method that returns tokenized captions, negatives, and pixel values', 'create a PyTorch dataset from a localized narratives source list with CLIP processing', 'review the COCOLocalizedNarrativesDataset getitem method that processes images and captions with CLIP', 'summarize the get_dataset_source function that loads annotations and filters by token length', 'run a CLIP model training job with LoRA adapters on densely captioned image datasets', 'create a training configuration dataclass with LoRA, dataset, loss, and sampling hyperparameters', 'build a descriptive output directory name string from a CLIPAndNegConfig object', 'create a submitit job wrapper to queue and checkpoint CLIP training runs', 'register the CLIPAndNegConfig dataclass with Hydra for CLI-based training execution', 'create a ClipAndNegTrainer instance with custom loss_alpha, loss_beta, and sampler settings', 'run compute_loss on a model with positive and negative bag inputs to get joint loss', 'get the training DataLoader with a configurable sampler choice like rand, seq, or rand_batch', 'compute clip-loss and neg-loss metrics from evaluation predictions returned by the model', 'configure the training sampler to use RandomSampler, SequentialSampler, or DenseCaptionBatchSampler']
```

Usage

```
{'get_dataset_source_train': 'get the COCO train dataset source with localized narratives and CLIP token filtering', 'get_dataset_source_valid': 'get the COCO validation dataset source with localized narratives and antonym negatives', 'create_COCOLocalizedNarrativesDataset': 'create a PyTorch dataset from a localized narratives source list with CLIP processing', 'review_COCOLocalizedNarrativesDataset_getitem': 'review the COCOLocalizedNarrativesDataset getitem method that processes images and captions with CLIP', 'summarize_get_dataset_source': 'summarize the get_dataset_source function that loads annotations and filters by token length'}
```

## File: facebookresearch_dci/reproduction/densely_captioned_images/repro/train/train_clip.py

Prompts

```
['get the COCO train 2017 dataset source with captions and Spacy negatives for a given split', 'get the COCO valid 2017 dataset source with captions and Spacy negatives for validation', 'get the COCO dataset source with Spacy antonym negatives enabled for contrastive learning', 'create a PyTorch COCO dataset wrapper that processes images and captions with a CLIP processor', 'review the COCODataset getitem method that returns tokenized captions, negatives, and pixel values', 'create a PyTorch dataset from a localized narratives source list with CLIP processing', 'review the COCOLocalizedNarrativesDataset getitem method that processes images and captions with CLIP', 'summarize the get_dataset_source function that loads annotations and filters by token length', 'run a CLIP model training job with LoRA adapters on densely captioned image datasets', 'create a training configuration dataclass with LoRA, dataset, loss, and sampling hyperparameters', 'build a descriptive output directory name string from a CLIPAndNegConfig object', 'create a submitit job wrapper to queue and checkpoint CLIP training runs', 'register the CLIPAndNegConfig dataclass with Hydra for CLI-based training execution', 'create a ClipAndNegTrainer instance with custom loss_alpha, loss_beta, and sampler settings', 'run compute_loss on a model with positive and negative bag inputs to get joint loss', 'get the training DataLoader with a configurable sampler choice like rand, seq, or rand_batch', 'compute clip-loss and neg-loss metrics from evaluation predictions returned by the model', 'configure the training sampler to use RandomSampler, SequentialSampler, or DenseCaptionBatchSampler']
```

Usage

```
{'run_train_clip': 'run a CLIP model training job with LoRA adapters on densely captioned image datasets', 'CLIPAndNegConfig': 'create a training configuration dataclass with LoRA, dataset, loss, and sampling hyperparameters', 'get_dir_name': 'build a descriptive output directory name string from a CLIPAndNegConfig object', 'CLIPTrainJob': 'create a submitit job wrapper to queue and checkpoint CLIP training runs', 'config_store': 'register the CLIPAndNegConfig dataclass with Hydra for CLI-based training execution'}
```

## File: facebookresearch_dci/reproduction/densely_captioned_images/repro/train/trainer.py

Prompts

```
['get the COCO train 2017 dataset source with captions and Spacy negatives for a given split', 'get the COCO valid 2017 dataset source with captions and Spacy negatives for validation', 'get the COCO dataset source with Spacy antonym negatives enabled for contrastive learning', 'create a PyTorch COCO dataset wrapper that processes images and captions with a CLIP processor', 'review the COCODataset getitem method that returns tokenized captions, negatives, and pixel values', 'create a PyTorch dataset from a localized narratives source list with CLIP processing', 'review the COCOLocalizedNarrativesDataset getitem method that processes images and captions with CLIP', 'summarize the get_dataset_source function that loads annotations and filters by token length', 'run a CLIP model training job with LoRA adapters on densely captioned image datasets', 'create a training configuration dataclass with LoRA, dataset, loss, and sampling hyperparameters', 'build a descriptive output directory name string from a CLIPAndNegConfig object', 'create a submitit job wrapper to queue and checkpoint CLIP training runs', 'register the CLIPAndNegConfig dataclass with Hydra for CLI-based training execution', 'create a ClipAndNegTrainer instance with custom loss_alpha, loss_beta, and sampler settings', 'run compute_loss on a model with positive and negative bag inputs to get joint loss', 'get the training DataLoader with a configurable sampler choice like rand, seq, or rand_batch', 'compute clip-loss and neg-loss metrics from evaluation predictions returned by the model', 'configure the training sampler to use RandomSampler, SequentialSampler, or DenseCaptionBatchSampler']
```

Usage

```
{'create_ClipAndNegTrainer': 'create a ClipAndNegTrainer instance with custom loss_alpha, loss_beta, and sampler settings', 'run_compute_loss': 'run compute_loss on a model with positive and negative bag inputs to get joint loss', 'get_train_dataloader': 'get the training DataLoader with a configurable sampler choice like rand, seq, or rand_batch', 'compute_metrics_eval': 'compute clip-loss and neg-loss metrics from evaluation predictions returned by the model', 'configure_get_train_sampler': 'configure the training sampler to use RandomSampler, SequentialSampler, or DenseCaptionBatchSampler'}
```

