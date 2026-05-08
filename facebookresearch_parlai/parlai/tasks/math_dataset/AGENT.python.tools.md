# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/math_dataset/agents.py

Prompts

```
['load math problems from JSON files across specified domains like algebra and geometry', 'yield math problems with questions, answers, and step-by-step reasoning for a given fold', 'extract the boxed final answer from a LaTeX math solution string', 'convert LaTeX math expressions to simplified plain text using substitution rules', 'clean and normalize math solution steps by removing extra whitespace and fixing formatting', 'build the MATH dataset by downloading and extracting MATH.tar into the ParlAI datapath directory', 'run the build function to download the MATH dataset from Berkeley and mark it as built', 'download the MATH dataset tar file using the RESOURCES list of DownloadableFile entries', 'check if the MATH dataset has already been built using build_data.built with the version string', 'remove an older version of the MATH dataset directory using build_data.remove_dir before rebuilding']
```

Usage

```
{'load_math_dataset': 'load math problems from JSON files across specified domains like algebra and geometry', 'get_data_for_fold': 'yield math problems with questions, answers, and step-by-step reasoning for a given fold', 'extract_boxed_answer': 'extract the boxed final answer from a LaTeX math solution string', 'convert_latex': 'convert LaTeX math expressions to simplified plain text using substitution rules', 'clean_solution_steps': 'clean and normalize math solution steps by removing extra whitespace and fixing formatting'}
```

## File: facebookresearch_parlai/parlai/tasks/math_dataset/build.py

Prompts

```
['load math problems from JSON files across specified domains like algebra and geometry', 'yield math problems with questions, answers, and step-by-step reasoning for a given fold', 'extract the boxed final answer from a LaTeX math solution string', 'convert LaTeX math expressions to simplified plain text using substitution rules', 'clean and normalize math solution steps by removing extra whitespace and fixing formatting', 'build the MATH dataset by downloading and extracting MATH.tar into the ParlAI datapath directory', 'run the build function to download the MATH dataset from Berkeley and mark it as built', 'download the MATH dataset tar file using the RESOURCES list of DownloadableFile entries', 'check if the MATH dataset has already been built using build_data.built with the version string', 'remove an older version of the MATH dataset directory using build_data.remove_dir before rebuilding']
```

Usage

```
{'build_math_dataset': 'build the MATH dataset by downloading and extracting MATH.tar into the ParlAI datapath directory', 'run_build_function': 'run the build function to download the MATH dataset from Berkeley and mark it as built', 'download_math_resources': 'download the MATH dataset tar file using the RESOURCES list of DownloadableFile entries', 'check_data_built': 'check if the MATH dataset has already been built using build_data.built with the version string', 'remove_old_data': 'remove an older version of the MATH dataset directory using build_data.remove_dir before rebuilding'}
```

