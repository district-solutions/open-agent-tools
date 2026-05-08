# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/compiler_gym/envs/gcc/gcc.py

Prompts

```
['run the Gcc class to query a GCC binary for its version, optimization flags, and parameter space', 'parse the GCC optimization help output to extract all available -O and -f flag options', 'parse the GCC param help output to extract all available --param options with their valid value ranges', 'create a GccFlagOption instance to represent a boolean -f flag with on and off variants', 'fix known GCC option parsing issues like invalid min values or renamed flags', 'create a GccEnv instance with a custom gcc_bin path and benchmark URI for reinforcement learning', 'reset the GccEnv with a new benchmark, action space, or observation space configuration', 'get the GccSpec description of the compiler specification including available options and flags', 'get the assembly code, object code, their sizes, and hashes from the GccEnv observation', 'set the current compiler flag choices as a list of ints matching gcc_spec options', 'create an AsmSizeReward instance to compute rewards based on assembly code size reduction in bytes', 'create an ObjSizeReward instance to compute rewards based on object code size reduction in bytes', 'reset the AsmSizeReward state by calling reset with a benchmark and observation view', 'reset the ObjSizeReward state by calling reset with a benchmark and observation view', 'update the AsmSizeReward and get the reward delta from the previous assembly size observation']
```

Usage

```
{'run_gcc_spec': 'run the Gcc class to query a GCC binary for its version, optimization flags, and parameter space', 'parse_gcc_optimize': 'parse the GCC optimization help output to extract all available -O and -f flag options', 'parse_gcc_params': 'parse the GCC param help output to extract all available --param options with their valid value ranges', 'create_gcc_flag_option': 'create a GccFlagOption instance to represent a boolean -f flag with on and off variants', 'fix_gcc_options': 'fix known GCC option parsing issues like invalid min values or renamed flags'}
```

## File: facebookresearch_compilergym/compiler_gym/envs/gcc/gcc_env.py

Prompts

```
['run the Gcc class to query a GCC binary for its version, optimization flags, and parameter space', 'parse the GCC optimization help output to extract all available -O and -f flag options', 'parse the GCC param help output to extract all available --param options with their valid value ranges', 'create a GccFlagOption instance to represent a boolean -f flag with on and off variants', 'fix known GCC option parsing issues like invalid min values or renamed flags', 'create a GccEnv instance with a custom gcc_bin path and benchmark URI for reinforcement learning', 'reset the GccEnv with a new benchmark, action space, or observation space configuration', 'get the GccSpec description of the compiler specification including available options and flags', 'get the assembly code, object code, their sizes, and hashes from the GccEnv observation', 'set the current compiler flag choices as a list of ints matching gcc_spec options', 'create an AsmSizeReward instance to compute rewards based on assembly code size reduction in bytes', 'create an ObjSizeReward instance to compute rewards based on object code size reduction in bytes', 'reset the AsmSizeReward state by calling reset with a benchmark and observation view', 'reset the ObjSizeReward state by calling reset with a benchmark and observation view', 'update the AsmSizeReward and get the reward delta from the previous assembly size observation']
```

Usage

```
{'create_gcc_env': 'create a GccEnv instance with a custom gcc_bin path and benchmark URI for reinforcement learning', 'reset_gcc_env_benchmark': 'reset the GccEnv with a new benchmark, action space, or observation space configuration', 'get_gcc_spec': 'get the GccSpec description of the compiler specification including available options and flags', 'get_asm_and_obj_observations': 'get the assembly code, object code, their sizes, and hashes from the GccEnv observation', 'set_gcc_compiler_choices': 'set the current compiler flag choices as a list of ints matching gcc_spec options'}
```

## File: facebookresearch_compilergym/compiler_gym/envs/gcc/gcc_rewards.py

Prompts

```
['run the Gcc class to query a GCC binary for its version, optimization flags, and parameter space', 'parse the GCC optimization help output to extract all available -O and -f flag options', 'parse the GCC param help output to extract all available --param options with their valid value ranges', 'create a GccFlagOption instance to represent a boolean -f flag with on and off variants', 'fix known GCC option parsing issues like invalid min values or renamed flags', 'create a GccEnv instance with a custom gcc_bin path and benchmark URI for reinforcement learning', 'reset the GccEnv with a new benchmark, action space, or observation space configuration', 'get the GccSpec description of the compiler specification including available options and flags', 'get the assembly code, object code, their sizes, and hashes from the GccEnv observation', 'set the current compiler flag choices as a list of ints matching gcc_spec options', 'create an AsmSizeReward instance to compute rewards based on assembly code size reduction in bytes', 'create an ObjSizeReward instance to compute rewards based on object code size reduction in bytes', 'reset the AsmSizeReward state by calling reset with a benchmark and observation view', 'reset the ObjSizeReward state by calling reset with a benchmark and observation view', 'update the AsmSizeReward and get the reward delta from the previous assembly size observation']
```

Usage

```
{'create_asm_size_reward': 'create an AsmSizeReward instance to compute rewards based on assembly code size reduction in bytes', 'create_obj_size_reward': 'create an ObjSizeReward instance to compute rewards based on object code size reduction in bytes', 'reset_asm_size_reward': 'reset the AsmSizeReward state by calling reset with a benchmark and observation view', 'reset_obj_size_reward': 'reset the ObjSizeReward state by calling reset with a benchmark and observation view', 'update_asm_size_reward': 'update the AsmSizeReward and get the reward delta from the previous assembly size observation'}
```

