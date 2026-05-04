# Agent Python Tools

- repo: google-deepmind/formal-conjectures
- repo_uri: https://github.com/google-deepmind/formal-conjectures

## File: google-deepmind_formal-conjectures/scripts/check_erdos_status.py

Prompts

```
['run the script to check if Erdos problem statuses in the repo match erdosproblems.com and print mismatches as JSON', 'run the script with --create-issues flag to create GitHub issues for status mismatches between the repo and erdosproblems.com', 'fetch the latest problems.yaml from the teorth/erdosproblems GitHub repository and parse it with yaml.safe_load', 'scan all .lean files in the ErdosProblems directory and return a dict mapping problem numbers to their open or solved status', 'find mismatches between the Lean file category annotations and the erdosproblems.com YAML status for each Erdos problem', 'run the script to generate FC100Open.lean and FC100Solved.lean subset files from extracted_names.json', 'generate a Lean file with a problems list definition from a sample of theorem problems', 'sample 100 research open problems uniformly at random from the extracted names JSON data', 'sample 100 non-open problems uniformly at random from solved, test, API, and textbook categories', 'verify the category distribution counts in the generated Lean subset files using verifyCategoryCounts']
```

Usage

```
{'run_check_erdos_status': 'run the script to check if Erdos problem statuses in the repo match erdosproblems.com and print mismatches as JSON', 'run_create_issues': 'run the script with --create-issues flag to create GitHub issues for status mismatches between the repo and erdosproblems.com', 'fetch_yaml': 'fetch the latest problems.yaml from the teorth/erdosproblems GitHub repository and parse it with yaml.safe_load', 'scan_lean_files': 'scan all .lean files in the ErdosProblems directory and return a dict mapping problem numbers to their open or solved status', 'find_mismatches': 'find mismatches between the Lean file category annotations and the erdosproblems.com YAML status for each Erdos problem'}
```

## File: google-deepmind_formal-conjectures/scripts/generate_fc_subsets.py

Prompts

```
['run the script to check if Erdos problem statuses in the repo match erdosproblems.com and print mismatches as JSON', 'run the script with --create-issues flag to create GitHub issues for status mismatches between the repo and erdosproblems.com', 'fetch the latest problems.yaml from the teorth/erdosproblems GitHub repository and parse it with yaml.safe_load', 'scan all .lean files in the ErdosProblems directory and return a dict mapping problem numbers to their open or solved status', 'find mismatches between the Lean file category annotations and the erdosproblems.com YAML status for each Erdos problem', 'run the script to generate FC100Open.lean and FC100Solved.lean subset files from extracted_names.json', 'generate a Lean file with a problems list definition from a sample of theorem problems', 'sample 100 research open problems uniformly at random from the extracted names JSON data', 'sample 100 non-open problems uniformly at random from solved, test, API, and textbook categories', 'verify the category distribution counts in the generated Lean subset files using verifyCategoryCounts']
```

Usage

```
{'generate_lean_subset_files': 'run the script to generate FC100Open.lean and FC100Solved.lean subset files from extracted_names.json', 'generate_lean_file_function': 'generate a Lean file with a problems list definition from a sample of theorem problems', 'sample_open_problems': 'sample 100 research open problems uniformly at random from the extracted names JSON data', 'sample_solved_problems': 'sample 100 non-open problems uniformly at random from solved, test, API, and textbook categories', 'verify_category_counts': 'verify the category distribution counts in the generated Lean subset files using verifyCategoryCounts'}
```

