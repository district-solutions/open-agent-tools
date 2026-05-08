# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/compiler_gym/envs/gcc/service/gcc_service.py

Prompts

```
['create a GCC compilation service session class using make_gcc_compilation_session with a gcc binary path', 'compile a benchmark source file to an object file using the GccCompilationSession compile method', 'assemble a benchmark source file to assembly code using the GccCompilationSession assemble method', 'apply a SimpleAction or IncrAction to change GCC compiler flag choices in a session', 'get an observation like asm_size obj_hash or instruction_counts from a GccCompilationSession']
```

Usage

```
{'create_gcc_compilation_session': 'create a GCC compilation service session class using make_gcc_compilation_session with a gcc binary path', 'compile_benchmark_to_object': 'compile a benchmark source file to an object file using the GccCompilationSession compile method', 'assemble_benchmark_to_asm': 'assemble a benchmark source file to assembly code using the GccCompilationSession assemble method', 'apply_compiler_action': 'apply a SimpleAction or IncrAction to change GCC compiler flag choices in a session', 'get_observation': 'get an observation like asm_size obj_hash or instruction_counts from a GccCompilationSession'}
```

