# Agent Python Tools

- repo: facebookresearch/suncet
- repo_uri: https://github.com/facebookresearch/suncet

## File: facebookresearch_suncet/main.py

Prompts

```
['run the PAWS training script using a YAML config file on specified GPU devices', 'run the Suncet training script using a YAML config file on specified GPU devices', 'run the fine-tuning script using a YAML config file on specified GPU devices', 'run the SNN fine-tuning script using a YAML config file on specified GPU devices', 'run the multi-GPU process main function with a config file and selected training script', 'run a distributed training job on SLURM using submitit with a YAML config file', 'batch launch multiple training jobs by providing a YAML file listing config file names', 'run the SNN evaluation pipeline on ImageNet or CIFAR-10 with a pretrained encoder model', 'evaluate embeddings using a Softmax Nearest Neighbor classifier and report top1 and top5 accuracy', 'create feature embeddings for all images in a data loader using a pretrained encoder', 'build a Softmax Nearest Neighbor classifier from training embeddings and labels with temperature scaling', 'initialize a ResNet or Wide ResNet encoder with a projection head and optional prediction head']
```

Usage

```
{'run_paws_train': 'run the PAWS training script using a YAML config file on specified GPU devices', 'run_suncet_train': 'run the Suncet training script using a YAML config file on specified GPU devices', 'run_fine_tune': 'run the fine-tuning script using a YAML config file on specified GPU devices', 'run_snn_fine_tune': 'run the SNN fine-tuning script using a YAML config file on specified GPU devices', 'run_process_main': 'run the multi-GPU process main function with a config file and selected training script'}
```

## File: facebookresearch_suncet/main_distributed.py

Prompts

```
['run the PAWS training script using a YAML config file on specified GPU devices', 'run the Suncet training script using a YAML config file on specified GPU devices', 'run the fine-tuning script using a YAML config file on specified GPU devices', 'run the SNN fine-tuning script using a YAML config file on specified GPU devices', 'run the multi-GPU process main function with a config file and selected training script', 'run a distributed training job on SLURM using submitit with a YAML config file', 'batch launch multiple training jobs by providing a YAML file listing config file names', 'run the SNN evaluation pipeline on ImageNet or CIFAR-10 with a pretrained encoder model', 'evaluate embeddings using a Softmax Nearest Neighbor classifier and report top1 and top5 accuracy', 'create feature embeddings for all images in a data loader using a pretrained encoder', 'build a Softmax Nearest Neighbor classifier from training embeddings and labels with temperature scaling', 'initialize a ResNet or Wide ResNet encoder with a projection head and optional prediction head']
```

Usage

```
{'run_distributed_training': 'run a distributed training job on SLURM using submitit with a YAML config file', 'run_batch_launch': 'batch launch multiple training jobs by providing a YAML file listing config file names', 'run_paws_train': 'run the PAWS training script via the distributed launcher with --sel paws_train', 'run_suncet_train': 'run the SUNCET training script via the distributed launcher with --sel suncet_train', 'run_fine_tune': 'run the fine-tuning script via the distributed launcher with --sel fine_tune'}
```

## File: facebookresearch_suncet/snn_eval.py

Prompts

```
['run the PAWS training script using a YAML config file on specified GPU devices', 'run the Suncet training script using a YAML config file on specified GPU devices', 'run the fine-tuning script using a YAML config file on specified GPU devices', 'run the SNN fine-tuning script using a YAML config file on specified GPU devices', 'run the multi-GPU process main function with a config file and selected training script', 'run a distributed training job on SLURM using submitit with a YAML config file', 'batch launch multiple training jobs by providing a YAML file listing config file names', 'run the SNN evaluation pipeline on ImageNet or CIFAR-10 with a pretrained encoder model', 'evaluate embeddings using a Softmax Nearest Neighbor classifier and report top1 and top5 accuracy', 'create feature embeddings for all images in a data loader using a pretrained encoder', 'build a Softmax Nearest Neighbor classifier from training embeddings and labels with temperature scaling', 'initialize a ResNet or Wide ResNet encoder with a projection head and optional prediction head']
```

Usage

```
{'main': 'run the SNN evaluation pipeline on ImageNet or CIFAR-10 with a pretrained encoder model', 'evaluate_embeddings': 'evaluate embeddings using a Softmax Nearest Neighbor classifier and report top1 and top5 accuracy', 'make_embeddings': 'create feature embeddings for all images in a data loader using a pretrained encoder', 'make_snn': 'build a Softmax Nearest Neighbor classifier from training embeddings and labels with temperature scaling', 'init_model': 'initialize a ResNet or Wide ResNet encoder with a projection head and optional prediction head'}
```

