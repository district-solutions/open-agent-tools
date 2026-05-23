# Agent Python Tools

- repo: facebookresearch/recipes
- repo_uri: https://github.com/facebookresearch/recipes

## File: facebookresearch_recipes/torchrecipes/paved_path/airflow/charnn_dag.py

Prompts

```
['create an Airflow DAG to train a charnn model using AWS Batch and torchx', 'run a BashOperator task that trains charnn via torchx on a GPU job queue', 'wait for an AWS Batch job to complete by polling its status via boto3', 'export a trained PyTorch module to TorchScript format using a BatchOperator job', 'deploy an exported TorchScript model to a serving endpoint via a BatchOperator job']
```

Usage

```
{'create_airflow_dag_charnn': 'create an Airflow DAG to train a charnn model using AWS Batch and torchx', 'run_train_task': 'run a BashOperator task that trains charnn via torchx on a GPU job queue', 'wait_for_batch_job': 'wait for an AWS Batch job to complete by polling its status via boto3', 'export_torchscript_module': 'export a trained PyTorch module to TorchScript format using a BatchOperator job', 'deploy_exported_model': 'deploy an exported TorchScript model to a serving endpoint via a BatchOperator job'}
```

