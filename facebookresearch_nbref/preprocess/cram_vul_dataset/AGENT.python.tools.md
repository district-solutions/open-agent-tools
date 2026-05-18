# Agent Python Tools

- repo: facebookresearch/nbref
- repo_uri: https://github.com/facebookresearch/nbref

## File: facebookresearch_nbref/preprocess/cram_vul_dataset/src2asm.py

Prompts

```
['run src2asm.py to compile FFmpeg or qemu source functions into paired assembly code with configurable optimization levels', 'run the process function to checkout a git commit, build the project, and extract assembly for a target C function', 'extract assembly code from a compiled object file using nm and objdump with start and stop addresses', 'clone a FFmpeg or qemu repository and build it with a specified optimization level and parallel job count', 'filter and compile only vulnerable C functions by passing the --vulnerable flag to src2asm.py']
```

Usage

```
{'build_src2asm_dataset': 'run src2asm.py to compile FFmpeg or qemu source functions into paired assembly code with configurable optimization levels', 'run_process_function': 'run the process function to checkout a git commit, build the project, and extract assembly for a target C function', 'extract_assembly_from_object': 'extract assembly code from a compiled object file using nm and objdump with start and stop addresses', 'clone_and_build_repo': 'clone a FFmpeg or qemu repository and build it with a specified optimization level and parallel job count', 'filter_vulnerable_functions': 'filter and compile only vulnerable C functions by passing the --vulnerable flag to src2asm.py'}
```

