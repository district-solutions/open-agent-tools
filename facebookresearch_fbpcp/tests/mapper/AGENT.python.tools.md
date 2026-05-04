# Agent Python Tools

- repo: facebookresearch/fbpcp
- repo_uri: https://github.com/facebookresearch/fbpcp

## File: facebookresearch_fbpcp/tests/mapper/test_aws.py

Prompts

```
['map an AWS ECS task dict to a ContainerInstance with status, IP, and exit code', 'map an AWS ECS cluster dict to a Cluster with tags, running and pending task counts', 'map an AWS EC2 subnet dict to a Subnet with availability zone and tags', 'map AWS Cost Explorer cost dicts to a CloudCost with aggregated service costs', 'map an AWS EC2 route dict to a Route with CIDR, gateway target, and state']
```

Usage

```
{'map_ecstask_to_containerinstance': 'map an AWS ECS task dict to a ContainerInstance with status, IP, and exit code', 'map_esccluster_to_clusterinstance': 'map an AWS ECS cluster dict to a Cluster with tags, running and pending task counts', 'map_ec2subnet_to_subnet': 'map an AWS EC2 subnet dict to a Subnet with availability zone and tags', 'map_cecost_to_cloud_cost': 'map AWS Cost Explorer cost dicts to a CloudCost with aggregated service costs', 'map_ec2route_to_route': 'map an AWS EC2 route dict to a Route with CIDR, gateway target, and state'}
```

