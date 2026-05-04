# Agent Python Tools

- repo: facebookresearch/fbpcs
- repo_uri: https://github.com/facebookresearch/fbpcs

## File: facebookresearch_fbpcs/fbpcs/experimental/cloud_logs/test/test_log_retriever.py

Prompts

```
['test the AWSLogRetriever get_log_url method with a valid ECS container ARN', 'test the AWSLogRetriever raises IndexError when given an invalid container ID string', 'test the AWSLogRetriever get_log_url with a custom awslogs_group for the publisher', 'test the AWSLogRetriever get_log_url using the default FROM_ARN guess strategy for a partner container', 'test the AWSLogRetriever _get_cloudwatch_log_svc method with valid and invalid CloudWatchLogServiceArgs']
```

Usage

```
{'test_AWSLogRetriever_get_log_url': 'test the AWSLogRetriever get_log_url method with a valid ECS container ARN', 'test_AWSLogRetriever_invalid_container_id': 'test the AWSLogRetriever raises IndexError when given an invalid container ID string', 'test_AWSLogRetriever_publisher_log_group': 'test the AWSLogRetriever get_log_url with a custom awslogs_group for the publisher', 'test_AWSLogRetriever_partner_log_group': 'test the AWSLogRetriever get_log_url using the default FROM_ARN guess strategy for a partner container', 'test_AWSLogRetriever_cloudwatch_log_service': 'test the AWSLogRetriever _get_cloudwatch_log_svc method with valid and invalid CloudWatchLogServiceArgs'}
```

