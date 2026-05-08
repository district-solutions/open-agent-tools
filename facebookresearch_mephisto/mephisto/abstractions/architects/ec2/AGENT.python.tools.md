# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/mephisto/abstractions/architects/ec2/ec2_architect.py

Prompts

```
['deploy a task server to an EC2 instance using the EC2Architect deploy method', 'compile and build server files into a directory ready for EC2 deployment', 'shut down an EC2 server instance and clean up its routing rules and resources', 'get a list of websocket channel objects for the EC2 architect subdomain', 'check if a subdomain is unused locally by verifying no detail file exists', 'create a VPC with two subnets, an internet gateway, and routing tables in us-east-2', 'create an EC2 instance with a specified key pair, security group, subnet, and volume size', 'create an internet-facing application load balancer across the given subnets and security group', 'cleanup and delete all EC2, ELB, VPC, and security group resources from a server details file', 'deploy the fallback server files to an EC2 instance via scp and run first setup', 'launch an EC2 fallback server with VPC, load balancer, and SSL certificate for a given domain', 'update an open JSON file by overwriting its contents with new dictionary data', 'run the interactive CLI to set up a Mephisto EC2 fallback server with IAM credentials', 'review the launch_ec2_fallback function to understand the AWS resource provisioning order and idempotency logic', 'refactor launch_ec2_fallback to support AWS regions beyond us-east-2']
```

Usage

```
{'deploy_ec2_architect': 'deploy a task server to an EC2 instance using the EC2Architect deploy method', 'compile_server_ec2': 'compile and build server files into a directory ready for EC2 deployment', 'shutdown_ec2_server': 'shut down an EC2 server instance and clean up its routing rules and resources', 'get_websocket_channels_ec2': 'get a list of websocket channel objects for the EC2 architect subdomain', 'check_domain_unused_ec2': 'check if a subdomain is unused locally by verifying no detail file exists'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/architects/ec2/ec2_helpers.py

Prompts

```
['deploy a task server to an EC2 instance using the EC2Architect deploy method', 'compile and build server files into a directory ready for EC2 deployment', 'shut down an EC2 server instance and clean up its routing rules and resources', 'get a list of websocket channel objects for the EC2 architect subdomain', 'check if a subdomain is unused locally by verifying no detail file exists', 'create a VPC with two subnets, an internet gateway, and routing tables in us-east-2', 'create an EC2 instance with a specified key pair, security group, subnet, and volume size', 'create an internet-facing application load balancer across the given subnets and security group', 'cleanup and delete all EC2, ELB, VPC, and security group resources from a server details file', 'deploy the fallback server files to an EC2 instance via scp and run first setup', 'launch an EC2 fallback server with VPC, load balancer, and SSL certificate for a given domain', 'update an open JSON file by overwriting its contents with new dictionary data', 'run the interactive CLI to set up a Mephisto EC2 fallback server with IAM credentials', 'review the launch_ec2_fallback function to understand the AWS resource provisioning order and idempotency logic', 'refactor launch_ec2_fallback to support AWS regions beyond us-east-2']
```

Usage

```
{'create_mephisto_vpc': 'create a VPC with two subnets, an internet gateway, and routing tables in us-east-2', 'create_instance': 'create an EC2 instance with a specified key pair, security group, subnet, and volume size', 'create_load_balancer': 'create an internet-facing application load balancer across the given subnets and security group', 'cleanup_fallback_server': 'cleanup and delete all EC2, ELB, VPC, and security group resources from a server details file', 'deploy_fallback_server': 'deploy the fallback server files to an EC2 instance via scp and run first setup'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/architects/ec2/prepare_ec2_servers.py

Prompts

```
['deploy a task server to an EC2 instance using the EC2Architect deploy method', 'compile and build server files into a directory ready for EC2 deployment', 'shut down an EC2 server instance and clean up its routing rules and resources', 'get a list of websocket channel objects for the EC2 architect subdomain', 'check if a subdomain is unused locally by verifying no detail file exists', 'create a VPC with two subnets, an internet gateway, and routing tables in us-east-2', 'create an EC2 instance with a specified key pair, security group, subnet, and volume size', 'create an internet-facing application load balancer across the given subnets and security group', 'cleanup and delete all EC2, ELB, VPC, and security group resources from a server details file', 'deploy the fallback server files to an EC2 instance via scp and run first setup', 'launch an EC2 fallback server with VPC, load balancer, and SSL certificate for a given domain', 'update an open JSON file by overwriting its contents with new dictionary data', 'run the interactive CLI to set up a Mephisto EC2 fallback server with IAM credentials', 'review the launch_ec2_fallback function to understand the AWS resource provisioning order and idempotency logic', 'refactor launch_ec2_fallback to support AWS regions beyond us-east-2']
```

Usage

```
{'launch_ec2_fallback': 'launch an EC2 fallback server with VPC, load balancer, and SSL certificate for a given domain', 'update_details': 'update an open JSON file by overwriting its contents with new dictionary data', 'run_main': 'run the interactive CLI to set up a Mephisto EC2 fallback server with IAM credentials', 'review_launch_ec2_fallback': 'review the launch_ec2_fallback function to understand the AWS resource provisioning order and idempotency logic', 'refactor_launch_ec2_fallback': 'refactor launch_ec2_fallback to support AWS regions beyond us-east-2'}
```

