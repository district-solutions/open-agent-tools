# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-baselines/habitat_baselines/agents/mp_agents.py

Prompts

```
['build a ParameterizedAgent subclass to control a robot arm in a Habitat simulation environment', 'create an AgentComposition that chains multiple ParameterizedAgent skills to execute sequentially in order', 'use an ArmTargModule to plan and execute arm motion toward a target end-effector position', 'implement an IkMoveArm agent that moves the arm end-effector toward a target using inverse kinematics', 'run a SpaManipPick agent to plan a grasp approach and pick up a specified object', 'run a PPO agent benchmark evaluation using a pretrained checkpoint and task config YAML', 'create a PPOAgentConfig dataclass with custom input type, model path, resolution, and hidden size', 'get the default OmegaConf DictConfig for a PPO agent from PPOAgentConfig', 'reset the PPO agent recurrent hidden states, not done masks, and previous actions tensors', 'act with the PPO agent on observations using the actor-critic policy and return an action', 'run a RandomAgent that takes random actions until the goal distance threshold is reached', 'run a ForwardOnlyAgent that moves forward until the goal distance threshold is reached', 'run a RandomForwardAgent that moves forward with 80% probability and turns otherwise', 'run a GoalFollower agent that turns toward the goal and moves forward when aligned', 'evaluate any agent class against a Habitat task config and log benchmark metrics', 'run the ORBSLAM2Agent with RGBD input for navigation in Habitat simulator environments', 'run the ORBSLAM2MonodepthAgent that estimates depth from RGB images using a mono depth model', 'run the BlindAgent that navigates toward a goal using only GPS compass sensor data', 'run the main CLI to benchmark blind, orbslam2-rgbd, or orbslam2-rgb-monod agents on Habitat tasks']
```

Usage

```
{'build_ParameterizedAgent': 'build a ParameterizedAgent subclass to control a robot arm in a Habitat simulation environment', 'create_AgentComposition': 'create an AgentComposition that chains multiple ParameterizedAgent skills to execute sequentially in order', 'use_ArmTargModule': 'use an ArmTargModule to plan and execute arm motion toward a target end-effector position', 'implement_IkMoveArm': 'implement an IkMoveArm agent that moves the arm end-effector toward a target using inverse kinematics', 'run_SpaManipPick': 'run a SpaManipPick agent to plan a grasp approach and pick up a specified object'}
```

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-baselines/habitat_baselines/agents/ppo_agents.py

Prompts

```
['build a ParameterizedAgent subclass to control a robot arm in a Habitat simulation environment', 'create an AgentComposition that chains multiple ParameterizedAgent skills to execute sequentially in order', 'use an ArmTargModule to plan and execute arm motion toward a target end-effector position', 'implement an IkMoveArm agent that moves the arm end-effector toward a target using inverse kinematics', 'run a SpaManipPick agent to plan a grasp approach and pick up a specified object', 'run a PPO agent benchmark evaluation using a pretrained checkpoint and task config YAML', 'create a PPOAgentConfig dataclass with custom input type, model path, resolution, and hidden size', 'get the default OmegaConf DictConfig for a PPO agent from PPOAgentConfig', 'reset the PPO agent recurrent hidden states, not done masks, and previous actions tensors', 'act with the PPO agent on observations using the actor-critic policy and return an action', 'run a RandomAgent that takes random actions until the goal distance threshold is reached', 'run a ForwardOnlyAgent that moves forward until the goal distance threshold is reached', 'run a RandomForwardAgent that moves forward with 80% probability and turns otherwise', 'run a GoalFollower agent that turns toward the goal and moves forward when aligned', 'evaluate any agent class against a Habitat task config and log benchmark metrics', 'run the ORBSLAM2Agent with RGBD input for navigation in Habitat simulator environments', 'run the ORBSLAM2MonodepthAgent that estimates depth from RGB images using a mono depth model', 'run the BlindAgent that navigates toward a goal using only GPS compass sensor data', 'run the main CLI to benchmark blind, orbslam2-rgbd, or orbslam2-rgb-monod agents on Habitat tasks']
```

Usage

```
{'run_ppo_agent_benchmark': 'run a PPO agent benchmark evaluation using a pretrained checkpoint and task config YAML', 'create_ppo_agent_config': 'create a PPOAgentConfig dataclass with custom input type, model path, resolution, and hidden size', 'get_default_ppo_config': 'get the default OmegaConf DictConfig for a PPO agent from PPOAgentConfig', 'reset_ppo_agent': 'reset the PPO agent recurrent hidden states, not done masks, and previous actions tensors', 'act_ppo_agent': 'act with the PPO agent on observations using the actor-critic policy and return an action'}
```

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-baselines/habitat_baselines/agents/simple_agents.py

Prompts

```
['build a ParameterizedAgent subclass to control a robot arm in a Habitat simulation environment', 'create an AgentComposition that chains multiple ParameterizedAgent skills to execute sequentially in order', 'use an ArmTargModule to plan and execute arm motion toward a target end-effector position', 'implement an IkMoveArm agent that moves the arm end-effector toward a target using inverse kinematics', 'run a SpaManipPick agent to plan a grasp approach and pick up a specified object', 'run a PPO agent benchmark evaluation using a pretrained checkpoint and task config YAML', 'create a PPOAgentConfig dataclass with custom input type, model path, resolution, and hidden size', 'get the default OmegaConf DictConfig for a PPO agent from PPOAgentConfig', 'reset the PPO agent recurrent hidden states, not done masks, and previous actions tensors', 'act with the PPO agent on observations using the actor-critic policy and return an action', 'run a RandomAgent that takes random actions until the goal distance threshold is reached', 'run a ForwardOnlyAgent that moves forward until the goal distance threshold is reached', 'run a RandomForwardAgent that moves forward with 80% probability and turns otherwise', 'run a GoalFollower agent that turns toward the goal and moves forward when aligned', 'evaluate any agent class against a Habitat task config and log benchmark metrics', 'run the ORBSLAM2Agent with RGBD input for navigation in Habitat simulator environments', 'run the ORBSLAM2MonodepthAgent that estimates depth from RGB images using a mono depth model', 'run the BlindAgent that navigates toward a goal using only GPS compass sensor data', 'run the main CLI to benchmark blind, orbslam2-rgbd, or orbslam2-rgb-monod agents on Habitat tasks']
```

Usage

```
{'run_random_agent': 'run a RandomAgent that takes random actions until the goal distance threshold is reached', 'run_forward_only_agent': 'run a ForwardOnlyAgent that moves forward until the goal distance threshold is reached', 'run_random_forward_agent': 'run a RandomForwardAgent that moves forward with 80% probability and turns otherwise', 'run_goal_follower_agent': 'run a GoalFollower agent that turns toward the goal and moves forward when aligned', 'evaluate_agent_with_benchmark': 'evaluate any agent class against a Habitat task config and log benchmark metrics'}
```

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-baselines/habitat_baselines/agents/slam_agents.py

Prompts

```
['build a ParameterizedAgent subclass to control a robot arm in a Habitat simulation environment', 'create an AgentComposition that chains multiple ParameterizedAgent skills to execute sequentially in order', 'use an ArmTargModule to plan and execute arm motion toward a target end-effector position', 'implement an IkMoveArm agent that moves the arm end-effector toward a target using inverse kinematics', 'run a SpaManipPick agent to plan a grasp approach and pick up a specified object', 'run a PPO agent benchmark evaluation using a pretrained checkpoint and task config YAML', 'create a PPOAgentConfig dataclass with custom input type, model path, resolution, and hidden size', 'get the default OmegaConf DictConfig for a PPO agent from PPOAgentConfig', 'reset the PPO agent recurrent hidden states, not done masks, and previous actions tensors', 'act with the PPO agent on observations using the actor-critic policy and return an action', 'run a RandomAgent that takes random actions until the goal distance threshold is reached', 'run a ForwardOnlyAgent that moves forward until the goal distance threshold is reached', 'run a RandomForwardAgent that moves forward with 80% probability and turns otherwise', 'run a GoalFollower agent that turns toward the goal and moves forward when aligned', 'evaluate any agent class against a Habitat task config and log benchmark metrics', 'run the ORBSLAM2Agent with RGBD input for navigation in Habitat simulator environments', 'run the ORBSLAM2MonodepthAgent that estimates depth from RGB images using a mono depth model', 'run the BlindAgent that navigates toward a goal using only GPS compass sensor data', 'run the main CLI to benchmark blind, orbslam2-rgbd, or orbslam2-rgb-monod agents on Habitat tasks']
```

Usage

```
{'run_orbslam2_rgbd_agent': 'run the ORBSLAM2Agent with RGBD input for navigation in Habitat simulator environments', 'run_orbslam2_monodepth_agent': 'run the ORBSLAM2MonodepthAgent that estimates depth from RGB images using a mono depth model', 'run_blind_agent': 'run the BlindAgent that navigates toward a goal using only GPS compass sensor data', 'run_random_agent': 'run the RandomAgent baseline that takes random actions until the goal distance threshold is reached', 'run_slam_agents_benchmark': 'run the main CLI to benchmark blind, orbslam2-rgbd, or orbslam2-rgb-monod agents on Habitat tasks'}
```

