# Agent Python Tools

- repo: facebookresearch/fbpcp
- repo_uri: https://github.com/facebookresearch/fbpcp

## File: facebookresearch_fbpcp/fbpcp/entity/certificate_request.py

Prompts

```
['create a CertificateRequest instance from a JSON string with key algorithm, key size, and optional certificate parameters', 'convert a CertificateRequest object to a JSON string representation with all non-null fields included', 'get a list of non-optional field names from the CertificateRequest dataclass using introspection', 'check if a given key algorithm name like RSA is supported by the KeyAlgorithm enum', 'review the CertificateRequest class validation logic for required fields and supported key algorithms', 'get the cpu and memory config for an AWS SMALL container using ContainerTypeConfig.get_config', 'get the cpu and memory config for an AWS MEDIUM container using ContainerTypeConfig.get_config', 'get the cpu and memory config for an AWS LARGE container using ContainerTypeConfig.get_config', 'list all available ContainerType enum values including SMALL, MEDIUM, and LARGE', 'review the ContainerTypeConfig dataclass and its get_config classmethod for supported cloud providers', 'convert an Insight instance to a JSON string that includes its class name', 'serialize an Insight dataclass instance to a dictionary using the inherited to_dict method', 'create an Insight instance from a dictionary using the inherited from_dict method', 'serialize an Insight dataclass instance to a JSON string using the inherited to_json method', 'create an Insight instance from a JSON string using the inherited from_json method']
```

Usage

```
{'create_certificate_request_from_json': 'create a CertificateRequest instance from a JSON string with key algorithm, key size, and optional certificate parameters', 'convert_certificate_request_to_json': 'convert a CertificateRequest object to a JSON string representation with all non-null fields included', 'get_non_optional_fields': 'get a list of non-optional field names from the CertificateRequest dataclass using introspection', 'check_key_algorithm_support': 'check if a given key algorithm name like RSA is supported by the KeyAlgorithm enum', 'review_certificate_request_validation': 'review the CertificateRequest class validation logic for required fields and supported key algorithms'}
```

## File: facebookresearch_fbpcp/fbpcp/entity/container_type.py

Prompts

```
['create a CertificateRequest instance from a JSON string with key algorithm, key size, and optional certificate parameters', 'convert a CertificateRequest object to a JSON string representation with all non-null fields included', 'get a list of non-optional field names from the CertificateRequest dataclass using introspection', 'check if a given key algorithm name like RSA is supported by the KeyAlgorithm enum', 'review the CertificateRequest class validation logic for required fields and supported key algorithms', 'get the cpu and memory config for an AWS SMALL container using ContainerTypeConfig.get_config', 'get the cpu and memory config for an AWS MEDIUM container using ContainerTypeConfig.get_config', 'get the cpu and memory config for an AWS LARGE container using ContainerTypeConfig.get_config', 'list all available ContainerType enum values including SMALL, MEDIUM, and LARGE', 'review the ContainerTypeConfig dataclass and its get_config classmethod for supported cloud providers', 'convert an Insight instance to a JSON string that includes its class name', 'serialize an Insight dataclass instance to a dictionary using the inherited to_dict method', 'create an Insight instance from a dictionary using the inherited from_dict method', 'serialize an Insight dataclass instance to a JSON string using the inherited to_json method', 'create an Insight instance from a JSON string using the inherited from_json method']
```

Usage

```
{'get_container_config_aws_small': 'get the cpu and memory config for an AWS SMALL container using ContainerTypeConfig.get_config', 'get_container_config_aws_medium': 'get the cpu and memory config for an AWS MEDIUM container using ContainerTypeConfig.get_config', 'get_container_config_aws_large': 'get the cpu and memory config for an AWS LARGE container using ContainerTypeConfig.get_config', 'list_container_types': 'list all available ContainerType enum values including SMALL, MEDIUM, and LARGE', 'review_container_type_config': 'review the ContainerTypeConfig dataclass and its get_config classmethod for supported cloud providers'}
```

## File: facebookresearch_fbpcp/fbpcp/entity/insight.py

Prompts

```
['create a CertificateRequest instance from a JSON string with key algorithm, key size, and optional certificate parameters', 'convert a CertificateRequest object to a JSON string representation with all non-null fields included', 'get a list of non-optional field names from the CertificateRequest dataclass using introspection', 'check if a given key algorithm name like RSA is supported by the KeyAlgorithm enum', 'review the CertificateRequest class validation logic for required fields and supported key algorithms', 'get the cpu and memory config for an AWS SMALL container using ContainerTypeConfig.get_config', 'get the cpu and memory config for an AWS MEDIUM container using ContainerTypeConfig.get_config', 'get the cpu and memory config for an AWS LARGE container using ContainerTypeConfig.get_config', 'list all available ContainerType enum values including SMALL, MEDIUM, and LARGE', 'review the ContainerTypeConfig dataclass and its get_config classmethod for supported cloud providers', 'convert an Insight instance to a JSON string that includes its class name', 'serialize an Insight dataclass instance to a dictionary using the inherited to_dict method', 'create an Insight instance from a dictionary using the inherited from_dict method', 'serialize an Insight dataclass instance to a JSON string using the inherited to_json method', 'create an Insight instance from a JSON string using the inherited from_json method']
```

Usage

```
{'convert_insight_to_json_with_class_name': 'convert an Insight instance to a JSON string that includes its class name', 'serialize_insight_to_dict': 'serialize an Insight dataclass instance to a dictionary using the inherited to_dict method', 'deserialize_insight_from_dict': 'create an Insight instance from a dictionary using the inherited from_dict method', 'serialize_insight_to_json': 'serialize an Insight dataclass instance to a JSON string using the inherited to_json method', 'deserialize_insight_from_json': 'create an Insight instance from a JSON string using the inherited from_json method'}
```

