# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/third_party/envoy-api/tools/generate_listeners.py

Prompts

```
['generate Envoy listener protobuf and JSON files from a listeners proto and filter config fragment paths', 'convert an arbitrary protobuf message to its opaque Struct proto representation via JSON round-trip', 'parse a filter config proto text file from the filesystem into a known protobuf message type', 'run the script with CLI args to merge filter config fragments into a listeners proto and output pb and json', 'review the GenerateListeners function that merges filter config fragments into Envoy listener filter chains', 'convert an Envoy tap trace proto file to a PCAP file for Wireshark analysis', 'format a tap event with direction, timestamp, and hex-encoded packet data using od', 'convert a tap trace with IPv4 addresses to a PCAP file using text2pcap', 'convert a tap trace with IPv6 addresses to a PCAP file using text2pcap', 'parse a tap trace from a .pb_text file and convert it to a PCAP file']
```

Usage

```
{'generate_listeners': 'generate Envoy listener protobuf and JSON files from a listeners proto and filter config fragment paths', 'proto_to_struct': 'convert an arbitrary protobuf message to its opaque Struct proto representation via JSON round-trip', 'parse_proto': 'parse a filter config proto text file from the filesystem into a known protobuf message type', 'run_generate_listeners_cli': 'run the script with CLI args to merge filter config fragments into a listeners proto and output pb and json', 'review_generate_listeners': 'review the GenerateListeners function that merges filter config fragments into Envoy listener filter chains'}
```

## File: facebookresearch_torchbeast/third_party/grpc/third_party/envoy-api/tools/tap2pcap.py

Prompts

```
['generate Envoy listener protobuf and JSON files from a listeners proto and filter config fragment paths', 'convert an arbitrary protobuf message to its opaque Struct proto representation via JSON round-trip', 'parse a filter config proto text file from the filesystem into a known protobuf message type', 'run the script with CLI args to merge filter config fragments into a listeners proto and output pb and json', 'review the GenerateListeners function that merges filter config fragments into Envoy listener filter chains', 'convert an Envoy tap trace proto file to a PCAP file for Wireshark analysis', 'format a tap event with direction, timestamp, and hex-encoded packet data using od', 'convert a tap trace with IPv4 addresses to a PCAP file using text2pcap', 'convert a tap trace with IPv6 addresses to a PCAP file using text2pcap', 'parse a tap trace from a .pb_text file and convert it to a PCAP file']
```

Usage

```
{'tap2pcap_convert': 'convert an Envoy tap trace proto file to a PCAP file for Wireshark analysis', 'dump_event_format': 'format a tap event with direction, timestamp, and hex-encoded packet data using od', 'tap2pcap_ipv4': 'convert a tap trace with IPv4 addresses to a PCAP file using text2pcap', 'tap2pcap_ipv6': 'convert a tap trace with IPv6 addresses to a PCAP file using text2pcap', 'tap2pcap_text_proto': 'parse a tap trace from a .pb_text file and convert it to a PCAP file'}
```

