# Agent Python Tools

- repo: facebookresearch/salina
- repo_uri: https://github.com/facebookresearch/salina

## File: facebookresearch_salina/salina/rl/functional.py

Prompts

```
['compute the mean cumulated reward across batch trajectories using reward and done tensors', 'compute temporal difference targets for a critic network given reward, done, and discount factor', 'compute double Q-learning temporal difference using Q values, actions, target Q, reward, and done', 'compute generalized advantage estimation from critic values, rewards, done flags, discount, and GAE coefficient', 'compute REINFORCE policy gradient loss with baseline loss, policy loss, and entropy loss components', 'create a ReplayBuffer with a max size and target device for RL experience storage', 'put a Workspace of trajectories into the ReplayBuffer for later sampling', 'sample a batch of random transitions from the ReplayBuffer as a Workspace', 'check the current number of stored transitions in the ReplayBuffer', 'move all ReplayBuffer tensors to a new device like cuda']
```

Usage

```
{'compute_cumulated_reward': 'compute the mean cumulated reward across batch trajectories using reward and done tensors', 'compute_temporal_difference': 'compute temporal difference targets for a critic network given reward, done, and discount factor', 'compute_double_q_td': 'compute double Q-learning temporal difference using Q values, actions, target Q, reward, and done', 'compute_gae': 'compute generalized advantage estimation from critic values, rewards, done flags, discount, and GAE coefficient', 'compute_reinforce_loss': 'compute REINFORCE policy gradient loss with baseline loss, policy loss, and entropy loss components'}
```

## File: facebookresearch_salina/salina/rl/replay_buffer.py

Prompts

```
['compute the mean cumulated reward across batch trajectories using reward and done tensors', 'compute temporal difference targets for a critic network given reward, done, and discount factor', 'compute double Q-learning temporal difference using Q values, actions, target Q, reward, and done', 'compute generalized advantage estimation from critic values, rewards, done flags, discount, and GAE coefficient', 'compute REINFORCE policy gradient loss with baseline loss, policy loss, and entropy loss components', 'create a ReplayBuffer with a max size and target device for RL experience storage', 'put a Workspace of trajectories into the ReplayBuffer for later sampling', 'sample a batch of random transitions from the ReplayBuffer as a Workspace', 'check the current number of stored transitions in the ReplayBuffer', 'move all ReplayBuffer tensors to a new device like cuda']
```

Usage

```
{'create_replay_buffer': 'create a ReplayBuffer with a max size and target device for RL experience storage', 'put_workspace_into_buffer': 'put a Workspace of trajectories into the ReplayBuffer for later sampling', 'sample_from_replay_buffer': 'sample a batch of random transitions from the ReplayBuffer as a Workspace', 'check_replay_buffer_size': 'check the current number of stored transitions in the ReplayBuffer', 'move_replay_buffer_to_device': 'move all ReplayBuffer tensors to a new device like cuda'}
```

