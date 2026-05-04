# Agent Python Tools

- repo: facebookresearch/fbpcp
- repo_uri: https://github.com/facebookresearch/fbpcp

## File: facebookresearch_fbpcp/tests/entity/test_certificate_request.py

Prompts

```
['create a CertificateRequest instance with RSA key algorithm, key size 4096, and passphrase', 'test creating a CertificateRequest from cert params JSON string using create_instance class method', 'test that create_instance raises InvalidParameterError when given malformed JSON cert params', 'test that create_instance raises InvalidParameterError when required cert params are missing', 'convert a CertificateRequest object to a JSON cert params string using convert_to_cert_params method', 'test the ContainerInsight class convert_to_str_with_class_name method returns correct JSON string', 'create a ContainerInsight instance with time, cluster_name, instance_id, status, and exit_code fields', 'test the Insight parent class convert_to_str_with_class_name serialization method', 'run the TestContainerInsight unittest suite to validate ContainerInsight entity serialization', 'review the ContainerInsight dataclass fields and Insight parent class inheritance structure']
```

Usage

```
{'create_certificate_request_instance': 'create a CertificateRequest instance with RSA key algorithm, key size 4096, and passphrase', 'test_create_instance_from_cert_params': 'test creating a CertificateRequest from cert params JSON string using create_instance class method', 'test_create_instance_invalid_json': 'test that create_instance raises InvalidParameterError when given malformed JSON cert params', 'test_create_instance_missing_params': 'test that create_instance raises InvalidParameterError when required cert params are missing', 'convert_certificate_request_to_cert_params': 'convert a CertificateRequest object to a JSON cert params string using convert_to_cert_params method'}
```

## File: facebookresearch_fbpcp/tests/entity/test_container_insight.py

Prompts

```
['create a CertificateRequest instance with RSA key algorithm, key size 4096, and passphrase', 'test creating a CertificateRequest from cert params JSON string using create_instance class method', 'test that create_instance raises InvalidParameterError when given malformed JSON cert params', 'test that create_instance raises InvalidParameterError when required cert params are missing', 'convert a CertificateRequest object to a JSON cert params string using convert_to_cert_params method', 'test the ContainerInsight class convert_to_str_with_class_name method returns correct JSON string', 'create a ContainerInsight instance with time, cluster_name, instance_id, status, and exit_code fields', 'test the Insight parent class convert_to_str_with_class_name serialization method', 'run the TestContainerInsight unittest suite to validate ContainerInsight entity serialization', 'review the ContainerInsight dataclass fields and Insight parent class inheritance structure']
```

Usage

```
{'test_ContainerInsight_convert_to_str_with_class_name': 'test the ContainerInsight class convert_to_str_with_class_name method returns correct JSON string', 'create_ContainerInsight_instance': 'create a ContainerInsight instance with time, cluster_name, instance_id, status, and exit_code fields', 'test_Insight_parent_class': 'test the Insight parent class convert_to_str_with_class_name serialization method', 'run_TestContainerInsight_unit_tests': 'run the TestContainerInsight unittest suite to validate ContainerInsight entity serialization', 'review_ContainerInsight_dataclass': 'review the ContainerInsight dataclass fields and Insight parent class inheritance structure'}
```

