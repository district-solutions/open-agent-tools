# Agent Python Tools

- repo: facebookresearch/fairscale
- repo_uri: https://github.com/facebookresearch/fairscale

## File: facebookresearch_fairscale/fairscale/experimental/nn/data_parallel/gossip/distributed.py

Prompts

```
['build a SlowMoDistributedDataParallel wrapper around a PyTorch module for multi-node distributed training with SlowMo momentum', 'create a SlowMoBaseAlgorithm enum to choose between LOCALSGD or SGP base algorithms for distributed averaging', 'run the perform_slowmo method after optimizer.step to synchronize parameters across nodes using slow momentum', 'review the _sgp_gossip_target static method that runs the background gossip thread for push-sum parameter mixing', 'refactor the _init_global_momentum_buffers method to shard slow momentum parameters across nodes for memory efficiency', 'create a Gossiper instance with a torch tensor message and GraphManager for multi-peer communication', 'run a PushSum mix step to perform consensus averaging across distributed peers', 'run a PushPull mix step to perform doubly-stochastic consensus averaging across peers', 'refresh the in and out peers on a Gossiper instance using refresh_peers_ with rotation', 'mix outgoing messages with weights using mix_out_msg_ to prepare tensors for gossip communication', 'create a RingGraph instance to build a static ring topology for peer-to-peer communication', 'create a DynamicDirectedExponentialGraph to build an exponential peer-to-peer communication topology', 'create a DynamicBipartiteExponentialGraph to build a bipartite graph for alternating peer communication', 'get the out-peers and in-peers for a rank using GraphManager get_peers or get_edges methods', 'create an NPeerDynamicDirectedExponentialGraph to build a configurable N-peer dynamic topology', 'create a UniformMixing instance with a GraphManager and torch device for gossip mixing weights', 'get mixing weights from a UniformMixing instance using uniform allocation across peers', 'check if a MixingManager graph is regular with no bias in stationary distribution', 'check if a MixingManager distributes mixing weights uniformly over peers', 'review the MixingManager abstract class API for implementing custom gossip mixing strategies']
```

Usage

```
{'build_slowmo_ddp_wrapper': 'build a SlowMoDistributedDataParallel wrapper around a PyTorch module for multi-node distributed training with SlowMo momentum', 'create_slowmo_base_algorithm': 'create a SlowMoBaseAlgorithm enum to choose between LOCALSGD or SGP base algorithms for distributed averaging', 'run_perform_slowmo_step': 'run the perform_slowmo method after optimizer.step to synchronize parameters across nodes using slow momentum', 'review_sgp_gossip_thread': 'review the _sgp_gossip_target static method that runs the background gossip thread for push-sum parameter mixing', 'refactor_global_momentum_buffers': 'refactor the _init_global_momentum_buffers method to shard slow momentum parameters across nodes for memory efficiency'}
```

## File: facebookresearch_fairscale/fairscale/experimental/nn/data_parallel/gossip/gossiper.py

Prompts

```
['build a SlowMoDistributedDataParallel wrapper around a PyTorch module for multi-node distributed training with SlowMo momentum', 'create a SlowMoBaseAlgorithm enum to choose between LOCALSGD or SGP base algorithms for distributed averaging', 'run the perform_slowmo method after optimizer.step to synchronize parameters across nodes using slow momentum', 'review the _sgp_gossip_target static method that runs the background gossip thread for push-sum parameter mixing', 'refactor the _init_global_momentum_buffers method to shard slow momentum parameters across nodes for memory efficiency', 'create a Gossiper instance with a torch tensor message and GraphManager for multi-peer communication', 'run a PushSum mix step to perform consensus averaging across distributed peers', 'run a PushPull mix step to perform doubly-stochastic consensus averaging across peers', 'refresh the in and out peers on a Gossiper instance using refresh_peers_ with rotation', 'mix outgoing messages with weights using mix_out_msg_ to prepare tensors for gossip communication', 'create a RingGraph instance to build a static ring topology for peer-to-peer communication', 'create a DynamicDirectedExponentialGraph to build an exponential peer-to-peer communication topology', 'create a DynamicBipartiteExponentialGraph to build a bipartite graph for alternating peer communication', 'get the out-peers and in-peers for a rank using GraphManager get_peers or get_edges methods', 'create an NPeerDynamicDirectedExponentialGraph to build a configurable N-peer dynamic topology', 'create a UniformMixing instance with a GraphManager and torch device for gossip mixing weights', 'get mixing weights from a UniformMixing instance using uniform allocation across peers', 'check if a MixingManager graph is regular with no bias in stationary distribution', 'check if a MixingManager distributes mixing weights uniformly over peers', 'review the MixingManager abstract class API for implementing custom gossip mixing strategies']
```

Usage

```
{'create_gossiper_instance': 'create a Gossiper instance with a torch tensor message and GraphManager for multi-peer communication', 'run_pushsum_mix': 'run a PushSum mix step to perform consensus averaging across distributed peers', 'run_pushpull_mix': 'run a PushPull mix step to perform doubly-stochastic consensus averaging across peers', 'refresh_gossiper_peers': 'refresh the in and out peers on a Gossiper instance using refresh_peers_ with rotation', 'mix_outgoing_messages': 'mix outgoing messages with weights using mix_out_msg_ to prepare tensors for gossip communication'}
```

## File: facebookresearch_fairscale/fairscale/experimental/nn/data_parallel/gossip/graph_manager.py

Prompts

```
['build a SlowMoDistributedDataParallel wrapper around a PyTorch module for multi-node distributed training with SlowMo momentum', 'create a SlowMoBaseAlgorithm enum to choose between LOCALSGD or SGP base algorithms for distributed averaging', 'run the perform_slowmo method after optimizer.step to synchronize parameters across nodes using slow momentum', 'review the _sgp_gossip_target static method that runs the background gossip thread for push-sum parameter mixing', 'refactor the _init_global_momentum_buffers method to shard slow momentum parameters across nodes for memory efficiency', 'create a Gossiper instance with a torch tensor message and GraphManager for multi-peer communication', 'run a PushSum mix step to perform consensus averaging across distributed peers', 'run a PushPull mix step to perform doubly-stochastic consensus averaging across peers', 'refresh the in and out peers on a Gossiper instance using refresh_peers_ with rotation', 'mix outgoing messages with weights using mix_out_msg_ to prepare tensors for gossip communication', 'create a RingGraph instance to build a static ring topology for peer-to-peer communication', 'create a DynamicDirectedExponentialGraph to build an exponential peer-to-peer communication topology', 'create a DynamicBipartiteExponentialGraph to build a bipartite graph for alternating peer communication', 'get the out-peers and in-peers for a rank using GraphManager get_peers or get_edges methods', 'create an NPeerDynamicDirectedExponentialGraph to build a configurable N-peer dynamic topology', 'create a UniformMixing instance with a GraphManager and torch device for gossip mixing weights', 'get mixing weights from a UniformMixing instance using uniform allocation across peers', 'check if a MixingManager graph is regular with no bias in stationary distribution', 'check if a MixingManager distributes mixing weights uniformly over peers', 'review the MixingManager abstract class API for implementing custom gossip mixing strategies']
```

Usage

```
{'create_ring_graph_topology': 'create a RingGraph instance to build a static ring topology for peer-to-peer communication', 'create_dynamic_exponential_graph': 'create a DynamicDirectedExponentialGraph to build an exponential peer-to-peer communication topology', 'create_bipartite_graph': 'create a DynamicBipartiteExponentialGraph to build a bipartite graph for alternating peer communication', 'get_peers_and_edges': 'get the out-peers and in-peers for a rank using GraphManager get_peers or get_edges methods', 'create_npeer_dynamic_graph': 'create an NPeerDynamicDirectedExponentialGraph to build a configurable N-peer dynamic topology'}
```

## File: facebookresearch_fairscale/fairscale/experimental/nn/data_parallel/gossip/mixing_manager.py

Prompts

```
['build a SlowMoDistributedDataParallel wrapper around a PyTorch module for multi-node distributed training with SlowMo momentum', 'create a SlowMoBaseAlgorithm enum to choose between LOCALSGD or SGP base algorithms for distributed averaging', 'run the perform_slowmo method after optimizer.step to synchronize parameters across nodes using slow momentum', 'review the _sgp_gossip_target static method that runs the background gossip thread for push-sum parameter mixing', 'refactor the _init_global_momentum_buffers method to shard slow momentum parameters across nodes for memory efficiency', 'create a Gossiper instance with a torch tensor message and GraphManager for multi-peer communication', 'run a PushSum mix step to perform consensus averaging across distributed peers', 'run a PushPull mix step to perform doubly-stochastic consensus averaging across peers', 'refresh the in and out peers on a Gossiper instance using refresh_peers_ with rotation', 'mix outgoing messages with weights using mix_out_msg_ to prepare tensors for gossip communication', 'create a RingGraph instance to build a static ring topology for peer-to-peer communication', 'create a DynamicDirectedExponentialGraph to build an exponential peer-to-peer communication topology', 'create a DynamicBipartiteExponentialGraph to build a bipartite graph for alternating peer communication', 'get the out-peers and in-peers for a rank using GraphManager get_peers or get_edges methods', 'create an NPeerDynamicDirectedExponentialGraph to build a configurable N-peer dynamic topology', 'create a UniformMixing instance with a GraphManager and torch device for gossip mixing weights', 'get mixing weights from a UniformMixing instance using uniform allocation across peers', 'check if a MixingManager graph is regular with no bias in stationary distribution', 'check if a MixingManager distributes mixing weights uniformly over peers', 'review the MixingManager abstract class API for implementing custom gossip mixing strategies']
```

Usage

```
{'create_UniformMixing_instance': 'create a UniformMixing instance with a GraphManager and torch device for gossip mixing weights', 'get_mixing_weights_UniformMixing': 'get mixing weights from a UniformMixing instance using uniform allocation across peers', 'check_is_regular_MixingManager': 'check if a MixingManager graph is regular with no bias in stationary distribution', 'check_is_uniform_MixingManager': 'check if a MixingManager distributes mixing weights uniformly over peers', 'review_MixingManager_abstract_class': 'review the MixingManager abstract class API for implementing custom gossip mixing strategies'}
```

