# Agent Python Tools

- repo: facebookresearch/crypten
- repo_uri: https://github.com/facebookresearch/crypten

## File: facebookresearch_crypten/pycon-workshop-2020/multiprocess_launcher.py

Prompts

```
['create a MultiProcessLauncher with world_size and run_process_fn to spawn Crypten MPC processes', 'start all spawned processes in the MultiProcessLauncher by calling the start method', 'join all spawned processes and assert zero exit codes using the join method', 'terminate all spawned processes in the MultiProcessLauncher using the terminate method', 'run a function in a subprocess with Crypten init and environment variables set', 'run the jointly_train function to perform secure multi-party logistic regression training on MNIST data', 'create a Crypten encrypted LogisticRegression model with a linear layer for 28x28 image classification', 'train an encrypted Crypten model using CrossEntropyLoss and gradient updates across multiple epochs', 'encrypt MNIST digit images and labels and save them to separate parties using crypten save_from_party', 'take a sample of images and one-hot encoded labels from a torchvision dataset for training']
```

Usage

```
{'create_multiprocess_launcher': 'create a MultiProcessLauncher with world_size and run_process_fn to spawn Crypten MPC processes', 'start_multiprocess_launcher': 'start all spawned processes in the MultiProcessLauncher by calling the start method', 'join_multiprocess_launcher': 'join all spawned processes and assert zero exit codes using the join method', 'terminate_multiprocess_launcher': 'terminate all spawned processes in the MultiProcessLauncher using the terminate method', 'run_process_in_subprocess': 'run a function in a subprocess with Crypten init and environment variables set'}
```

## File: facebookresearch_crypten/pycon-workshop-2020/training_across_parties.py

Prompts

```
['create a MultiProcessLauncher with world_size and run_process_fn to spawn Crypten MPC processes', 'start all spawned processes in the MultiProcessLauncher by calling the start method', 'join all spawned processes and assert zero exit codes using the join method', 'terminate all spawned processes in the MultiProcessLauncher using the terminate method', 'run a function in a subprocess with Crypten init and environment variables set', 'run the jointly_train function to perform secure multi-party logistic regression training on MNIST data', 'create a Crypten encrypted LogisticRegression model with a linear layer for 28x28 image classification', 'train an encrypted Crypten model using CrossEntropyLoss and gradient updates across multiple epochs', 'encrypt MNIST digit images and labels and save them to separate parties using crypten save_from_party', 'take a sample of images and one-hot encoded labels from a torchvision dataset for training']
```

Usage

```
{'run_jointly_train': 'run the jointly_train function to perform secure multi-party logistic regression training on MNIST data', 'create_LogisticRegression': 'create a Crypten encrypted LogisticRegression model with a linear layer for 28x28 image classification', 'train_model_encrypted': 'train an encrypted Crypten model using CrossEntropyLoss and gradient updates across multiple epochs', 'encrypt_digits_MNIST': 'encrypt MNIST digit images and labels and save them to separate parties using crypten save_from_party', 'take_samples_dataset': 'take a sample of images and one-hot encoded labels from a torchvision dataset for training'}
```

