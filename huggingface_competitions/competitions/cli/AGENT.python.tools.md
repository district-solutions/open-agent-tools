# Agent Python Tools

- repo: huggingface/competitions
- repo_uri: https://github.com/huggingface/competitions

## File: huggingface_competitions/competitions/cli/create.py

Prompts

```
['launch the Gradio UI to create a new Hugging Face competition', 'register the create subcommand with an argparse parser for competition creation', 'run the CreateCompetitionAppCommand to start the competition creation UI', 'refactor the create_command_factory to accept additional arguments for competition setup', 'review the CreateCompetitionAppCommand class and its run method for launching the competition UI', 'run the competitions app on host 0.0.0.0 and port 7860 using uvicorn', 'run the competitions app on a custom host and port using the run subcommand', 'register the run subcommand with host and port arguments on an argparse parser', 'create a RunCompetitionsAppCommand instance from parsed CLI arguments using the factory function', 'run the competitions app on a specific port by passing the --port argument', 'submit a local file to a HuggingFace competition using competition_id and token', 'submit a HuggingFace hub repo to a competition with an optional comment', 'register the submit subcommand parser with competition_id submission comment and token arguments', 'run the SubmitCompetitionAppCommand to POST a submission to the competition API endpoint', 'create a SubmitCompetitionAppCommand instance from argparse args for competition submission']
```

Usage

```
{'create_competition_ui': 'launch the Gradio UI to create a new Hugging Face competition', 'register_create_subcommand': 'register the create subcommand with an argparse parser for competition creation', 'run_create_command': 'run the CreateCompetitionAppCommand to start the competition creation UI', 'refactor_create_command_factory': 'refactor the create_command_factory to accept additional arguments for competition setup', 'review_CreateCompetitionAppCommand': 'review the CreateCompetitionAppCommand class and its run method for launching the competition UI'}
```

## File: huggingface_competitions/competitions/cli/run.py

Prompts

```
['launch the Gradio UI to create a new Hugging Face competition', 'register the create subcommand with an argparse parser for competition creation', 'run the CreateCompetitionAppCommand to start the competition creation UI', 'refactor the create_command_factory to accept additional arguments for competition setup', 'review the CreateCompetitionAppCommand class and its run method for launching the competition UI', 'run the competitions app on host 0.0.0.0 and port 7860 using uvicorn', 'run the competitions app on a custom host and port using the run subcommand', 'register the run subcommand with host and port arguments on an argparse parser', 'create a RunCompetitionsAppCommand instance from parsed CLI arguments using the factory function', 'run the competitions app on a specific port by passing the --port argument', 'submit a local file to a HuggingFace competition using competition_id and token', 'submit a HuggingFace hub repo to a competition with an optional comment', 'register the submit subcommand parser with competition_id submission comment and token arguments', 'run the SubmitCompetitionAppCommand to POST a submission to the competition API endpoint', 'create a SubmitCompetitionAppCommand instance from argparse args for competition submission']
```

Usage

```
{'run_competitions_app': 'run the competitions app on host 0.0.0.0 and port 7860 using uvicorn', 'run_app_custom_host_port': 'run the competitions app on a custom host and port using the run subcommand', 'register_run_subcommand': 'register the run subcommand with host and port arguments on an argparse parser', 'create_run_command_instance': 'create a RunCompetitionsAppCommand instance from parsed CLI arguments using the factory function', 'run_competitions_app_on_port': 'run the competitions app on a specific port by passing the --port argument'}
```

## File: huggingface_competitions/competitions/cli/submit.py

Prompts

```
['launch the Gradio UI to create a new Hugging Face competition', 'register the create subcommand with an argparse parser for competition creation', 'run the CreateCompetitionAppCommand to start the competition creation UI', 'refactor the create_command_factory to accept additional arguments for competition setup', 'review the CreateCompetitionAppCommand class and its run method for launching the competition UI', 'run the competitions app on host 0.0.0.0 and port 7860 using uvicorn', 'run the competitions app on a custom host and port using the run subcommand', 'register the run subcommand with host and port arguments on an argparse parser', 'create a RunCompetitionsAppCommand instance from parsed CLI arguments using the factory function', 'run the competitions app on a specific port by passing the --port argument', 'submit a local file to a HuggingFace competition using competition_id and token', 'submit a HuggingFace hub repo to a competition with an optional comment', 'register the submit subcommand parser with competition_id submission comment and token arguments', 'run the SubmitCompetitionAppCommand to POST a submission to the competition API endpoint', 'create a SubmitCompetitionAppCommand instance from argparse args for competition submission']
```

Usage

```
{'submit_competition_file': 'submit a local file to a HuggingFace competition using competition_id and token', 'submit_competition_hub_repo': 'submit a HuggingFace hub repo to a competition with an optional comment', 'register_submit_subcommand': 'register the submit subcommand parser with competition_id submission comment and token arguments', 'run_submit_command': 'run the SubmitCompetitionAppCommand to POST a submission to the competition API endpoint', 'submit_commands_factory': 'create a SubmitCompetitionAppCommand instance from argparse args for competition submission'}
```

