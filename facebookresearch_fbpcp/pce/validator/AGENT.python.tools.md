# Agent Python Tools

- repo: facebookresearch/fbpcp
- repo_uri: https://github.com/facebookresearch/fbpcp

## File: facebookresearch_fbpcp/pce/validator/duplicate_pce_resources_checker.py

Prompts

```
['create a DuplicatePCEResourcesChecker instance and call check_pce to find duplicate VPCs, route tables, and clusters for a given PCE ID', 'use DuplicatePCEResourcesChecker to detect multiple VPCs tagged with the same PCE ID in an AWS region', 'use DuplicatePCEResourcesChecker to detect multiple route tables tagged with the same PCE ID in an AWS region', "use DuplicatePCEResourcesChecker to detect multiple VPC peerings associated with a PCE's VPC and tagged with the same PCE ID", 'use DuplicatePCEResourcesChecker to detect multiple ECS clusters or container definitions tagged with the same PCE ID', 'run all PCE network and compute validation steps and return warnings and errors', 'validate that a PCE VPC CIDR is private and within the expected default range', 'validate that inbound peer routes are allowed by firewall rules with correct port ranges', 'validate that the route table has active VPC peering and internet gateway routes', 'summarize a list of validation results grouped by error and warning result codes', 'run the pce validator CLI to validate AWS PCE environments by region and pce-id', 'validate a PCE environment by checking duplicate resources and running network and compute validation steps', 'get the caller ARN from AWS STS using region, key id, and key data credentials', 'review the ValidatorResult enum that defines SUCCESS and ERROR exit codes for validation outcomes', 'review the main function that parses CLI args via docopt and schema validation before calling validate_pce']
```

Usage

```
{'check_duplicate_pce_resources': 'create a DuplicatePCEResourcesChecker instance and call check_pce to find duplicate VPCs, route tables, and clusters for a given PCE ID', 'detect_duplicate_vpcs': 'use DuplicatePCEResourcesChecker to detect multiple VPCs tagged with the same PCE ID in an AWS region', 'detect_duplicate_route_tables': 'use DuplicatePCEResourcesChecker to detect multiple route tables tagged with the same PCE ID in an AWS region', 'detect_duplicate_vpc_peerings': "use DuplicatePCEResourcesChecker to detect multiple VPC peerings associated with a PCE's VPC and tagged with the same PCE ID", 'detect_duplicate_ecs_resources': 'use DuplicatePCEResourcesChecker to detect multiple ECS clusters or container definitions tagged with the same PCE ID'}
```

## File: facebookresearch_fbpcp/pce/validator/validation_suite.py

Prompts

```
['create a DuplicatePCEResourcesChecker instance and call check_pce to find duplicate VPCs, route tables, and clusters for a given PCE ID', 'use DuplicatePCEResourcesChecker to detect multiple VPCs tagged with the same PCE ID in an AWS region', 'use DuplicatePCEResourcesChecker to detect multiple route tables tagged with the same PCE ID in an AWS region', "use DuplicatePCEResourcesChecker to detect multiple VPC peerings associated with a PCE's VPC and tagged with the same PCE ID", 'use DuplicatePCEResourcesChecker to detect multiple ECS clusters or container definitions tagged with the same PCE ID', 'run all PCE network and compute validation steps and return warnings and errors', 'validate that a PCE VPC CIDR is private and within the expected default range', 'validate that inbound peer routes are allowed by firewall rules with correct port ranges', 'validate that the route table has active VPC peering and internet gateway routes', 'summarize a list of validation results grouped by error and warning result codes', 'run the pce validator CLI to validate AWS PCE environments by region and pce-id', 'validate a PCE environment by checking duplicate resources and running network and compute validation steps', 'get the caller ARN from AWS STS using region, key id, and key data credentials', 'review the ValidatorResult enum that defines SUCCESS and ERROR exit codes for validation outcomes', 'review the main function that parses CLI args via docopt and schema validation before calling validate_pce']
```

Usage

```
{'run_validate_network_and_compute': 'run all PCE network and compute validation steps and return warnings and errors', 'validate_vpc_cidr': 'validate that a PCE VPC CIDR is private and within the expected default range', 'validate_firewall': 'validate that inbound peer routes are allowed by firewall rules with correct port ranges', 'validate_route_table': 'validate that the route table has active VPC peering and internet gateway routes', 'summarize_errors': 'summarize a list of validation results grouped by error and warning result codes'}
```

## File: facebookresearch_fbpcp/pce/validator/validator.py

Prompts

```
['create a DuplicatePCEResourcesChecker instance and call check_pce to find duplicate VPCs, route tables, and clusters for a given PCE ID', 'use DuplicatePCEResourcesChecker to detect multiple VPCs tagged with the same PCE ID in an AWS region', 'use DuplicatePCEResourcesChecker to detect multiple route tables tagged with the same PCE ID in an AWS region', "use DuplicatePCEResourcesChecker to detect multiple VPC peerings associated with a PCE's VPC and tagged with the same PCE ID", 'use DuplicatePCEResourcesChecker to detect multiple ECS clusters or container definitions tagged with the same PCE ID', 'run all PCE network and compute validation steps and return warnings and errors', 'validate that a PCE VPC CIDR is private and within the expected default range', 'validate that inbound peer routes are allowed by firewall rules with correct port ranges', 'validate that the route table has active VPC peering and internet gateway routes', 'summarize a list of validation results grouped by error and warning result codes', 'run the pce validator CLI to validate AWS PCE environments by region and pce-id', 'validate a PCE environment by checking duplicate resources and running network and compute validation steps', 'get the caller ARN from AWS STS using region, key id, and key data credentials', 'review the ValidatorResult enum that defines SUCCESS and ERROR exit codes for validation outcomes', 'review the main function that parses CLI args via docopt and schema validation before calling validate_pce']
```

Usage

```
{'run_pce_validator_cli': 'run the pce validator CLI to validate AWS PCE environments by region and pce-id', 'validate_pce_function': 'validate a PCE environment by checking duplicate resources and running network and compute validation steps', 'get_arn_function': 'get the caller ARN from AWS STS using region, key id, and key data credentials', 'review_ValidatorResult_enum': 'review the ValidatorResult enum that defines SUCCESS and ERROR exit codes for validation outcomes', 'review_main_cli_parsing': 'review the main function that parses CLI args via docopt and schema validation before calling validate_pce'}
```

