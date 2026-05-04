# Agent Python Tools

- repo: facebookresearch/fbpcp
- repo_uri: https://github.com/facebookresearch/fbpcp

## File: facebookresearch_fbpcp/tests/error/mapper/test_aws.py

Prompts

```
['test map_aws_error converts a generic AWS ClientError into a PcpError with the request ID', 'test map_aws_error converts a ThrottlingException ClientError into a ThrottlingError with the request ID', 'test the TestMapAwsError unittest class that validates AWS error mapping behavior', 'review map_aws_error to understand how AWS ClientError codes map to PcpError subclasses', 'refactor TestMapAwsError to add test cases for InvalidParameterException and LimitExceededException error codes', 'test that map_gcp_error maps a GoogleCloudError to a PcpError', 'test that map_gcp_error maps a 429 GoogleCloudError to a ThrottlingError', 'run the TestMapGCPError unittest class to verify GCP error mapping behavior', 'review the test_pcs_error method that validates generic GCP error mapping to PcpError', 'review the test_throttling_error method that validates 429 error mapping to ThrottlingError', 'test map_k8s_error maps ApiValueError and ApiTypeError to InvalidParameterError', 'test map_k8s_error maps ApiException status 429 to ThrottlingError', 'test map_k8s_error maps ApiException status 503 to default PcpError', 'review the map_k8s_error function that maps Kubernetes exceptions to PcpError types', 'refactor TestMapK8SError to add test cases for ApiException status 404 mapping']
```

Usage

```
{'test_map_aws_error_pcp': 'test map_aws_error converts a generic AWS ClientError into a PcpError with the request ID', 'test_map_aws_error_throttling': 'test map_aws_error converts a ThrottlingException ClientError into a ThrottlingError with the request ID', 'test_TestMapAwsError_class': 'test the TestMapAwsError unittest class that validates AWS error mapping behavior', 'review_map_aws_error': 'review map_aws_error to understand how AWS ClientError codes map to PcpError subclasses', 'refactor_TestMapAwsError': 'refactor TestMapAwsError to add test cases for InvalidParameterException and LimitExceededException error codes'}
```

## File: facebookresearch_fbpcp/tests/error/mapper/test_gcp.py

Prompts

```
['test map_aws_error converts a generic AWS ClientError into a PcpError with the request ID', 'test map_aws_error converts a ThrottlingException ClientError into a ThrottlingError with the request ID', 'test the TestMapAwsError unittest class that validates AWS error mapping behavior', 'review map_aws_error to understand how AWS ClientError codes map to PcpError subclasses', 'refactor TestMapAwsError to add test cases for InvalidParameterException and LimitExceededException error codes', 'test that map_gcp_error maps a GoogleCloudError to a PcpError', 'test that map_gcp_error maps a 429 GoogleCloudError to a ThrottlingError', 'run the TestMapGCPError unittest class to verify GCP error mapping behavior', 'review the test_pcs_error method that validates generic GCP error mapping to PcpError', 'review the test_throttling_error method that validates 429 error mapping to ThrottlingError', 'test map_k8s_error maps ApiValueError and ApiTypeError to InvalidParameterError', 'test map_k8s_error maps ApiException status 429 to ThrottlingError', 'test map_k8s_error maps ApiException status 503 to default PcpError', 'review the map_k8s_error function that maps Kubernetes exceptions to PcpError types', 'refactor TestMapK8SError to add test cases for ApiException status 404 mapping']
```

Usage

```
{'test_map_gcp_error_generic': 'test that map_gcp_error maps a GoogleCloudError to a PcpError', 'test_map_gcp_error_throttling': 'test that map_gcp_error maps a 429 GoogleCloudError to a ThrottlingError', 'run_test_map_gcp_error_class': 'run the TestMapGCPError unittest class to verify GCP error mapping behavior', 'review_test_pcs_error_method': 'review the test_pcs_error method that validates generic GCP error mapping to PcpError', 'review_test_throttling_error_method': 'review the test_throttling_error method that validates 429 error mapping to ThrottlingError'}
```

## File: facebookresearch_fbpcp/tests/error/mapper/test_k8s.py

Prompts

```
['test map_aws_error converts a generic AWS ClientError into a PcpError with the request ID', 'test map_aws_error converts a ThrottlingException ClientError into a ThrottlingError with the request ID', 'test the TestMapAwsError unittest class that validates AWS error mapping behavior', 'review map_aws_error to understand how AWS ClientError codes map to PcpError subclasses', 'refactor TestMapAwsError to add test cases for InvalidParameterException and LimitExceededException error codes', 'test that map_gcp_error maps a GoogleCloudError to a PcpError', 'test that map_gcp_error maps a 429 GoogleCloudError to a ThrottlingError', 'run the TestMapGCPError unittest class to verify GCP error mapping behavior', 'review the test_pcs_error method that validates generic GCP error mapping to PcpError', 'review the test_throttling_error method that validates 429 error mapping to ThrottlingError', 'test map_k8s_error maps ApiValueError and ApiTypeError to InvalidParameterError', 'test map_k8s_error maps ApiException status 429 to ThrottlingError', 'test map_k8s_error maps ApiException status 503 to default PcpError', 'review the map_k8s_error function that maps Kubernetes exceptions to PcpError types', 'refactor TestMapK8SError to add test cases for ApiException status 404 mapping']
```

Usage

```
{'test_map_k8s_error_invalid': 'test map_k8s_error maps ApiValueError and ApiTypeError to InvalidParameterError', 'test_map_k8s_error_throttling': 'test map_k8s_error maps ApiException status 429 to ThrottlingError', 'test_map_k8s_error_default': 'test map_k8s_error maps ApiException status 503 to default PcpError', 'review_map_k8s_error': 'review the map_k8s_error function that maps Kubernetes exceptions to PcpError types', 'refactor_test_map_k8s_error': 'refactor TestMapK8SError to add test cases for ApiException status 404 mapping'}
```

