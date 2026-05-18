# Agent Python Tools

- repo: facebookresearch/nevergrad
- repo_uri: https://github.com/facebookresearch/nevergrad

## File: facebookresearch_nevergrad/nevergrad/functions/powersystems/core.py

Prompts

```
['create an Agent neural network with specified input size, output size, layers, and layer width', 'set the Agent weights by passing a flattened numpy array matching the agent dimension', 'get the Agent output by passing input data through tanh-activated layers and returning the result', 'simulate a power system with dams and thermal plants over hourly time steps to compute total cost', 'make plots showing losses, marginal costs, consumption, and hydro production saved to a PNG file', 'test the PowerSystem function with 2 dams and 0.2 years simulation using a fixed random seed', 'test the PowerSystem make_plots method by mocking matplotlib and verifying subplot and savefig calls', 'run a PowerSystem simulation with configurable dams and years then evaluate the objective function value', 'review the test_powersystem_small function to verify the expected output value matches the deterministic simulation', 'refactor the test_make_plots function to verify additional matplotlib call counts or assertion conditions']
```

Usage

```
{'create_agent': 'create an Agent neural network with specified input size, output size, layers, and layer width', 'set_agent_parameters': 'set the Agent weights by passing a flattened numpy array matching the agent dimension', 'get_agent_output': 'get the Agent output by passing input data through tanh-activated layers and returning the result', 'simulate_power_system': 'simulate a power system with dams and thermal plants over hourly time steps to compute total cost', 'make_power_system_plots': 'make plots showing losses, marginal costs, consumption, and hydro production saved to a PNG file'}
```

## File: facebookresearch_nevergrad/nevergrad/functions/powersystems/test_core.py

Prompts

```
['create an Agent neural network with specified input size, output size, layers, and layer width', 'set the Agent weights by passing a flattened numpy array matching the agent dimension', 'get the Agent output by passing input data through tanh-activated layers and returning the result', 'simulate a power system with dams and thermal plants over hourly time steps to compute total cost', 'make plots showing losses, marginal costs, consumption, and hydro production saved to a PNG file', 'test the PowerSystem function with 2 dams and 0.2 years simulation using a fixed random seed', 'test the PowerSystem make_plots method by mocking matplotlib and verifying subplot and savefig calls', 'run a PowerSystem simulation with configurable dams and years then evaluate the objective function value', 'review the test_powersystem_small function to verify the expected output value matches the deterministic simulation', 'refactor the test_make_plots function to verify additional matplotlib call counts or assertion conditions']
```

Usage

```
{'test_powersystem_small': 'test the PowerSystem function with 2 dams and 0.2 years simulation using a fixed random seed', 'test_make_plots': 'test the PowerSystem make_plots method by mocking matplotlib and verifying subplot and savefig calls', 'run_powersystem_simulation': 'run a PowerSystem simulation with configurable dams and years then evaluate the objective function value', 'review_test_powersystem_small': 'review the test_powersystem_small function to verify the expected output value matches the deterministic simulation', 'refactor_test_make_plots': 'refactor the test_make_plots function to verify additional matplotlib call counts or assertion conditions'}
```

