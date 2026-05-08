# Agent Python Tools

- repo: facebookresearch/habitat-sim
- repo_uri: https://github.com/facebookresearch/habitat-sim

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/deep_mimic/learning/solvers/mpi_solver.py

Prompts

```
['create an MPISolver instance with a TensorFlow session, optimizer, and model variables for distributed training', 'update the MPISolver with computed gradients and an optional gradient scale factor across MPI processes', 'sync model variables across all MPI processes using broadcast from the root process', 'check whether model parameters are synchronized across all MPI processes in the cluster', 'get the current learning rate stepsize from the optimizer attached to the MPISolver', 'create a subclass of Solver that implements the abstract update method with gradient descent logic', 'implement the abstract update method in a Solver subclass to apply gradients to stored vars', 'initialize a Solver subclass instance by passing a list of trainable variables to the constructor', 'review the Solver abstract base class and its update method contract for optimizer implementations', 'refactor a Solver subclass to support a different optimization strategy in its update method']
```

Usage

```
{'create_MPISolver': 'create an MPISolver instance with a TensorFlow session, optimizer, and model variables for distributed training', 'update_MPISolver_grads': 'update the MPISolver with computed gradients and an optional gradient scale factor across MPI processes', 'sync_MPISolver': 'sync model variables across all MPI processes using broadcast from the root process', 'check_synced_MPISolver': 'check whether model parameters are synchronized across all MPI processes in the cluster', 'get_stepsize_MPISolver': 'get the current learning rate stepsize from the optimizer attached to the MPISolver'}
```

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/deep_mimic/learning/solvers/solver.py

Prompts

```
['create an MPISolver instance with a TensorFlow session, optimizer, and model variables for distributed training', 'update the MPISolver with computed gradients and an optional gradient scale factor across MPI processes', 'sync model variables across all MPI processes using broadcast from the root process', 'check whether model parameters are synchronized across all MPI processes in the cluster', 'get the current learning rate stepsize from the optimizer attached to the MPISolver', 'create a subclass of Solver that implements the abstract update method with gradient descent logic', 'implement the abstract update method in a Solver subclass to apply gradients to stored vars', 'initialize a Solver subclass instance by passing a list of trainable variables to the constructor', 'review the Solver abstract base class and its update method contract for optimizer implementations', 'refactor a Solver subclass to support a different optimization strategy in its update method']
```

Usage

```
{'create_solver_subclass': 'create a subclass of Solver that implements the abstract update method with gradient descent logic', 'implement_solver_update': 'implement the abstract update method in a Solver subclass to apply gradients to stored vars', 'initialize_solver_with_vars': 'initialize a Solver subclass instance by passing a list of trainable variables to the constructor', 'review_solver_abc': 'review the Solver abstract base class and its update method contract for optimizer implementations', 'refactor_solver_subclass': 'refactor a Solver subclass to support a different optimization strategy in its update method'}
```

