# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/plugins/hydra_ray_launcher/integration_test_tools/create_integration_test_ami.py

Prompts

```
['run the script to create a new AWS EC2 AMI for hydra ray launcher integration tests', 'run the set_up_machine function to provision a Ray cluster, set up conda envs, and export an AMI', 'run a shell command with timestamped logging via the _run_command helper function', 'refactor the set_up_machine function to support additional Python versions or custom Ray cluster configurations', 'review the set_up_machine function for AWS security group management, Ray cluster lifecycle, and AMI creation logic', 'run the integration test AMI setup script with a specific Python version argument', 'run a shell command via subprocess and print timestamped output to stdout', 'create a conda environment named hydra with a given Python version for testing', 'install the required pip dependencies including boto3, hydra-core, and ray into the conda environment', 'review the run function that sets up a conda environment and installs dependencies for AMI integration tests']
```

Usage

```
{'run_create_integration_test_ami': 'run the script to create a new AWS EC2 AMI for hydra ray launcher integration tests', 'run_set_up_machine': 'run the set_up_machine function to provision a Ray cluster, set up conda envs, and export an AMI', 'run_run_command': 'run a shell command with timestamped logging via the _run_command helper function', 'refactor_set_up_machine': 'refactor the set_up_machine function to support additional Python versions or custom Ray cluster configurations', 'review_set_up_machine': 'review the set_up_machine function for AWS security group management, Ray cluster lifecycle, and AMI creation logic'}
```

## File: facebookresearch_hydra/plugins/hydra_ray_launcher/integration_test_tools/setup_integration_test_ami.py

Prompts

```
['run the script to create a new AWS EC2 AMI for hydra ray launcher integration tests', 'run the set_up_machine function to provision a Ray cluster, set up conda envs, and export an AMI', 'run a shell command with timestamped logging via the _run_command helper function', 'refactor the set_up_machine function to support additional Python versions or custom Ray cluster configurations', 'review the set_up_machine function for AWS security group management, Ray cluster lifecycle, and AMI creation logic', 'run the integration test AMI setup script with a specific Python version argument', 'run a shell command via subprocess and print timestamped output to stdout', 'create a conda environment named hydra with a given Python version for testing', 'install the required pip dependencies including boto3, hydra-core, and ray into the conda environment', 'review the run function that sets up a conda environment and installs dependencies for AMI integration tests']
```

Usage

```
{'run_ami_setup': 'run the integration test AMI setup script with a specific Python version argument', 'run_command_helper': 'run a shell command via subprocess and print timestamped output to stdout', 'create_conda_env': 'create a conda environment named hydra with a given Python version for testing', 'install_dependencies': 'install the required pip dependencies including boto3, hydra-core, and ray into the conda environment', 'review_run_function': 'review the run function that sets up a conda environment and installs dependencies for AMI integration tests'}
```

