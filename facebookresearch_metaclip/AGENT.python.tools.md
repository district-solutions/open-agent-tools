# Agent Python Tools

- repo: facebookresearch/metaclip
- repo_uri: https://github.com/facebookresearch/metaclip

## File: facebookresearch_metaclip/submit.py

Prompts

```
['submit a multinode training job to the SLURM scheduler using submitit with a config name', 'parse command line arguments for job submission including ngpus, nodes, timeout, and partition', 'create a Trainer instance and call it to dynamically import and run a training main function', 'checkpoint a Trainer to requeue the job with the latest epoch checkpoint file', 'get a unique initialization file URI for distributed training process group setup']
```

Usage

```
{'submit_multinode_training_job': 'submit a multinode training job to the SLURM scheduler using submitit with a config name', 'run_parse_args': 'parse command line arguments for job submission including ngpus, nodes, timeout, and partition', 'create_Trainer_call': 'create a Trainer instance and call it to dynamically import and run a training main function', 'checkpoint_Trainer_requeue': 'checkpoint a Trainer to requeue the job with the latest epoch checkpoint file', 'get_init_file_dist_url': 'get a unique initialization file URI for distributed training process group setup'}
```

