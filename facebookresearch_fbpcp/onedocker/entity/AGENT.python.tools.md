# Agent Python Tools

- repo: facebookresearch/fbpcp
- repo_uri: https://github.com/facebookresearch/fbpcp

## File: facebookresearch_fbpcp/onedocker/entity/measurement.py

Prompts

```
['create a Measurement dataclass instance with a sha256 key and a hash value string', 'create a Measurement dataclass instance with a sha512 key and a hash value string', 'check if a given name is a valid MeasurementType enum member using has_member', 'serialize a Measurement dataclass instance to JSON using the dataclass_json decorator', 'deserialize a JSON string into a Measurement dataclass instance using from_json', 'create a PackageMetadata instance with a package name, version, and optional measurements dictionary', 'call to_dict on a PackageMetadata instance to get a serializable dictionary with package_name, version, and measurements', 'create a PackageMetadata instance with a sha256 measurement using MeasurementType enum as the key', 'review the PackageMetadata dataclass fields including package_name, version, and measurements with default_factory', 'refactor the PackageMetadata to_dict method to convert MeasurementType enum keys to their string values', 'create an OPAWDLWorkflowInstance with an instance_id, workflow, state instances, and status', 'get the instance_id string from an OPAWDLWorkflowInstance using get_instance_id method', 'serialize an OPAWDLWorkflowInstance to a JSON string using the to_json method', 'deserialize an OPAWDLWorkflowInstance from a JSON string using the from_json class method', 'check the Status enum of an OPAWDLWorkflowInstance to see if it is CREATED, STARTED, FAILED, or COMPLETED']
```

Usage

```
{'create_measurement_sha256': 'create a Measurement dataclass instance with a sha256 key and a hash value string', 'create_measurement_sha512': 'create a Measurement dataclass instance with a sha512 key and a hash value string', 'check_measurement_type_exists': 'check if a given name is a valid MeasurementType enum member using has_member', 'serialize_measurement_to_json': 'serialize a Measurement dataclass instance to JSON using the dataclass_json decorator', 'deserialize_measurement_from_json': 'deserialize a JSON string into a Measurement dataclass instance using from_json'}
```

## File: facebookresearch_fbpcp/onedocker/entity/metadata.py

Prompts

```
['create a Measurement dataclass instance with a sha256 key and a hash value string', 'create a Measurement dataclass instance with a sha512 key and a hash value string', 'check if a given name is a valid MeasurementType enum member using has_member', 'serialize a Measurement dataclass instance to JSON using the dataclass_json decorator', 'deserialize a JSON string into a Measurement dataclass instance using from_json', 'create a PackageMetadata instance with a package name, version, and optional measurements dictionary', 'call to_dict on a PackageMetadata instance to get a serializable dictionary with package_name, version, and measurements', 'create a PackageMetadata instance with a sha256 measurement using MeasurementType enum as the key', 'review the PackageMetadata dataclass fields including package_name, version, and measurements with default_factory', 'refactor the PackageMetadata to_dict method to convert MeasurementType enum keys to their string values', 'create an OPAWDLWorkflowInstance with an instance_id, workflow, state instances, and status', 'get the instance_id string from an OPAWDLWorkflowInstance using get_instance_id method', 'serialize an OPAWDLWorkflowInstance to a JSON string using the to_json method', 'deserialize an OPAWDLWorkflowInstance from a JSON string using the from_json class method', 'check the Status enum of an OPAWDLWorkflowInstance to see if it is CREATED, STARTED, FAILED, or COMPLETED']
```

Usage

```
{'create_package_metadata': 'create a PackageMetadata instance with a package name, version, and optional measurements dictionary', 'serialize_package_metadata_to_dict': 'call to_dict on a PackageMetadata instance to get a serializable dictionary with package_name, version, and measurements', 'create_package_metadata_with_sha256': 'create a PackageMetadata instance with a sha256 measurement using MeasurementType enum as the key', 'review_package_metadata_dataclass': 'review the PackageMetadata dataclass fields including package_name, version, and measurements with default_factory', 'refactor_package_metadata_to_dict': 'refactor the PackageMetadata to_dict method to convert MeasurementType enum keys to their string values'}
```

## File: facebookresearch_fbpcp/onedocker/entity/opawdl_workflow_instance.py

Prompts

```
['create a Measurement dataclass instance with a sha256 key and a hash value string', 'create a Measurement dataclass instance with a sha512 key and a hash value string', 'check if a given name is a valid MeasurementType enum member using has_member', 'serialize a Measurement dataclass instance to JSON using the dataclass_json decorator', 'deserialize a JSON string into a Measurement dataclass instance using from_json', 'create a PackageMetadata instance with a package name, version, and optional measurements dictionary', 'call to_dict on a PackageMetadata instance to get a serializable dictionary with package_name, version, and measurements', 'create a PackageMetadata instance with a sha256 measurement using MeasurementType enum as the key', 'review the PackageMetadata dataclass fields including package_name, version, and measurements with default_factory', 'refactor the PackageMetadata to_dict method to convert MeasurementType enum keys to their string values', 'create an OPAWDLWorkflowInstance with an instance_id, workflow, state instances, and status', 'get the instance_id string from an OPAWDLWorkflowInstance using get_instance_id method', 'serialize an OPAWDLWorkflowInstance to a JSON string using the to_json method', 'deserialize an OPAWDLWorkflowInstance from a JSON string using the from_json class method', 'check the Status enum of an OPAWDLWorkflowInstance to see if it is CREATED, STARTED, FAILED, or COMPLETED']
```

Usage

```
{'create_workflow_instance': 'create an OPAWDLWorkflowInstance with an instance_id, workflow, state instances, and status', 'get_instance_id': 'get the instance_id string from an OPAWDLWorkflowInstance using get_instance_id method', 'serialize_to_json': 'serialize an OPAWDLWorkflowInstance to a JSON string using the to_json method', 'deserialize_from_json': 'deserialize an OPAWDLWorkflowInstance from a JSON string using the from_json class method', 'check_workflow_status': 'check the Status enum of an OPAWDLWorkflowInstance to see if it is CREATED, STARTED, FAILED, or COMPLETED'}
```

