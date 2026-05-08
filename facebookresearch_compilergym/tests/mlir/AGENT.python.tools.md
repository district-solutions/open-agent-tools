# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/tests/mlir/mlir_env_test.py

Prompts

```
['test the MlirEnv service version matches the compiler_gym package version', 'test the MlirEnv compiler version starts with LLVM 14', 'test the MlirEnv action space structure for MatrixMultiplication tile and vectorize options', 'test creating an MLIR RL wrapper environment and verify its action and observation spaces', 'test converting RL wrapper discrete actions back to native MlirEnv action format', 'test the RLlib PPO smoke test that trains a PPO agent on the CompilerGym MLIR environment using Ray in local mode', 'run the PPO smoke test module directly to verify RLlib integration with the MLIR gym environment', 'review the test_rllib_ppo_smoke function that configures a PPOTrainer with a minimal torch model for MLIR optimization', 'summarize the test_rllib_ppo_smoke function that registers an MLIR RL wrapper env and runs a single PPO training step', 'refactor the test_rllib_ppo_smoke function to adjust PPO training config parameters like batch size or rollout length']
```

Usage

```
{'test_MlirEnv_service_version': 'test the MlirEnv service version matches the compiler_gym package version', 'test_MlirEnv_compiler_version': 'test the MlirEnv compiler version starts with LLVM 14', 'test_MlirEnv_action_space': 'test the MlirEnv action space structure for MatrixMultiplication tile and vectorize options', 'test_make_mlir_rl_wrapper_env': 'test creating an MLIR RL wrapper environment and verify its action and observation spaces', 'test_convert_action': 'test converting RL wrapper discrete actions back to native MlirEnv action format'}
```

## File: facebookresearch_compilergym/tests/mlir/rllib_ppo_smoke_test.py

Prompts

```
['test the MlirEnv service version matches the compiler_gym package version', 'test the MlirEnv compiler version starts with LLVM 14', 'test the MlirEnv action space structure for MatrixMultiplication tile and vectorize options', 'test creating an MLIR RL wrapper environment and verify its action and observation spaces', 'test converting RL wrapper discrete actions back to native MlirEnv action format', 'test the RLlib PPO smoke test that trains a PPO agent on the CompilerGym MLIR environment using Ray in local mode', 'run the PPO smoke test module directly to verify RLlib integration with the MLIR gym environment', 'review the test_rllib_ppo_smoke function that configures a PPOTrainer with a minimal torch model for MLIR optimization', 'summarize the test_rllib_ppo_smoke function that registers an MLIR RL wrapper env and runs a single PPO training step', 'refactor the test_rllib_ppo_smoke function to adjust PPO training config parameters like batch size or rollout length']
```

Usage

```
{'test_rllib_ppo_smoke': 'test the RLlib PPO smoke test that trains a PPO agent on the CompilerGym MLIR environment using Ray in local mode', 'run_rllib_ppo_smoke_test': 'run the PPO smoke test module directly to verify RLlib integration with the MLIR gym environment', 'review_test_rllib_ppo_smoke': 'review the test_rllib_ppo_smoke function that configures a PPOTrainer with a minimal torch model for MLIR optimization', 'summarize_test_rllib_ppo_smoke': 'summarize the test_rllib_ppo_smoke function that registers an MLIR RL wrapper env and runs a single PPO training step', 'refactor_test_rllib_ppo_smoke': 'refactor the test_rllib_ppo_smoke function to adjust PPO training config parameters like batch size or rollout length'}
```

