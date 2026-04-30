# Agent Python Tools

- repo: huggingface/safetensors
- repo_uri: https://github.com/huggingface/safetensors

## File: huggingface_safetensors/bindings/python/convert.py

Prompts

```
['convert a Hugging Face PyTorch model to safetensors format and open a PR on the hub', 'convert a single pytorch_model.bin file to model.safetensors with duplicate removal', 'convert a sharded pytorch model using pytorch_model.bin.index.json to multiple safetensors files', 'convert generic .bin or .ckpt weights files on a Hugging Face repo to safetensors format', 'convert a local PyTorch state dict file to safetensors format with size and equality checks', 'test the safetensors load_file function with atheris fuzzer on arbitrary binary data', 'run stub.py to generate .pyi and .py stub files for the safetensors Python module', 'run stub.py --check to verify generated stub files are up to date', 'build Python .pyi stub files from the safetensors Rust extension module', 'build Python __init__.py stub files with re-exports from the safetensors module', 'test stub.py generates correct .pyi and .py files for the safetensors_rust module']
```

Usage

```
{'convert_model_to_safetensors': 'convert a Hugging Face PyTorch model to safetensors format and open a PR on the hub', 'convert_single_pytorch_model': 'convert a single pytorch_model.bin file to model.safetensors with duplicate removal', 'convert_multi_sharded_model': 'convert a sharded pytorch model using pytorch_model.bin.index.json to multiple safetensors files', 'convert_generic_weights': 'convert generic .bin or .ckpt weights files on a Hugging Face repo to safetensors format', 'convert_file_locally': 'convert a local PyTorch state dict file to safetensors format with size and equality checks'}
```

## File: huggingface_safetensors/bindings/python/fuzz.py

Prompts

```
['convert a Hugging Face PyTorch model to safetensors format and open a PR on the hub', 'convert a single pytorch_model.bin file to model.safetensors with duplicate removal', 'convert a sharded pytorch model using pytorch_model.bin.index.json to multiple safetensors files', 'convert generic .bin or .ckpt weights files on a Hugging Face repo to safetensors format', 'convert a local PyTorch state dict file to safetensors format with size and equality checks', 'test the safetensors load_file function with atheris fuzzer on arbitrary binary data', 'run stub.py to generate .pyi and .py stub files for the safetensors Python module', 'run stub.py --check to verify generated stub files are up to date', 'build Python .pyi stub files from the safetensors Rust extension module', 'build Python __init__.py stub files with re-exports from the safetensors module', 'test stub.py generates correct .pyi and .py files for the safetensors_rust module']
```

Usage

```
{'test_fuzz_safetensors_load_file': 'test the safetensors load_file function with atheris fuzzer on arbitrary binary data'}
```

## File: huggingface_safetensors/bindings/python/stub.py

Prompts

```
['convert a Hugging Face PyTorch model to safetensors format and open a PR on the hub', 'convert a single pytorch_model.bin file to model.safetensors with duplicate removal', 'convert a sharded pytorch model using pytorch_model.bin.index.json to multiple safetensors files', 'convert generic .bin or .ckpt weights files on a Hugging Face repo to safetensors format', 'convert a local PyTorch state dict file to safetensors format with size and equality checks', 'test the safetensors load_file function with atheris fuzzer on arbitrary binary data', 'run stub.py to generate .pyi and .py stub files for the safetensors Python module', 'run stub.py --check to verify generated stub files are up to date', 'build Python .pyi stub files from the safetensors Rust extension module', 'build Python __init__.py stub files with re-exports from the safetensors module', 'test stub.py generates correct .pyi and .py files for the safetensors_rust module']
```

Usage

```
{'run_stub_generate_pyi': 'run stub.py to generate .pyi and .py stub files for the safetensors Python module', 'run_stub_check_generated': 'run stub.py --check to verify generated stub files are up to date', 'build_pyi_stubs': 'build Python .pyi stub files from the safetensors Rust extension module', 'build_init_py_stubs': 'build Python __init__.py stub files with re-exports from the safetensors module', 'test_stub_generation': 'test stub.py generates correct .pyi and .py files for the safetensors_rust module'}
```

