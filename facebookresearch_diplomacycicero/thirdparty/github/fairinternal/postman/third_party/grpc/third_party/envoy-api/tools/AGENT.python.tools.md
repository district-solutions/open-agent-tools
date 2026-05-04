# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/envoy-api/tools/generate_listeners.py

Prompts

```
['run the script to generate Envoy listener .pb and .json files from a listeners proto and filter config fragments', 'create a function that converts an arbitrary protobuf message to its opaque Struct proto representation via JSON', 'parse a filter config proto text file from the filesystem into a known filter config object', 'review the GenerateListeners function that merges filter config fragments into an Envoy listener proto and writes output files', 'summarize the ProtoToStruct function that serializes a proto to JSON then parses it into a Struct proto', 'run the tap2pcap tool to convert an Envoy tap trace .pb file to a PCAP file', 'run the tap2pcap tool to convert an Envoy tap trace .pb_text file to a PCAP file', 'create a text2pcap-compatible hex dump from a tap event direction, timestamp, and data bytes', 'build a PCAP file from an Envoy tap trace protobuf by invoking text2pcap with synthesized TCP streams', 'review the DumpEvent function that formats tap events using od hex dump and timezone-adjusted timestamps']
```

Usage

```
{'generate_envoy_listeners': 'run the script to generate Envoy listener .pb and .json files from a listeners proto and filter config fragments', 'convert_proto_to_struct': 'create a function that converts an arbitrary protobuf message to its opaque Struct proto representation via JSON', 'parse_filter_config_proto': 'parse a filter config proto text file from the filesystem into a known filter config object', 'review_GenerateListeners': 'review the GenerateListeners function that merges filter config fragments into an Envoy listener proto and writes output files', 'summarize_ProtoToStruct': 'summarize the ProtoToStruct function that serializes a proto to JSON then parses it into a Struct proto'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/envoy-api/tools/tap2pcap.py

Prompts

```
['run the script to generate Envoy listener .pb and .json files from a listeners proto and filter config fragments', 'create a function that converts an arbitrary protobuf message to its opaque Struct proto representation via JSON', 'parse a filter config proto text file from the filesystem into a known filter config object', 'review the GenerateListeners function that merges filter config fragments into an Envoy listener proto and writes output files', 'summarize the ProtoToStruct function that serializes a proto to JSON then parses it into a Struct proto', 'run the tap2pcap tool to convert an Envoy tap trace .pb file to a PCAP file', 'run the tap2pcap tool to convert an Envoy tap trace .pb_text file to a PCAP file', 'create a text2pcap-compatible hex dump from a tap event direction, timestamp, and data bytes', 'build a PCAP file from an Envoy tap trace protobuf by invoking text2pcap with synthesized TCP streams', 'review the DumpEvent function that formats tap events using od hex dump and timezone-adjusted timestamps']
```

Usage

```
{'run_tap2pcap_cli': 'run the tap2pcap tool to convert an Envoy tap trace .pb file to a PCAP file', 'run_tap2pcap_text': 'run the tap2pcap tool to convert an Envoy tap trace .pb_text file to a PCAP file', 'create_dump_event': 'create a text2pcap-compatible hex dump from a tap event direction, timestamp, and data bytes', 'build_tap_to_pcap': 'build a PCAP file from an Envoy tap trace protobuf by invoking text2pcap with synthesized TCP streams', 'review_dump_event': 'review the DumpEvent function that formats tap events using od hex dump and timezone-adjusted timestamps'}
```

