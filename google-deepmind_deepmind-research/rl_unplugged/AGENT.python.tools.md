# Agent Python Tools

- repo: google-deepmind/deepmind-research
- repo_uri: https://github.com/google-deepmind/deepmind-research

## File: google-deepmind_deepmind-research/rl_unplugged/atari.py

Prompts

```
['build a tensorflow dataset of Atari SARSA transitions from TFRecord shards for a given game and run', 'create a fully wrapped Atari environment with frame stacking and single precision for a given game', 'decode four PNG encoded frames into an 84x84x4 grayscale uint8 tensor', 'create a Reverb replay sample from SARSA transition data including observations actions rewards and discounts', 'wrap a Dopamine Atari environment to produce dm_env transitions with episode step tracking and max step truncation', 'build a ControlSuite environment for a dm_control task like humanoid_run or cheetah_run', 'build a CmuThirdParty environment for humanoid locomotion tasks like humanoid_walls or humanoid_gaps', 'build a Rodent environment for rodent locomotion tasks like rodent_escape or rodent_mazes', 'create a TensorFlow dataset from TFRecord files for RL training with SARSA or sequence sampling', 'wrap an environment with FilterObservationsWrapper to keep only specified observation keys', 'build a ControlNetwork module to encode proprioceptive observations for an RL actor or critic', 'create a function that applies instance normalization and ELU activation to a tensor', 'test the ControlNetwork call method with a dictionary of observation tensors and optional actions', 'refactor the ControlNetwork init to support custom activation functions and proprioceptive key filtering', 'review the ControlNetwork call method input validation that rejects pixel-like tensors as proprioceptive state', 'build a TF dataset of RWRL SARSA tuples from TFRecord shards for offline RL training', 'create a Real World RL environment for a given domain and task with single precision wrapper', 'convert a TF Example episode into SARSA Reverb replay samples for offline RL', 'deflatten a flat dictionary with delimited keys back into its original nested structure', 'parse a TF Example string tensor and return its feature description with fixed length features']
```

Usage

```
{'build_atari_dataset': 'build a tensorflow dataset of Atari SARSA transitions from TFRecord shards for a given game and run', 'create_atari_environment': 'create a fully wrapped Atari environment with frame stacking and single precision for a given game', 'decode_atari_frames': 'decode four PNG encoded frames into an 84x84x4 grayscale uint8 tensor', 'create_reverb_sample': 'create a Reverb replay sample from SARSA transition data including observations actions rewards and discounts', 'wrap_atari_with_dopamine': 'wrap a Dopamine Atari environment to produce dm_env transitions with episode step tracking and max step truncation'}
```

## File: google-deepmind_deepmind-research/rl_unplugged/dm_control_suite.py

Prompts

```
['build a tensorflow dataset of Atari SARSA transitions from TFRecord shards for a given game and run', 'create a fully wrapped Atari environment with frame stacking and single precision for a given game', 'decode four PNG encoded frames into an 84x84x4 grayscale uint8 tensor', 'create a Reverb replay sample from SARSA transition data including observations actions rewards and discounts', 'wrap a Dopamine Atari environment to produce dm_env transitions with episode step tracking and max step truncation', 'build a ControlSuite environment for a dm_control task like humanoid_run or cheetah_run', 'build a CmuThirdParty environment for humanoid locomotion tasks like humanoid_walls or humanoid_gaps', 'build a Rodent environment for rodent locomotion tasks like rodent_escape or rodent_mazes', 'create a TensorFlow dataset from TFRecord files for RL training with SARSA or sequence sampling', 'wrap an environment with FilterObservationsWrapper to keep only specified observation keys', 'build a ControlNetwork module to encode proprioceptive observations for an RL actor or critic', 'create a function that applies instance normalization and ELU activation to a tensor', 'test the ControlNetwork call method with a dictionary of observation tensors and optional actions', 'refactor the ControlNetwork init to support custom activation functions and proprioceptive key filtering', 'review the ControlNetwork call method input validation that rejects pixel-like tensors as proprioceptive state', 'build a TF dataset of RWRL SARSA tuples from TFRecord shards for offline RL training', 'create a Real World RL environment for a given domain and task with single precision wrapper', 'convert a TF Example episode into SARSA Reverb replay samples for offline RL', 'deflatten a flat dictionary with delimited keys back into its original nested structure', 'parse a TF Example string tensor and return its feature description with fixed length features']
```

Usage

```
{'build_control_suite_environment': 'build a ControlSuite environment for a dm_control task like humanoid_run or cheetah_run', 'build_cmu_third_party_environment': 'build a CmuThirdParty environment for humanoid locomotion tasks like humanoid_walls or humanoid_gaps', 'build_rodent_environment': 'build a Rodent environment for rodent locomotion tasks like rodent_escape or rodent_mazes', 'create_training_dataset': 'create a TensorFlow dataset from TFRecord files for RL training with SARSA or sequence sampling', 'filter_observations_wrapper': 'wrap an environment with FilterObservationsWrapper to keep only specified observation keys'}
```

## File: google-deepmind_deepmind-research/rl_unplugged/networks.py

Prompts

```
['build a tensorflow dataset of Atari SARSA transitions from TFRecord shards for a given game and run', 'create a fully wrapped Atari environment with frame stacking and single precision for a given game', 'decode four PNG encoded frames into an 84x84x4 grayscale uint8 tensor', 'create a Reverb replay sample from SARSA transition data including observations actions rewards and discounts', 'wrap a Dopamine Atari environment to produce dm_env transitions with episode step tracking and max step truncation', 'build a ControlSuite environment for a dm_control task like humanoid_run or cheetah_run', 'build a CmuThirdParty environment for humanoid locomotion tasks like humanoid_walls or humanoid_gaps', 'build a Rodent environment for rodent locomotion tasks like rodent_escape or rodent_mazes', 'create a TensorFlow dataset from TFRecord files for RL training with SARSA or sequence sampling', 'wrap an environment with FilterObservationsWrapper to keep only specified observation keys', 'build a ControlNetwork module to encode proprioceptive observations for an RL actor or critic', 'create a function that applies instance normalization and ELU activation to a tensor', 'test the ControlNetwork call method with a dictionary of observation tensors and optional actions', 'refactor the ControlNetwork init to support custom activation functions and proprioceptive key filtering', 'review the ControlNetwork call method input validation that rejects pixel-like tensors as proprioceptive state', 'build a TF dataset of RWRL SARSA tuples from TFRecord shards for offline RL training', 'create a Real World RL environment for a given domain and task with single precision wrapper', 'convert a TF Example episode into SARSA Reverb replay samples for offline RL', 'deflatten a flat dictionary with delimited keys back into its original nested structure', 'parse a TF Example string tensor and return its feature description with fixed length features']
```

Usage

```
{'build_control_network': 'build a ControlNetwork module to encode proprioceptive observations for an RL actor or critic', 'create_instance_norm_elu': 'create a function that applies instance normalization and ELU activation to a tensor', 'test_control_network_call': 'test the ControlNetwork call method with a dictionary of observation tensors and optional actions', 'refactor_control_network_init': 'refactor the ControlNetwork init to support custom activation functions and proprioceptive key filtering', 'review_control_network_validation': 'review the ControlNetwork call method input validation that rejects pixel-like tensors as proprioceptive state'}
```

## File: google-deepmind_deepmind-research/rl_unplugged/rwrl.py

Prompts

```
['build a tensorflow dataset of Atari SARSA transitions from TFRecord shards for a given game and run', 'create a fully wrapped Atari environment with frame stacking and single precision for a given game', 'decode four PNG encoded frames into an 84x84x4 grayscale uint8 tensor', 'create a Reverb replay sample from SARSA transition data including observations actions rewards and discounts', 'wrap a Dopamine Atari environment to produce dm_env transitions with episode step tracking and max step truncation', 'build a ControlSuite environment for a dm_control task like humanoid_run or cheetah_run', 'build a CmuThirdParty environment for humanoid locomotion tasks like humanoid_walls or humanoid_gaps', 'build a Rodent environment for rodent locomotion tasks like rodent_escape or rodent_mazes', 'create a TensorFlow dataset from TFRecord files for RL training with SARSA or sequence sampling', 'wrap an environment with FilterObservationsWrapper to keep only specified observation keys', 'build a ControlNetwork module to encode proprioceptive observations for an RL actor or critic', 'create a function that applies instance normalization and ELU activation to a tensor', 'test the ControlNetwork call method with a dictionary of observation tensors and optional actions', 'refactor the ControlNetwork init to support custom activation functions and proprioceptive key filtering', 'review the ControlNetwork call method input validation that rejects pixel-like tensors as proprioceptive state', 'build a TF dataset of RWRL SARSA tuples from TFRecord shards for offline RL training', 'create a Real World RL environment for a given domain and task with single precision wrapper', 'convert a TF Example episode into SARSA Reverb replay samples for offline RL', 'deflatten a flat dictionary with delimited keys back into its original nested structure', 'parse a TF Example string tensor and return its feature description with fixed length features']
```

Usage

```
{'build_rwrl_dataset': 'build a TF dataset of RWRL SARSA tuples from TFRecord shards for offline RL training', 'create_rwrl_environment': 'create a Real World RL environment for a given domain and task with single precision wrapper', 'convert_tf_example_to_reverb_sample': 'convert a TF Example episode into SARSA Reverb replay samples for offline RL', 'deflatten_nested_dict': 'deflatten a flat dictionary with delimited keys back into its original nested structure', 'parse_tf_example_features': 'parse a TF Example string tensor and return its feature description with fixed length features'}
```

