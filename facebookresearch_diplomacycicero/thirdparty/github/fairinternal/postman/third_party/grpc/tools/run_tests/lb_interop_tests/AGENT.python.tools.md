# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/tools/run_tests/lb_interop_tests/gen_build_yaml.py

Prompts

```
['run the script to generate YAML output for all gRPC load balancer interop test scenarios', 'generate LB interop test configs where the balancer A record returns NX domain for all transport security types', 'generate LB interop test configs where the balancer A record returns no data for all transport security types', 'generate LB interop test configs for clients referred to a backend with optional short stream and multiple transport security types', 'generate LB interop test configs where the client falls back because the balancer returns no backends']
```

Usage

```
{'run_lb_interop_test_scenarios': 'run the script to generate YAML output for all gRPC load balancer interop test scenarios', 'generate_no_balancer_nx_domain': 'generate LB interop test configs where the balancer A record returns NX domain for all transport security types', 'generate_no_balancer_no_data': 'generate LB interop test configs where the balancer A record returns no data for all transport security types', 'generate_client_referred_to_backend': 'generate LB interop test configs for clients referred to a backend with optional short stream and multiple transport security types', 'generate_client_falls_back_no_backends': 'generate LB interop test configs where the client falls back because the balancer returns no backends'}
```

