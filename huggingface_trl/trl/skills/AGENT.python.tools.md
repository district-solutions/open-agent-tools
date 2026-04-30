# Agent Python Tools

- repo: huggingface/trl
- repo_uri: https://github.com/huggingface/trl.git

## File: huggingface_trl/trl/skills/cli.py

Prompts

```
['build a CLI that lists available TRL skills for installation using add_skills_subcommands', 'create a CLI command to install a TRL skill to an AI agent directory with --target and --scope', 'run a CLI command to uninstall a TRL skill from an AI agent directory', 'test listing installed skills in a specific target directory using the skills list command', 'summarize how resolve_target_path converts agent names and scopes to filesystem paths', 'list skills installed in TRL, an agent directory, or a custom path', 'install a TRL skill to an agent directory like claude or codex with global or project scope', 'uninstall a skill from an agent directory or custom path by skill name', 'resolve an agent name with scope or a custom path string to a concrete filesystem directory', 'list the supported agent names like claude, codex, and opencode']
```

Usage

```
{'build_skills_list_cli': 'build a CLI that lists available TRL skills for installation using add_skills_subcommands', 'create_skills_install_command': 'create a CLI command to install a TRL skill to an AI agent directory with --target and --scope', 'run_skills_uninstall_command': 'run a CLI command to uninstall a TRL skill from an AI agent directory', 'test_skills_list_installed': 'test listing installed skills in a specific target directory using the skills list command', 'summarize_skills_resolve_target': 'summarize how resolve_target_path converts agent names and scopes to filesystem paths'}
```

## File: huggingface_trl/trl/skills/skills.py

Prompts

```
['build a CLI that lists available TRL skills for installation using add_skills_subcommands', 'create a CLI command to install a TRL skill to an AI agent directory with --target and --scope', 'run a CLI command to uninstall a TRL skill from an AI agent directory', 'test listing installed skills in a specific target directory using the skills list command', 'summarize how resolve_target_path converts agent names and scopes to filesystem paths', 'list skills installed in TRL, an agent directory, or a custom path', 'install a TRL skill to an agent directory like claude or codex with global or project scope', 'uninstall a skill from an agent directory or custom path by skill name', 'resolve an agent name with scope or a custom path string to a concrete filesystem directory', 'list the supported agent names like claude, codex, and opencode']
```

Usage

```
{'list_skills': 'list skills installed in TRL, an agent directory, or a custom path', 'install_skill': 'install a TRL skill to an agent directory like claude or codex with global or project scope', 'uninstall_skill': 'uninstall a skill from an agent directory or custom path by skill name', 'resolve_target_path': 'resolve an agent name with scope or a custom path string to a concrete filesystem directory', 'list_agent_names': 'list the supported agent names like claude, codex, and opencode'}
```

