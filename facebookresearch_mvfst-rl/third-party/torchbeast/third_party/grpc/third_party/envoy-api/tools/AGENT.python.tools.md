# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/envoy-api/tools/generate_listeners.py

Prompts

```
['run the script to generate Envoy listener protobuf and JSON files from filter config fragments', 'create a function that converts an arbitrary protobuf message to its opaque Struct representation', 'parse a filter config proto text file from the filesystem into a protobuf message object', 'review the GenerateListeners function that merges filter config fragments into a listener protobuf', 'test the ProtoToStruct function to verify protobuf to Struct conversion works correctly', 'convert an Envoy tap trace protobuf file to a PCAP file for Wireshark analysis', 'format a tap event with direction, timestamp, and hex data for text2pcap input', 'run the tap2pcap CLI tool to convert a .pb or .pb_text tap file to PCAP', 'parse an Envoy tap trace protobuf or text format and extract connection and event data', 'review the DumpEvent function that formats tap events into text2pcap-compatible hex dumps']
```

Usage

```
{'generate_listeners_from_fragments': 'run the script to generate Envoy listener protobuf and JSON files from filter config fragments', 'convert_proto_to_struct': 'create a function that converts an arbitrary protobuf message to its opaque Struct representation', 'parse_filter_config_proto': 'parse a filter config proto text file from the filesystem into a protobuf message object', 'review_GenerateListeners': 'review the GenerateListeners function that merges filter config fragments into a listener protobuf', 'test_ProtoToStruct': 'test the ProtoToStruct function to verify protobuf to Struct conversion works correctly'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/envoy-api/tools/tap2pcap.py

Prompts

```
['run the script to generate Envoy listener protobuf and JSON files from filter config fragments', 'create a function that converts an arbitrary protobuf message to its opaque Struct representation', 'parse a filter config proto text file from the filesystem into a protobuf message object', 'review the GenerateListeners function that merges filter config fragments into a listener protobuf', 'test the ProtoToStruct function to verify protobuf to Struct conversion works correctly', 'convert an Envoy tap trace protobuf file to a PCAP file for Wireshark analysis', 'format a tap event with direction, timestamp, and hex data for text2pcap input', 'run the tap2pcap CLI tool to convert a .pb or .pb_text tap file to PCAP', 'parse an Envoy tap trace protobuf or text format and extract connection and event data', 'review the DumpEvent function that formats tap events into text2pcap-compatible hex dumps']
```

Usage

```
{'convert_tap_to_pcap': 'convert an Envoy tap trace protobuf file to a PCAP file for Wireshark analysis', 'dump_event_format': 'format a tap event with direction, timestamp, and hex data for text2pcap input', 'run_tap2pcap_cli': 'run the tap2pcap CLI tool to convert a .pb or .pb_text tap file to PCAP', 'parse_tap_protobuf': 'parse an Envoy tap trace protobuf or text format and extract connection and event data', 'review_DumpEvent': 'review the DumpEvent function that formats tap events into text2pcap-compatible hex dumps'}
```

