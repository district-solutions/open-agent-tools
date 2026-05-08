# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/examples/example_unrolling_service/service_py/example_service.py

Prompts

```
['run the CompilerGym loop unrolling service as a standalone process using create_and_run_compiler_gym_service', 'create an UnrollingCompilationSession instance with a working directory, action space, and benchmark', 'apply a loop unrolling action with unroll count 2, 4, or 8 to the LLVM IR', 'get the current LLVM IR string observation from the compilation session', 'get the average execution runtime observation by compiling and running the benchmark binary', 'extract statistics from LLVM IR source code and count control flow, arithmetic, and memory opcodes', 'summarize the extract_statistics_from_ir function that categorizes LLVM IR opcodes into control flow, arithmetic, and memory groups', 'test the extract_statistics_from_ir function with sample LLVM IR code to verify opcode counting accuracy', 'refactor the extract_statistics_from_ir function to support additional LLVM IR opcode categories', 'review the extract_statistics_from_ir function for completeness of LLVM IR opcode coverage']
```

Usage

```
{'run_unrolling_service': 'run the CompilerGym loop unrolling service as a standalone process using create_and_run_compiler_gym_service', 'create_unrolling_session': 'create an UnrollingCompilationSession instance with a working directory, action space, and benchmark', 'apply_loop_unroll_action': 'apply a loop unrolling action with unroll count 2, 4, or 8 to the LLVM IR', 'get_ir_observation': 'get the current LLVM IR string observation from the compilation session', 'get_runtime_observation': 'get the average execution runtime observation by compiling and running the benchmark binary'}
```

## File: facebookresearch_compilergym/examples/example_unrolling_service/service_py/utils.py

Prompts

```
['run the CompilerGym loop unrolling service as a standalone process using create_and_run_compiler_gym_service', 'create an UnrollingCompilationSession instance with a working directory, action space, and benchmark', 'apply a loop unrolling action with unroll count 2, 4, or 8 to the LLVM IR', 'get the current LLVM IR string observation from the compilation session', 'get the average execution runtime observation by compiling and running the benchmark binary', 'extract statistics from LLVM IR source code and count control flow, arithmetic, and memory opcodes', 'summarize the extract_statistics_from_ir function that categorizes LLVM IR opcodes into control flow, arithmetic, and memory groups', 'test the extract_statistics_from_ir function with sample LLVM IR code to verify opcode counting accuracy', 'refactor the extract_statistics_from_ir function to support additional LLVM IR opcode categories', 'review the extract_statistics_from_ir function for completeness of LLVM IR opcode coverage']
```

Usage

```
{'extract_statistics_from_ir': 'extract statistics from LLVM IR source code and count control flow, arithmetic, and memory opcodes', 'summarize_extract_statistics_from_ir': 'summarize the extract_statistics_from_ir function that categorizes LLVM IR opcodes into control flow, arithmetic, and memory groups', 'test_extract_statistics_from_ir': 'test the extract_statistics_from_ir function with sample LLVM IR code to verify opcode counting accuracy', 'refactor_extract_statistics_from_ir': 'refactor the extract_statistics_from_ir function to support additional LLVM IR opcode categories', 'review_extract_statistics_from_ir': 'review the extract_statistics_from_ir function for completeness of LLVM IR opcode coverage'}
```

