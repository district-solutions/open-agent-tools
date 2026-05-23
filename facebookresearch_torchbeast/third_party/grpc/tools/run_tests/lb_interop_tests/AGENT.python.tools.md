# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/tools/run_tests/lb_interop_tests/gen_build_yaml.py

Prompts

```
['run the script to generate YAML output of all LB interop test scenarios', 'generate test configs where the LB A record returns NX domain for all transport security types', 'generate test configs where the LB A record returns no data for all transport security types', 'generate test configs for client referred to a single backend with optional short stream', 'generate test configs where the client falls back because the balancer returns no backends']
```

Usage

```
{'generate_lb_interop_test_scenarios': 'run the script to generate YAML output of all LB interop test scenarios', 'generate_no_balancer_because_lb_a_record_returns_nx_domain': 'generate test configs where the LB A record returns NX domain for all transport security types', 'generate_no_balancer_because_lb_a_record_returns_no_data': 'generate test configs where the LB A record returns no data for all transport security types', 'generate_client_referred_to_backend': 'generate test configs for client referred to a single backend with optional short stream', 'generate_client_falls_back_because_no_backends': 'generate test configs where the client falls back because the balancer returns no backends'}
```

