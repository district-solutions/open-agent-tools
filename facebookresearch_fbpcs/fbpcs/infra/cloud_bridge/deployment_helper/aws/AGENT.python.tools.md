# Agent Python Tools

- repo: facebookresearch/fbpcs
- repo_uri: https://github.com/facebookresearch/fbpcs

## File: facebookresearch_fbpcs/fbpcs/infra/cloud_bridge/deployment_helper/aws/aws_deployment_helper.py

Prompts

```
['create an AWS IAM user with a given username using AwsDeploymentHelper.create_user', 'delete an AWS IAM user and all their access keys using AwsDeploymentHelper.delete_user_workflow', 'create an IAM policy from a JSON template with interpolated parameters using AwsDeploymentHelper.create_policy', 'attach an existing IAM policy to an AWS IAM user using AwsDeploymentHelper.attach_user_policy', 'create access and secret keys for an existing AWS IAM user using AwsDeploymentHelper.create_access_key', 'create an AWS IAM user workflow using AwsDeploymentHelperTool with a specified username via CLI args', 'attach an IAM policy to an AWS user using AwsDeploymentHelperTool with policy name and username', 'delete an AWS IAM user workflow using AwsDeploymentHelperTool destroy method with a specified username', 'detach an IAM policy from an AWS user using AwsDeploymentHelperTool with policy name and username', 'build an AwsParserBuilder that adds default AWS access key, secret key, account ID, and region arguments', 'create an argparse group with arguments to add an IAM user to an AWS account', 'create an argparse group with arguments to add an IAM policy including bucket, database, and Lambda names', 'create argparse groups to attach or detach an IAM policy to or from an IAM user', 'create argparse groups with arguments to delete an IAM user or destroy an IAM policy']
```

Usage

```
{'create_aws_iam_user': 'create an AWS IAM user with a given username using AwsDeploymentHelper.create_user', 'delete_aws_iam_user': 'delete an AWS IAM user and all their access keys using AwsDeploymentHelper.delete_user_workflow', 'create_iam_policy': 'create an IAM policy from a JSON template with interpolated parameters using AwsDeploymentHelper.create_policy', 'attach_policy_to_user': 'attach an existing IAM policy to an AWS IAM user using AwsDeploymentHelper.attach_user_policy', 'create_user_access_keys': 'create access and secret keys for an existing AWS IAM user using AwsDeploymentHelper.create_access_key'}
```

## File: facebookresearch_fbpcs/fbpcs/infra/cloud_bridge/deployment_helper/aws/aws_deployment_helper_tool.py

Prompts

```
['create an AWS IAM user with a given username using AwsDeploymentHelper.create_user', 'delete an AWS IAM user and all their access keys using AwsDeploymentHelper.delete_user_workflow', 'create an IAM policy from a JSON template with interpolated parameters using AwsDeploymentHelper.create_policy', 'attach an existing IAM policy to an AWS IAM user using AwsDeploymentHelper.attach_user_policy', 'create access and secret keys for an existing AWS IAM user using AwsDeploymentHelper.create_access_key', 'create an AWS IAM user workflow using AwsDeploymentHelperTool with a specified username via CLI args', 'attach an IAM policy to an AWS user using AwsDeploymentHelperTool with policy name and username', 'delete an AWS IAM user workflow using AwsDeploymentHelperTool destroy method with a specified username', 'detach an IAM policy from an AWS user using AwsDeploymentHelperTool with policy name and username', 'build an AwsParserBuilder that adds default AWS access key, secret key, account ID, and region arguments', 'create an argparse group with arguments to add an IAM user to an AWS account', 'create an argparse group with arguments to add an IAM policy including bucket, database, and Lambda names', 'create argparse groups to attach or detach an IAM policy to or from an IAM user', 'create argparse groups with arguments to delete an IAM user or destroy an IAM policy']
```

Usage

```
{'create_iam_user_workflow': 'create an AWS IAM user workflow using AwsDeploymentHelperTool with a specified username via CLI args', 'create_iam_policy': 'create an AWS IAM policy using AwsDeploymentHelperTool with policy name, template path, and policy parameters', 'attach_iam_policy_to_user': 'attach an IAM policy to an AWS user using AwsDeploymentHelperTool with policy name and username', 'delete_iam_user_workflow': 'delete an AWS IAM user workflow using AwsDeploymentHelperTool destroy method with a specified username', 'detach_iam_policy_from_user': 'detach an IAM policy from an AWS user using AwsDeploymentHelperTool with policy name and username'}
```

## File: facebookresearch_fbpcs/fbpcs/infra/cloud_bridge/deployment_helper/aws/aws_parser_builder.py

Prompts

```
['create an AWS IAM user with a given username using AwsDeploymentHelper.create_user', 'delete an AWS IAM user and all their access keys using AwsDeploymentHelper.delete_user_workflow', 'create an IAM policy from a JSON template with interpolated parameters using AwsDeploymentHelper.create_policy', 'attach an existing IAM policy to an AWS IAM user using AwsDeploymentHelper.attach_user_policy', 'create access and secret keys for an existing AWS IAM user using AwsDeploymentHelper.create_access_key', 'create an AWS IAM user workflow using AwsDeploymentHelperTool with a specified username via CLI args', 'attach an IAM policy to an AWS user using AwsDeploymentHelperTool with policy name and username', 'delete an AWS IAM user workflow using AwsDeploymentHelperTool destroy method with a specified username', 'detach an IAM policy from an AWS user using AwsDeploymentHelperTool with policy name and username', 'build an AwsParserBuilder that adds default AWS access key, secret key, account ID, and region arguments', 'create an argparse group with arguments to add an IAM user to an AWS account', 'create an argparse group with arguments to add an IAM policy including bucket, database, and Lambda names', 'create argparse groups to attach or detach an IAM policy to or from an IAM user', 'create argparse groups with arguments to delete an IAM user or destroy an IAM policy']
```

Usage

```
{'build_aws_parser_with_default_args': 'build an AwsParserBuilder that adds default AWS access key, secret key, account ID, and region arguments', 'create_iam_user_parser_args': 'create an argparse group with arguments to add an IAM user to an AWS account', 'create_iam_policy_parser_args': 'create an argparse group with arguments to add an IAM policy including bucket, database, and Lambda names', 'attach_detach_iam_policy_parser_args': 'create argparse groups to attach or detach an IAM policy to or from an IAM user', 'destroy_iam_user_policy_parser_args': 'create argparse groups with arguments to delete an IAM user or destroy an IAM policy'}
```

