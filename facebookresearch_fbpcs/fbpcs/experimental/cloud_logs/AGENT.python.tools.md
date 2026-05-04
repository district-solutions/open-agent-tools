# Agent Python Tools

- repo: facebookresearch/fbpcs
- repo_uri: https://github.com/facebookresearch/fbpcs

## File: facebookresearch_fbpcs/fbpcs/experimental/cloud_logs/aws_log_retriever.py

Prompts

```
['fetch log events from AWS CloudWatch for a given container ARN identifier', "get the AWS CloudWatch console URL for a container's log stream by container ARN", 'create an AWSLogRetriever instance with a custom log group guess strategy and CloudWatch service args', 'review the LogGroupGuessStrategy enum to choose between FROM_PCE_SERVICE and FROM_ARN strategies', 'summarize the ContainerInfo dataclass fields including awslogs_group, awslogs_stream, and awslogs_region', 'create a DummyLogRetriever instance that returns an empty string for any container log URL', 'use DummyLogRetriever get_log_url to retrieve an empty log URL for a given container ID', 'use DummyLogRetriever fetch to return an empty list of log events for a container', 'use DummyLogRetriever log_events_to_str to format a list of log events into a newline-separated string', 'test the DummyLogRetriever class to verify it returns empty results for all log retrieval methods', 'review the LogRetriever abstract class and its get_log_url method for container log URL retrieval', 'review the LogRetriever fetch method that returns a list of LogEvent objects for a container', 'review the LogRetriever log_events_to_str method that formats log events into a newline-separated string', 'refactor the LogRetriever fetch method to actually retrieve log events from a cloud provider', 'build a concrete subclass of LogRetriever that implements get_log_url for a specific cloud provider']
```

Usage

```
{'fetch_aws_container_logs': 'fetch log events from AWS CloudWatch for a given container ARN identifier', 'get_aws_log_url': "get the AWS CloudWatch console URL for a container's log stream by container ARN", 'create_aws_log_retriever': 'create an AWSLogRetriever instance with a custom log group guess strategy and CloudWatch service args', 'review_log_group_guess_strategy': 'review the LogGroupGuessStrategy enum to choose between FROM_PCE_SERVICE and FROM_ARN strategies', 'summarize_container_info_dataclass': 'summarize the ContainerInfo dataclass fields including awslogs_group, awslogs_stream, and awslogs_region'}
```

## File: facebookresearch_fbpcs/fbpcs/experimental/cloud_logs/dummy_log_retriever.py

Prompts

```
['fetch log events from AWS CloudWatch for a given container ARN identifier', "get the AWS CloudWatch console URL for a container's log stream by container ARN", 'create an AWSLogRetriever instance with a custom log group guess strategy and CloudWatch service args', 'review the LogGroupGuessStrategy enum to choose between FROM_PCE_SERVICE and FROM_ARN strategies', 'summarize the ContainerInfo dataclass fields including awslogs_group, awslogs_stream, and awslogs_region', 'create a DummyLogRetriever instance that returns an empty string for any container log URL', 'use DummyLogRetriever get_log_url to retrieve an empty log URL for a given container ID', 'use DummyLogRetriever fetch to return an empty list of log events for a container', 'use DummyLogRetriever log_events_to_str to format a list of log events into a newline-separated string', 'test the DummyLogRetriever class to verify it returns empty results for all log retrieval methods', 'review the LogRetriever abstract class and its get_log_url method for container log URL retrieval', 'review the LogRetriever fetch method that returns a list of LogEvent objects for a container', 'review the LogRetriever log_events_to_str method that formats log events into a newline-separated string', 'refactor the LogRetriever fetch method to actually retrieve log events from a cloud provider', 'build a concrete subclass of LogRetriever that implements get_log_url for a specific cloud provider']
```

Usage

```
{'create_DummyLogRetriever': 'create a DummyLogRetriever instance that returns an empty string for any container log URL', 'use_DummyLogRetriever_get_log_url': 'use DummyLogRetriever get_log_url to retrieve an empty log URL for a given container ID', 'use_DummyLogRetriever_fetch': 'use DummyLogRetriever fetch to return an empty list of log events for a container', 'use_DummyLogRetriever_log_events_to_str': 'use DummyLogRetriever log_events_to_str to format a list of log events into a newline-separated string', 'test_DummyLogRetriever': 'test the DummyLogRetriever class to verify it returns empty results for all log retrieval methods'}
```

## File: facebookresearch_fbpcs/fbpcs/experimental/cloud_logs/log_retriever.py

Prompts

```
['fetch log events from AWS CloudWatch for a given container ARN identifier', "get the AWS CloudWatch console URL for a container's log stream by container ARN", 'create an AWSLogRetriever instance with a custom log group guess strategy and CloudWatch service args', 'review the LogGroupGuessStrategy enum to choose between FROM_PCE_SERVICE and FROM_ARN strategies', 'summarize the ContainerInfo dataclass fields including awslogs_group, awslogs_stream, and awslogs_region', 'create a DummyLogRetriever instance that returns an empty string for any container log URL', 'use DummyLogRetriever get_log_url to retrieve an empty log URL for a given container ID', 'use DummyLogRetriever fetch to return an empty list of log events for a container', 'use DummyLogRetriever log_events_to_str to format a list of log events into a newline-separated string', 'test the DummyLogRetriever class to verify it returns empty results for all log retrieval methods', 'review the LogRetriever abstract class and its get_log_url method for container log URL retrieval', 'review the LogRetriever fetch method that returns a list of LogEvent objects for a container', 'review the LogRetriever log_events_to_str method that formats log events into a newline-separated string', 'refactor the LogRetriever fetch method to actually retrieve log events from a cloud provider', 'build a concrete subclass of LogRetriever that implements get_log_url for a specific cloud provider']
```

Usage

```
{'review_LogRetriever_get_log_url': 'review the LogRetriever abstract class and its get_log_url method for container log URL retrieval', 'review_LogRetriever_fetch': 'review the LogRetriever fetch method that returns a list of LogEvent objects for a container', 'review_LogRetriever_log_events_to_str': 'review the LogRetriever log_events_to_str method that formats log events into a newline-separated string', 'refactor_LogRetriever_fetch': 'refactor the LogRetriever fetch method to actually retrieve log events from a cloud provider', 'build_LogRetriever_subclass': 'build a concrete subclass of LogRetriever that implements get_log_url for a specific cloud provider'}
```

