# Agent Python Tools

- repo: facebookresearch/fbpcs
- repo_uri: https://github.com/facebookresearch/fbpcs

## File: facebookresearch_fbpcs/fbpcs/infra/cloud_bridge/deployment_helper/aws/test/test_aws_deployment_helper.py

Prompts

```
['create an AWS IAM user using AwsDeploymentHelper.create_user with a given username', 'delete an AWS IAM user using AwsDeploymentHelper.delete_user with a given username', 'create an IAM policy from a JSON template using AwsDeploymentHelper.create_policy with params', 'attach or detach an IAM policy to a user using attach_user_policy or detach_user_policy', 'create, delete, or list AWS access keys using create_access_key, delete_access_key, and list_access_keys', 'test the AwsDeploymentHelperTool create method to add an IAM user with a given username', 'test the AwsDeploymentHelperTool create method to add an IAM policy with region and template path', 'test the AwsDeploymentHelperTool create method to attach an IAM policy to a user', 'test the AwsDeploymentHelperTool destroy method to delete IAM users, policies, and detach policies', 'review the TestAwsDeploymentHelperTool unittest class and its subTest cases for IAM user and policy operations']
```

Usage

```
{'create_aws_user': 'create an AWS IAM user using AwsDeploymentHelper.create_user with a given username', 'delete_aws_user': 'delete an AWS IAM user using AwsDeploymentHelper.delete_user with a given username', 'create_iam_policy': 'create an IAM policy from a JSON template using AwsDeploymentHelper.create_policy with params', 'attach_detach_user_policy': 'attach or detach an IAM policy to a user using attach_user_policy or detach_user_policy', 'manage_access_keys': 'create, delete, or list AWS access keys using create_access_key, delete_access_key, and list_access_keys'}
```

## File: facebookresearch_fbpcs/fbpcs/infra/cloud_bridge/deployment_helper/aws/test/test_aws_deployment_helper_tool.py

Prompts

```
['create an AWS IAM user using AwsDeploymentHelper.create_user with a given username', 'delete an AWS IAM user using AwsDeploymentHelper.delete_user with a given username', 'create an IAM policy from a JSON template using AwsDeploymentHelper.create_policy with params', 'attach or detach an IAM policy to a user using attach_user_policy or detach_user_policy', 'create, delete, or list AWS access keys using create_access_key, delete_access_key, and list_access_keys', 'test the AwsDeploymentHelperTool create method to add an IAM user with a given username', 'test the AwsDeploymentHelperTool create method to add an IAM policy with region and template path', 'test the AwsDeploymentHelperTool create method to attach an IAM policy to a user', 'test the AwsDeploymentHelperTool destroy method to delete IAM users, policies, and detach policies', 'review the TestAwsDeploymentHelperTool unittest class and its subTest cases for IAM user and policy operations']
```

Usage

```
{'test_aws_deployment_helper_create_iam_user': 'test the AwsDeploymentHelperTool create method to add an IAM user with a given username', 'test_aws_deployment_helper_create_iam_policy': 'test the AwsDeploymentHelperTool create method to add an IAM policy with region and template path', 'test_aws_deployment_helper_attach_policy': 'test the AwsDeploymentHelperTool create method to attach an IAM policy to a user', 'test_aws_deployment_helper_destroy_resources': 'test the AwsDeploymentHelperTool destroy method to delete IAM users, policies, and detach policies', 'review_TestAwsDeploymentHelperTool_class': 'review the TestAwsDeploymentHelperTool unittest class and its subTest cases for IAM user and policy operations'}
```

