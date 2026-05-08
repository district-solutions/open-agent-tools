# Agent Python Tools

- repo: facebookresearch/collaborative-reasoner
- repo_uri: https://github.com/facebookresearch/collaborative-reasoner

## File: facebookresearch_collaborative-reasoner/finetuning/eval_finetuned_model.py

Prompts

```
['run eval_model to evaluate a finetuned model checkpoint at a given step on a specified task', 'run eval_model with skip_convert to skip weight conversion when the HuggingFace checkpoint already exists', 'run eval_model with additional evaluation arguments passed via the add_eval_args list parameter', 'run eval_model with a custom logs_dir_name to change where evaluation logs are saved', 'run the eval_model CLI via fire to evaluate a model checkpoint by step, size, and task', 'run iterative SFT or DPO training with eval and sampling across multiple iterations using fire CLI', 'deploy a HuggingFace model as a temporary serving application using the matrix append deploy function', 'evaluate a model checkpoint and sample reasoning traces from it in a single step', 'launch fairseq2 finetuning training and convert model weights to HuggingFace format', 'create iteratively split training data using random sample or even split strategies', 'run fairseq2 instruction fine-tuning on an 8b or 70b model using SLURM job submission', 'run fairseq2 preference fine-tuning with DPO on a 70b model via SLURM batch job', 'run fairseq2 preference fine-tuning with SimPO on a model using SLURM and config files', 'run fairseq2 fine-tuning without checkpoint evaluation monitoring by setting no_eval to true', 'run fairseq2 fine-tuning with additional custom arguments passed via the add_args parameter', 'wait for a submitit Job to complete with periodic status polling and optional error exit', 'run a teacher-student interaction evaluation experiment on SLURM via submitit with a Llama extractor model', 'submit a teacher-student model inference job to SLURM using submitit AutoExecutor with configurable parameters', 'configure a submitit AutoExecutor with SLURM account, QoS, node, and CPU parameters for job submission', 'build a command list for the teacher-student interaction validation experiment with optional matrix and extra args']
```

Usage

```
{'run_eval_model': 'run eval_model to evaluate a finetuned model checkpoint at a given step on a specified task', 'run_eval_model_skip_convert': 'run eval_model with skip_convert to skip weight conversion when the HuggingFace checkpoint already exists', 'run_eval_model_custom_args': 'run eval_model with additional evaluation arguments passed via the add_eval_args list parameter', 'run_eval_model_custom_logs': 'run eval_model with a custom logs_dir_name to change where evaluation logs are saved', 'run_eval_model_cli': 'run the eval_model CLI via fire to evaluate a model checkpoint by step, size, and task'}
```

## File: facebookresearch_collaborative-reasoner/finetuning/iterative_training.py

Prompts

```
['run eval_model to evaluate a finetuned model checkpoint at a given step on a specified task', 'run eval_model with skip_convert to skip weight conversion when the HuggingFace checkpoint already exists', 'run eval_model with additional evaluation arguments passed via the add_eval_args list parameter', 'run eval_model with a custom logs_dir_name to change where evaluation logs are saved', 'run the eval_model CLI via fire to evaluate a model checkpoint by step, size, and task', 'run iterative SFT or DPO training with eval and sampling across multiple iterations using fire CLI', 'deploy a HuggingFace model as a temporary serving application using the matrix append deploy function', 'evaluate a model checkpoint and sample reasoning traces from it in a single step', 'launch fairseq2 finetuning training and convert model weights to HuggingFace format', 'create iteratively split training data using random sample or even split strategies', 'run fairseq2 instruction fine-tuning on an 8b or 70b model using SLURM job submission', 'run fairseq2 preference fine-tuning with DPO on a 70b model via SLURM batch job', 'run fairseq2 preference fine-tuning with SimPO on a model using SLURM and config files', 'run fairseq2 fine-tuning without checkpoint evaluation monitoring by setting no_eval to true', 'run fairseq2 fine-tuning with additional custom arguments passed via the add_args parameter', 'wait for a submitit Job to complete with periodic status polling and optional error exit', 'run a teacher-student interaction evaluation experiment on SLURM via submitit with a Llama extractor model', 'submit a teacher-student model inference job to SLURM using submitit AutoExecutor with configurable parameters', 'configure a submitit AutoExecutor with SLURM account, QoS, node, and CPU parameters for job submission', 'build a command list for the teacher-student interaction validation experiment with optional matrix and extra args']
```

Usage

```
{'run_iterative_training': 'run iterative SFT or DPO training with eval and sampling across multiple iterations using fire CLI', 'deploy_model_with_matrix': 'deploy a HuggingFace model as a temporary serving application using the matrix append deploy function', 'eval_and_sample_model': 'evaluate a model checkpoint and sample reasoning traces from it in a single step', 'launch_training_and_conversion': 'launch fairseq2 finetuning training and convert model weights to HuggingFace format', 'create_iter_split_data': 'create iteratively split training data using random sample or even split strategies'}
```

## File: facebookresearch_collaborative-reasoner/finetuning/run_fairseq2_training.py

Prompts

```
['run eval_model to evaluate a finetuned model checkpoint at a given step on a specified task', 'run eval_model with skip_convert to skip weight conversion when the HuggingFace checkpoint already exists', 'run eval_model with additional evaluation arguments passed via the add_eval_args list parameter', 'run eval_model with a custom logs_dir_name to change where evaluation logs are saved', 'run the eval_model CLI via fire to evaluate a model checkpoint by step, size, and task', 'run iterative SFT or DPO training with eval and sampling across multiple iterations using fire CLI', 'deploy a HuggingFace model as a temporary serving application using the matrix append deploy function', 'evaluate a model checkpoint and sample reasoning traces from it in a single step', 'launch fairseq2 finetuning training and convert model weights to HuggingFace format', 'create iteratively split training data using random sample or even split strategies', 'run fairseq2 instruction fine-tuning on an 8b or 70b model using SLURM job submission', 'run fairseq2 preference fine-tuning with DPO on a 70b model via SLURM batch job', 'run fairseq2 preference fine-tuning with SimPO on a model using SLURM and config files', 'run fairseq2 fine-tuning without checkpoint evaluation monitoring by setting no_eval to true', 'run fairseq2 fine-tuning with additional custom arguments passed via the add_args parameter', 'wait for a submitit Job to complete with periodic status polling and optional error exit', 'run a teacher-student interaction evaluation experiment on SLURM via submitit with a Llama extractor model', 'submit a teacher-student model inference job to SLURM using submitit AutoExecutor with configurable parameters', 'configure a submitit AutoExecutor with SLURM account, QoS, node, and CPU parameters for job submission', 'build a command list for the teacher-student interaction validation experiment with optional matrix and extra args']
```

Usage

```
{'run_fairseq2_finetuning_sft': 'run fairseq2 instruction fine-tuning on an 8b or 70b model using SLURM job submission', 'run_fairseq2_finetuning_dpo': 'run fairseq2 preference fine-tuning with DPO on a 70b model via SLURM batch job', 'run_fairseq2_finetuning_simpo': 'run fairseq2 preference fine-tuning with SimPO on a model using SLURM and config files', 'run_fairseq2_finetuning_no_eval': 'run fairseq2 fine-tuning without checkpoint evaluation monitoring by setting no_eval to true', 'run_fairseq2_finetuning_with_args': 'run fairseq2 fine-tuning with additional custom arguments passed via the add_args parameter'}
```

## File: facebookresearch_collaborative-reasoner/finetuning/slurm_utils.py

Prompts

```
['run eval_model to evaluate a finetuned model checkpoint at a given step on a specified task', 'run eval_model with skip_convert to skip weight conversion when the HuggingFace checkpoint already exists', 'run eval_model with additional evaluation arguments passed via the add_eval_args list parameter', 'run eval_model with a custom logs_dir_name to change where evaluation logs are saved', 'run the eval_model CLI via fire to evaluate a model checkpoint by step, size, and task', 'run iterative SFT or DPO training with eval and sampling across multiple iterations using fire CLI', 'deploy a HuggingFace model as a temporary serving application using the matrix append deploy function', 'evaluate a model checkpoint and sample reasoning traces from it in a single step', 'launch fairseq2 finetuning training and convert model weights to HuggingFace format', 'create iteratively split training data using random sample or even split strategies', 'run fairseq2 instruction fine-tuning on an 8b or 70b model using SLURM job submission', 'run fairseq2 preference fine-tuning with DPO on a 70b model via SLURM batch job', 'run fairseq2 preference fine-tuning with SimPO on a model using SLURM and config files', 'run fairseq2 fine-tuning without checkpoint evaluation monitoring by setting no_eval to true', 'run fairseq2 fine-tuning with additional custom arguments passed via the add_args parameter', 'wait for a submitit Job to complete with periodic status polling and optional error exit', 'run a teacher-student interaction evaluation experiment on SLURM via submitit with a Llama extractor model', 'submit a teacher-student model inference job to SLURM using submitit AutoExecutor with configurable parameters', 'configure a submitit AutoExecutor with SLURM account, QoS, node, and CPU parameters for job submission', 'build a command list for the teacher-student interaction validation experiment with optional matrix and extra args']
```

Usage

```
{'wait_job_completion': 'wait for a submitit Job to complete with periodic status polling and optional error exit', 'run_ts_interaction': 'run a teacher-student interaction evaluation experiment on SLURM via submitit with a Llama extractor model', 'submit_ts_eval_job': 'submit a teacher-student model inference job to SLURM using submitit AutoExecutor with configurable parameters', 'configure_slurm_executor': 'configure a submitit AutoExecutor with SLURM account, QoS, node, and CPU parameters for job submission', 'build_ts_exp_command': 'build a command list for the teacher-student interaction validation experiment with optional matrix and extra args'}
```

