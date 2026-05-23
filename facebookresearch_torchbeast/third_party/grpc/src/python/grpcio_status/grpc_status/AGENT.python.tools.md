# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/src/python/grpcio_status/grpc_status/_common.py

Prompts

```
['convert an integer status code to its corresponding gRPC StatusCode enum value', 'validate that a given integer code is a valid gRPC status code', 'reference the standard gRPC binary status details metadata key constant', 'review the code_to_grpc_status_code function to understand gRPC status code mapping logic', 'summarize how the _CODE_TO_GRPC_CODE_MAPPING dictionary maps integer codes to gRPC StatusCode enums', "extract a google.rpc.status.Status message from a gRPC call's trailing metadata using from_call", 'convert a google.rpc.status.Status protobuf message to a grpc.Status using to_status', 'review the from_call function to understand how it validates code and message consistency', 'review the to_status function to see how it serializes a Status proto into trailing metadata', 'summarize the _Status namedtuple that wraps code, details, and trailing_metadata for grpc.Status']
```

Usage

```
{'code_to_grpc_status_code_convert': 'convert an integer status code to its corresponding gRPC StatusCode enum value', 'code_to_grpc_status_code_validate': 'validate that a given integer code is a valid gRPC status code', 'GRPC_DETAILS_METADATA_KEY_reference': 'reference the standard gRPC binary status details metadata key constant', 'review_code_to_grpc_status_code': 'review the code_to_grpc_status_code function to understand gRPC status code mapping logic', 'summarize_code_mapping': 'summarize how the _CODE_TO_GRPC_CODE_MAPPING dictionary maps integer codes to gRPC StatusCode enums'}
```

## File: facebookresearch_torchbeast/third_party/grpc/src/python/grpcio_status/grpc_status/rpc_status.py

Prompts

```
['convert an integer status code to its corresponding gRPC StatusCode enum value', 'validate that a given integer code is a valid gRPC status code', 'reference the standard gRPC binary status details metadata key constant', 'review the code_to_grpc_status_code function to understand gRPC status code mapping logic', 'summarize how the _CODE_TO_GRPC_CODE_MAPPING dictionary maps integer codes to gRPC StatusCode enums', "extract a google.rpc.status.Status message from a gRPC call's trailing metadata using from_call", 'convert a google.rpc.status.Status protobuf message to a grpc.Status using to_status', 'review the from_call function to understand how it validates code and message consistency', 'review the to_status function to see how it serializes a Status proto into trailing metadata', 'summarize the _Status namedtuple that wraps code, details, and trailing_metadata for grpc.Status']
```

Usage

```
{'extract_status_from_grpc_call': "extract a google.rpc.status.Status message from a gRPC call's trailing metadata using from_call", 'convert_status_to_grpc_status': 'convert a google.rpc.status.Status protobuf message to a grpc.Status using to_status', 'review_from_call_validation': 'review the from_call function to understand how it validates code and message consistency', 'review_to_status_serialization': 'review the to_status function to see how it serializes a Status proto into trailing metadata', 'summarize_Status_namedtuple': 'summarize the _Status namedtuple that wraps code, details, and trailing_metadata for grpc.Status'}
```

