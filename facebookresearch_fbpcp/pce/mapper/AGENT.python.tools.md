# Agent Python Tools

- repo: facebookresearch/fbpcp
- repo_uri: https://github.com/facebookresearch/fbpcp

## File: facebookresearch_fbpcp/pce/mapper/aws.py

Prompts

```
['create a python module that maps AWS IAM role ID and attached policies to an IAMRole object', 'create a python module that extracts the AWS CloudWatch log group name from an ECS task definition', 'review the map_attachedrolepolicies_to_rolepolicies function to ensure it correctly returns None for empty policies', 'review the map_ecstaskdefinition_to_awslogsgroupname function to verify it handles missing keys gracefully', 'test the map_ecstaskdefinition_to_awslogsgroupname function with a sample ECS task definition dictionary']
```

Usage

```
{'map_attachedrolepolicies_to_rolepolicies': 'create a python module that maps AWS IAM role ID and attached policies to an IAMRole object', 'map_ecstaskdefinition_to_awslogsgroupname': 'create a python module that extracts the AWS CloudWatch log group name from an ECS task definition', 'review_map_attachedrolepolicies_to_rolepolicies': 'review the map_attachedrolepolicies_to_rolepolicies function to ensure it correctly returns None for empty policies', 'review_map_ecstaskdefinition_to_awslogsgroupname': 'review the map_ecstaskdefinition_to_awslogsgroupname function to verify it handles missing keys gracefully', 'test_map_ecstaskdefinition_to_awslogsgroupname': 'test the map_ecstaskdefinition_to_awslogsgroupname function with a sample ECS task definition dictionary'}
```

