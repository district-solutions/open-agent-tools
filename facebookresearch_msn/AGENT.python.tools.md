# Agent Python Tools

- repo: facebookresearch/msn
- repo_uri: https://github.com/facebookresearch/msn

## File: facebookresearch_msn/linear_eval.py

Prompts

```
['run linear evaluation on a pretrained encoder using a linear classifier with distributed training', 'create a LinearClassifier with LayerNorm and optional L2 normalization for classification on encoder features', 'load a pretrained encoder and optional classifier state dict from a checkpoint file', 'initialize a pretrained encoder, linear classifier, SGD optimizer, and cosine learning rate scheduler', 'load encoder, classifier, optimizer, and scheduler state from a saved checkpoint path', 'run logistic regression evaluation on pretrained DEiT model embeddings for ImageNet classification', 'run the make_embeddings function to extract feature embeddings from a data loader using a pretrained encoder', 'run load_pretrained to load pretrained weights into a DEiT encoder model from a checkpoint file', 'run init_model to create and initialize a DEiT encoder with pretrained weights on a given device', 'run the main evaluation pipeline that computes embeddings and fits a logistic classifier on train and test sets', 'run the MSN training script with a YAML config file across multiple GPUs using torch multiprocessing', 'run the process_main function to load config params, init distributed training, and start MSN training', 'run torch multiprocessing spawn to launch MSN training processes across specified GPU devices', 'review the process_main function that loads YAML configs, dumps params, and initializes distributed training', 'review the argparse parser that accepts fname and devices arguments for MSN training configuration', 'run the MSN pre-training job on a SLURM cluster using submitit with a YAML config file', 'create a Trainer instance with a config YAML file path and optional linear evaluation mode', 'submit a distributed training job using submitit AutoExecutor with configurable nodes and GPUs per node', 'create a checkpointed Trainer submission that resumes training from a saved model checkpoint']
```

Usage

```
{'run_linear_evaluation': 'run linear evaluation on a pretrained encoder using a linear classifier with distributed training', 'create_linear_classifier': 'create a LinearClassifier with LayerNorm and optional L2 normalization for classification on encoder features', 'load_pretrained_encoder': 'load a pretrained encoder and optional classifier state dict from a checkpoint file', 'init_model_with_optimizer': 'initialize a pretrained encoder, linear classifier, SGD optimizer, and cosine learning rate scheduler', 'load_checkpoint_from_path': 'load encoder, classifier, optimizer, and scheduler state from a saved checkpoint path'}
```

## File: facebookresearch_msn/logistic_eval.py

Prompts

```
['run linear evaluation on a pretrained encoder using a linear classifier with distributed training', 'create a LinearClassifier with LayerNorm and optional L2 normalization for classification on encoder features', 'load a pretrained encoder and optional classifier state dict from a checkpoint file', 'initialize a pretrained encoder, linear classifier, SGD optimizer, and cosine learning rate scheduler', 'load encoder, classifier, optimizer, and scheduler state from a saved checkpoint path', 'run logistic regression evaluation on pretrained DEiT model embeddings for ImageNet classification', 'run the make_embeddings function to extract feature embeddings from a data loader using a pretrained encoder', 'run load_pretrained to load pretrained weights into a DEiT encoder model from a checkpoint file', 'run init_model to create and initialize a DEiT encoder with pretrained weights on a given device', 'run the main evaluation pipeline that computes embeddings and fits a logistic classifier on train and test sets', 'run the MSN training script with a YAML config file across multiple GPUs using torch multiprocessing', 'run the process_main function to load config params, init distributed training, and start MSN training', 'run torch multiprocessing spawn to launch MSN training processes across specified GPU devices', 'review the process_main function that loads YAML configs, dumps params, and initializes distributed training', 'review the argparse parser that accepts fname and devices arguments for MSN training configuration', 'run the MSN pre-training job on a SLURM cluster using submitit with a YAML config file', 'create a Trainer instance with a config YAML file path and optional linear evaluation mode', 'submit a distributed training job using submitit AutoExecutor with configurable nodes and GPUs per node', 'create a checkpointed Trainer submission that resumes training from a saved model checkpoint']
```

Usage

```
{'run_logistic_evaluation': 'run logistic regression evaluation on pretrained DEiT model embeddings for ImageNet classification', 'run_make_embeddings': 'run the make_embeddings function to extract feature embeddings from a data loader using a pretrained encoder', 'run_load_pretrained': 'run load_pretrained to load pretrained weights into a DEiT encoder model from a checkpoint file', 'run_init_model': 'run init_model to create and initialize a DEiT encoder with pretrained weights on a given device', 'run_main': 'run the main evaluation pipeline that computes embeddings and fits a logistic classifier on train and test sets'}
```

## File: facebookresearch_msn/main.py

Prompts

```
['run linear evaluation on a pretrained encoder using a linear classifier with distributed training', 'create a LinearClassifier with LayerNorm and optional L2 normalization for classification on encoder features', 'load a pretrained encoder and optional classifier state dict from a checkpoint file', 'initialize a pretrained encoder, linear classifier, SGD optimizer, and cosine learning rate scheduler', 'load encoder, classifier, optimizer, and scheduler state from a saved checkpoint path', 'run logistic regression evaluation on pretrained DEiT model embeddings for ImageNet classification', 'run the make_embeddings function to extract feature embeddings from a data loader using a pretrained encoder', 'run load_pretrained to load pretrained weights into a DEiT encoder model from a checkpoint file', 'run init_model to create and initialize a DEiT encoder with pretrained weights on a given device', 'run the main evaluation pipeline that computes embeddings and fits a logistic classifier on train and test sets', 'run the MSN training script with a YAML config file across multiple GPUs using torch multiprocessing', 'run the process_main function to load config params, init distributed training, and start MSN training', 'run torch multiprocessing spawn to launch MSN training processes across specified GPU devices', 'review the process_main function that loads YAML configs, dumps params, and initializes distributed training', 'review the argparse parser that accepts fname and devices arguments for MSN training configuration', 'run the MSN pre-training job on a SLURM cluster using submitit with a YAML config file', 'create a Trainer instance with a config YAML file path and optional linear evaluation mode', 'submit a distributed training job using submitit AutoExecutor with configurable nodes and GPUs per node', 'create a checkpointed Trainer submission that resumes training from a saved model checkpoint']
```

Usage

```
{'run_msn_training': 'run the MSN training script with a YAML config file across multiple GPUs using torch multiprocessing', 'run_process_main': 'run the process_main function to load config params, init distributed training, and start MSN training', 'run_multi_gpu_spawn': 'run torch multiprocessing spawn to launch MSN training processes across specified GPU devices', 'review_process_main': 'review the process_main function that loads YAML configs, dumps params, and initializes distributed training', 'review_argparse_parser': 'review the argparse parser that accepts fname and devices arguments for MSN training configuration'}
```

## File: facebookresearch_msn/main_distributed.py

Prompts

```
['run linear evaluation on a pretrained encoder using a linear classifier with distributed training', 'create a LinearClassifier with LayerNorm and optional L2 normalization for classification on encoder features', 'load a pretrained encoder and optional classifier state dict from a checkpoint file', 'initialize a pretrained encoder, linear classifier, SGD optimizer, and cosine learning rate scheduler', 'load encoder, classifier, optimizer, and scheduler state from a saved checkpoint path', 'run logistic regression evaluation on pretrained DEiT model embeddings for ImageNet classification', 'run the make_embeddings function to extract feature embeddings from a data loader using a pretrained encoder', 'run load_pretrained to load pretrained weights into a DEiT encoder model from a checkpoint file', 'run init_model to create and initialize a DEiT encoder with pretrained weights on a given device', 'run the main evaluation pipeline that computes embeddings and fits a logistic classifier on train and test sets', 'run the MSN training script with a YAML config file across multiple GPUs using torch multiprocessing', 'run the process_main function to load config params, init distributed training, and start MSN training', 'run torch multiprocessing spawn to launch MSN training processes across specified GPU devices', 'review the process_main function that loads YAML configs, dumps params, and initializes distributed training', 'review the argparse parser that accepts fname and devices arguments for MSN training configuration', 'run the MSN pre-training job on a SLURM cluster using submitit with a YAML config file', 'create a Trainer instance with a config YAML file path and optional linear evaluation mode', 'submit a distributed training job using submitit AutoExecutor with configurable nodes and GPUs per node', 'create a checkpointed Trainer submission that resumes training from a saved model checkpoint']
```

Usage

```
{'run_distributed_pretraining': 'run the MSN pre-training job on a SLURM cluster using submitit with a YAML config file', 'run_linear_evaluation': 'run linear evaluation on a pre-trained MSN model by passing the --linear-eval flag', 'create_trainer_instance': 'create a Trainer instance with a config YAML file path and optional linear evaluation mode', 'submit_job_with_executor': 'submit a distributed training job using submitit AutoExecutor with configurable nodes and GPUs per node', 'checkpoint_trainer': 'create a checkpointed Trainer submission that resumes training from a saved model checkpoint'}
```

