# Agent Python Tools

- repo: facebookresearch/crypten
- repo_uri: https://github.com/facebookresearch/crypten

## File: facebookresearch_crypten/scripts/aws_launcher.py

Prompts

```
['run MPC distributed training across multiple AWS EC2 instances using the aws_launcher CLI tool', 'connect to an AWS EC2 instance over SSH using paramiko with key-based authentication and retry logic', 'upload local files to remote EC2 instances concurrently using SFTP through an SSH client connection', 'execute shell commands on remote EC2 instances and stream stdout and stderr output in real time', 'query and retrieve EC2 instance objects from AWS using boto3 given a list of instance IDs', 'run a Crypten MPC training script across multiple processes using the distributed launcher', 'run a training script with a specified world size to launch multiple MPC parties', 'run a multi-process distributed training job by passing the script path and arguments', 'review the parse_args function that handles world size and training script CLI arguments', 'review the main function that spawns subprocesses with distributed environment variables for MPC training']
```

Usage

```
{'run_mpc_distributed_training_on_aws': 'run MPC distributed training across multiple AWS EC2 instances using the aws_launcher CLI tool', 'connect_to_ec2_instance_via_ssh': 'connect to an AWS EC2 instance over SSH using paramiko with key-based authentication and retry logic', 'upload_files_to_ec2_instances': 'upload local files to remote EC2 instances concurrently using SFTP through an SSH client connection', 'execute_remote_commands_on_instances': 'execute shell commands on remote EC2 instances and stream stdout and stderr output in real time', 'query_ec2_instances_by_id': 'query and retrieve EC2 instance objects from AWS using boto3 given a list of instance IDs'}
```

## File: facebookresearch_crypten/scripts/distributed_launcher.py

Prompts

```
['run MPC distributed training across multiple AWS EC2 instances using the aws_launcher CLI tool', 'connect to an AWS EC2 instance over SSH using paramiko with key-based authentication and retry logic', 'upload local files to remote EC2 instances concurrently using SFTP through an SSH client connection', 'execute shell commands on remote EC2 instances and stream stdout and stderr output in real time', 'query and retrieve EC2 instance objects from AWS using boto3 given a list of instance IDs', 'run a Crypten MPC training script across multiple processes using the distributed launcher', 'run a training script with a specified world size to launch multiple MPC parties', 'run a multi-process distributed training job by passing the script path and arguments', 'review the parse_args function that handles world size and training script CLI arguments', 'review the main function that spawns subprocesses with distributed environment variables for MPC training']
```

Usage

```
{'run_distributed_mpc_training': 'run a Crypten MPC training script across multiple processes using the distributed launcher', 'run_training_script_with_world_size': 'run a training script with a specified world size to launch multiple MPC parties', 'run_multi_process_training': 'run a multi-process distributed training job by passing the script path and arguments', 'review_parse_args': 'review the parse_args function that handles world size and training script CLI arguments', 'review_main': 'review the main function that spawns subprocesses with distributed environment variables for MPC training'}
```

