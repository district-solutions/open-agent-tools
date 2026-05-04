# Agent Python Tools

- repo: facebookresearch/fbpcp
- repo_uri: https://github.com/facebookresearch/fbpcp

## File: facebookresearch_fbpcp/fbpcp/error/mapper/aws.py

Prompts

```
['map a boto3 ClientError to the appropriate PcpError subclass based on the AWS error code', 'handle an AWS InvalidParameterException by mapping it to an InvalidParameterError', 'handle an AWS ThrottlingException by mapping it to a ThrottlingError', 'handle an AWS LimitExceededException by mapping it to a LimitExceededError', 'map any unhandled AWS ClientError to a generic PcpError with response metadata', 'map a GoogleCloudError to a PcpError based on the HTTP status code', 'handle GCP 429 throttling errors by mapping them to ThrottlingError', 'handle GCP 400 bad request errors by mapping them to InvalidParameterError', 'review the map_gcp_error function to understand GCP to PCP error mapping logic', 'refactor map_gcp_error to support additional GCP error codes beyond 429 and 400', 'map a Kubernetes OpenApiException to a PcpError using map_k8s_error', 'handle ApiValueError by mapping it to InvalidParameterError via map_k8s_error', 'handle ApiTypeError by mapping it to InvalidParameterError via map_k8s_error', 'handle a 429 status ApiException by mapping it to ThrottlingError via map_k8s_error', 'handle a 404 status ApiException by mapping it to InvalidParameterError via map_k8s_error']
```

Usage

```
{'map_aws_error_to_pcp_error': 'map a boto3 ClientError to the appropriate PcpError subclass based on the AWS error code', 'handle_invalid_parameter_exception': 'handle an AWS InvalidParameterException by mapping it to an InvalidParameterError', 'handle_throttling_exception': 'handle an AWS ThrottlingException by mapping it to a ThrottlingError', 'handle_limit_exceeded_exception': 'handle an AWS LimitExceededException by mapping it to a LimitExceededError', 'map_unknown_aws_error': 'map any unhandled AWS ClientError to a generic PcpError with response metadata'}
```

## File: facebookresearch_fbpcp/fbpcp/error/mapper/gcp.py

Prompts

```
['map a boto3 ClientError to the appropriate PcpError subclass based on the AWS error code', 'handle an AWS InvalidParameterException by mapping it to an InvalidParameterError', 'handle an AWS ThrottlingException by mapping it to a ThrottlingError', 'handle an AWS LimitExceededException by mapping it to a LimitExceededError', 'map any unhandled AWS ClientError to a generic PcpError with response metadata', 'map a GoogleCloudError to a PcpError based on the HTTP status code', 'handle GCP 429 throttling errors by mapping them to ThrottlingError', 'handle GCP 400 bad request errors by mapping them to InvalidParameterError', 'review the map_gcp_error function to understand GCP to PCP error mapping logic', 'refactor map_gcp_error to support additional GCP error codes beyond 429 and 400', 'map a Kubernetes OpenApiException to a PcpError using map_k8s_error', 'handle ApiValueError by mapping it to InvalidParameterError via map_k8s_error', 'handle ApiTypeError by mapping it to InvalidParameterError via map_k8s_error', 'handle a 429 status ApiException by mapping it to ThrottlingError via map_k8s_error', 'handle a 404 status ApiException by mapping it to InvalidParameterError via map_k8s_error']
```

Usage

```
{'map_gcp_error_to_pcp': 'map a GoogleCloudError to a PcpError based on the HTTP status code', 'handle_gcp_throttling': 'handle GCP 429 throttling errors by mapping them to ThrottlingError', 'handle_gcp_invalid_param': 'handle GCP 400 bad request errors by mapping them to InvalidParameterError', 'review_map_gcp_error': 'review the map_gcp_error function to understand GCP to PCP error mapping logic', 'refactor_map_gcp_error': 'refactor map_gcp_error to support additional GCP error codes beyond 429 and 400'}
```

## File: facebookresearch_fbpcp/fbpcp/error/mapper/k8s.py

Prompts

```
['map a boto3 ClientError to the appropriate PcpError subclass based on the AWS error code', 'handle an AWS InvalidParameterException by mapping it to an InvalidParameterError', 'handle an AWS ThrottlingException by mapping it to a ThrottlingError', 'handle an AWS LimitExceededException by mapping it to a LimitExceededError', 'map any unhandled AWS ClientError to a generic PcpError with response metadata', 'map a GoogleCloudError to a PcpError based on the HTTP status code', 'handle GCP 429 throttling errors by mapping them to ThrottlingError', 'handle GCP 400 bad request errors by mapping them to InvalidParameterError', 'review the map_gcp_error function to understand GCP to PCP error mapping logic', 'refactor map_gcp_error to support additional GCP error codes beyond 429 and 400', 'map a Kubernetes OpenApiException to a PcpError using map_k8s_error', 'handle ApiValueError by mapping it to InvalidParameterError via map_k8s_error', 'handle ApiTypeError by mapping it to InvalidParameterError via map_k8s_error', 'handle a 429 status ApiException by mapping it to ThrottlingError via map_k8s_error', 'handle a 404 status ApiException by mapping it to InvalidParameterError via map_k8s_error']
```

Usage

```
{'map_k8s_error_to_pcp_error': 'map a Kubernetes OpenApiException to a PcpError using map_k8s_error', 'handle_k8s_api_value_error': 'handle ApiValueError by mapping it to InvalidParameterError via map_k8s_error', 'handle_k8s_api_type_error': 'handle ApiTypeError by mapping it to InvalidParameterError via map_k8s_error', 'handle_k8s_throttling_error': 'handle a 429 status ApiException by mapping it to ThrottlingError via map_k8s_error', 'handle_k8s_not_found_error': 'handle a 404 status ApiException by mapping it to InvalidParameterError via map_k8s_error'}
```

