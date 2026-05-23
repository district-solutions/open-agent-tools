# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/test/cpp/naming/utils/dns_resolver.py

Prompts

```
['run the dns resolver CLI to query A records for a given domain name against a DNS server', 'run the dns resolver CLI with a custom server host and port to query DNS A records', 'run the dns resolver CLI with a custom timeout to force process exit after N seconds', 'review the main function that parses CLI args and initiates DNS A record queries via Twisted', 'review the OnResolverResultAvailable callback that prints DNS answer payloads from resolver results', 'run a local DNS server on a specified port for gRPC resolver tests', 'start a DNS server using a YAML config file with A, AAAA, SRV, and TXT records', 'add an extra A record via command line argument in format name:ipv4_address', 'create a NoFileAuthority DNS resolver that serves records from memory instead of disk', 'configure a DNS health check record to verify the local DNS server is alive']
```

Usage

```
{'run_dns_resolver_cli': 'run the dns resolver CLI to query A records for a given domain name against a DNS server', 'run_dns_resolver_custom_server': 'run the dns resolver CLI with a custom server host and port to query DNS A records', 'run_dns_resolver_timeout': 'run the dns resolver CLI with a custom timeout to force process exit after N seconds', 'review_main_function': 'review the main function that parses CLI args and initiates DNS A record queries via Twisted', 'review_OnResolverResultAvailable': 'review the OnResolverResultAvailable callback that prints DNS answer payloads from resolver results'}
```

## File: facebookresearch_torchbeast/third_party/grpc/test/cpp/naming/utils/dns_server.py

Prompts

```
['run the dns resolver CLI to query A records for a given domain name against a DNS server', 'run the dns resolver CLI with a custom server host and port to query DNS A records', 'run the dns resolver CLI with a custom timeout to force process exit after N seconds', 'review the main function that parses CLI args and initiates DNS A record queries via Twisted', 'review the OnResolverResultAvailable callback that prints DNS answer payloads from resolver results', 'run a local DNS server on a specified port for gRPC resolver tests', 'start a DNS server using a YAML config file with A, AAAA, SRV, and TXT records', 'add an extra A record via command line argument in format name:ipv4_address', 'create a NoFileAuthority DNS resolver that serves records from memory instead of disk', 'configure a DNS health check record to verify the local DNS server is alive']
```

Usage

```
{'run_local_dns_server': 'run a local DNS server on a specified port for gRPC resolver tests', 'start_dns_server_with_yaml_config': 'start a DNS server using a YAML config file with A, AAAA, SRV, and TXT records', 'add_extra_a_record': 'add an extra A record via command line argument in format name:ipv4_address', 'create_no_file_authority': 'create a NoFileAuthority DNS resolver that serves records from memory instead of disk', 'configure_dns_health_check': 'configure a DNS health check record to verify the local DNS server is alive'}
```

