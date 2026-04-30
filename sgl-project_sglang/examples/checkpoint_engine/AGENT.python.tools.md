# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/examples/checkpoint_engine/update.py

Prompts

```
['run checkpoint weight update on an SGLang inference server using broadcast or p2p method', 'run checkpoint join using saved metas file to update weights with p2p method on SGLang server', 'build a dict of named tensors by splitting checkpoint files across ranks using safetensors index', 'test if SGLang inference server endpoint is ready by polling the /ping route', 'build a request function that POSTs updated weights from IPC to an SGLang server endpoint']
```

Usage

```
{'run_update_weights': 'run checkpoint weight update on an SGLang inference server using broadcast or p2p method', 'run_join_checkpoint': 'run checkpoint join using saved metas file to update weights with p2p method on SGLang server', 'build_split_tensors': 'build a dict of named tensors by splitting checkpoint files across ranks using safetensors index', 'test_check_sglang_ready': 'test if SGLang inference server endpoint is ready by polling the /ping route', 'build_req_inference': 'build a request function that POSTs updated weights from IPC to an SGLang server endpoint'}
```

