# Agent Python Tools

- repo: facebookresearch/fbpcp
- repo_uri: https://github.com/facebookresearch/fbpcp

## File: facebookresearch_fbpcp/onedocker/gateway/dynamodb.py

Prompts

```
['create a DynamoDBGateway instance with a region and optional AWS credentials to interact with DynamoDB', 'create a python module to put an item into a DynamoDB table with a conditional check for duplicate instance_id', 'create a python module to get an item from a DynamoDB table by its key name and key value', 'create a python module to update an attribute of an existing DynamoDB item by its key', 'create a python module to delete an item from a DynamoDB table by its key name and key value', 'build a RepositoryServiceGateway instance that initializes an AWS-backed OneDocker repository service', 'get package measurements by name and version using the RepositoryServiceGateway get_measurements method', 'review the RepositoryServiceGateway class and its AWS cloud provider initialization pattern', 'refactor the get_measurements method to support additional cloud providers beyond AWS', 'test the RepositoryServiceGateway get_measurements method with a sample package name and version']
```

Usage

```
{'create_dynamodb_gateway': 'create a DynamoDBGateway instance with a region and optional AWS credentials to interact with DynamoDB', 'put_item_dynamodb': 'create a python module to put an item into a DynamoDB table with a conditional check for duplicate instance_id', 'get_item_dynamodb': 'create a python module to get an item from a DynamoDB table by its key name and key value', 'update_item_dynamodb': 'create a python module to update an attribute of an existing DynamoDB item by its key', 'delete_item_dynamodb': 'create a python module to delete an item from a DynamoDB table by its key name and key value'}
```

## File: facebookresearch_fbpcp/onedocker/gateway/repository_service.py

Prompts

```
['create a DynamoDBGateway instance with a region and optional AWS credentials to interact with DynamoDB', 'create a python module to put an item into a DynamoDB table with a conditional check for duplicate instance_id', 'create a python module to get an item from a DynamoDB table by its key name and key value', 'create a python module to update an attribute of an existing DynamoDB item by its key', 'create a python module to delete an item from a DynamoDB table by its key name and key value', 'build a RepositoryServiceGateway instance that initializes an AWS-backed OneDocker repository service', 'get package measurements by name and version using the RepositoryServiceGateway get_measurements method', 'review the RepositoryServiceGateway class and its AWS cloud provider initialization pattern', 'refactor the get_measurements method to support additional cloud providers beyond AWS', 'test the RepositoryServiceGateway get_measurements method with a sample package name and version']
```

Usage

```
{'build_repository_service_gateway': 'build a RepositoryServiceGateway instance that initializes an AWS-backed OneDocker repository service', 'get_package_measurements': 'get package measurements by name and version using the RepositoryServiceGateway get_measurements method', 'review_repository_service_gateway': 'review the RepositoryServiceGateway class and its AWS cloud provider initialization pattern', 'refactor_get_measurements': 'refactor the get_measurements method to support additional cloud providers beyond AWS', 'test_repository_service_gateway': 'test the RepositoryServiceGateway get_measurements method with a sample package name and version'}
```

