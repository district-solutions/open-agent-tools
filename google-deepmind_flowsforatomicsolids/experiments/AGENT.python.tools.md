# Agent Python Tools

- repo: google-deepmind/flowsforatomicsolids
- repo_uri: https://github.com/google-deepmind/flows_for_atomic_solids

## File: google-deepmind_flowsforatomicsolids/experiments/lennard_jones_config.py

Prompts

```
['build a config dict for a Lennard-Jones FCC solid phase simulation with a given number of particles', 'review the get_config function that returns a ConfigDict for Lennard-Jones particle model training and testing', 'summarize the FREQUENCIES dictionary mapping particle counts 32, 256, 500 to their corresponding frequency values', 'test the LennardJonesEnergy constructor kwargs used for train and test energy configurations in the config', 'refactor the conditioner dict to use a different Transformer constructor or adjust embedding size and frequency parameters', 'build a ConfigDict for monatomic water in the hexagonal ice phase with a given number of particles', 'build a ConfigDict for monatomic water in the cubic ice phase with a given number of particles', 'summarize the get_config function which constructs training and test configs for flow-based particle models', 'test the get_config function with different particle counts and lattice types to verify config output', 'run energy-based training of a flow model on an atomistic system like Lennard-Jones or monatomic water', 'run the training script with --system=lj_32 and --num_iterations=100000 for a Lennard-Jones 32-particle system', 'review the _get_loss function that samples from a distrax distribution and computes energy-based loss with log probabilities', 'review the main training loop that uses Haiku transforms, JAX JIT, and Optax Adam optimizer with gradient clipping', 'summarize the _num_particles helper function that extracts the particle count from a system name string', 'create a learning rate schedule with configurable decay steps and decay factor for training', 'compute edge lengths of an orthorhombic simulation box given particle count, density, and shape factor', 'compute edge lengths of a hexagonal simulation box for Ih crystal packing', 'compute equal edge lengths of a cubic simulation box from particle count and density', 'summarize the experiment utility functions for learning rate scheduling and simulation box length calculations']
```

Usage

```
{'build_lennard_jones_config': 'build a config dict for a Lennard-Jones FCC solid phase simulation with a given number of particles', 'review_get_config': 'review the get_config function that returns a ConfigDict for Lennard-Jones particle model training and testing', 'summarize_FREQUENCIES': 'summarize the FREQUENCIES dictionary mapping particle counts 32, 256, 500 to their corresponding frequency values', 'test_lennard_jones_energy': 'test the LennardJonesEnergy constructor kwargs used for train and test energy configurations in the config', 'refactor_conditioner': 'refactor the conditioner dict to use a different Transformer constructor or adjust embedding size and frequency parameters'}
```

## File: google-deepmind_flowsforatomicsolids/experiments/monatomic_water_config.py

Prompts

```
['build a config dict for a Lennard-Jones FCC solid phase simulation with a given number of particles', 'review the get_config function that returns a ConfigDict for Lennard-Jones particle model training and testing', 'summarize the FREQUENCIES dictionary mapping particle counts 32, 256, 500 to their corresponding frequency values', 'test the LennardJonesEnergy constructor kwargs used for train and test energy configurations in the config', 'refactor the conditioner dict to use a different Transformer constructor or adjust embedding size and frequency parameters', 'build a ConfigDict for monatomic water in the hexagonal ice phase with a given number of particles', 'build a ConfigDict for monatomic water in the cubic ice phase with a given number of particles', 'summarize the get_config function which constructs training and test configs for flow-based particle models', 'test the get_config function with different particle counts and lattice types to verify config output', 'run energy-based training of a flow model on an atomistic system like Lennard-Jones or monatomic water', 'run the training script with --system=lj_32 and --num_iterations=100000 for a Lennard-Jones 32-particle system', 'review the _get_loss function that samples from a distrax distribution and computes energy-based loss with log probabilities', 'review the main training loop that uses Haiku transforms, JAX JIT, and Optax Adam optimizer with gradient clipping', 'summarize the _num_particles helper function that extracts the particle count from a system name string', 'create a learning rate schedule with configurable decay steps and decay factor for training', 'compute edge lengths of an orthorhombic simulation box given particle count, density, and shape factor', 'compute edge lengths of a hexagonal simulation box for Ih crystal packing', 'compute equal edge lengths of a cubic simulation box from particle count and density', 'summarize the experiment utility functions for learning rate scheduling and simulation box length calculations']
```

Usage

```
{'build_config_hexagonal_ice': 'build a ConfigDict for monatomic water in the hexagonal ice phase with a given number of particles', 'build_config_cubic_ice': 'build a ConfigDict for monatomic water in the cubic ice phase with a given number of particles', 'review_get_config': 'review the get_config function that returns a ConfigDict for monatomic water simulation experiments', 'summarize_get_config': 'summarize the get_config function which constructs training and test configs for flow-based particle models', 'test_get_config': 'test the get_config function with different particle counts and lattice types to verify config output'}
```

## File: google-deepmind_flowsforatomicsolids/experiments/train.py

Prompts

```
['build a config dict for a Lennard-Jones FCC solid phase simulation with a given number of particles', 'review the get_config function that returns a ConfigDict for Lennard-Jones particle model training and testing', 'summarize the FREQUENCIES dictionary mapping particle counts 32, 256, 500 to their corresponding frequency values', 'test the LennardJonesEnergy constructor kwargs used for train and test energy configurations in the config', 'refactor the conditioner dict to use a different Transformer constructor or adjust embedding size and frequency parameters', 'build a ConfigDict for monatomic water in the hexagonal ice phase with a given number of particles', 'build a ConfigDict for monatomic water in the cubic ice phase with a given number of particles', 'summarize the get_config function which constructs training and test configs for flow-based particle models', 'test the get_config function with different particle counts and lattice types to verify config output', 'run energy-based training of a flow model on an atomistic system like Lennard-Jones or monatomic water', 'run the training script with --system=lj_32 and --num_iterations=100000 for a Lennard-Jones 32-particle system', 'review the _get_loss function that samples from a distrax distribution and computes energy-based loss with log probabilities', 'review the main training loop that uses Haiku transforms, JAX JIT, and Optax Adam optimizer with gradient clipping', 'summarize the _num_particles helper function that extracts the particle count from a system name string', 'create a learning rate schedule with configurable decay steps and decay factor for training', 'compute edge lengths of an orthorhombic simulation box given particle count, density, and shape factor', 'compute edge lengths of a hexagonal simulation box for Ih crystal packing', 'compute equal edge lengths of a cubic simulation box from particle count and density', 'summarize the experiment utility functions for learning rate scheduling and simulation box length calculations']
```

Usage

```
{'run_flow_model_training': 'run energy-based training of a flow model on an atomistic system like Lennard-Jones or monatomic water', 'run_training_with_system_flag': 'run the training script with --system=lj_32 and --num_iterations=100000 for a Lennard-Jones 32-particle system', 'review_get_loss_function': 'review the _get_loss function that samples from a distrax distribution and computes energy-based loss with log probabilities', 'review_main_training_loop': 'review the main training loop that uses Haiku transforms, JAX JIT, and Optax Adam optimizer with gradient clipping', 'summarize_num_particles_helper': 'summarize the _num_particles helper function that extracts the particle count from a system name string'}
```

## File: google-deepmind_flowsforatomicsolids/experiments/utils.py

Prompts

```
['build a config dict for a Lennard-Jones FCC solid phase simulation with a given number of particles', 'review the get_config function that returns a ConfigDict for Lennard-Jones particle model training and testing', 'summarize the FREQUENCIES dictionary mapping particle counts 32, 256, 500 to their corresponding frequency values', 'test the LennardJonesEnergy constructor kwargs used for train and test energy configurations in the config', 'refactor the conditioner dict to use a different Transformer constructor or adjust embedding size and frequency parameters', 'build a ConfigDict for monatomic water in the hexagonal ice phase with a given number of particles', 'build a ConfigDict for monatomic water in the cubic ice phase with a given number of particles', 'summarize the get_config function which constructs training and test configs for flow-based particle models', 'test the get_config function with different particle counts and lattice types to verify config output', 'run energy-based training of a flow model on an atomistic system like Lennard-Jones or monatomic water', 'run the training script with --system=lj_32 and --num_iterations=100000 for a Lennard-Jones 32-particle system', 'review the _get_loss function that samples from a distrax distribution and computes energy-based loss with log probabilities', 'review the main training loop that uses Haiku transforms, JAX JIT, and Optax Adam optimizer with gradient clipping', 'summarize the _num_particles helper function that extracts the particle count from a system name string', 'create a learning rate schedule with configurable decay steps and decay factor for training', 'compute edge lengths of an orthorhombic simulation box given particle count, density, and shape factor', 'compute edge lengths of a hexagonal simulation box for Ih crystal packing', 'compute equal edge lengths of a cubic simulation box from particle count and density', 'summarize the experiment utility functions for learning rate scheduling and simulation box length calculations']
```

Usage

```
{'get_lr_schedule': 'create a learning rate schedule with configurable decay steps and decay factor for training', 'get_orthorhombic_box_lengths': 'compute edge lengths of an orthorhombic simulation box given particle count, density, and shape factor', 'get_hexagonal_box_lengths': 'compute edge lengths of a hexagonal simulation box for Ih crystal packing', 'get_cubic_box_lengths': 'compute equal edge lengths of a cubic simulation box from particle count and density', 'summarize_utils': 'summarize the experiment utility functions for learning rate scheduling and simulation box length calculations'}
```

