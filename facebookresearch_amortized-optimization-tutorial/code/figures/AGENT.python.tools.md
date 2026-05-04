# Agent Python Tools

- repo: facebookresearch/amortized-optimization-tutorial
- repo_uri: https://github.com/facebookresearch/amortized-optimization-tutorial

## File: facebookresearch_amortized-optimization-tutorial/code/figures/main-example.py

Prompts

```
['run the script to generate all four amortized optimization tutorial PDF figures', 'generate a contour plot of the objective function f(y; x) with the optimal y* curve', 'generate a regression-based loss visualization comparing predicted y-hat against optimal y-star', 'generate an objective-based loss plot showing gradient quivers from predicted to optimal points', 'generate an RL-based loss plot with perturbed predicted trajectories overlaid on the contour', 'run the maxent animation script to generate gradient descent frames and a GIF', 'compute a parameterized 1D probability distribution with mean and variance constraints using JAX', 'compute the entropy of a discretized probability distribution over a domain', 'normalize a distribution domain to zero mean and unit variance using flow transformation', 'compute the negative entropy loss for gradient-based maximum entropy optimization', 'run the maxent script to generate a PDF figure of distribution optimization over 20 gradient steps', 'compute the entropy of a discretized probability distribution given x coordinates and density values y', 'normalize a distribution domain to zero mean and identity variance using the flow function', 'perform gradient descent on the negative entropy loss to maximize entropy of the learned distribution', 'run the script to generate a smoothed loss plot saved as smoothed-loss.pdf', 'review the python function f that computes cos(x) + 0.2*abs(x - pi/2)', 'summarize the python loop that computes smoothed values by averaging f over 50000 random perturbations', 'refactor the python smoothing loop to vectorize the 50000-sample Monte Carlo estimation', 'test the python module to verify smoothed-loss.pdf is generated with correct matplotlib styling']
```

Usage

```
{'run_main_example_script': 'run the script to generate all four amortized optimization tutorial PDF figures', 'generate_opt_contour_plot': 'generate a contour plot of the objective function f(y; x) with the optimal y* curve', 'generate_regression_loss_plot': 'generate a regression-based loss visualization comparing predicted y-hat against optimal y-star', 'generate_objective_loss_plot': 'generate an objective-based loss plot showing gradient quivers from predicted to optimal points', 'generate_rl_loss_plot': 'generate an RL-based loss plot with perturbed predicted trajectories overlaid on the contour'}
```

## File: facebookresearch_amortized-optimization-tutorial/code/figures/maxent-animation.py

Prompts

```
['run the script to generate all four amortized optimization tutorial PDF figures', 'generate a contour plot of the objective function f(y; x) with the optimal y* curve', 'generate a regression-based loss visualization comparing predicted y-hat against optimal y-star', 'generate an objective-based loss plot showing gradient quivers from predicted to optimal points', 'generate an RL-based loss plot with perturbed predicted trajectories overlaid on the contour', 'run the maxent animation script to generate gradient descent frames and a GIF', 'compute a parameterized 1D probability distribution with mean and variance constraints using JAX', 'compute the entropy of a discretized probability distribution over a domain', 'normalize a distribution domain to zero mean and unit variance using flow transformation', 'compute the negative entropy loss for gradient-based maximum entropy optimization', 'run the maxent script to generate a PDF figure of distribution optimization over 20 gradient steps', 'compute the entropy of a discretized probability distribution given x coordinates and density values y', 'normalize a distribution domain to zero mean and identity variance using the flow function', 'perform gradient descent on the negative entropy loss to maximize entropy of the learned distribution', 'run the script to generate a smoothed loss plot saved as smoothed-loss.pdf', 'review the python function f that computes cos(x) + 0.2*abs(x - pi/2)', 'summarize the python loop that computes smoothed values by averaging f over 50000 random perturbations', 'refactor the python smoothing loop to vectorize the 50000-sample Monte Carlo estimation', 'test the python module to verify smoothed-loss.pdf is generated with correct matplotlib styling']
```

Usage

```
{'run_maxent_animation': 'run the maxent animation script to generate gradient descent frames and a GIF', 'compute_dist_distribution': 'compute a parameterized 1D probability distribution with mean and variance constraints using JAX', 'entr_entropy': 'compute the entropy of a discretized probability distribution over a domain', 'flow_normalize': 'normalize a distribution domain to zero mean and unit variance using flow transformation', 'loss_negative_entropy': 'compute the negative entropy loss for gradient-based maximum entropy optimization'}
```

## File: facebookresearch_amortized-optimization-tutorial/code/figures/maxent.py

Prompts

```
['run the script to generate all four amortized optimization tutorial PDF figures', 'generate a contour plot of the objective function f(y; x) with the optimal y* curve', 'generate a regression-based loss visualization comparing predicted y-hat against optimal y-star', 'generate an objective-based loss plot showing gradient quivers from predicted to optimal points', 'generate an RL-based loss plot with perturbed predicted trajectories overlaid on the contour', 'run the maxent animation script to generate gradient descent frames and a GIF', 'compute a parameterized 1D probability distribution with mean and variance constraints using JAX', 'compute the entropy of a discretized probability distribution over a domain', 'normalize a distribution domain to zero mean and unit variance using flow transformation', 'compute the negative entropy loss for gradient-based maximum entropy optimization', 'run the maxent script to generate a PDF figure of distribution optimization over 20 gradient steps', 'compute the entropy of a discretized probability distribution given x coordinates and density values y', 'normalize a distribution domain to zero mean and identity variance using the flow function', 'perform gradient descent on the negative entropy loss to maximize entropy of the learned distribution', 'run the script to generate a smoothed loss plot saved as smoothed-loss.pdf', 'review the python function f that computes cos(x) + 0.2*abs(x - pi/2)', 'summarize the python loop that computes smoothed values by averaging f over 50000 random perturbations', 'refactor the python smoothing loop to vectorize the 50000-sample Monte Carlo estimation', 'test the python module to verify smoothed-loss.pdf is generated with correct matplotlib styling']
```

Usage

```
{'run_maxent_optimization': 'run the maxent script to generate a PDF figure of distribution optimization over 20 gradient steps', 'compute_dist_distribution': 'compute a normalized probability distribution from discretized domain points and learnable parameters phi', 'compute_entropy': 'compute the entropy of a discretized probability distribution given x coordinates and density values y', 'normalize_distribution_flow': 'normalize a distribution domain to zero mean and identity variance using the flow function', 'gradient_descent_maxent': 'perform gradient descent on the negative entropy loss to maximize entropy of the learned distribution'}
```

## File: facebookresearch_amortized-optimization-tutorial/code/figures/smoothed-loss.py

Prompts

```
['run the script to generate all four amortized optimization tutorial PDF figures', 'generate a contour plot of the objective function f(y; x) with the optimal y* curve', 'generate a regression-based loss visualization comparing predicted y-hat against optimal y-star', 'generate an objective-based loss plot showing gradient quivers from predicted to optimal points', 'generate an RL-based loss plot with perturbed predicted trajectories overlaid on the contour', 'run the maxent animation script to generate gradient descent frames and a GIF', 'compute a parameterized 1D probability distribution with mean and variance constraints using JAX', 'compute the entropy of a discretized probability distribution over a domain', 'normalize a distribution domain to zero mean and unit variance using flow transformation', 'compute the negative entropy loss for gradient-based maximum entropy optimization', 'run the maxent script to generate a PDF figure of distribution optimization over 20 gradient steps', 'compute the entropy of a discretized probability distribution given x coordinates and density values y', 'normalize a distribution domain to zero mean and identity variance using the flow function', 'perform gradient descent on the negative entropy loss to maximize entropy of the learned distribution', 'run the script to generate a smoothed loss plot saved as smoothed-loss.pdf', 'review the python function f that computes cos(x) + 0.2*abs(x - pi/2)', 'summarize the python loop that computes smoothed values by averaging f over 50000 random perturbations', 'refactor the python smoothing loop to vectorize the 50000-sample Monte Carlo estimation', 'test the python module to verify smoothed-loss.pdf is generated with correct matplotlib styling']
```

Usage

```
{'run_smoothed_loss_plot': 'run the script to generate a smoothed loss plot saved as smoothed-loss.pdf', 'review_function_f': 'review the python function f that computes cos(x) + 0.2*abs(x - pi/2)', 'summarize_smoothing_loop': 'summarize the python loop that computes smoothed values by averaging f over 50000 random perturbations', 'refactor_sampling_efficiency': 'refactor the python smoothing loop to vectorize the 50000-sample Monte Carlo estimation', 'test_plot_generation': 'test the python module to verify smoothed-loss.pdf is generated with correct matplotlib styling'}
```

