# Agent Python Tools

- repo: google-deepmind/diplomacy
- repo_uri: https://github.com/google-deepmind/diplomacy

## File: google-deepmind_diplomacy/tests/mila_actions_test.py

Prompts

```
['test that converting a DM action to MILA and back recovers the original DM action', 'test that converting a MILA action to DM and back recovers the original MILA action', 'test that every MILA action maps to at least one corresponding DM action', 'test that ambiguous MILA actions only map to REMOVE and DISBAND DM actions', 'test that each DM action maps to 1, 2, 3, 4, or 6 possible MILA actions', 'test the EncoderCore network module with random adjacency matrices and verify output tensor shapes', 'test the BoardEncoder network module with state representations, seasons, and build numbers for 7 players', 'test the RelationalOrderDecoder recurrent network with teacher forcing and verify action output shapes', 'test the Network inference method with batched observations and multiple copies per observation', 'test the Network loss_info method to verify all expected loss keys and scalar output shapes', 'reconstruct an Observation tuple from a base-type OrderedDict loaded from an npz file', 'sort the last moves in a sequence of Observations to make tests permutation invariant', 'create a FixedPlayPolicy that returns pre-defined actions sequentially for testing Diplomacy game trajectories', 'test network loading by running 10 turns of a Diplomacy game and comparing against reference observations', 'test a Diplomacy adjudicator implementation by comparing game trajectories against reference observations and legal actions']
```

Usage

```
{'test_dm_to_mila_inversion': 'test that converting a DM action to MILA and back recovers the original DM action', 'test_mila_to_dm_inversion': 'test that converting a MILA action to DM and back recovers the original MILA action', 'test_mila_dm_coverage': 'test that every MILA action maps to at least one corresponding DM action', 'test_disband_remove_ambiguity': 'test that ambiguous MILA actions only map to REMOVE and DISBAND DM actions', 'test_mila_action_count_bounds': 'test that each DM action maps to 1, 2, 3, 4, or 6 possible MILA actions'}
```

## File: google-deepmind_diplomacy/tests/network_test.py

Prompts

```
['test that converting a DM action to MILA and back recovers the original DM action', 'test that converting a MILA action to DM and back recovers the original MILA action', 'test that every MILA action maps to at least one corresponding DM action', 'test that ambiguous MILA actions only map to REMOVE and DISBAND DM actions', 'test that each DM action maps to 1, 2, 3, 4, or 6 possible MILA actions', 'test the EncoderCore network module with random adjacency matrices and verify output tensor shapes', 'test the BoardEncoder network module with state representations, seasons, and build numbers for 7 players', 'test the RelationalOrderDecoder recurrent network with teacher forcing and verify action output shapes', 'test the Network inference method with batched observations and multiple copies per observation', 'test the Network loss_info method to verify all expected loss keys and scalar output shapes', 'reconstruct an Observation tuple from a base-type OrderedDict loaded from an npz file', 'sort the last moves in a sequence of Observations to make tests permutation invariant', 'create a FixedPlayPolicy that returns pre-defined actions sequentially for testing Diplomacy game trajectories', 'test network loading by running 10 turns of a Diplomacy game and comparing against reference observations', 'test a Diplomacy adjudicator implementation by comparing game trajectories against reference observations and legal actions']
```

Usage

```
{'test_encoder_core': 'test the EncoderCore network module with random adjacency matrices and verify output tensor shapes', 'test_board_encoder': 'test the BoardEncoder network module with state representations, seasons, and build numbers for 7 players', 'test_relational_order_decoder': 'test the RelationalOrderDecoder recurrent network with teacher forcing and verify action output shapes', 'test_network_inference': 'test the Network inference method with batched observations and multiple copies per observation', 'test_network_loss_info': 'test the Network loss_info method to verify all expected loss keys and scalar output shapes'}
```

## File: google-deepmind_diplomacy/tests/observation_test.py

Prompts

```
['test that converting a DM action to MILA and back recovers the original DM action', 'test that converting a MILA action to DM and back recovers the original MILA action', 'test that every MILA action maps to at least one corresponding DM action', 'test that ambiguous MILA actions only map to REMOVE and DISBAND DM actions', 'test that each DM action maps to 1, 2, 3, 4, or 6 possible MILA actions', 'test the EncoderCore network module with random adjacency matrices and verify output tensor shapes', 'test the BoardEncoder network module with state representations, seasons, and build numbers for 7 players', 'test the RelationalOrderDecoder recurrent network with teacher forcing and verify action output shapes', 'test the Network inference method with batched observations and multiple copies per observation', 'test the Network loss_info method to verify all expected loss keys and scalar output shapes', 'reconstruct an Observation tuple from a base-type OrderedDict loaded from an npz file', 'sort the last moves in a sequence of Observations to make tests permutation invariant', 'create a FixedPlayPolicy that returns pre-defined actions sequentially for testing Diplomacy game trajectories', 'test network loading by running 10 turns of a Diplomacy game and comparing against reference observations', 'test a Diplomacy adjudicator implementation by comparing game trajectories against reference observations and legal actions']
```

Usage

```
{'construct_observations': 'reconstruct an Observation tuple from a base-type OrderedDict loaded from an npz file', 'sort_last_moves': 'sort the last moves in a sequence of Observations to make tests permutation invariant', 'FixedPlayPolicy': 'create a FixedPlayPolicy that returns pre-defined actions sequentially for testing Diplomacy game trajectories', 'test_network_play': 'test network loading by running 10 turns of a Diplomacy game and comparing against reference observations', 'test_fixed_play': 'test a Diplomacy adjudicator implementation by comparing game trajectories against reference observations and legal actions'}
```

