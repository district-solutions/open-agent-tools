# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/tools/run_tests/xds_k8s_test_driver/framework/xds_k8s_testcase.py

Prompts

```
['create a subclass of XdsKubernetesTestCase to set up gRPC XDS tests on Kubernetes with GCP Traffic Director', 'test that all RPCs succeed by sending requests and verifying every backend received at least one RPC', 'test that all RPCs fail by sending requests and verifying the expected number of failures', 'build mTLS or TLS security policies for client and server using Traffic Director secure manager', 'review the security mode of connected client and server sockets to verify mTLS, TLS, or plaintext']
```

Usage

```
{'setup_xds_kubernetes_test': 'create a subclass of XdsKubernetesTestCase to set up gRPC XDS tests on Kubernetes with GCP Traffic Director', 'assert_successful_rpcs': 'test that all RPCs succeed by sending requests and verifying every backend received at least one RPC', 'assert_failed_rpcs': 'test that all RPCs fail by sending requests and verifying the expected number of failures', 'setup_security_policies': 'build mTLS or TLS security policies for client and server using Traffic Director secure manager', 'assert_test_app_security': 'review the security mode of connected client and server sockets to verify mTLS, TLS, or plaintext'}
```

