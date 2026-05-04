# Agent Python Tools

- repo: facebookresearch/fbpcp
- repo_uri: https://github.com/facebookresearch/fbpcp

## File: facebookresearch_fbpcp/pce/validator/tests/test_duplicate_pce_resources_checker.py

Prompts

```
['test the DuplicatePCEResourcesChecker class to detect duplicate VPCs, route tables, and clusters for a PCE ID', 'test check_pce method returns empty list when all PCE resources are unique across VPCs and clusters', 'test check_pce method detects multiple duplicated resource types including VPCs, route tables, and clusters', 'test check_pce method detects a single resource type with three or more duplicate instances', 'review the DuplicatePCEResourcesChecker class and its check_pce method for detecting duplicate PCE cloud resources', 'test the validate_pce function to check PCE resource validation with mocked dependencies', 'test the main CLI entry point for the PCE validator with various argument combinations', 'test the get_arn function that wraps STSGateway to retrieve the caller ARN', 'test the validate_pce function to detect duplicate PCE resources like VPCs', 'test the validate_pce function to verify proper ERROR logging when validation fails', 'test the ValidationSuite to validate VPC CIDR blocks are private IPv4 networks', 'test the ValidationSuite to validate firewall rulesets allow inbound traffic from VPC peering CIDR', 'test the ValidationSuite to validate route tables have active VPC peering and IGW routes', 'test the ValidationSuite to validate subnets span all availability zones in the region', 'test the ValidationSuite to run all network and compute validation steps at once']
```

Usage

```
{'test_duplicate_pce_resources_checker': 'test the DuplicatePCEResourcesChecker class to detect duplicate VPCs, route tables, and clusters for a PCE ID', 'test_check_pce_no_duplicates': 'test check_pce method returns empty list when all PCE resources are unique across VPCs and clusters', 'test_check_pce_multiple_duplicated': 'test check_pce method detects multiple duplicated resource types including VPCs, route tables, and clusters', 'test_check_pce_single_multiplicated': 'test check_pce method detects a single resource type with three or more duplicate instances', 'review_duplicate_pce_resources_checker': 'review the DuplicatePCEResourcesChecker class and its check_pce method for detecting duplicate PCE cloud resources'}
```

## File: facebookresearch_fbpcp/pce/validator/tests/test_validator.py

Prompts

```
['test the DuplicatePCEResourcesChecker class to detect duplicate VPCs, route tables, and clusters for a PCE ID', 'test check_pce method returns empty list when all PCE resources are unique across VPCs and clusters', 'test check_pce method detects multiple duplicated resource types including VPCs, route tables, and clusters', 'test check_pce method detects a single resource type with three or more duplicate instances', 'review the DuplicatePCEResourcesChecker class and its check_pce method for detecting duplicate PCE cloud resources', 'test the validate_pce function to check PCE resource validation with mocked dependencies', 'test the main CLI entry point for the PCE validator with various argument combinations', 'test the get_arn function that wraps STSGateway to retrieve the caller ARN', 'test the validate_pce function to detect duplicate PCE resources like VPCs', 'test the validate_pce function to verify proper ERROR logging when validation fails', 'test the ValidationSuite to validate VPC CIDR blocks are private IPv4 networks', 'test the ValidationSuite to validate firewall rulesets allow inbound traffic from VPC peering CIDR', 'test the ValidationSuite to validate route tables have active VPC peering and IGW routes', 'test the ValidationSuite to validate subnets span all availability zones in the region', 'test the ValidationSuite to run all network and compute validation steps at once']
```

Usage

```
{'test_validate_pce': 'test the validate_pce function to check PCE resource validation with mocked dependencies', 'test_main_cli': 'test the main CLI entry point for the PCE validator with various argument combinations', 'test_get_arn': 'test the get_arn function that wraps STSGateway to retrieve the caller ARN', 'test_duplicate_resource_detection': 'test the validate_pce function to detect duplicate PCE resources like VPCs', 'test_validation_failure_logging': 'test the validate_pce function to verify proper ERROR logging when validation fails'}
```

## File: facebookresearch_fbpcp/pce/validator/tests/validator_tests.py

Prompts

```
['test the DuplicatePCEResourcesChecker class to detect duplicate VPCs, route tables, and clusters for a PCE ID', 'test check_pce method returns empty list when all PCE resources are unique across VPCs and clusters', 'test check_pce method detects multiple duplicated resource types including VPCs, route tables, and clusters', 'test check_pce method detects a single resource type with three or more duplicate instances', 'review the DuplicatePCEResourcesChecker class and its check_pce method for detecting duplicate PCE cloud resources', 'test the validate_pce function to check PCE resource validation with mocked dependencies', 'test the main CLI entry point for the PCE validator with various argument combinations', 'test the get_arn function that wraps STSGateway to retrieve the caller ARN', 'test the validate_pce function to detect duplicate PCE resources like VPCs', 'test the validate_pce function to verify proper ERROR logging when validation fails', 'test the ValidationSuite to validate VPC CIDR blocks are private IPv4 networks', 'test the ValidationSuite to validate firewall rulesets allow inbound traffic from VPC peering CIDR', 'test the ValidationSuite to validate route tables have active VPC peering and IGW routes', 'test the ValidationSuite to validate subnets span all availability zones in the region', 'test the ValidationSuite to run all network and compute validation steps at once']
```

Usage

```
{'test_validate_vpc_cidr': 'test the ValidationSuite to validate VPC CIDR blocks are private IPv4 networks', 'test_validate_firewall': 'test the ValidationSuite to validate firewall rulesets allow inbound traffic from VPC peering CIDR', 'test_validate_route_table': 'test the ValidationSuite to validate route tables have active VPC peering and IGW routes', 'test_validate_subnet': 'test the ValidationSuite to validate subnets span all availability zones in the region', 'test_validate_network_and_compute': 'test the ValidationSuite to run all network and compute validation steps at once'}
```

