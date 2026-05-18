# Agent Python Tools

- repo: facebookresearch/neuralstpp
- repo_uri: https://github.com/facebookresearch/neural_stpp

## File: facebookresearch_neuralstpp/models/temporal/basic.py

Prompts

```
['build a HomogeneousPoissonPointProcess model to compute log-likelihood of event times with a constant rate parameter', 'build a HawkesPointProcess model to compute log-likelihood of self-exciting temporal event sequences', 'build a SelfCorrectingPointProcess model to compute log-likelihood of self-correcting temporal event sequences', 'review the TemporalPointProcess abstract base class and its logprob method signature for event time modeling', 'test the fill_triu helper function to zero out upper triangle of a tensor with a fill value', 'build a neural point process model with split hidden state dynamics and ODE-based intensity', 'run the logprob method to compute log-likelihood of event times given intensities', 'create a diffeq network with gated linear layers and activation normalization', 'review the TimeVariableODE integrate method that solves ODEs over normalized time intervals', 'test the ActNorm module that normalizes activations using batch statistics on first forward pass']
```

Usage

```
{'build_homogeneous_poisson_process': 'build a HomogeneousPoissonPointProcess model to compute log-likelihood of event times with a constant rate parameter', 'build_hawkes_process': 'build a HawkesPointProcess model to compute log-likelihood of self-exciting temporal event sequences', 'build_self_correcting_process': 'build a SelfCorrectingPointProcess model to compute log-likelihood of self-correcting temporal event sequences', 'review_temporal_point_process': 'review the TemporalPointProcess abstract base class and its logprob method signature for event time modeling', 'test_fill_triu': 'test the fill_triu helper function to zero out upper triangle of a tensor with a fill value'}
```

## File: facebookresearch_neuralstpp/models/temporal/neural.py

Prompts

```
['build a HomogeneousPoissonPointProcess model to compute log-likelihood of event times with a constant rate parameter', 'build a HawkesPointProcess model to compute log-likelihood of self-exciting temporal event sequences', 'build a SelfCorrectingPointProcess model to compute log-likelihood of self-correcting temporal event sequences', 'review the TemporalPointProcess abstract base class and its logprob method signature for event time modeling', 'test the fill_triu helper function to zero out upper triangle of a tensor with a fill value', 'build a neural point process model with split hidden state dynamics and ODE-based intensity', 'run the logprob method to compute log-likelihood of event times given intensities', 'create a diffeq network with gated linear layers and activation normalization', 'review the TimeVariableODE integrate method that solves ODEs over normalized time intervals', 'test the ActNorm module that normalizes activations using batch statistics on first forward pass']
```

Usage

```
{'build_NeuralPointProcess': 'build a neural point process model with split hidden state dynamics and ODE-based intensity', 'run_NeuralPointProcess_logprob': 'run the logprob method to compute log-likelihood of event times given intensities', 'create_construct_diffeqnet': 'create a diffeq network with gated linear layers and activation normalization', 'review_TimeVariableODE_integrate': 'review the TimeVariableODE integrate method that solves ODEs over normalized time intervals', 'test_ActNorm_forward': 'test the ActNorm module that normalizes activations using batch statistics on first forward pass'}
```

